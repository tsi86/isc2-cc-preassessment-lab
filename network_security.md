# Network Security

This file contains key network security concepts from the ISC2 Certified in Cybersecurity (CC) pre-assessment.

---

## Common Network Devices

- **Firewall** – Filters incoming and outgoing traffic based on security rules.
- **Router** – Connects different networks and routes traffic.
- **Switch** – Forwards traffic within the same network.
- **Proxy** – Acts as an intermediary between a user and a resource.
- **IDS/IPS** – Intrusion Detection/Prevention Systems monitor and block suspicious traffic.

---

## Network Segmentation

- Separates parts of a network to reduce the attack surface.
- Helps limit lateral movement in case of a breach.
- Common practice: placing critical systems in a separate VLAN or subnet.

---

## Secure Protocols

| Protocol | Purpose | Secure Alternative |
|----------|---------|--------------------|
| HTTP     | Web browsing | HTTPS |
| FTP      | File transfer | SFTP / FTPS |
| Telnet   | Remote access | SSH |
| DNS      | Name resolution | DNSSEC |

---

## Defense-in-Depth

- Layered approach to security.
- Includes firewalls, IDS/IPS, endpoint protection, authentication, and physical security.
- If one layer fails, others still provide protection.

---

## Summary

Strong network security design is fundamental to preventing, detecting, and responding to cyber threats. Use layered controls and secure protocols to protect communications and infrastructure.
