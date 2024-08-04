---
Title: Penetration Testing
Tags: ["guide"]
Image : ""
Description: "script kiddie"
Draft: 
---

## Introduction


## Related tools
- Nmap
- Metasploit
- Exploit Database [Website](https://www.exploit-db.com/)
- enum4linux, SMB share enumeration

## Key concepts
- Enumeration
    - Port scanning
        - `nmap -sC -sV`
    - SMB shares
        - `smbclient -L target_ip`
    - FTP server
    - WinRM
- Gaining access
    - Web shell
- Privillege escalation
    - Restricted shell
        - Usually done with rbash
        - Look for binaries you can execute and check its functionalities to see if you can take advantage of anything
    - Permission
        - Check binaries for SUID permission bit
    - Kernel explits

## .