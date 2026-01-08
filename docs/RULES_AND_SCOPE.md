# RULES_AND_SCOPE

## Purpose
This repository documents Shane’s I.T. Platform (SITP) and Shane’s SITP Lab (SSL).
It exists to demonstrate hands-on Help Desk and junior system administration skills
using real tooling, structured troubleshooting, and repeatable lab workflows.

## Scope

### In Scope
- Home lab infrastructure and design decisions
- Windows and Active Directory fundamentals
- User account lifecycle management
- Permissions, shares, and authentication testing
- Networking fundamentals and troubleshooting
- Hyper-V virtualization
- Break/Fix scenarios using a Help Desk workflow
- Ticket-style technical documentation

### Out of Scope
- Passwords, license keys, recovery codes, or secrets
- Personally identifiable information
- Screenshots containing sensitive system data
- Production or employer-owned environments

## Documentation Standards
- Documentation prioritizes clarity and repeatability
- Steps must be reproducible by another technician
- When applicable, documentation follows a ticket-style format:
  - Problem
  - Symptoms
  - Root Cause
  - Resolution
  - Verification
  - Prevention Notes

## SSL Folder Structure
- All lab work resides under `/ssl`
- Day 1–2 use README-only documentation
- Day 3+ include README.md and a screenshots folder

## Screenshot Rules
Screenshots are captured only to prove task completion.
Low-value screenshots are intentionally excluded.

Required proof screenshots may include:
- Active Directory Users and Computers showing correct OUs/users
- User account status changes (enabled/disabled)
- Domain authentication proof on client systems
- Key Help Desk workflows (password resets, forced password change)

Screenshots are stored per lab day in `/screenshots` and referenced in README files.

## Troubleshooting Methodology
All break/fix exercises follow a structured Help Desk workflow:
1. Identify the problem
2. Establish a theory
3. Test the theory
4. Plan the fix
5. Implement the fix
6. Verify system functionality
7. Document and prevent recurrence
