# Networking Task 02: Network Devices & IP Addressing

## Objective

The purpose of this task is to understand common network devices, IP addressing concepts, and how data travels within a network.

---

# Part A: Network Devices Research

## Router

### Purpose

A router connects different networks and provides internet access to devices.

### How It Works

It forwards data packets between networks and determines the best path for data.

### Real-World Usage

Home Wi-Fi routers and office network routers.

---

## Switch

### Purpose

A switch connects multiple devices within a local network.

### How It Works

It uses MAC addresses to send data directly to the intended device.

### Real-World Usage

Office LAN environments.

---

## Hub

### Purpose

A hub connects multiple devices in a network.

### How It Works

It broadcasts incoming data to all connected devices.

### Real-World Usage

Older network environments.

---

## Access Point

### Purpose

Provides wireless network connectivity.

### How It Works

It connects wireless devices to a wired network.

### Real-World Usage

Wi-Fi hotspots and office wireless networks.

---

## Firewall

### Purpose

Protects networks from unauthorized access.

### How It Works

It monitors and filters incoming and outgoing network traffic.

### Real-World Usage

Windows Firewall and enterprise security systems.

---

## Modem

### Purpose

Connects a local network to an Internet Service Provider.

### How It Works

Converts ISP signals into digital data for devices.

### Real-World Usage

Home broadband connections.

---

# Part B: IP Address Classification

| IP Address    | Classification |
| ------------- | -------------- |
| 192.168.1.10  | Private        |
| 10.0.0.5      | Private        |
| 172.16.5.20   | Private        |
| 8.8.8.8       | Public         |
| 1.1.1.1       | Public         |
| 192.168.100.1 | Private        |

### Explanation

Private IP addresses belong to reserved ranges used inside local networks.

Public IP addresses are accessible over the Internet and are globally unique.

---

# Part C: Understanding My Network

### IPv4 Address

192.168.150.100

### Default Gateway

192.168.150.1

### DNS Server

192.168.150.1

### Which IP range does your device belong to?

192.168.150.0/24

### Is it Public or Private?

Private IP Address

### What role does your router play?

The router connects my device to the Internet and forwards traffic between local and external networks.

### What would happen if DNS stopped working?

Websites would not open using names like google.com because domain names would not be translated into IP addresses.

---

# Part D: Network Communication Flow

1. The user enters [www.google.com](http://www.google.com) into a browser.

2. The request is sent to the router.

3. The router contacts the DNS server to resolve the domain name.

4. The DNS server returns Google's IP address.

5. The request reaches Google's server.

6. Google sends the webpage response back to the user's device.

---

# Conclusion

This task helped me understand network devices, IP addressing, DNS functionality, and how communication occurs between a device and an Internet server.
