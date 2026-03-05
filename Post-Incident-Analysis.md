\# Post-Incident Analysis and Continuous Improvement



\## Overview

Post-incident analysis ensures that security events are fully understood and that defensive capabilities improve over time. This process includes root cause analysis (RCA), lessons learned, and measurement of SOC performance metrics.



---



\## Root Cause Analysis (5 Whys)



\*\*Incident:\*\* Phishing Email Compromise



| Question | Answer |

|----------|--------|

| Why was the email opened? | User clicked malicious link |

| Why did the user click the link? | Email appeared legitimate |

| Why was the email convincing? | Weak email filtering rules |

| Why were filters insufficient? | Outdated detection signatures |

| Why were signatures outdated? | Patch/update cycle delay |



\### RCA Conclusion

The root cause was inadequate email filtering combined with delayed signature updates, allowing the phishing email to reach the end user.



---



\## Fishbone Analysis (Summary)



Primary contributing factors identified:



\- \*\*Technology:\*\* Outdated email filtering  

\- \*\*Process:\*\* Delayed signature updates  

\- \*\*People:\*\* Lack of user awareness  

\- \*\*Detection:\*\* Insufficient phishing rules  



---



\## SOC Metrics Calculation



\### Mean Time to Detect (MTTD)



\- Detection Time: 2 hours  

\- Incident Start: 10:00  

\- Alert Generated: 12:00  



\*\*MTTD = 2 hours\*\*



---



\### Mean Time to Respond (MTTR)



\- Response Initiated: 12:00  

\- Containment Completed: 16:00  



\*\*MTTR = 4 hours\*\*



---



\## Metrics Assessment



The current MTTD and MTTR values indicate moderate detection capability but highlight opportunities to improve response automation and alert tuning.



---



\## Lessons Learned



\- Improve email filtering rules  

\- Update detection signatures regularly  

\- Conduct phishing awareness training  

\- Enhance automated alerting  



---



\## Outcome



Post-incident analysis enables continuous SOC improvement by identifying root causes, strengthening controls, and reducing future detection and response times.

