Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

  Artemis Financial is a consulting company that focuses on custom financial planning. Due to sensitive client data and the nature of secure file verification and data integrity, the company identified the need for enhanced security on its web application to protect its client's sensitive data better. There were two significant issues with handling this: one was that they used WhatsApp to communicate, essentially an unsecured messaging platform and the second was the nature of the data transmitted — highly sensitive financial information. Due to time constraints and the industry's desperate need, this software had not been implemented with a range of security protocols such as checksum verification, data encryption, and other security best practices generally accepted in the industry.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

  I quickly and effectively performed a threat analysis to identify weak points in Artemis Financial’s software and its use of insecure data transmission and validation mechanisms. For example, I followed secure coding practices for my code to reduce the risk of unauthorized access, data manipulation, and unscoped encryption. Key improvements included checksum verification using SHA-256 for data integrity checks, hardened HTTPS enforcement, and keystore validation to secure communication. Secure coding is crucial because it protects sensitive information, reduces cybersecurity threats, and ensures compliance with industry standards.
  Companies without proper security might suffer data breaches, financial loss, and reputational harm. In contrast, systems under proper security incite customer trust, guarantee compliance with regulations, and avert financial liabilities from being raised. Strong software security plays a vital role in other interests of an organization, which assures customers of the ability to protect their data, meets any expensive security events that will give rise to adverse legal results or financial results, and will secure compliance with standards such as PCI DSS, GDPR or NIST guidelines. Strong safety solutions can also reduce the system's downtime with cyber-attacks, allowing business processes to run uninterruptedly. I assisted in increasing the company's data security structure by removing security weaknesses within Artemis Financial, ensuring that the company and its customers are preserved and flexible against potential threats.

Which part of the vulnerability assessment was challenging or helpful to you?

  One of the most challenging yet valuable aspects of vulnerability assessment was configuring and validating the Java Keytool for secure keystore management. Ensuring that self-sign certificates were generated correctly, stored, and applied within the application required careful attention to security protocols and troubleshooting unexpected errors. Additionally, enforcing HTTPS and integrating cryptographic hashing for checksum verification with SHA-256 required a strong understanding of encryption standards and how they interact with secure data transmission. Another challenge was running the dependency-check tool and analyzing the results. Identifying security vulnerabilities within dependencies and determining the appropriate remediation steps helped reinforce the importance of maintaining updated libraries and minimizing exposure to known exploits. Scanning for vulnerabilities, interpreting security reports, and implementing necessary fixes provided a hands-on learning experience in secure software development. Despite the challenges, these experiences were incredibly helpful in reinforcing my understanding of cybersecurity principles. Working with key management, cryptographic security, and dependency analysis strengthened my technical competencies and deepened my consciousness of real-world security risks and mitigation strategies.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

  To enhance the security of Artemis Financial’s software, I implemented multiple layers of protection, focusing on secure communication, data integrity, and access control. One of the primary improvements made in implementing HTTPS was the usage of a Java KeyStore  (JKS) to secure information transmission, ensuring that touchy monetary information turned encrypted in transit. Additionally, I included cryptographic hashing with SHA-256 for checksum verification, validating the facts’ integrity and preventing unauthorized changes. Another critical security enhancement was input validation, which prevented malicious data manipulation by enforcing constraints on user input. By restricting data length and requiring non-empty inputs, I minimized the risk of injection attacks and unexpected system behavior. Furthermore, I transitioned API requests to @PostMapping instead of @GetMapping, reducing exposure to logging and URL-based security risks.
  I will assess the vulnerabilities of automated tools and manual security reviews in the coming days. The OWASP Dependency-Check tool will be a primary source for identifying known security weaknesses in third-party libraries. However, static code analysis will improve failure detection before software deployment. Penetration testing would also be included to simulate actual attacks and help uncover possible exploitable weaknesses before malicious actors could take advantage of them. To this end, I would use security updates and best practices from the industry on secure coding, including multi-factor authentication (MFA), for an extra level of security in sensitive application areas. A further key requirement would be regular security audits that enable detecting and resolving new threats in real-time via monitoring tools. Through the improvement and continued evaluation of security practices, I keep applications safe from various risks that may arise in cybersecurity.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

  During this project, I used different resources, equipment, and coding practices that would be valuable for future tasks and software development. Java Insect was one of the most influential devices, which allowed me to generate and manage self-composed certificates to ensure safe HTTPS communication. Understanding how to configure and validate keystores will be beneficial for implementing secure connections in future projects. Additionally, I used SHA-256 cryptographic hashing for checksum verification, reinforcing my knowledge of secure data integrity techniques. This practice will benefit applications requiring data verification, authentication, or tamper detection.
  I used the OWASP addiction class equipment to identify security weaknesses and scan project addiction for known security risks. This experience emphasized the importance of keeping libraries on third parties up to date and addressed the weaknesses before they were utilized. I focused on safe entry confirmation from the coding perspective and ensured the user met predetermined obstacles to preventing input injection attacks and unexpected errors. Implementing structured error handling, such as throwing exceptions for invalid inputs, reinforced the importance of writing robust and resilient code.
  For API security, I switched from GetMapping to @PostMapping, mastering that POST requests provide better security by retaining sensitive records in the request frame instead of exposing them in URLs. While I didn’t wholly enforce authentication mechanisms in this task, I now apprehend the importance of OAuth, API tokens, and multi-factor authentication (MFA) for securing API endpoints. I plan to incorporate these practices in future work. Overall, this project strengthened my understanding of secure coding principles, cryptographic security, and software vulnerability management, which will be instrumental in future software development and cybersecurity-focused tasks.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

  I successfully implemented multiple security enhancements throughout this project to strengthen Artemis Financial’s software. One of the key improvements was enforcing HTTPS communication using Java Keytool and keystore validation, ensuring encrypted data transmission. This demonstrated my knowledge of secure web application development and certificate management. To further enhance security, I integrated SHA-256 checksum verification, allowing for data integrity validation and preventing unauthorized modifications, reinforcing my understanding of cryptographic security and data protection.
  Additionally, I focused on secure API development by implementing structured input validation and utilizing @PostMapping instead of @GetMapping, reducing the risk of exposing sensitive URL information. This highlights my ability to design APIs with security best practices in mind. I performed a vulnerability assessment and dependency management using the OWASP Dependency-Check tool to identify and mitigate risks. This allowed me to detect and address security vulnerabilities within third-party dependencies. This experience strengthened my ability to conduct security audits and maintain secure software components.
  Beyond implementation, I encountered and resolved several problem-solving and debugging challenges, such as keystore configuration issues, HTTPS enforcement complexities, and checksum hashing validation. These troubleshooting experiences reinforced my ability to handle security-related development challenges effectively. My approach adhered to industry best practices, including proper exception handling, structured input validation, and multi-layered security integration. These measures demonstrate my commitment to writing secure, maintainable, and efficient code that meets modern security standards.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

  To ensure encrypted data transmission, I successfully enforced HTTPS by configuring Java Keytool and integrating keystore validation. This secured all client-server interactions and prevented unauthorized interception. By leveraging TLS encryption and managing SSL certificates, I demonstrated proficiency in certificate management and secure server configuration. For API security, I applied input validation and switched from @GetMapping to @PostMapping, preventing the exposure of sensitive data in URLs. This significantly reduced the risk of injection attacks and ensured only properly formatted inputs were processed. Additionally, I implemented structured exception handling and security layer enforcement, further reinforcing backend security.
To strengthen application security, I used the OWASP Dependency-Check tool to identify and mitigate 88 security vulnerabilities in third-party dependencies. This reduced the attack surface by ensuring all external libraries adhered to secure coding standards.   During the project, I resolved complex keystore configuration challenges to enforce HTTPS, debugged cryptographic hashing functions properly, and tested checksum verification using Postman API. These challenges allowed me to refine my debugging skills while applying real-world security best practices.
  Beyond these security measures, I implemented input validation checks to prevent unexpected or malformed data entries. This included verifying that inputs were neither empty nor exceeded the maximum character limit, protecting the server’s resources from potential misuse. While this significantly improved input security, future enhancements could include more rigorous validation techniques to harden the backend against attacks further. I adhered to secure coding principles throughout the project, including structured input validation, exception handling, and encryption standards. I ensured compliance with NIST and OWASP tips, aligning my paintings with identified secure software development frameworks. This project showcases my potential to enforce high-quality practices, troubleshoot safety vulnerabilities, and hold facts integrity in net programs. It demonstrates my skill in stable software development, cryptographic safety, API hardening, and vulnerability assessment—all vital for growing sturdy, industry-compliant software programs.
