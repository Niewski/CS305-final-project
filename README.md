# Artemis Financial Practices for Secure Software Report

## **1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**  
Artemis Financial is a consulting firm that provides personalized financial plans, including savings, retirement, investments, and insurance. The company wanted to modernize its software while ensuring client data security. To achieve this they required a file verification system using a checksum and secure communication through HTTPS encryption to protect financial transactions and sensitive client information.  

## **2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**  
During the assessment, I successfully identified vulnerabilities in data transmission, encryption, and key management, then implemented security measures to address them. Secure coding is essential as it prevents data breaches, financial fraud, and system exploits. A strong and proactive security process builds trust with clients, ensures regulatory compliance, and protects the company's reputation. By refactoring the application and enhancing security protocols, the software now provides better data protection, integrity verification, and encrypted communication.  

## **3. Which part of the vulnerability assessment was challenging or helpful to you?**  
Understanding encryption keys, secure communication protocols, and their implementation in real-world applications was both challenging and valuable. 

## **4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**  
To strengthen the system, I implemented multiple security layer, including:  
- **AES-256 encryption** for high-strength data protection.  
- **Checksum validation** to detect unauthorized modifications.  
- **HTTPS enforcement** to prevent man-in-the-middle attacks.  

For future assessments, I would perform penetration testing to assess vulnerabilities and make decisions on mitigation strategies.  

## **5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**  
After refactoring the code I performed functional testing to ensure expected behavior, along with security scans to check for newly introduced vulnerabilities. These measures ensured that the software was both functional and secure.  

## **6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**  
- **Keytool** for SSL certificate generation and management.  
- **OWASP Secure Coding Practices** to align with industry security standards.  
- **Spring Boot Security Configurations** to enforce HTTPS encryption.  
- **Static analysis tools** to identify software vulnerabilities.  


## **7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**  
This project highlights my ability to identify security vulnerabilities, refactor code for compliance, and implement industry-standard security protocols. 
Key highlights include:  
- **AES-256 encryption for data protection**  
- **SSL/TLS implementation for secure communication**  
- **Cryptographic checksum validation for data integrity**  

