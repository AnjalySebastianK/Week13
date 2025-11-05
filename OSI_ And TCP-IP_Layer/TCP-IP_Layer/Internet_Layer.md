# Internet Layer

## 1. Functionality
- Responsible for **logical addressing** and **routing** packets from source to destination across multiple networks.
- Provides **best-effort delivery**; does not guarantee reliability.
- Handles **fragmentation and reassembly** of packets if necessary.
- Supports communication between hosts on different networks (IP layer).

---

## 2. Sublayers
The Internet Layer generally does not have formal sublayers, but conceptually:
1. **Logical Addressing & Routing** – Determines IP addressing and best path.
2. **Packet Forwarding / Delivery** – Moves packets across routers to the destination.

---

## 3. Devices
- **Routers** – Forward packets between networks.
- **Layer 3 Switches** – Perform routing along with switching.
- **Firewalls** – Filter traffic based on IP addresses.
- **Gateways** – Connect networks using different architectures or protocols.

---

## 4. Protocols
- **IPv4 / IPv6** – Provides addressing and routing.
- **ICMP (Internet Control Message Protocol)** – Error reporting and diagnostics.
- **IGMP (Internet Group Management Protocol)** – Manages multicast group membership.
- **IPsec** – Secures IP packets (encryption and authentication).

---

## 5. Attacks
- **IP Spoofing** – Forging source IP addresses to impersonate a host.
- **ICMP Flood / Ping of Death** – Denial-of-service attacks using ICMP.
- **Smurf Attack** – ICMP broadcast amplification.
- **Routing Attacks** – Route hijacking, blackhole attacks.
- **Fragmentation Attacks** – Exploit fragmented packets to bypass filters.

---

## 6. Mitigation
- **Packet Filtering** – Block malicious traffic using firewalls and ACLs.
- **Ingress & Egress Filtering** – Prevent IP spoofing.
- **ICMP Rate Limiting** – Control ICMP traffic to prevent flooding.
- **Secure Routing Protocols** – Use authentication (e.g., OSPF with MD5).
- **VPN & Encryption** – Secure data in transit.
- **IDS/IPS Deployment** – Detect and block suspicious traffic.
- **Network Segmentation** – Isolate networks to reduce attack impact.
