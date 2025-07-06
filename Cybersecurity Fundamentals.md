# 🛡️ Cybersecurity Fundamentals

This page documents the foundational knowledge, resources, and methods I used while beginning my journey into cybersecurity. Each section can be expanded for more detail.

---

<details>
<summary>📘 What Are Cybersecurity Fundamentals?</summary>
  
## The First Thing I Learned

The very first thing I learned when entering the field was the ever-growing rate of cybersecurity attacks. I asked myself why this was and the answer is surprisingly simple.

As we’ve all witnessed, technology is being used more and more each day. Since the internet boom of the 1990s and the rise of the World Wide Web which brought major companies like Amazon, Facebook, and Cisco real-world attackers quickly saw an opportunity.
There’s money, ideas, and information flying across the internet in massive quantities every day. Black hat hackers know this, and they’ve been stealing data, launching phishing campaigns, and building botnets for years.
There is proof of attacker success Just look at the rise of ransomware attacks in recent years.

But before I could dive deep into cybersecurity tactics, I had to step back and understand how the internet, endpoints, and operating systems really work.
It’s one thing to understand how attackers operate it’s another to actually be able to stop them. And to do that, I had to learn the fundamentals first.

## Networking Basics

If I could go back to the beginning, I would start with networking first, even before touching any cybersecurity material.

There were moments early on when I wondered, "How is this attack even possible?" and the answer was almost always buried in some networking concept I hadn’t fully learned yet.

One of the best introductions I found was through the Cisco Networking Academy’s free course: [Networking Basics].
It’s simple, beginner-friendly, and offers a Credly badge upon completion.

I’ll go into more detail about this and other courses in the next section:
“Learning Resources I Used.”

## Introduction to Cybersecurity
This is where the learning truly begins and if I’m being honest, you’ll benefit from reviewing some of these concepts more than once.

The difference between good and bad cybersecurity hygiene often comes down to small decisions:

Someone who knows how to spot a phishing email might check the sender address and hover over a suspicious link before clicking.

Someone who understands protocols might recognize the lack of a secure connection when visiting a new site, simply by spotting HTTP instead of HTTPS.

In Cisco’s Introduction to Cybersecurity, i learned the basics of:

Internet safety

How attackers operate

How security professionals and tools protect users

What makes good passwords, and why protocols and firewalls matter

It's beginner-friendly, free, and includes a shareable badge once you complete it.

🧑‍💻 Ethical Hacking
Believe it or not, not all hackers are bad guys.

I learned this firsthand by taking Cisco’s Ethical Hacker course, which introduced me to the world of penetration testing.
This is where skilled individuals use their hacking knowledge to help organizations test and strengthen their defenses.

Big companies are constantly targeted by attackers looking to steal money or sensitive data. Ethical hackers are actually a line of defense, simulating attacks before the real ones happen.

This is also where I returned to Kali Linux — a tool I had used in the past, but only recently learned to appreciate. After completing the course, I earned another badge and walked away with a deeper understanding of how red teamers think.

Even if you're aiming for blue team roles, it’s important to understand the red team mindset and vice versa.
Attackers can carry out the same goal in many different ways and knowing those techniques helps defenders stay one step ahead.


<!-- Explain what you consider to be the core fundamentals — basic terms, goals of cyber defense, etc. -->

</details>

---

<details>
<summary>🧠 Learning Resources I Used</summary>

## Here are some resources that I found extremely helpful throughout my journey. These are completely free unless otherwise noted.

## PowerCert Animated Videos
https://www.youtube.com/@PowerCertAnimatedVideos/featured

This channel is incredible. It explains everything from basic to advanced networking topics including devices, protocols, and key concepts in short videos under 10 minutes.

I learned a lot about protocols such as:

DHCP, HTTP, HTTPS, SSL

DNS, FTP, TCP/UDP, ARP, and more

All of it is visual, beginner-friendly, and completely free.

## Cisco – Networking Basics

Cisco offers a free course called Networking Basics through its Networking Academy. It’s a 22-hour self-paced course with 13 hands-on labs.

One of the most valuable parts is access to the Cisco Packet Tracer simulator. This lets you build virtual network topologies using simulated routers and switches.

In this course, I learned:

Types of networks and how they function

How data moves across the internet

IP addresses and DNS resolution

The difference between IPv4 and IPv6

Protocol standards and wireless communication

It’s interactive, informative, and you receive a Credly badge at the end.

## Introduction to Cybersecurity
NetworkChuck
https://www.youtube.com/@NetworkChuck/videos

NetworkChuck is a great YouTube channel focused on IT and cybersecurity. His teaching style is energetic, hands-on, and easy to follow.

I used his videos to study away from my main workstation. His lessons are fun, and the way he presents concepts helped me retain the information much better.

SomeOrdinaryGamers
https://www.youtube.com/@SomeOrdinaryGamers/videos

I’ve been watching this channel for years, even before I stepped into cybersecurity. It gained popularity through its “Deep Web Browsing” series, where I was first introduced to the TOR browser and virtual machines.

If something major happens in the world of cybersecurity, this channel often breaks it down in an understandable way.
My favorite series on the channel is the Malware Investigation playlist. The creator, Mutahar, runs malware inside virtual machines and explains what’s happening and why.

If you’re interested in malware and how it behaves, these videos are definitely worth checking out.

## Introduction to Cybersecurity – Cisco Networking Academy
This was one of the most valuable beginner courses I took. It helped shift how I thought about cybersecurity and gave me a more structured understanding of the field.

It’s a 6-hour self-paced course with 7 interactive labs. The course covers:

Cybersecurity principles and goals

Privacy and data confidentiality

Network vulnerabilities and threats

Common attack methods and how to detect them

Cyber best practices and safety tips

You’ll finish with a short final exam and receive a Credly badge that you can add to your resume or LinkedIn profile. It’s short, free, and extremely helpful for beginners.

## TryHackMe (Paid & Free Options)
After I built a foundation in networking and cybersecurity basics, I spent most of my hands-on training time on TryHackMe.

I started by exploring rooms related to red team activities. I was curious about how attackers gain access to machines and what tools they use to stay hidden. That curiosity led to real experience with tools like:

Metasploit – For launching exploits on vulnerable systems

JohnTheRipper – For password cracking

Gobuster, Shodan.io – For enumeration and reconnaissance

msfvenom – For creating custom payloads

EternalBlue – A well-known SMB vulnerability that I learned to recreate and exploit

TryHackMe was where I tied together everything I learned. I highly recommend checking out the next section, “How I Practiced”, where I go into more detail about how I used the platform during my training.


<!-- List the books, platforms, YouTube channels, blogs, or courses you used to get started.
Example: TryHackMe (Intro to Cyber, SOC Level 1), Professor Messer, etc. -->

</details>

---

<details>
<summary>🧪 How I Practiced</summary>
  
I had a lot of fun and learned a ton of valuable information from the red team rooms on TryHackMe. But at some point, I made the decision to focus on blue teaming in cybersecurity.

On the TryHackMe platform, there’s a helpful breakdown of different cybersecurity career paths. After exploring those options, I realized I wanted to work in a Security Operations Center (SOC) as a Security Analyst.

The idea of reading alerts, triaging events, identifying true and false positives, and writing reports really appealed to me.

## The Roadmap I Followed
TryHackMe offers structured learning paths. I started with the Pre-Security track, which teaches essential foundational knowledge about both attacking and defending in cybersecurity.

Next, I completed Cyber **Security 101**, where I learned about:

- Computer networking

- Cryptography

- Windows and Linux operating systems

- Offensive and defensive security tools

- The different roles and paths in cybersecurity

After that, you choose a path. I chose the Security Analyst track and enrolled in the **SOC Level 1 pathway.**

## Tools I Trained With as a SOC Analyst
This is where i really began enjoying cybersecurity. I learned how to detect threats across different operating systems and networks. I worked with both CLI and GUI-based tools, focusing on network security and traffic analysis.

I also learned how to build queries, create detection rules, and spot anomalies using the following tools:

| Snort | NetworkMiner | Zeek | Brim | Wireshark | TShark |

Some tools were easier to use than others, but I made sure to get comfortable with each one and understand how they function.
But Snort and Wireshark became favorites of mine.

## Getting Into Endpoint Security
Next, I dove into endpoint security. I started by learning how systems and applications behave under normal conditions, so I could better recognize anomalies.

This is when I became more interested in Windows processes, learning about PIDs, PPIDs, and event logs. I also gained hands-on experience with Event Viewer, a powerful tool built into most Windows systems.

I used these tools during this part of my training:

| Sysinternals Suite | Sysmon | Osquery | Wazuh |

## SIEM, Incident Handling, and Report Writing
As I progressed, I began working with Security Information and Event Management (SIEM) tools. I learned to use both Splunk and the ELK Stack to investigate alerts and analyze logs.

This part of the path focused on:

- Creating detection queries

- Managing incident response workflows

- Writing clear and effective SOC reports

After learning the basics of Splunk, I took on advanced investigation rooms where I worked with compromised hosts to strengthen my skills.

## DFIR and Malware Analysis
The final stages of my SOC Level 1 training focused on Digital Forensics and Incident Response (DFIR). I studied the critical forensic artifacts found on Windows and Linux systems and learned how to extract and investigate them.

Before completing the challenge rooms, I got a great introduction to malware analysis, where I practiced both static and dynamic analysis. I learned how to reverse engineer malware and understand its behavior by using tools like:

**strings** to extract readable text from **binaries**

**Ghidra** for reverse engineering

**VirusTotal** for cross-analysis and reputation checks

I also analyzed memory dumps and performed Windows registry forensics to solve investigation cases. These were some of the DFIR tools I worked with:

| Autopsy | Redline | KAPE | Volatility | Velociraptor |

## Phishing and the Capstone Challenge
Toward the end of the SOC Level 1 path, I worked through rooms focused on phishing. These lessons were very valuable to me. I analyzed real phishing emails and learned how attackers craft convincing social engineering attempts.

I also learned that phishing is responsible for nearly 90% of cybersecurity attacks, which made the lessons feel that much more important.

Then came the Capstone Challenges, which tested almost everything I had learned.
I investigated a compromised endpoint, followed the entire attack chain, identified the attacker’s actions, and documented my findings.
I wrapped up the journey with an investigation through the “Boogeyman” 1–3 rooms, which challenged most of the skills I had built so far.

## Final Thoughts
To say that TryHackMe helped me is an understatement. I learned so much through hands-on practice and structured lessons. Even though the platform is paid, it was affordable and absolutely worth the investment.

I plan to stick around on TryHackMe a little longer, but I’m also starting to look for companies that are more blue team tranining oriented.

TryHackMe has been one of the most impactful parts of my journey, and I’m thankful for the creators and contributors who built such an accessible and valuable platform.
<!-- Explain how you practiced — labs, hands-on challenges, simulations, etc. 
Mention TryHackMe rooms, GitHub writeups, or daily exercises. -->

</details>

---

<details>
<summary>🔐 Summary, Important Topics I Focused On</summary>

## Cybersecurity can feel overwhelming at first, but mastering the core fundamentals is key. Once you know what security aims to protect, the rest starts making sense.

I realized quickly that people working in cybersecurity aren’t just using tools and applications. They’re applying a mindset, a framework behind every action. I had to learn those core concepts and ways of thinking. Most of them weren’t even that difficult to understand in fact, many were just common-sense security principles.

Learning the CIA Triad (Confidentiality, Integrity, Availability) helped me understand, as a SOC Analyst, how to look at logs and ask, “What’s being targeted here?”

Here are a few simple examples.

- An employee enters credentials into a fake bank login page → **Confidentiality** is compromised

- The company homepage is defaced with 'Hacked By Anonymous!' → **Integrity** is compromised

- Servers are down due to a flood of packets from an attacker → **Availability** is compromised

I also studied other concepts that helped shape how I approach cybersecurity. Some of these are essential, like the CIA Triad, while others helped me go deeper into attacker behavior.

One was the Cyber Kill Chain by Lockheed Martin a framework that breaks down the steps of a typical cyberattack from reconnaissance to actions on objectives.

I also spent time with the MITRE ATT&CK framework, a powerful knowledge base of adversary tactics and techniques. Some of the most useful categories that stuck with me throughout investigations were:

- TA0043 – Reconnaissance

- TA0001 – Initial Access

- TA0003 – Persistence

- TA0010 – Exfiltration

- TA0011 – Command and Control

Another major focus of mine was core Windows processes, along with Process IDs (PIDs) and Event IDs. Understanding how these work really speeds up investigations. Even with just a basic understanding of legitimate vs suspicious process behavior, you can start seeing red flags quickly.

example:

> powershell.exe or cmd.exe spawned by winword.exe or svchost.exe

That’s a major red flag in most cases. There's rarely a legitimate reason for winword.exe (Microsoft Word) to launch PowerShell and it usually indicates a macro-based attack or command execution abuse.

I also learned to use Windows Event IDs to back up my analysis. Everything you do on a Windows system generates logs, and certain actions create specific Event IDs. Here are two basic but essential examples:

4624 → Successful login

4625 → Failed login

**A few 4625 failures from a known device? Probably a user mistyped their password. But 100+ failures from an unknown IP followed by a 4624? That’s a successful brute-force login, and now we may be looking at a compromised account.**

## I want to make it very clear that not every alert seen by a SOC Analyst is malicious. In fact, most aren’t. But knowing normal Windows behavior, common process names, and frequent Event IDs helps you quickly filter out false positives and focus on what really matters.

## Networking Protocols
A basic working knowledge of common networking protocols also helped me tremendously when investigating attacks and understanding the flow of traffic across a network. Here are a few of the most important ones I focused on:

- DNS (Domain Name System) Translates domain names like google.com into IP addresses. Attackers may abuse DNS for tunneling or data exfiltration.

- HTTP/HTTPS – The primary protocols used for web traffic. I learned to check for suspicious URLs, HTTP methods, and certificate issues.

- FTP/SFTP – Used for file transfers. Anomalies here can indicate data exfiltration or unauthorized uploads.

- SMB (Server Message Block) Commonly used for file sharing on Windows networks. This protocol was famously exploited in the EternalBlue vulnerability.

- ICMP – Often used for ping requests, but also abused for covert communication and reconnaissance.

- TCP/UDP – Core transport layer protocols. Understanding port behavior helped me identify whether traffic was normal or unusual for a given system.

By understanding these protocols and their legitimate use cases, I was better equipped to detect when something abnormal was happening whether it was command and control traffic, data being exfiltrated, or a remote exploit being delivered.


</details>

---

<details>
<summary> ⏩ Onwards</summary>

## Im greatful for my learning, But cybersecurity is a big field there is still much to learn, And real experience to have.

Grabbing my first certification (SAL1) was a big milestone for me, and the months leading up to it were not all smooth sailing. There were times I doubted myself and feared failure. I believe this is normal to feel, and the important thing is to push on when you find something you enjoy doing.

My main goal has been to land a job in the cybersecurity field, and every day I'm working towards that goal. My plans are to write a couple of writeups on challenge rooms on TryHackMe and maybe CyberDefenders. I've also heard some good things about the Google Cybersecurity Certificate, which I'll probably use to learn a few of the same things over again — but like I said, it doesn't hurt to learn the basics a few times over. I believe I'll apply to some entry-level Security Analyst jobs, but another main goal is to grab the Security+ cert from CompTIA around the start of 2026.

With that being said, I hope anyone who has read along learned something. My main goal with this GitHub repo was to help anyone like myself who had no idea where to start in cybersecurity.

I hope you gained inspiration or at least enjoyed reading my story of stepping into cybersecurity...

</details>

---
