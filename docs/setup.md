# Setup and environment

## Confirmed starting point
Date: 20 October 2026.

Command in Windows PowerShell:
```powershell
wsl --list --verbose
```
Observed: kali-linux was the default distribution, stopped, WSL version 2; Debian was stopped, WSL version 2.

## Next checks
Start Kali from PowerShell:
```powershell
wsl -d kali-linux
```
Run individually inside Kali:
```bash
whoami
cat /etc/os-release
ip -br addr
command -v sshd
sudo service ssh status
sudo ss -lntp
```
Record actual output and interpretation before changing configuration. Service-management commands depend on whether systemd is enabled. An absent executable or unrecognised service is a diagnostic observation, not proof of a completed installation.

## Pending setup record
Document prerequisites, installation if needed, service startup, relevant configuration and successful verification. Record the Windows client command, destination address, port and authentication method actually used. Explain the WSL networking behaviour observed.

## Verification record
For each check record: command; expected behaviour; actual result; interpretation; next action. Do not publish passwords or private keys.
