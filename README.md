# Justin's Lab

Personal homelab used for learning systems administration, virtualization, networking, Docker, monitoring, and infrastructure management.

## Hardware

 - Proxmox Host
   - HP EliteDesk 800 G1 Mini
     - RAM: 8 GB
     - Internal storage: 1 TB Samsung SSD
     - External storage: 2 TB Seagate FireCuda SSHD
     - Hypervisor: Proxmox VE

## Network Devices

 - Proxmox 
   - IP: 192.168.1.10
   - Purpose: Virtualization host
 - docker01 
   - IP: 192.168.1.20
   - Purpose: Debian Docker server

## Network Configuration

 - Subnet: 192.168.1.0/24
 - Gateway: 192.168.1.1

## VMs

 - docker01
   - OS: Debian 13
   - VM ID: 100
   - CPU: 2 cores
   - RAM: 4 GB
   - Disk: 100 GB
   - Docker Engine
   - Docker Compose

## Docker Services

 - Jellyfin
   - Port: 8096
   - Purpose: Media server
 - Nginx Proxy Manager
   - Port: 80/81/443
   - Purpose: Reverse proxy
 - Uptime Kuma
   - Port: 3001
   - Purpose: Monitoring
 - Portainer
   - Port: 9443
   - Purpose: Docker management
 - Dozzle
   - Port: 9999
   - Purpose: Docker logs
 - Dashy
   - Port: 4000
   - Purpose: Lab dashboard
 - IT-Tools
   - Port: 8082
   - Purpose: IT utilities
 - whoami
   - Port: 8081
   - Purpose: Reverse proxy testing
 - Adguard Home
   - Port: 3000/53
   - Purpose: DNS and ad blocking

## Storage

External storage is mounted at:
'/storage'

Directories:
 - '/storage/media/movies'
 - '/storage/media/tv'
 - '/storage/media/music'
 - '/storage/media/books'
 - '/storage/roms'

Samba shares:
 - '\\192.168.1.20\media'
 - '\\192.168.1.20\roms' 

## Domain

'justinmh.it.com'

Services:
 - 'jellyfin.justinmh.it.com'
 - 'portainer.justinmh.it.com'
 - 'kuma.justinmh.it.com'
 - 'dozzle.justinmh.it.com'
 - 'dash.justinmh.it.com'
 - 'tools.justinmh.it.com'

## Technologies

 - Proxmox VE
 - Debian Linux
 - Docker
 - Docker Compose
 - Nginx Proxy Manager
 - AdGuard Home
 - Samba
 - Git
 - PowerShell
 - Networking
 - DNS
 - Reverse proxying
 - Virtualization

## Goals

 - Build a Windows AD environment
 - Learn Group Policy
 - Practice Windows Server administration
 - Improve PowerShell scripting
 - Implement automated backups
 - Improve Docker networking
 - Implement HTTPS
 - Expand monitoring
 - Document infrastructure changes
# homelab
