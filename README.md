<h1>Analysis of Network Hardening</h1>

<h2>Description</h2>
In this project, there is a presented scenario about a social media organization that recently experienced a major data breach caused by undetected vulnerabilities. I will write a security risk assessment to analyze the incident and explain what methods can be used to further secure the network. To address the breach, I will identify some common network hardening tools that can be implemented to protect the organization’s overall security. Then, I will select specific vulnerabilities that the company has and propose different network hardening methods. Finally, I will explain how the methods and tools I chose will be effective for managing the vulnerabilities and how they will prevent potential breaches in the future. 

<h2>Scenario</h2>
I am a security analyst working for a social media organization. The organization recently experienced a major data breach, which compromised the safety of customers’ personal information, such as names and addresses. My organization wants to implement strong network hardening practices that can be consistently performed to prevent attacks and breaches in the future. 
<br />
<br />
After inspecting the organization’s network, I discover four major vulnerabilities. The four vulnerabilities are as follows:
<br />
<br />
1. The organization’s employees share passwords.
<br />
2. The admin password for the database is set to the default.
<br />
3. The firewalls do not have rules in place to filter traffic coming in and out of the network.
<br />
4. Multifactor authentication (MFA) is not used.
<br />
<br />
If no action is taken to address these vulnerabilities, the organization is at risk of experiencing another data breach or other attacks in the future. 

<h2>Security Risk Assessment Report</h2>

<h3>Selecting three hardening tools and methods to implement</h3>
Three hardening tools the organization can use to address the vulnerabilities found include:
<br />
<br />
1. Setting and enforcing strong password policies.
<br />
2. Implementing multi-factor authentication (MFA).
<br />
3. Implementing port filtering rules on the firewall.
<br />
<br />
Password policies can be refined to include rules about password length, a list of acceptable character requirements, a disclaimer to discourage password sharing, a limit of unsuccessful login attempts, a requirement of frequent password updates, and prohibiting the use of default passwords and the reuse of passwords.
<br />
<br />
MFA requires users to use more than one method to identify and verify their credentials and identity in order to be granted access. Some MFA methods are ID cards, fingerprint scans, and an OTP sent to another device.
<br />
<br />
Port filtering is a firewall function that blocks or allows certain port numbers to limit unwanted communication.

<h3>Explanining my recommendations</h3>
Creating and enforcing a strong password policy within the company will make it more challenging for malicious actors to access the network. Since two of the identified vulnerabilities are that the organization's employees share passwords and that the admin password for the database is set to the default, implementing a password policy will address these vulnerabilities by prohibiting the sharing of passwords and the use of default passwords. Increasing the length and complexity requirements of passwords will prevent threat actors from easily guessing user passwords either manually or through a brute-force attack. 
<br />
<br />
Since one of the identified vulnerabilities was that MFA is currently not in use, implementing and enforcing MFA will add an additional layer of security beyond a password. This will reduce the likelihood that a malicious actor can access a network through a brute-force attack since there is an additional method of authentication required. MFA will also address the identified vulnerability of password sharing within the company. This is because the recipient of the shared password will require an additional authentication method besides a password, making it less convenient and useful to share passwords, thus reducing the likelihood of password sharing.
<br />
<br />
Implementing port filtering rules on the firewall will help control network traffic and prevent potential attackers from entering the organization's network. This will address the identified vulnerability of the firewalls not having rules in place to filter traffic coming in and out of the network. The port filtering rules should be updated whenever a security incident occurs, particularly events that allow suspicious network traffic into the network. This measure can be used to protect against DoS and DDoS attacks.
