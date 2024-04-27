# Security
This section gives a cyber security risk assessment for the company and recommended security controls.

[Risk Assesment](#risk-assessment) | [Security Controls](#security-controls) | [Plan](./plan.md) | [Network Design](./network.md) | [Cloud Services](./cloud.md) | [Reflection](./reflection.md) | [Return to index](./README.md)

## Risk Assessment
[View risk assessment spreadsheet](./Files/risk-assessment.xlsx)

[TVA Matrix](./images/TVAMatrix_1.png) <br>
[TVA Matrix](./images/TVAMatrix_2.png) <br>
[TVA Matrix](./images/TVAMatrix_1.png) <br>
[TVA Matrix](./images/TVAMatrix_4.png) <br>

## Security Controls
### Security Control 1: Network Segmentation

-	Asset/Threat Protected: This control protects sensitive company data, including engineering designs and financial information, from unauthorized access.

-	How: Implement network segmentation to isolate critical assets (engineering and financial data servers) from the rest of the network. Use firewalls and access controls to enforce strict access policies. Refer to the NIST Cybersecurity Framework's "Identify" and "Protect" functions.

### Security Control 2: Encryption

-	Asset/Threat Protected: This control protects data in transit and data at rest, ensuring that even if intercepted, it remains confidential.

-	How: Implement end-to-end encryption for data transferred between the cloud backup server and local servers. Use strong encryption algorithms and key management. Follow industry encryption standards like FIPS 140-2.

### Security Control 3: Access Controls

-	Asset/Threat Protected: This control safeguards all network resources, ensuring only authorized personnel access them.

-	How: Enforce strict access controls using role-based access control (RBAC) and multi-factor authentication (MFA). Limit access to sensitive systems based on job roles. Follow ACSC Essential Eight principles for user access management.

### Security Control 4: Intrusion Detection and Prevention System (IDPS)

-	Asset/Threat Protected: Protects the network from unauthorized access attempts and suspicious activities.

-	How: Deploy an IDPS to monitor network traffic for signs of malicious activities and intrusions. Set up alerts and automated responses to mitigate threats. Follow guidelines from NIST Cybersecurity Framework.

### Security Control 5: Regular Patch Management

-	Asset/Threat Protected: This control protects systems from vulnerabilities that could be exploited.

-	How: Establish a patch management policy to regularly update all software and devices in the network, including servers, routers, and firewalls. Patch known vulnerabilities promptly, following industry best practices and NIST guidelines.

### Security Control 6: Employee Training

-	Asset/Threat Protected: Human error and social engineering threats.

-	How: Conduct regular cybersecurity awareness training for employees to educate them about phishing, social engineering, and safe computing practices. Ensure they are aware of security policies and best practices.

### Security Control 7: Incident Response Plan

-	Asset/Threat Protected: Ensures an organized response in case of a security breach.

-	How: Develop an incident response plan (IRP) that outlines procedures for identifying, containing, and recovering from security incidents. Follow NIST guidelines for incident response planning.

