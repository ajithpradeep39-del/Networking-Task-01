# Networking Task 01

## Objective

The objective of this task is to understand basic networking concepts and identify the network configuration of my system.

---

## System Information

| Item | Value |
|--------|--------|
| Hostname | Asta |
| IPv4 Address | 192.168.150.100 |
| MAC Address | 30-D1-6B-AE-FD-2F |
| Default Gateway | 192.168.150.1 |
| DNS Server | 192.168.150.1 |

---

## Basic Networking Concepts

### What is an IP Address?

An IP Address is a unique numerical address assigned to a device on a network. It allows devices to communicate and exchange data over a network.

### What is a MAC Address?

A MAC Address (Media Access Control Address) is a unique hardware identifier assigned to a network adapter by the manufacturer. It is used for communication within a local network.

### What is a Default Gateway?

A Default Gateway is the router that connects a local network to other networks, such as the Internet. All traffic destined outside the local network is sent through the gateway.

### What is DNS?

DNS (Domain Name System) translates human-readable domain names such as google.com into IP addresses that computers use to communicate.

### Difference Between Public IP and Private IP

| Public IP | Private IP |
|------------|------------|
| Accessible from the Internet | Used within local networks |
| Assigned by ISP | Assigned by router |
| Globally unique | Can be reused in different networks |

---

## Network Diagram

Internet
│
▼
Router (192.168.150.1)
│
▼
Laptop/Desktop (192.168.150.100)

---

## Network Connectivity Test

### Ping Test

Command:

ping google.com

Result:

- Packets Sent: 4
- Packets Received: 4
- Packets Lost: 0
- Minimum Time: 61 ms
- Maximum Time: 74 ms
- Average Time: 68 ms

Status: Successful

### Traceroute Test

Command:

tracert google.com

Result:

Hop 1 → 192.168.150.1 (Router)

Hop 2 → google.com (142.250.207.78)

Total Hops: 2

---

## Conclusion

This task helped me understand how network communication works, how to identify network configuration details, and how tools such as ping and traceroute can be used to test connectivity and analyze network paths.