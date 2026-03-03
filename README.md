# Splunk SIEM Labs

This repository documents my hands-on work using **Splunk as a SIEM**, focused on log ingestion, searching, and basic security analysis of Windows authentication activity.

The goal of this lab is to build practical familiarity with how security-relevant events appear in logs and how they can be explored and analyzed in Splunk, similar to entry-level SOC workflows.

---

## 🧪 What This Lab Covers
- Setting up a Splunk lab environment
- Ingesting **Windows Security Event Logs**
- Analyzing authentication activity (successful and failed logins)
- Identifying baseline behavior versus potentially suspicious patterns

---

## 📁 Repository Structure
- **Splunk Setup/**  
  Environment setup notes, configuration steps, and initial Splunk configuration

- **Windows Security Logs/**  
  Analysis of Windows authentication events, including successful and failed login attempts, with documented observations and interpretation

---

## 🔧 Tools Used
- Splunk Enterprise
- Windows Event Logs (Security)
- Windows 10 Pro (VirtualBox VM)

---

## 📘 What I Learned
- How Windows authentication events (Event IDs 4624 and 4625) are generated and logged
- How to ingest and validate Windows Security logs in Splunk
- How failed login activity can indicate user error or potential brute-force behavior
- How SIEM tools support visibility and investigation of authentication-related events
