# OSCP

## Recon

[1. nmapAutomater](https://github.com/stephenlthorn/nmapAutomator)

nmap command

```bash
nmap -sC -sV -oA nmap/initial <<IP_ADDRESS>>
```

can add the -sT option if there is a firewall product that would detect you as a bot. sT completes the handshake.
