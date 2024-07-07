<p align="center">
  <img src = "https://business.defense.gov/portals/57/Images/cyber-carousel/cyber-slide1.jpg?ver=_ACNVKwiING6pUukzdhhWw%3D%3D" width=800 height=300>
</p>

## 🚩 Table of Contents
 1. [Cyber Attacks](#cyber-attacks)
 2. [Security Frameworks](#security-frameworks)
 3. [SOC](#soc)
 4. [OSI Threats](#osi-threats)

---

## Cyber Attacks:

## DDos:
 - A DoS attack is a cyber attack in which the perpetrator seeks to make a machine or network resource unavailable to its intended users by temporarily or indefinitely disrupting services of a host connected to the Internet.
 - This is typically accomplished by flooding the targeted machine or resource with superfluous requests in an attempt to overload systems and prevent some or all legitimate requests from being fulfilled.
 - In essence, this forces the targeted computer or network to reset, or consumes its resources so that it can no longer provide its intended service.

## DDoS (Distributed Denial of Service) Attack:
- A DDoS attack is an amplification of a DoS attack, where the incoming traffic flooding the victim originates from many different sources – potentially hundreds of thousands or more.
- This effectively makes it impossible to stop the attack simply by blocking a single IP address; plus, it is very difficult to distinguish legitimate user traffic from attack traffic when spread across so many points of origin.
- As a result, these attacks can cause serious disruptions of network services and resources.

---

## MITM:
 - A MITM attack is a type of cyber attack where a malicious actor inserts themselves into a conversation between two parties, impersonates both parties and gains access to information that the two parties were trying to send to each other.
 - The attacker intercepts, relays and possibly alters the communication without the knowledge of the two parties who believe they are directly communicating with each other.
 - One common method of a MITM attack involves distributing malware which provides the attacker with access to a victim’s device. The attacker can then install software to process all of the victim’s information.
 - MITM attacks can target communication at any level, from Wi-Fi connections to more application-specific forms, such as HTTP or HTTPS sessions.
 - These attacks can lead to serious consequences, such as unauthorized access to sensitive data, loss of data integrity, or theft of personal information.

---

## Phishing:
 - Phishing is a type of cyber attack that involves tricking the email recipient into believing that the message is something they want or need — a request from their bank, for instance, or a note from someone in their company — and clicking a link or downloading an attachment.
 - The attacker, disguised as a trusted entity, tricks a victim into opening an email, instant message, or text message.
 - The recipient is then tricked into clicking a malicious link, which can lead to the installation of malware, the freezing of the system as part of a ransomware attack or the revealing of sensitive information.
 - An attack can have devastating results. For individuals, this includes unauthorized purchases, the stealing of funds, or identify theft.
 - Furthermore, phishing is often used to gain a foothold in corporate or governmental networks as a part of a larger attack, such as an advanced persistent threat (APT) event.


## Spear-phishing attacks: 
 - Whale spear-phishing is a more targeted version of phishing. It’s a cyber attack that is specifically aimed at high-profile targets like senior executives (the ‘whales’) within a business or other organization.
 - The attacker spends considerable time gathering specific personal and professional information about the target to make the attack more credible.
 - The goal of a whale spear-phishing attack is often to trick the executive into revealing sensitive company information, such as financial details, employee data, or access credentials.

---

## Randsomeware: 
 - Ransomware is a type of malicious software, or malware, that prevents you from accessing your computer files, systems, or networks and demands you pay a ransom for their return.
Ransomw are attacks can cause significant data loss and financial damage.
 - The attacker usually demands the ransom in a form of cryptocurrency, such as Bitcoin, to maintain anonymity.
 - There are different types of ransomware, including scareware, screen lockers, and encryption ransomware.
 - Ransomware can be spread through email attachments, infected software apps, infected external storage devices, and compromised websites, though a majority are spread through phishing emails.


--- 

## SQL injection:

- A common method of exploiting websites that rely on databases. It involves sending an SQL query from a client computer to a server database.
- Injection Process: The malicious command is inserted, or “injected”, into a data plane in place of normal data, such as a password or login. The server then executes the command, leading to system penetration.
- Potential Consequences: If successful, an SQL injection can lead to the release, modification, or deletion of sensitive data. It can also allow attackers to execute administrative operations, such as a shutdown command, disrupting the database’s function.
- Prevention Strategy: Implement a least-privileged model, where only necessary personnel have access to key databases. This limits access to sensitive areas of the network, even for high-ranking individuals within the organization if their roles do not require it.
- Example: A CEO might be restricted from accessing certain network areas, even if they have the right to know the contents. This policy helps prevent both malicious actors and well-intentioned individuals who might inadvertently leave their login credentials exposed or their workstations unattended.


---

## URL Interpretation: 
- URL interpretation is a type of cyber attack where attackers alter and fabricate URL addresses to gain unauthorized access to personal and professional data.
This attack is also known as URL poisoning.
- The attacker understands the syntax of a webpage’s URL and uses this knowledge to access areas they shouldn’t have access to.
- To execute a URL interpretation attack, a hacker may guess URLs to gain administrator privileges or access the site’s back end to get into a user’s account.
- Once they access the desired page, they can manipulate the site or gain access to sensitive user information.
- An example of this attack could be a hacker trying to access the admin section of a site by typing in the site’s URL followed by ‘/admin’. This could lead them to an admin login page.
- In some cases, the admin username and password may be the default “admin” and “admin” or very easy to guess. The attacker may also have already figured out the admin’s password or narrowed it down to a few possibilities.
- Once the attacker gains access, they can manipulate, steal, or delete data at will.
- To prevent URL interpretation attacks, use secure authentication methods for any sensitive areas of your site. This may include multi-factor authentication (MFA) or secure passwords consisting of seemingly random characters.

---

## DNS Spoofing:
- DNS spoofing is a type of cyber attack where a hacker alters DNS records to redirect traffic to a fake or “spoofed” website.
- Once on the fraudulent site, the victim may enter sensitive information that the hacker can use or sell.
- The hacker may also create a poor-quality site with derogatory or inflammatory content to tarnish the reputation of a competitor company.
- In a DNS spoofing attack, the attacker capitalizes on the user’s belief that the site they are visiting is legitimate. This allows the attacker to commit crimes in the name of an innocent company, at least from the perspective of the visitor.
- To prevent DNS spoofing, it’s important to keep your DNS servers up-to-date. Attackers aim to exploit vulnerabilities in DNS servers, and the most recent software versions often contain fixes that close known vulnerabilities.

---


## Session Hijacking:
- Session hijacking is a type of Man-in-the-Middle (MITM) attack where the attacker takes over a session between a client and a server.
- The attacker’s computer substitutes its Internet Protocol (IP) address for that of the client’s computer. The server continues the session, believing it is communicating with the client.
- This attack is effective because the server uses the client’s IP address to verify its identity. If the attacker’s IP address is inserted partway through the session, the server may not suspect a breach because it is already engaged in a trusted connection.
- To prevent session hijacking, use a Virtual Private Network (VPN) to access business-critical servers. This way, all communication is encrypted, and an attacker cannot gain access to the secure tunnel created by the VPN.

---





## Security Frameworks:

A cybersecurity framework is a set of guidelines designed to help organizations mitigate cybersecurity risks. It provides a structured approach to managing cybersecurity risks and protecting valuable information assets.

## NIST Cybersecurity Framework: US federal guidance1

- The NIST CSF is a set of optional standards, best practices, and recommendations for improving cybersecurity and risk management at the organizational level1.
- It provides guidance to industry, government agencies, and other organizations to manage cybersecurity risks2.
- The CSF offers a taxonomy of high-level cybersecurity outcomes that can be used by any organization — regardless of its size, sector, or maturity2.
- It helps businesses of all sizes better understand, manage, and reduce their cybersecurity risk and protect their networks and data3.
- The Framework is voluntary and gives your business an outline of best practices to help you decide where to focus your time and money for cybersecurity protection3.
- The CSF does not prescribe how outcomes should be achieved. Rather, it links to online resources that provide additional guidance on practices and controls that could be used to achieve those outcomes2.
- The NIST CSF 2.0 has been released, along with other supplementary resources4.
- It provides a reasonable base level of cyber security and establishes basic processes and essential controls for cybersecurity5.
- It is particularly useful for private sector organizations that own, operate, or supply critical infrastructure5.
- The NIST CSF 2.0 also provides templates and useful resources for creating and using both CSF profiles

## COBIT: ISACA framework1

## ANSI/TIA-568: Industrial automation standard1

## ISO IEC 27001/ISO 27002: International standards1

## IASME Governance: UK SME certification1

## SOC 2: AICPA framework1

## CIS v7: CIS best practices1

## COSO: Risk management framework1

## TC CYBER: European telecom standard1

## HITRUST CSF: Healthcare industry framework1

## CISQ: Software quality standard1

## FedRAMP: Cloud migration program1

## HIPAA: Health data regulation1

## GDPR: EU data protection law1

## FISMA: Federal security act1

## NY DFS: Financial services regulation1

## NERC CIP: Electric reliability standard1

## SCAP: Security automation protocol1

---


## SOC: 
(Security Operations Center) Its main role is to continuously monitor, investigate, prevent, and respond to cyber threats. The SOC team is responsible for protecting various assets like intellectual property, personnel data, business systems, and brand integrity. The team size can vary based on the organization’s size.

### Preparation and Prevention: 
- As a Junior Security Analyst, staying updated with current cybersecurity threats is crucial. This involves threat detection, security roadmap creation, and preparedness for worst-case scenarios.
- Prevention methods include gathering data on latest threats, threat actors, and their TTPs (Tactics, Techniques, and Procedures).
- Maintenance procedures involve updating firewall signatures, patching system vulnerabilities, and managing block-lists and safe-lists for applications, email addresses, and IPs.
- For understanding TTPs, refer to alerts like the one from CISA on APT40 (Chinese Advanced Persistent Threat).
### Monitoring and Investigation: 
- The SOC team uses tools like SIEM (Security Information and Event Management) and EDR (Endpoint Detection and Response) to monitor network activities.
- Alerts are prioritized based on their level: Low, Medium, High, and Critical, starting from the highest level.
- Junior Security Analysts play a key role in investigating alerts, understanding attack mechanisms, and preventing potential damage.
- The investigation involves asking “How? When, and why?” and finding answers by analyzing data logs and alerts, often using open-source tools.
### Response: 
Post-investigation, the SOC team takes action on compromised hosts, which may involve isolating them from the network, terminating malicious processes, deleting files, etc.


---

## Hash Values:

### MD5 (Message Digest): 
Designed by Ron Rivest in 1992, it’s a cryptographic hash function that produces a 128-bit hash value. However, MD5 hashes are not considered secure due to vulnerability to attacks, including hash collision.

### SHA-1 (Secure Hash Algorithm 1):
Invented by the United States National Security Agency in 1995, it produces a 160-bit hash value string as a 40 digit hexadecimal number. Due to susceptibility to brute-force attacks, its use was deprecated by NIST in 2011, especially for digital signatures. NIST recommends migrating to stronger hash algorithms like SHA-2 and SHA-3.

### SHA-2 (Secure Hash Algorithm 2): 
Designed by NIST and the NSA in 2001 to replace SHA-1. It has several variants, with SHA-256 being the most common. The SHA-256 algorithm produces a 256-bit hash value as a 64 digit hexadecimal number.

---

## OSI Threats:

### Physical Layer Threats:
- Malicious Insiders: Individuals within the organization can pose a threat by tampering with the physical components.
- Malfunction or Sabotage: The physical layer can be compromised through intentional damage or malfunction of the hardware.
- Degradation and Overload: The physical layer can be affected by degradation of components or overload of the system.
- Natural Disasters: Environmental factors such as temperature, humidity, and electrical interference from other equipment can also pose threats.
- Denial of Service (DoS) Attacks: These attacks aim to halt all network functions, often targeting the physical layer.
- Eavesdropping and Data Theft: Cybercriminals can exploit vulnerabilities to access traffic, steal sensitive information, or even cut cables and unplug devices.
- Physical Access: Unauthorized individuals gaining physical access to the infrastructure can pose a significant threat.

### Data Link Layer Threats:
- Frame Manipulation: Malicious actors can compromise data by viewing or manipulating the frames, which are pieces of information that are part of the transmission.
- Overload: The data link layer can suffer from overload, leading to degraded performance1.
- MAC Address Spoofing: Attackers can impersonate a device by spoofing its Media Access Control (MAC) address.
- MAC Address Flooding: This attack overwhelms a network switch’s memory by flooding it with data frames that have different source MAC addresses.
- Virtual Local Area Network (LAN) Circumvention: Attackers can bypass network segmentation and gain unauthorized access to sensitive information.
- Address Resolution Protocol (ARP) Poisoning: This attack involves sending falsified ARP messages over a local area network to link the attacker’s MAC address with the IP address of a legitimate computer or server on the network

### Network Layer Threats:
- Overloading: The network can be overloaded with excessive data, causing it to slow down or crash.
- Spoofing: Attackers can deceive the network by pretending to be another device or user.
- Sniffing: Cybercriminals can intercept and steal data as it travels across the network.
- Man-in-the-Middle Attacks: Attackers can intercept and potentially alter the communication between two parties without their knowledge.
- Exploitation of Vulnerabilities: Attackers can exploit known vulnerabilities in the network layer protocols to gain unauthorized access or disrupt services.

### Protocols Used at Network Layer:
- IP
- IPsec
- ICMP
- IGMP
- GRE

### Transport Layer Threats: 
- Sniffing: This involves intercepting and possibly altering data related to ports and protocols.
- Distributed Denial of Services (DDoS) Attacks: These attacks aim to overwhelm the target with traffic, causing a shutdown of services.
- SYN Floods: In this type of attack, an attacker initiates many connections to a server using a spoofed IP address, without waiting for a connection to finalize.
- Smurf Attacks: These attacks use malware to overload network resources, resulting in an infinite loop of requests.
- Reconnaissance: The transport layer can be used by malicious actors to gather information about the target’s environment.

### Protocols Used at Transport Layer:
- Transmission Control Protocol (TCP)
- User Datagram Protocol (UDP)
- Stream Control Transmission Protocol (SCTP)
- Datagram Congestion Control Protocol (DCCP)
- AppleTalk Transaction Protocol (ATP)
- Fibre Channel Protocol (FCP)
- Reliable Data Protocol (RDP)
- Reliable User Data Protocol (RUDP)
- Structured Steam Transport (SST)
- Sequenced Packet Exchange (SPX)

### Session Layer Threats: 
- Session Hijacking: This involves taking control of a user session after successfully obtaining or generating an authentication session ID. Session hijacking can occur in various ways, including cross-site scripting, sidejacking, fixation, cookie theft, and brute force attempts.
- Code Flaws: Attacks at this layer are often related to flaws in code, allowing attackers to implement their own code into your network and extract data.
- FTP Sniffing: File Transfer Protocol (FTP) on its own is not secure. While many organizations have moved to secure FTP solutions such as SFTP (securing with SSH) or FTPS (securing with SSL), unsecured FTP is still prevalent and can be exploited.


