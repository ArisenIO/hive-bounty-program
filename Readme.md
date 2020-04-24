====

# HIVE (Hackers Identifying Various Exploits) Bounty Program
A successful software is dependent upon it being secure for the users who use it. There isn't a single technology out there that's perfect and Peeps places a lot of value in working with the world's greatest security researchers and hackers alike, to identify weaknesses in various technologies being developed by the PeepsLabs team. 

Peeps and DevGenesis have partnered to bring to life an exploit bounty program, as well as a yearly hackathon, in order to identify weaknesses in Peeps-based technologies.

The HIVE Exploit Bounty Program is focused around all the software currently being developed by our teams and is an open offer to compensate hackers and security experts who report bus.

## HIVE-Approved Software Assets 
The following software assets are approved for the HIVE Bounty Program:
- Arisen Blockchain Software (https://github.com/arisenio/arisen)
- ArisenJS Libraries - (https://github.com/arisenio/arisenjs)
- Arisen Contract Development Toolkit (https://github.com/arisenio/arisen.cdt)
- Arisen System-Based Smart Contracts (https://github.com/arisenio/arisen.contracts)
- dWebJS Libraries (https://github.com/dwebjs) (Any exploit found in these libraries is in scope).
- dBrowser (https://github.com/dbrowser)
- Air Drop System (https://github.com/arisenio/air-drop-app)
- aVote Wallet (https://github.com/arisenio/avote)
- aBank Core Wallet (https://github.com/arisenio/abank)
- Any DOS-style vulnerabilities that apply to the above libraries.

**NOTE:** You must not use any public networks for PoC. All attacks must be proven against test networks, as long as you have permission from the test network you're exploiting. 

## Qualifying Vulnerabilities
There are only a few vulnerabilities that qualify for HIVE's Exploit Bounty Program due to how they affect the stability or security of the software in the HIVE-approved software assets. Common examples include:

1. Cause aOS to crash via the net_plugin
2. Cause aOS to crash via the HTTP RPC API
3. Send a smart contract into an infinite loop
4. Cause a contract to use an infinite amount of memory (more than 64MB)
5. Cash aOS with a smart contract
6. Trigger unauthorized actions on accounts
7. Cause a contract to run for more than 10ms over deadline
8. Edit the contents of a dDrive without its private key 
9. DDOS or DOS the DHT
10. Bypass social media requirements to get unlimited RIX tokens on air drop
11. Various malware and viruses initiated via dBrowser

For other vulnerabilities that are not mentioned above, our number one goal at Peeps is to make sure our customers are utilizing secure infrastructure and software as well. As a result, we will reward reports that we feel qualify for HIVE, using the following reward guidelines:

- **Critical** ***(CVSS 9.0-10.0)*** - 10,000 RIX - 20,000 RIX
- **High** ***(CVSS 7.0-8.9)*** - 5,000 RIX - 10,000 RIX
- **Medium** ***(CVSS 4.0-6.9)*** - 2,500 RIX - 5,000 RIX
- **Low** ***(CVSS 0.0-3.9)*** - 1,000 RIX - 2,500 RIX

## HIVE Policy
- HIVE only covers technical vulnerabilities of Peeps software.
- Do not sneak into Peeps or Dev Genesis offices.
- Do not attempt phishing attacks against Peeps or DevGenesis employees.
- Do not leverage black hat SEO techniques, carry out DOS attacks on public networks or servers, spam people or do other similarly questionable and/or illegal things.
- Do not use vulnerability testing tools on any of our HTTP-based networks or services that automatically generate significant volumes of traffic.
- To qualify for HIVE, the security bug must be original and previously unreported.

## Non-Qualifying Vulnerabilities
Some issues do not qualify for HIVE, including the following:
1. WAST Files
2. Non X86-64 Architecture
3. 64-Bit WASM
4. Build Tools in the WASM SDK
5. URL Redirection or Phishing
6. Flaws Affecting The Users Of Out Of Date Software
7. Presence of Banner or Version Information
8. Click jacking On Non-Sensitive Pages
9. Unauthenticated/Logout/Login CSRF
10. Attacks Requiring MITM or Physical Access To A User's Device
11. Previously Known Vulnerable Libraries Without A PoC
12. CSV Injection Without Demonstrating Vulnerabilities
13. Missing Best Practices In SSL/TSL Configuration
14. Content Spoofing And Text Injection Issues Without Slowing An Attack Vector Or Being Able To Modify HTML/CSS.

## Reward Amounts 
- The base amount of a reward is currently 20,000 RIX
- Final amount of rewards is always determined by the HIVE panel
- We may decide to pay higher rewards for novel vulnerabilities and may hand out a lower reward for vulnerabilities that require unusual user interaction; decide that a single report actually constitutes multiple bugs; or that multiple reports are so closely related that they only warrant a single reward.
- For multiple vulnerabilities with one underlying root cause, where one fix can be applied to remediate, we will consider this as one vulnerability and only award once.

## Investigating and Reporting Bugs
If you have found a vulnerability in any Peeps-related platforms or infrastructure-based software, please submit a report through this repository, by creating an issue with the following details:
- Software Asset - What software asset the exploit is related to (Arisen, Arisen.CDT, etc.)
- Severity - Your opinion on the severity of the issue (critical, high, medium or low)
- Summary - Summarize the details related to the vulnerability
- Description - Detail additional details related to the vulnerability
- Steps - Steps to reproduce the vulnerability
- Supporting Material/References - Source code to replicate, list any additional material (e.g. screenshots, logs, etc.)
- Impact - What security impact could an attacker achieve?
- Your name and country

You must make yourself available for both teams at PeepsLabs and DevGenesis, to provide further information in case it is needed. Additionally, please note that unidentified report submitters will not be eligible for the bounty payment. Please expect to be asked for additional identification details for us to be able to progress with the payment. Please submit your report as soon as you have discovered a potential security issue. Peeps will choose the reward, based on the impact of the vulnerability. We may pay higher rewards for otherwise well written and useful submission, where the reporter didn't notice or couldn't fully analyze the impact of a particular flaw.

Please note that you must be the first person to identify and report a vulnerability to be rewarded for it. We will update all reporters on the status of their report when it is accepted, validated, fixed and when the bounty is repaid.

## Legal Points
This is not a competition. It is a experimental and discretionary rewards program for helping identify security issues within the software our engineering teams are actively developing. We can cancel the HIVE Bounty Program at any time and the decision as to whether or not to pay a reward is entirely at our discretion. Of course, your testing must not violate any law or disrupt or compromise any data that is not your own.

## Safe Harbor
Any activities that take place while contributing to HIVE, in a manner consistent with this policy, will be considered authorized conduct and we will not initiate legal action against you. If legal action is initiated by a third party against you in connection with activities conducted under this policy, we will take steps to make it known that your actions were conducted in compliance with this policy.