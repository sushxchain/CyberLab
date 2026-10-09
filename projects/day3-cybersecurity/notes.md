# Day 3: Cybersecurity Fundamentals

## 1. What Is Cybersecurity?

Cybersecurity is the practice of protecting computers, networks, applications, and data from unauthorized access, attacks, and damage.

## 2. CIA Triad

The CIA Triad is a basic model used in cybersecurity.

- Confidentiality: Only authorized people can access information.
- Integrity: Information remains accurate and is not changed without authorization.
- Availability: Systems and information are accessible when needed.

## 3. Threat, Vulnerability, and Risk

- Threat: Something that could cause harm to a system.
- Vulnerability: A weakness in a system.
- Risk: The possibility of a threat exploiting a vulnerability and causing harm.

## 4. Common Types of Malware

- Virus: Malicious code that attaches to a file or program and spreads when it is executed.
- Worm: Malware that can spread between systems.
- Trojan: Malicious software disguised as legitimate software.
- Ransomware: Malware that locks or encrypts data and demands payment.

## 5. Phishing

Phishing is an attack in which someone uses fake emails, messages, or websites to trick people into revealing sensitive information.

## 6. Brute-Force Attack

A brute-force attack attempts many possible passwords or credentials until a correct one is found.

## 7. Authentication

Authentication is the process of verifying someone's identity.

Examples:
- Passwords
- Fingerprints
- One-time passwords (OTPs)
- Multi-factor authentication (MFA)

## 8. Encryption

Encryption converts readable information into a protected form so that it cannot easily be understood without the appropriate key.

## 9. Firewall

A firewall controls network traffic according to security rules. It helps block unauthorized connections.

UFW is a Linux tool for managing firewall rules.

## 10. Ethical Hacking

Ethical hacking involves testing systems for security weaknesses with proper authorization and within an agreed scope.

## 11. Linux Practical Exercises

### Command 1: whoami

Purpose: Displays the current username.

Result: sushanthbhat

### Command 2: id

Purpose: Displays the user's UID, GID, and group memberships.

Observation: The current user belongs to the sudo group.

### Command 3: ls -l

Purpose: Lists files and directories with permissions, ownership, and other details.

Observation: The CyberLab repository contains labs, osint, projects, resources, tools, and writeups directories.

### Command 4: ps aux | head

Purpose: Displays the first 10 lines of detailed process information.

Observation: The output included system processes running in the Ubuntu WSL environment.

### Command 5: ss -tun

Purpose: Displays TCP and UDP socket information using numeric addresses and ports.

Observation: No matching sockets were listed when the command was executed.

### Command 6: sudo ufw status

Purpose: Checks the status of the UFW firewall tool.

Observation: The command returned "ufw: command not found". UFW may not be installed. This result does not establish whether the Windows or WSL environment is protected by a firewall.

## Key Learnings

- Learned basic cybersecurity terminology.
- Understood the CIA Triad.
- Explored Linux users and group memberships.
- Viewed file permissions and ownership.
- Inspected running processes.
- Practiced checking network sockets.
- Investigated the availability of a firewall management command.

## Day 3 Summary

Today, I learned foundational cybersecurity concepts and practiced Linux commands related to users, permissions, processes, and network sockets.
