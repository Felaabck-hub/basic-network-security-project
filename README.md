# basic-network-secuirty-project
A beginner friendly cybersecurity project using Kali Linux, UFW, and Wireshark.



This is a hands-on, beginner-friendly cybersecurity project designed to introduce foundational concepts in network security using Kali Linux,UFW Firewall, and Wireshark. It demonstrates how basic security measures and network monitoring can help protect small networks from common threats.



 🧰 Tools & Technologies

| Tool             | Purpose                              |
|------------------|--------------------------------------|
| Kali Linux       | Penetration testing & Linux platform |
| UFW Firewall     | Blocking/allowing network traffic    |
| Wireshark        | Capturing and analyzing packets      |
| WPA2/WPA3        | Wireless encryption (router security)|



  🧠 Project Objectives

- Understand different types of network threats
- Learn how to implement basic firewall and encryption configurations
- Capture and analyze real-time traffic using Wireshark
- Identify suspicious activity in network traffic
- Reflect on network security best practices



 ⚠️ Threats Researched

| Threat Type | Description |
|-------------|-------------|
| Virus       | Malicious code that spreads through files and programs |
| Worm        | Self-replicating malware that spreads over a network |
| Trojan      | Malware disguised as legitimate software |
| Phishing    | Attempts to trick users into revealing sensitive info |
| MITM Attack | Intercepts communication between two systems |



🛡️ Implementation Steps

 1. 🔒 Basic Network Setup
- Connected Kali Linux VM to home Wi-Fi
- Changed default router credentials
- Enabled WPA2/WPA3 encryption for secure Wi-Fi

2. 🔥 UFW Firewall Configuration
```bash
sudo ufw enable
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw allow ssh
sudo ufw status verbose


3. 📡 Capturing Network Traffic (Wireshark)
	•	Captured traffic using: sudo wireshark
	•	Filtered by protocol: http, dns, tcp
	•	Identified normal vs. suspicious packets
		
📸 Key Observations from Wireshark
Protocol
Observation
HTTP
Browsing websites (unencrypted)
DNS
Domain resolution requests
TCP SYN Flood
Potential DoS pattern observed
Suspicious IPs
Irregular access attempts from unknown sources


📚 Reflections & Best Practices
	•	Default credentials are dangerous – always change them.
	•	Wi-Fi encryption is non-negotiable – use WPA2/WPA3.
	•	Firewalls matter – even simple rules reduce attack surface.
	•	Monitoring network traffic reveals invisible threats.
	•	Regular updates & awareness are key to good security hygiene.



💡 What I Learned

“Security doesn’t start with advanced tools — it starts with awareness. Even basic setups like firewalls, encrypted Wi-Fi, and traffic monitoring can block serious attacks.”


📢 Educating Others

To teach network security:
	•	Use real-world examples like phishing emails and insecure Wi-Fi.
	•	Demonstrate tools like Wireshark in a live session.
	•	Emphasize everyday habits: password strength, 2FA, avoiding suspicious links.


👨‍💻 Author

Ade-Fernandes Oluwafela
🛠️ Exploring Network Defense | Passionate about Digital Security & Open Source
