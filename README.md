# LTHW - nmap - The Network Mapper

DO NOT ping
```bash
nmap -Pn TARGET_IP
```

Scan all ports
```bash
nmap -p- TARGET_IP
```

Scan HTTP Headers
```bash
nmap -sV --script=http-headers scanme.nmap.org
```

Scan SMB Server
```
nmap --script smb-os-discovery -p445 TARGET_IP
```
