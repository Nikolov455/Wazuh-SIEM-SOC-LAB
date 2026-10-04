# Wazuh-SIEM-SOC-

<img width="701" height="438" alt="image" src="https://github.com/user-attachments/assets/ae68556d-c764-462e-b654-b5b28f151e38" />

1.FTP brute-force simulation from Kali Linux using Hydra against the Windows target.

<img width="707" height="256" alt="Screenshot 2026-10-04 163145" src="https://github.com/user-attachments/assets/687e5123-a250-49d3-bba2-4877a22eb6e1" />


2. Wazuh Detection: Wazuh successfully detected multiple failed FTP authentication attempts generated during the Hydra brute-force simulation. The events were collected from the Windows endpoint and displayed in the Threat Hunting dashboard for further investigation.


<img width="1777" height="762" alt="Screenshot 2026-10-04 162419" src="https://github.com/user-attachments/assets/e75a243e-56ea-46f3-9f65-8a87b8da9970" />




 3 – Event Identification: The detected authentication event was examined in Wazuh using its unique event/operation ID, allowing the specific activity to be isolated for further investigation and correlation with the brute-force simulation.





<img width="988" height="752" alt="Screenshot 2026-10-04 161328" src="https://github.com/user-attachments/assets/e78e7e64-d4bb-493f-8895-2511713e5316" />
# SOC Incident Investigation Report

## 1. Incident Information

**Incident ID:**  
[INC-XXXX]

**Date:**  
[DD/MM/YYYY]

**Analyst:**  
[Name]

**Detection Platform:**  
[Wazuh / Splunk / Microsoft Sentinel / Other]

**Incident Type:**  
[Brute Force / Phishing / Malware / Suspicious Login / Other]

**Severity:**  
[Low / Medium / High / Critical]

**Status:**  
[Open / Investigating / Resolved]

---

## 2. Executive Summary

Provide a short summary of what happened.

**Summary:**  
[Describe what was detected, which system was affected, and why the activity was considered suspicious.]

---

## 3. Detection

**Detection Time:**  
[HH:MM:SS]

**Detection Source:**  
[Wazuh rule / Windows Event Log / IDS / SIEM alert]

**Rule ID:**  
[Rule ID]

**Rule Description:**  
[Rule description]

**Event ID:**  
[Windows Event ID, if applicable]

---

## 4. Affected Asset

**Hostname:**  
[Hostname]

**Operating System:**  
[Windows / Linux]

**Destination IP:**  
[IP address]

**Service / Port:**  
[Example: FTP / TCP 21]

---

## 5. Source of Activity

**Source IP:**  
[IP address]

**Source System:**  
[Example: Kali Linux]

**Username / Account Targeted:**  
[Username]

**Tool Identified:**  
[Hydra / Nmap / Unknown / Other]

---

## 6. Investigation

Describe how the alert was investigated.

**Observed Activity:**  
[What happened?]

**Number of Events / Attempts:**  
[Number]

**Time Range:**  
[Start time – End time]

**Relevant Log Information:**  
[Important fields found in the logs.]

**Indicators of Compromise / Indicators of Activity:**  
- [Source IP]
- [Username]
- [Hostname]
- [Other relevant indicator]

---

## 7. MITRE ATT&CK Mapping

**Tactic:**  
[Example: Credential Access]

**Technique:**  
[Technique name]

**Technique ID:**  
[TXXXX]

**Reason for Mapping:**  
[Explain briefly why the observed activity matches this technique.]

---

## 8. Analysis

Explain what the collected evidence indicates.

[Describe the relationship between the events, source system, target system, authentication attempts, and SIEM detection.]

---

## 9. Response / Recommended Actions

**Actions Taken:**  
- [Action 1]
- [Action 2]

**Recommended Actions:**  
- [Block suspicious source IP if appropriate]
- [Review affected account]
- [Review additional authentication logs]
- [Reset credentials if compromise is suspected]
- [Continue monitoring for related activity]

---

## 10. Conclusion

**Final Assessment:**  
[True Positive / False Positive / Benign Activity / Inconclusive]

**Conclusion:**  
[Summarize what happened and whether the activity represents a security incident.]

---

## 11. Evidence

**Screenshot 1:**  
[Attack / activity generation]

**Screenshot 2:**  
[SIEM detection]

**Screenshot 3:**  
[Event details]

**Screenshot 4:**  
[Additional investigation evidence]

---

### Analyst Notes

[Additional observations, limitations, or lessons learned.]
