# Ubuntu Blue Team Hardening & Audit

## Role
Junior SOC / Blue Team Analyst

## Objective
Perform a security baseline audit and hardening of an Ubuntu 24.04 system
to demonstrate Blue Team / SOC defensive skills.

## Environment
- OS: Ubuntu 24.04 LTS (GNOME)
- Platform: VMware Workstation
- Firewall: UFW
- Tools: ss, ufw, systemctl, journalctl

## Audit Scope
- Network exposure (listening ports)
- Running services
- Firewall baseline
- Local attack surface
- Hardening actions

## Baseline Findings
- No externally exposed TCP services
- Avahi (mDNS) running by default
- Firewall disabled by default

## Hardening Actions
- Enabled UFW with deny-by-default policy
- Disabled and removed unnecessary discovery services
- Verified reduced network attack surface

## Evidence
See `evidence/` directory for command outputs and system state before/after.

## Skills Demonstrated
- Linux security auditing
- Blue Team hardening
- SOC-style reasoning
- Risk-based decision making
- Clear documentation

## Next Steps
- Network traffic analysis
- Log analysis (auth, system)
- Incident-style reporting
# ubuntu-blue-team-hardening
Ubuntu 24.04 Blue Team hardening, firewall baseline, service audit, and SOC-style reporting.
