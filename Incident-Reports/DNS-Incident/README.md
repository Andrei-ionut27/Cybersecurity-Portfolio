# DNS Incident Report – Network Traffic Analysis

## Overview

This project analyzes a DNS network issue using a tcpdump log. During the investigation, DNS requests sent over UDP failed because the DNS server returned an ICMP "Destination Port Unreachable" message.

## Objective

- Analyze network traffic
- Identify the affected protocol
- Determine the root cause
- Document the incident in a professional report

## Skills Demonstrated

- DNS Analysis
- UDP
- ICMP
- TCP/IP Networking
- Packet Analysis
- Incident Reporting
- Cybersecurity Investigation

## Files

- DNS-Incident-Report.md
- tcpdump-log.txt

## Outcome

The investigation concluded that DNS requests could not reach the DNS server because UDP port 53 was unreachable. As a result, the website's domain name could not be resolved, preventing users from accessing the website.
