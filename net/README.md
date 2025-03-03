## LAN

### Prerequirements

1. Completely disable firewall: ufw, firewalld
2. Flush iptables/nftable rules

### P2P connection

1. Divide the students into pairs. Connect every one peer to peer
2. Setup Local Area Network. CIDR must be P2P
3. Ping check
4. P2P file transfer
5. Check local network speed

### LAN connection

1. Divide students into 2 groups. Connect group to switch (preferably hub)
2. Setup Local Area Network
3. Ping check
4. Connect several students to both LANs
5. Setup those students' laptops as router
6. Ping check the other LAN

### WAN

1. Connect several stundets to WiFi
2. Setup Internet access in both LANs
3. *Setup Fault Tolerant Internet access

### Bonus Task 1

1. Setup firewall. Block all incoming connections
2. Allow 8000 port

### Bonus Task 2

1. Stand inline between another student and LAN
2. Create inline L3/L4 firewall

### Decentralized Chat

You got me. Create it. Hack it.

### Homework 1

Create observability jail: netns <--> traffic logging tool <--> internet

### Homework 2

Write Docker alike network containers management script
