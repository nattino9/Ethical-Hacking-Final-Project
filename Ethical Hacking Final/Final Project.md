**Ethical Hacking Technical Report**

**Client: KineBench**

**Date: 5/5/2024**

**Prepared By: Nathaniel A. Tino and Joshua James A. Satuito**

**Executive Summary:**  This report presents the technical findings of the ethical hacking assessment 
conducted for KineBench. The assessment aimed to identify vulnerabilities within the 
organization's network infrastructure, applications, and systems. Through various testing methodologies, 
including penetration testing and vulnerability scanning, critical and high-risk issues were discovered. 
This report provides detailed descriptions of these findings, along with actionable recommendations for 
remediation. 

**Vulnerability Summary:**

1. **Network Infrastructure:**
- Critical: User inputs that is not properly validated, which may cause SQL injection.
2. **DDoS:**
- High: Prone to traffic making the system inaccessible
3. **Operating Systems:**
- High: Weak authentication for users making the system vulnarable from unauthorized access.
4. **Wireless Networks:**
- High: Using of weak encryption makes the system vulnerable for unauthorized access.
5. **Social Engineering:**
- Critical: Consumers fell for baits from outside sources, which made it simple to obtain private information.
6. **Impersonation**
- High: May clone other users as the legitimate one to gain access.
7. **Social Media Manipulation**
- High: System prone to social media platform making vulnerable for attacks.
8. **File Upload Vulnerability**
- High: Insufficient validation of uploads may lead to security breaches.
9. **Spear Phishing**
- High: Valued users may be a primary target for attacks.
10. **Sensitive Data Exposure**
- Unmonitored data may lead to system breach/attack.

**Recomendations:**
1. **Network Infrastructure:**
- Make sure the input fits into the expected lengths, formats, and types of data. Reject input containing unexpected characters or patterns that might be signs of an attempted SQL injection.
2. **DDoS:**
-  Implement network traffic monitoring and anomaly detection systems to identify abnormal traffic patterns that may indicate a DDoS attack. 
3. **Operating Systems:**
- Develop a strong password and authentication policies ensuring the safety and security of the end users.
4. **Wireless Networks:**
- Upgrade to a higher security protocol to ensure the security of the system.
5. **Social Engineering:**
- Provide frequent customers with well-written instructions on how to avoid bait attacks and the opportunity to educate them in order to reduce the frequency of attacks.
6. ***Impersonation**
-  Extend the security beyond passwords by implementing multi-factor authentication. Demand that users use an additional means of identity verification, like SMS codes, email verification, or authenticator apps, in order to confirm their identities.
- Provide users with security awareness to educate them about the risks of impersonation and the importance of safeguarding their credentials.
7. **Social Media Manipulation**
-  Encourage users to exercise caution when interacting with unknown or suspicious accounts and to verify the authenticity of messages and requests.
8. **File Upload Vulnerability**
- Strict validation procedures should be used to make sure uploaded files follow the correct file types and formats.
9. **Spear Phishing**
- Encourage users to avoid clicking on suspicious links and to navigate to websites directly by typing the URL into the browser's address bar.
10. **Sensitive Data Exposure**
- Use strong encryption algorithms and key management practices to ensure the confidentiality and integrity of encrypted data.

**Signature:**

![Nathaniel Tino](<Scan_20240506 (2).jpg>)
![Joshua James Satuito](Scan_20240506.jpg)