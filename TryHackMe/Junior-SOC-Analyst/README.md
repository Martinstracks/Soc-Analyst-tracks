This practical introduced me to the basic workflow of a Soc Analyst, particularly on how security analysts investigate alerts and conclude on which activity is considered malicious. 



what i learned

&#x20;How a security information and event management (SIEM) can help analyst in investigating security events.

&#x20;The basic process of alert triage.

&#x20;How to distinguish between legitimate and potential malicious activity

&#x20;How to escalate incident. 

&#x20;How to review alerts and identify suspicious activities using Splunk.



Practical investigation 

&#x20;My investigation process was:



1\. Reviewed the available security alerts.

2\. Selected an alert for investigation.

3\. identify the malicious IP address.

4\. Looked for indicators that could suggest malicious activity.

5\. Using IP hunter analyse the IP address

6\. Contain the incident by blocking the Ip in the firewall 

7\. Analysed the available event information and context.



This helped me understand that SOC analysts should investigate an alert using the available evidence rather than immediately assuming that every alert represents a successful attack.



SOC Skills Practised





\* Alert triage

\* Basic security-event analysis

\* Identifying indicators of compromise (IOCs)

\* Investigating suspicious activity

\* Understanding SOC workflows

\* Security monitoring

\* Analytical thinking

\* Documenting investigation findings



Key Takeaway



One of my main takeaways from this practical was that alert triage is an important first step in SOC operations.



A SOC analyst needs to quickly understand what triggered an alert, examine the available evidence, determine its severity, and decide what action should be taken.



This practical gave me my first hands-on experience with the type of investigation a junior SOC analyst may perform.



\## Tools / Technologies



\* TryHackMe

\* SOC alert dashboard

\* SIEM/security monitoring concepts (Splunk)

\* Security event analysis



Next Steps



I plan to continue developing my SOC skills through hands-on labs covering:



\* SIEM platforms

\* Splunk

\* Log analysis

\* Windows event logs

\* Linux logs

\* Network traffic analysis

\* Incident response

\* Detection and investigation of common attacks



Evidence



Screenshots of my completed practical and investigation is included.



# SOC Level 1 – Blue Team Introduction

**Platform:** TryHackMe  
**Path:** SOC Level 1  
**Room:** Blue Team Introduction  
**Status:** ✅ Completed

## What I Learned

### 1. SOC and Blue Team
- A Security Operations Centre (SOC) monitors and responds to security incidents.
- The Blue Team focuses on defending systems, networks and data.
- SOC analysts investigate suspicious activity and potential security incidents.

### 2. Security Hierarchy
- Cybersecurity contains different roles and levels of responsibility.
- SOC analysts can progress through different levels as they gain experience and technical skills.

### 3. Blue Team Roles
- Learned about the different roles involved in defensive security.
- SOC analysts are responsible for monitoring alerts, investigating events and escalating incidents when necessary.

### 4. SOC Career
- Learned about the typical progression of a SOC analyst.
- Developing technical knowledge, investigation skills and practical experience is important for progressing in a SOC career.

## Key Takeaways

- Understand the purpose of a SOC.
- Understand the difference between Blue Team and defensive security.
- Understand the general role of a SOC analyst.
- Understand that SOC roles can progress from entry-level positions to more advanced security roles.

## Task Completed 

i successfully chose the right people to deal with the cyber securitry incidents that was presented 

## Next Steps

- Learn more about security monitoring.
- Study SIEM fundamentals.
- Learn how to analyse security alerts.
- Practise investigating suspicious activity.


## Human as attack Vector

I recently completed the "Human as attack vector" module on TryHackMe as part of my journey toward becoming a Junior SOC Analyst. This module focused on understanding how cyber attacks target people rather than just systems, and the importance of defense in depth.

## Topic Breakdown

Description

**Task 1: Introduction** Overview of the module objectives and the importance of the human factor in cybersecurity. 
**Task 2: The Human Element**  Understanding why humans are the weakest link and how social engineering exploits psychology. 
**Task 3: Attacks on Humans**  Exploring common attack vectors such as phishing, vishing, and impersonation. 
**Task 4: Defending Humans**  Learning strategies to mitigate risks, including security awareness training and policy enforcement. 
**Task 5: Practice**  Practical application of concepts learned to identify and respond to threats. 
**Task 6: Conclusion**  Summary of key takeaways regarding human-centric security. 

### 💡 Key Takeaways
*   **The Weakest Link:** Technology is strong, but human psychology is often the easiest target for attackers.
*   **SOC Relevance:** As a SOC Analyst, understanding social engineering helps in triaging alerts related to compromised credentials and suspicious user behavior.
*   **Defense:** Security is not just about firewalls; it is about education and creating a security-conscious culture.


### practical 
For this lab "Human as Attack Vector Web App", I worked as SOC analyst at TryHackMe. I triaged alerts and was able to protect workers at Employees at Risk tab, and made TryHackMe more secure by proposing effective Security Policies to protect workers.

*Status: Completed


## Alert Triage

I have successfully completed the SOC L1 Alert Triage room on TryHackMe. This module provided a systematic approach to handling security alerts, which is a core responsibility of a Tier 1 Analyst.



Completed: SOC L1 Alert Triage (TryHackMe)

Key Takeaways:

Alert Lifecycle: Differentiated between raw Events and correlated Alerts.

Triage Methodology: Learned how to analyze Alert Properties (Source, Destination, Time) to determine scope.

Prioritization: Implemented strategies to prioritize alerts based on severity and impact, ensuring critical threats are addressed first.

Workflow: Developed a repeatable process for investigating, classifying, and escalating alerts.

This training strengthens my ability to efficiently manage the queue and reduce false positives in a SOC environment.



### practical 
using tryhackme SIEM, I worked as SOC L1 analyst triaging alerts, differentiated between raw Events and correlated alerts, analyzed alert Properties and was gave verdict on the status on whether its a true positive or false positive.  


*Status: Completed


## System as attack Vectors

I recently explored the SOC role in protecting the digital world, focusing on systems as attack vectors. I learnt what the systems are, why and how threat groups target them, and what i can do as a SOC analyst to keep companies secure.
## Topic Breakdown

Description

**Task 1: Introduction** Overview of the topic objectives and systems as attack vector in cybersecurity. 
**Task 2: Attack on system**  Understanding why systems are attacked, and how most of them are facilitated by human engineering, vulnerabilities in the system and supply chain attack which is those pushed through app updates.  
**Task 3: Vulnerabilities**  Exploring software vulnerabilities and patches. 
**Task 4: Misconfiguration**  updating the software does not fix a misconfiguration but rather a better setup, starting from strong passwords, permission and web firewall rules. 
**Task 5: Practice**  Practical application of concepts learned to identify and respond to threats. 
**Task 6: Conclusion**  Summary of key takeaways regarding System as attack vectors. 

### 💡 Key Takeaways
** Every piece of software has flaws, but some take years to be discovered. In the worst-case scenario, attackers discover the vulnerability before anyone else. This is known as a zero-day, and only your SOC skills can determine whether it gets detected in time.
 ** software updates does not fix a misconfiguration but rather a strong password, permissions, and firewall blocking.  
** Patches is the fix for vulnerabilities


### practical 
For this lab "system as Attack Vectors Web App", I worked as SOC analyst at TryHackMe reviewing and analyzing potential Systems at Risk,prepared and implemented the corporate Remediation Plan and chose the best measures to protect systems at the Remediation Plan tabs. 


*Status: Completed



