## Project 4 – DHCP Discover Flood & Recovery

Simulated a DHCP flood attack using **Yersinia**, then restored client access and analyzed normal DHCP traffic exchange.

### 🧰 Tools

- Ubuntu 22.04, Yersinia, tcpdump, Wireshark, DHCP client

### ✍️ What I did

- Launched a DHCP Discover Flood (DoS) from attacker VM  
- Observed client failure to obtain IP address  
- Stopped the attack and verified address recovery (192.168.x.x)  
- Analyzed DHCP 4-way exchange (Discover → Offer → Request → ACK)
