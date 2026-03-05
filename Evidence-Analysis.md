\# Evidence Analysis



\## Overview

Evidence analysis involves examining collected forensic artifacts to identify signs of compromise, suspicious behavior, or attacker activity. Proper analysis helps confirm incidents and supports accurate incident response decisions.



---



\## Network Connection Analysis



\*\*Tool:\*\* Velociraptor (conceptual workflow)  

\*\*Query Used:\*\* `SELECT \* FROM netstat`



\### Suspicious Findings



| Timestamp           | Local Address | Remote Address | State       | Notes                    |

|---------------------|--------------|---------------|------------|--------------------------|

| 2026-02-04 16:10:00 | 10.0.0.15    | 192.168.1.200 | ESTABLISHED | Unexpected outbound connection |



\### Analysis

An outbound connection to an unusual external IP was observed. The connection pattern did not match the host’s normal baseline behavior, indicating potential command-and-control communication.



---



\## File Integrity Verification



Evidence integrity was validated using SHA-256 hashing to ensure no tampering occurred during collection.



\### Evidence Record



| Item        | Description        | Collected By | Date       | Hash Value        |

|-------------|--------------------|--------------|------------|-------------------|

| Network Log | Server-Z Netstat   | SOC Analyst  | 2026-02-04 | `<SHA256\_HASH>`   |



---



\## Chain of Custody Controls



The following controls were maintained:



\- Evidence collected in read-only mode  

\- Hash values generated immediately after acquisition  

\- Secure storage location used  

\- Access restricted to authorized personnel  



---



\## Outcome



Evidence analysis confirmed suspicious outbound communication patterns and preserved forensic integrity, supporting further investigation and potential containment actions.

