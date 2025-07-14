<details>
<summary>🕵️ APT Investigation: Lazarus Group - Operation Troy</summary>
  
https://ibb.co/HfHmWrYD
  
**Lazarus** is one of the many names given to a criminal hacking group likely associated with the North Korean government. You may also see them referred to as **"Hidden Cobra"**, a name used by the U.S. Department of Homeland Security to categorize malicious cyber activity attributed to North Korea.

### Origin  
The earliest known attack traced back to the Lazarus Group occurred on **2009–2012**, during **Operation Troy** — a campaign that launched a series of cyberattacks leveraging **DDoS (Distributed Denial of Service)** techniques to disrupt high-profile targets in both **South Korea** and the **United States**.  
**MITRE ATT&CK ID: T1499**

On **July 4th, 2009**, websites belonging to entities such as the **White House, Pentagon, New York Stock Exchange, Washington Post, NASDAQ**, and **Amazon** were taken offline through Botnet DDoS attacks.

Three days later, on **July 7th**, similar attacks struck **South Korean** government sites including the **Ministry of Defense** and the **National Intelligence Service**.

---

###  Botnets

DDoS attacks were carried out using a **botnet** — a network of compromised machines that attackers controlled remotely through **Command and Control (C2)** infrastructure. The Botnet was used to flood victim websites with traffic, denying access to legitimate users.

However there was more than just a DDoS attack.

South Korean endpoints were also infected with a type of **wiper malware** known as **W32.Dozer**. Delivered via a **Trojan dropper** likely through phishing, this malware had the capability to **erase hard drives** and **wipe the Master Boot Record (MBR)**.
**MITRE ATT&CK ID: T1561.001**

W32.Dozer contained **time-bomb behavior**. Instead of triggering immediately, the malware was designed to **activate on July 10, 2009**. Whether the wiper executed as intended remains unclear.

On **July 9th**, another smaller wave of DDoS attacks were recorded, again targeting South Korean infrastructure. The **U.S. State Department** also reported attempted DDoS attacks to it's public facing websites.

---

### Attribution & Speculation

Most investigations pointed toward **North Korea** as the likely perpetrator of Operation Troy, based on malware signatures and infrastructure. However, **undisputed attribution in cyberattacks is extremely rare**.

---

### Final Notes

This is my **first APT investigation post**, and I plan to document many more in the future. The Lazarus Group has launched numerous campaigns since Operation Troy — many on a far greater scale and with more sophisticated tactics.

Studying APTs is valuable because their **tactics, techniques, and procedures (TTPs)** often shape the **playbooks** used by cyberdefenders today. By understanding how attackers gain initial access, move laterally, and exfiltrate data, we can better detect and stop similar attacks.

Thanks for reading.

</details>
