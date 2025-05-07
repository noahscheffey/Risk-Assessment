<h1> Risk Asseessment Report</h1>

<h2>Description</h2>
Project consists of a social media organization, which recently experienced a major data breach. This compromised the safety of their customers’ personal information including names and addresses. The organization wanted to implement strong network hardening practices that can be performed consistently to prevent attacks and breaches in the future.

After inspecting the organization’s network, I discovered four major vulnerabilities, which are as follows:

1. The organization’s employees' share passwords.
2. The admin password for the database is set to the default.
3. The firewalls do not have rules in place to filter traffic coming in and out of the network.
4. Multifactor authentication (MFA) is not used.

<h2>Recommended Hardening Tools and Methods to Implement</h2>

1. Requiring password policies.
   <br /> - MFA requires users to use more than one way to identify and verify their credentials before accessing an application. Some MFA methods include fingerprint scans, ID cards, pin numbers, and passwords.

2. Implementing multifactor authentication (MFA).
   <br /> - Password policies can be refined to include rules regarding password length, a list of acceptable characters, and a disclaimer to discourage password sharing. They can also include rules surrounding unsuccessful login attempts, such as the user losing access to the network after five unsuccessful attempts.

3. Utilizing firewall maintenance regularly.
   <br /> - Firewall maintenance entails checking and updating security configurations regularly to stay ahead of potential threats.
 
<h2>Further Explaination of Recommendations</h2>

1. Enforcing multi-factor authentication (MFA) will reduce the likelihood that
a malicious actor can access a network through a brute force or related attack.
MFA will also make it more difficult for people within the organization to share
passwords. Identifying and verifying credentials is especially critical among
employees with administrator level privileges on the network. MFA should be
enforced regularly.

2. Creating and enforcing a password policy within the company will make it
increasingly challenging for malicious actors to access the network. The rules
that are included in the password policy will need to be enforced regularly within
the organization to help increase user security.

3. Firewall maintenance should happen regularly. Firewall rules should be updated
whenever a security event occurs, especially an event that allows suspicious
network traffic into the network. This measure can be used to protect against
various DoS and DDoS attacks.
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
