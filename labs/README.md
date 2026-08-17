# labs/

Home lab setups and writeups. Phase 1 = attack/observation (Kali + Metasploitable 2). Phase 2 = detection (SIEM + victim + attacker).

## Phase 1: Attack/Observation

Goal: run real attacks and **watch what they leave behind** — logs, traffic, processes. You cannot detect an attack you have never seen.

Planned setup:
- VirtualBox (free)
- Kali Linux (attacker)
- Metasploitable 2 (victim, intentionally vulnerable)

Planned first attacks to run and document:
1. Service exploitation (known CVE against a service)
2. Brute force attempt (ssh)
3. Default credentials login

## Phase 2: Detection

Planned (after Core SOC Solutions + Security Monitoring modules):
- Free SIEM (Splunk Free / Elastic / Wazuh)
- Feed it phase-1 attack logs
- Write detection rules against attacks I have seen
- Practice triage end-to-end

## Hardware note

Phase 1 runs on an 8GB desktop. Phase 2 targets a 32GB upgrade (planned December 2026).
