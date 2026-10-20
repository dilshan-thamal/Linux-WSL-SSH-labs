# Linux SSH Administration and Troubleshooting Lab

A Windows and Kali Linux WSL2 lab demonstrating service administration, SSH access and systematic troubleshooting.

## Purpose
Establish remote terminal access from Windows to a local Linux environment, diagnose common service and authentication failures, and produce reproducible technical documentation.

## Current status
**In progress.** On 20 October 2026, `wsl --list --verbose` confirmed Kali Linux and Debian installed under WSL2. Kali was the default distribution; both were stopped. Current SSH installation, service state and connectivity have not yet been verified in this project.

## Environment
Windows SSH client → Kali Linux under WSL2 → OpenSSH server.

WSL networking and service management will be documented as observed. This environment is not assumed to behave identically to a separate production Linux server.

## Skills and evidence
| Skill | Evidence required | Status |
|---|---|---|
| Environment inventory | WSL distributions and version output | Observed |
| Linux administration | OS, user, service status and configuration checks | Pending |
| Network diagnostics | Interpret interfaces, addresses and listening TCP sockets | Pending |
| SSH administration | Successful connection and key authentication | Pending |
| Troubleshooting | Failure, hypotheses, checks, root cause, recovery and retest | Pending |
| Technical documentation | Reproducible setup and case reports | In progress |

## Completion checklist
- [x] Identify installed WSL distributions and versions.
- [ ] Record Linux version, current user, interfaces and service state.
- [ ] Verify or install OpenSSH server.
- [ ] Connect from Windows and explain the address and port used.
- [ ] Configure and verify SSH key authentication.
- [ ] Diagnose and recover from a stopped-service failure.
- [ ] Diagnose and recover from an authentication failure.
- [ ] Publish sanitised evidence and a short walkthrough.

## Documentation
- [Setup and environment](docs/setup.md)
- [Troubleshooting case template](docs/troubleshooting.md)
- [Skills evidence](docs/skills-evidence.md)
- [Evidence guidance](evidence/README.md)

## Scope and limitations
Local lab only; no router changes or public SSH exposure are required. This is learning-lab experience, not a claim of production system administration. Mark milestones complete only after observing and recording their results.

## Planned schedule
Approximately six focused hours across three sessions: inventory and setup (1.5 hours), connectivity and troubleshooting (2.5 hours), documentation and review (2 hours). Adjust after inspecting the environment.
