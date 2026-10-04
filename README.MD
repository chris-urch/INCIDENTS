# Wazuh Security Monitoring Lab

A practical cybersecurity lab focused on Windows endpoint monitoring, threat detection, investigation, and incident documentation using Wazuh.

## Project Objective

The goal of this project is to build hands-on experience with SIEM monitoring and demonstrate how security events can be collected, detected, investigated, and documented using Wazuh.

## Lab Environment

- Wazuh Manager
- Windows 11 endpoint
- Wazuh Agent
- Windows Security Event Logs
# Incident 01 — Windows Failed Authentication Detection

## Overview

This incident demonstrates how Wazuh detected failed login attempts on a Windows 11 endpoint.

The failed login attempts were intentionally generated on my own Windows laptop as part of a controlled cybersecurity lab.
## Objective

The objective of this test was to:

- Monitor a Windows 11 endpoint using Wazuh.
- Collect Windows Security Event Logs.
- Generate controlled failed login attempts.
- Confirm that Wazuh detects the activity.
- Investigate the security event.
## Test Environment

The test was performed on a Windows 11 laptop connected to a Wazuh Manager through the Wazuh Agent.

Windows Security Event Logs were configured to be collected by the Wazuh Agent.

The Wazuh Agent was confirmed to be active and communicating with the Wazuh Manager before the test was performed.
