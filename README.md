# Born2beroot
*This project aims to introduce you to the wonderful world of virtualization.*

## Mandatory Part
### Operating System Selection
Debian
### System Configuration
- Graphical Interface: X.org or any graphical server installation is prohibited to minimize resource usage and enhance security.
- SELinux: Security-Enhanced Linux provides Mandatory Access Control (MAC) and must be configured to meet project requirements.
- AppArmor: Mandatory for Debian, AppArmor provides security profiles for applications and must be enabled at startup.
Security Measures
- SSH Configuration: SSH service runs on port 4242 to enhance security. Root SSH login is disabled to prevent unauthorized access.
- Firewall Configuration: UFW (Uncomplicated Firewall) for Debian and firewalld for Rocky Linux are used to allow only port 4242 and restrict other ports.
### User Management
- Hostname: Hostname must match your login ending with '42'.
- Password Policy: Implement strict password policy including expiration, complexity requirements, and restrictions.
- Sudo Configuration: Configure sudo access with limited authentication attempts, custom error messages, logging, and path restrictions.
- Monitoring Script (monitoring.sh)
- Bash Script: Develop a script to display system information periodically using wall command.
- System Information: Display various system metrics including CPU, RAM, disk, network, and user information.
