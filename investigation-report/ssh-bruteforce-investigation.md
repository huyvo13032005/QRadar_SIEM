# SSH Brute Force Investigation

## Incident Summary
Multiple failed SSH login attempts were detected.

## Source IP
208.100.26.100

## Destination IP
208.100.26.131

## Attack Type
SSH Brute Force

## Evidence
- Failed password logs
- PAM authentication failures
- Multiple authentication attempts

## MITRE ATT&CK
T1110 - Brute Force

## Recommendation
- Enable Fail2Ban
- Restrict SSH access
- Disable password authentication
