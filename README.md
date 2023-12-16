# Level I IT help desk

## Windows

### User support

- user support services
- helpdesk hierarchy

### Incident tracking

- Triangle an incident
- Incident tracking
- Escalating a ticket
- Help desk best practices

### Skills needed for help desk support

- Troubleshooting methodology
- Communication skills
- Critical thinking
- Technical skills for user support

### Common support problems

- most frequent problems
- hardware issues
- software issues
- networking basics
- security vulnerabilities
- when to suspect malware
- when to replace equipment
- software installation

### End user training

- How to speak to non tech users

### Management Tools for help desk staff

- Ticketing systems inventory demonstration
- Malware best practices
- Remote control tools
- Active Directory tools for user management

## Linux

### System resource usage

- use tools like `top`, `htop` or `glances` to monitor CPU, memory and disk usage
- identify any processes consuming excessive resources

### Review Disk Space

Insufficient disk space can impact system performance, check available disk usage using `df` or `du`.

### Check background processes

Use `ps` and `systemctl` to list and manage processes. Review and stop unnecessary background processes and services.

### Evaluate startup application

- Check `/etc/rc.local` or user-specific startup folders.
- Review startup applications and disable unnecessary ones

### Examine system logs

- Review system logs (`/var/log/syslog`, `/var/log/messages` etc) for errors or warnings

### Optimize file system

- Run  `fsck` to check and repair the file system
- Optimize disk performance using tools like `hdparm`.

### Update and upgrade

### Check for malware

### Review network performance

use `ping` or `traceroute` to identify network bottlenecks

### Evaluate hardware health

- use `smartctl` for inspecting harddrive health
- inspect hardware components for signs of failure

### Misc

Optimize desktop environment. Identify and optimize resource-intensive applications.
