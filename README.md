# Overview

Welcome to the `Cybersecurity Incident Response` README for our multimedia company. This document provides insights into a recent security incident involving a `Distributed Denial of Service (DDoS) attack`. Please navigate through the sections below for a detailed overview.

## Scenario

### Context

You are a cybersecurity analyst working for a multimedia company that offers `web design services`, `graphic design`, and `social media marketing solutions` to small businesses. 

### Impact

During the attack, the organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources.

### Incident Details

Our organization recently experienced a `DDoS attack` that compromised the internal network for two hours until it was resolved.

- **Duration**: 2 hours
- **Incident Type**: DDoS attack
- **Resolution**: Incident management response

### Measures Implemented to Address Security Event

To mitigate the impact of the recent security event, the network security team swiftly implemented several crucial measures:

1. **Firewall Rate Limiting:** A new firewall rule was established to restrict the rate of incoming ICMP packets, effectively mitigating vulnerabilities to flooding attacks.

2. **Source IP Address Verification:** Enhanced firewall configurations were implemented to scrutinize incoming ICMP packets, specifically checking for spoofed IP addresses to prevent potential attacks leveraging falsified origins.

3. **Network Monitoring Software:** Specialized software was deployed to detect irregular traffic patterns, allowing proactive identification of potential threats or anomalies within the network.

4. **Intrusion Detection/Prevention Systems (IDS/IPS):** The implementation of IDS/IPS systems enables intelligent filtering of ICMP traffic based on suspicious characteristics, bolstering our defense mechanisms against potential threats.

These proactive measures significantly enhance our network security posture, reducing the likelihood of similar incidents in the future.

## License

> This project is licensed under [`Google Cybersecurity Professional Certificate`](https://www.coursera.org/professional-certificates/google-cybersecurity?isNewUser=true#testimonials).
