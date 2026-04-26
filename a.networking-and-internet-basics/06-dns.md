# DNS (Domain Name System)

## Overview

DNS (Domain Name System) is a system that translates human-readable domain names into IP addresses.

It allows users to access websites using easy-to-remember names instead of numerical addresses.

---

## Why It Matters

Understanding DNS is important because:

- It enables access to websites using domain names
- It connects human-friendly names to machine-readable addresses
- It is essential for all internet-based communication
- It plays a key role in how web requests are handled

---

## Key Concepts

- Domain Name: A human-readable name used to identify a website
- IP Address: A numerical address used by devices on a network
- DNS Resolution: The process of converting a domain name into an IP address
- DNS Server: A system that stores and provides DNS records

---

## How It Works

When a user enters a domain name in a browser:

1. The system checks if the address is already known (cached)
2. If not, a request is sent to a DNS server
3. The DNS server looks up the corresponding IP address
4. The IP address is returned to the device
5. The browser uses the IP address to connect to the server

This process happens quickly and is usually invisible to the user.

---

## DNS Hierarchy

DNS operates in a hierarchical structure:

- Root level
- Top-level domains (such as .com, .org)
- Domain level (specific website names)

Each level helps direct the request to the correct location.

---

## Types of DNS Records

DNS records store information about domains. Common types include:

- A Record: Maps a domain to an IP address
- CNAME Record: Maps one domain name to another
- MX Record: Specifies mail servers for a domain
- TXT Record: Stores additional information

---

## Caching

To improve performance:

- DNS results are temporarily stored (cached)
- Future requests can use cached data instead of repeating the lookup
- This reduces load and speeds up access

---

## Summary

DNS is a system that converts domain names into IP addresses, enabling users to access websites easily.

It plays a critical role in internet communication by connecting user-friendly names with network-level addresses.
