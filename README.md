# 🛡️ Responding to a Phishing Incident – Playbook Execution

This repository documents my response to a **phishing-based security alert** using a structured **incident response playbook**.  
It highlights how SOC analysts investigate suspicious alerts, evaluate severity, and document findings in an **Alert Ticket system**.

---

## 📌 Scenario
As a SOC Level-1 analyst at a financial services company, I received a phishing alert involving a **malicious email attachment**.  
The file hash had already been investigated in a previous activity and confirmed as **malicious**.  
Using the **Phishing Incident Response Playbook**, I followed step-by-step instructions to evaluate the alert, determine escalation, and update the ticket with my findings.

---

## 📝 Investigation Steps
- Reviewed **phishing playbook flowchart** and mapped actions  
- Updated the **Alert Ticket** status to *Investigating*  
- Analyzed **alert details**: sender, message body, attachments, and severity  
- Applied the **5 W’s** (Who, What, When, Where, Why) to document incident context  
- Verified attachment hash → already malicious (linked to phishing)  
- Decided whether to escalate or close the ticket based on findings  
- Finalized by updating ticket status and writing detailed comments  

---

## 📂 Repository Contents
- `alert-ticket.docx` → Completed alert ticket with updated status, comments, and **Additional Information** (includes malicious hash & phishing email details)  
- `phishing-playbook-v1.0.docx` → Playbook with flowchart and step-by-step instructions  

---

## 🎯 Learning Outcomes
By completing this activity, I practiced how to:
- Apply an **incident response playbook** to phishing alerts  
- Use the **Alert Ticket system** to track and resolve incidents  
- Document findings with **journal entries + ticket updates**  
- Evaluate when to **escalate vs. close** phishing alerts  

---

👉 *This activity builds directly on my previous work investigating a malicious file hash and extends it into a structured incident response scenario.*  
