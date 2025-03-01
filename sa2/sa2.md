# sa2

## Port Scanning

```bash
# rustscan_TCP
sudo $(which rustscan) -a 192.168.1.1 -- -A -oN nmap.txt
```

```bash
# nmap UDP port scanning
sudo nmap -Pn -n 192.168.1.1 -sU --top-ports=100 --reason
```

## Service Enumeration

## Foothold

## Privilege Escalation

### full pty

```bash
# script
script /dev/null -c /bin/bash
```

### Manual Enumeration

### exploit
