# 360-CYA-2

## Overview

For this career-yielding adventure, I contributed to the **ASDE** cybersecurity project repository for CPTS-360 by completing two technical issues related to simulated cyberattacks in a virtual lab environment. These issues focused on implementing a **directory enumeration attack** and a **password spray attack**, while integrating both attacks with **Splunk** for real-time log monitoring and alerting.

This work aligned with my goal of gaining hands-on cybersecurity experience by working on realistic attack simulations, detection pipelines, and alert tuning.

## Career Goals

### Short-Term Goal

My short-term goal is to **obtain a cybersecurity internship** where I can gain practical experience in areas like security operations, threat detection, and vulnerability assessment.

### Long-Term Goal

My long-term goal is to **continue building my cybersecurity knowledge** by earning relevant certifications and working on increasingly advanced projects involving attack simulation, detection engineering, and security automation.

## Contributions

### Issue 1: Directory Enumeration Attack

I implemented a **directory enumeration attack** using **Gobuster** from an attacker VM against a victim web server VM. This simulated reconnaissance behavior commonly used by attackers to discover hidden directories on web servers.

The process involved:

* Confirming the web server was active
* Verifying port 80 access
* Running Gobuster against the target web service
* Capturing attack activity in Splunk
* Creating alerts for suspicious enumeration behavior

Artifacts included:

* Gobuster execution logs
* Splunk alert screenshots
* Configuration notes for alert rules

### Issue 2: Password Spray Attack

I implemented a **password spray attack** using **Hydra** against SSH accounts on the victim VM. This simulated an attacker attempting one password against multiple accounts to avoid account lockouts.

The process involved:

* Creating multiple test accounts
* Executing the Hydra password spray attack
* Monitoring authentication logs in Splunk
* Configuring alerts for repeated login attempts across multiple accounts

Artifacts included:

* Hydra terminal output
* Splunk alert screenshots
* Detection rule documentation

## Deliverables

The repository includes:

* Attack implementation documentation
* Splunk alert screenshots
* Configuration details for detection logic
* Reflection report on the experience

## Outcome

Both attacks successfully generated **separate, fast, and non-conflicting alerts in Splunk**, demonstrating correct implementation of both offensive simulation and defensive detection mechanisms.
