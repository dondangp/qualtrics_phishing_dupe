# **Phishing Campaign: Qualtrics Credential Harvesting**

## **Overview**
This project involves designing and executing a phishing campaign as part of a cybersecurity group assignment. The objective is to simulate a realistic phishing attack to gain insights into potential vulnerabilities, enhance understanding of phishing mechanics, and practice ethical hacking principles.

---

## **Objective**
The campaign's objective is to:
- Simulate an attack aimed at harvesting the credentials of a specified target (e.g., a TA).
- Employ ethical methods to build a phishing infrastructure while adhering to the project’s guidelines.
- Demonstrate the effectiveness of the phishing email and website through realistic design and plausible infrastructure.

---

## **Approach**

### **1. Define the Objective**
- **Type of Campaign**: Spear phishing email designed to lure the target to a fake Qualtrics login page.
- **Desired Outcome**: Harvest the TA’s Qualtrics login credentials.
- **Monetary/Educational Value**: Simulates real-world risks associated with phishing attacks on educational platforms.

### **2. Delivery Platform**
- **Phishing Email**: 
  - A carefully crafted email appears to be from a trusted source (e.g., a department survey request).
  - Includes a link to the phishing website.
- **Phishing Website**: 
  - Mimics the official Qualtrics login page.
  - Captures credentials and redirects the target to the legitimate login page to minimize suspicion.
- **Backend Server**:
  - Logs credentials for later analysis.
  - Handles redirection to the official Qualtrics site.

---

## **Phishing Workflow**

### **Step-by-Step Process**
1. **Phishing Email**: 
   - Sent to the target with a compelling call-to-action and link to the fake site.
2. **Fake Login Page**: 
   - Designed to replicate the official Qualtrics interface visually.
   - Collects entered username and password.
3. **Backend Server**: 
   - Stores submitted credentials securely in a file or database.
   - Redirects the user to the legitimate Qualtrics login page.
4. **Redirection**: 
   - The target is directed to the real login page, reducing suspicion.

---

## **Infrastructure Diagram**
```plaintext
Target (TA) --> Phishing Email --> Fake Qualtrics Login Page --> Backend Server (Logs Credentials) --> Legitimate Qualtrics Login Page
