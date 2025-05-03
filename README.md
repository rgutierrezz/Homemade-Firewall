# Homemade Firewall

## Objective
To deploy and configure a secure homemade firewall on a linux based cloud server using UFW (Uncomplicated Firewall). The goal is to manage the incoming and outgoing network traffic, enforce the pivallage access, and strengthen the server security with our fundamental firewall tools.

### Skills Learned
- Configured UFW on  alinux based VPS.
- Deployed and accessed a cloud based server using our own unique SSH key authentication.
- Allowed and verified access for SSH (22), HTTP (80), and HTTPS (443).
- Applied default deny-all policies with allow-listed ports for our choosen essential services.
- Performed remote firewall management and connectivity troubleshooting.

### Tools Used
- UFW (for firewall rule management)
- SSH (for secure remote server access)
- DigitalOcean (for Linux VPS hosting)
- Ubuntu Linux (server operating system)
- Web browser (to confirm HTTP port reachability)

## Steps
- Created and connected to a new Ubuntu Linux VPS on DigitalOcean using a unique SSH key-based login.
- Updated our system and installed UFW.
- Allowed the OpenSSH service to prevent locking out remote access.
- Enabled UFW and set a default policy to deny all incoming traffic.
- Opened ports 80 (HTTP) and 443 (HTTPS) to allow potential web traffic.
- Verified the firewall rules with ufw status verbose and nmap scans.
- Confirmed that only allowed ports were open and all others were blocked.
