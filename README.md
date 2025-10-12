# Linux-SysAdmin

1. Tools :
- Virtual Box (NAT & Host Only)
- Ubuntuserver (CPU 2, 2GB RAM)

2. Konfigurasi Network :
network:
    version: 2
    ethernets:
      enp0s3:
        dhcp4: true

      enp0s8:
        addresses:
          - 10.10.10.11/24
        dhcp4: false
