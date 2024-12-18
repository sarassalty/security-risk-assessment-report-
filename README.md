# Security risk assessment report 

> [!NOTE]
> This exercise is a component of the [Google Cybersecurity Professional Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity) program. It's designed as a simulated scenario to solidify my understanding of Network Analysis.

## Activity Overview 
In this activity, you will be presented with a scenario about a social media organization that recently experienced a major data breach caused by undetected vulnerabilities. To address the breach, you will identify some common network hardening tools that can be implemented to protect the organization’s overall security. Then, you will select a specific vulnerability that the company has and propose different network hardening methods. Finally, you will explain how the methods and tools you chose will be effective for managing the vulnerability and how they will prevent potential breaches in the future. 

## Scenario
You are a security analyst working for a social media organization. The organization recently experienced a major data breach, which compromised the safety of their customers’ personal information, such as names and addresses. Your organization wants to implement strong network hardening practices that can be performed consistently to prevent attacks and breaches in the future. 

After inspecting the organization’s network, you discover four major vulnerabilities. The four vulnerabilities are as follows:

+ The organization’s employees' share passwords.

+ The admin password for the database is set to the default.

+ The firewalls do not have rules in place to filter traffic coming in and out of the network.

+ Multifactor authentication (MFA) is not used. 

If no action is taken to address these vulnerabilities, the organization is at risk of experiencing another data breach or other attacks in the future. 

In this activity, you will write a security risk assessment to analyze the incident and explain what methods can be used to further secure the network.

# Security risk assessment report 

|Part 1: Select up to three hardening tools and methods to implement|
|-------------------------------------------------------------------|
|:one: Multi-Factor Authentication (MFA): It adds more verification steps, requiring a user to verify their identity in two or more ways to access a system or network. 
:two: Firewall maintenance: Requires frequent updates and audits of system defenses to address evolving threats.
:three: Password policies: NIST's latest advice for password policies suggests adding a unique salt and hash to the passwords, rather than making passwords too complicated or forcing users to change them often.|

|Part 2: Explain your recommendations|
|------------------------------------|
|Implementing Multi-Factor Authentication (MFA) reduces the activity of malicious actors, as sharing passwords becomes less of a risk. This is because the user must verify their identity using two methods, such as something they know (like a password) and something they have (like a mobile device). This additional layer of security makes it significantly harder for external parties to gain unauthorized access to sensitive information, even if they have obtained the password.
Regular firewall maintenance ensures that the firewall remains updated, secure, and properly configured. By keeping the firewall in optimal condition, it can effectively prevent unauthorized access, block malicious traffic, and detect suspicious activities. In the event of a DoS attack, regular maintenance ensures that the firewall is equipped with the latest defense mechanisms and rules to mitigate the attack, prevent service disruption, and protect the network from being overwhelmed by malicious traffic.
The password policies prevent unauthorized users from gaining access by enforcing strong, complex password requirements. These policies make it harder for attackers to guess or crack passwords, as they often require a combination of uppercase and lowercase letters, numbers, and special characters. They can mandate periodic password changes and discourage the use of easily guessable information. The promotion of these best practices, strengthen overall security and reduce the risk of unauthorized access to sensitive systems and data.|



