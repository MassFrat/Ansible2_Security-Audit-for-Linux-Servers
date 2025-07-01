# Securing Linux Servers: SSH Configuration and Port Management

<br/>

This guide provides step-by-step instructions for securing Linux servers by configuring SSH access and implementing firewall rules to allow only essential ports (22, 80, and 443).

<br/>

## Overview:
Server security is critical for protecting your infrastructure from unauthorized access and attacks. This guide covers:

SSH service configuration and hardening
Firewall configuration using iptables and ufw
Port management for web services
Best practices for ongoing security

<br/>

## Prerequisites:

Root or sudo access to the Linux server
Basic understanding of Linux command line
SSH client for remote access

<br/>


## Port Configuration Strategy:
## Allowed Ports:

Port 22: SSH (Secure Shell) - For remote server administration
Port 80: HTTP - For web traffic (unencrypted)
Port 443: HTTPS - For secure web traffic (encrypted)

<br/>

## Troubleshooting
## Common Issues:

Locked out of SSH: Always test configuration before closing current session
Web services not accessible: Ensure web server is running and configured properly
Firewall blocking legitimate traffic: Review and adjust rules as needed

## Emergency Access:

Keep console access available (physical or virtual console)
Have alternative access methods configured
Document recovery procedures

<br/>

## Security Best Practices:

Use SSH keys instead of passwords
Change default SSH port if possible
Implement multi-factor authentication
Regular security audits
Monitor system logs
Keep software updated
Use strong passwords for user accounts
Limit user privileges (principle of least privilege)
Regular backups of configuration files
Network segmentation where possible
