# Task 3 – Network Security Basics

## Objective

To understand basic network security concepts and common attacks such as Man-in-the-Middle (MITM), Denial of Service (DoS), and Packet Sniffing.

## What is Network Security?

Network Security is the practice of protecting network infrastructure, devices, applications, and data from unauthorized access, misuse, disruption, interception, and modification.

The main goals of network security are:

- Confidentiality
- Integrity
- Availability

These principles are commonly known as the CIA Triad.

## 1. Man-in-the-Middle (MITM)

A Man-in-the-Middle attack occurs when an attacker attempts to position themselves between two communicating parties.

### Concept

Normal communication:

User A → User B

MITM concept:

User A → Attacker → User B

The attacker may attempt to observe or modify communication.

### Real-World Example

An attacker on an insecure or compromised public Wi-Fi network may attempt to interfere with users' network communication.

### Risks

- Data interception
- Credential exposure
- Session interception
- Communication modification
- Privacy loss

### Prevention

- Use HTTPS.
- Use secure Wi-Fi networks.
- Use VPN where appropriate.
- Validate security certificates.
- Avoid sensitive activities on suspicious networks.

## 2. Denial of Service (DoS)

A Denial of Service attack attempts to make a service or system unavailable to legitimate users.

An attacker may attempt to exhaust resources such as:

- Bandwidth
- CPU
- Memory
- Network connections
- Application resources

### Prevention

- Rate limiting
- Traffic filtering
- Network monitoring
- Redundancy
- DDoS protection
- Capacity planning

## 3. Packet Sniffing

Packet sniffing is the process of capturing and analyzing network packets.

It can be used legitimately for:

- Network troubleshooting
- Security monitoring
- Incident investigation
- Protocol analysis

However, unencrypted network traffic may expose sensitive information.

### Prevention

- Use HTTPS and TLS encryption.
- Use VPN when appropriate.
- Use secure network protocols.
- Avoid transmitting sensitive information over unsecured networks.

## Security Best Practices

Some important network security practices include:

- Use strong passwords.
- Keep systems and software updated.
- Use firewalls.
- Encrypt sensitive communication.
- Monitor network activity.
- Use secure Wi-Fi.
- Restrict unnecessary network access.

## Result

I learned the basic concepts of network security and understood how MITM, DoS, and packet sniffing can affect network communication. I also learned basic methods for reducing these security risks.
