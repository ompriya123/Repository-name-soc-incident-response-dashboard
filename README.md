# 🔐 Security Event Monitoring and Incident Response Dashboard

A web-based **SOC Incident Response Dashboard** developed using **Python Flask and SQLite** to monitor security events, track incident severity, and manage the incident response lifecycle.

This project was developed as **Task 5 of my cybersecurity internship** to demonstrate practical understanding of SOC monitoring and incident response processes.

---

## 📌 Project Overview

Security Operations Center (SOC) analysts continuously monitor security events and investigate suspicious activities.

This project simulates a basic SOC environment where security events can be:

- Monitored
- Classified based on severity
- Investigated
- Contained
- Resolved

The dashboard provides a centralized interface for managing security events and tracking the incident response workflow.

---

## 🎯 Objectives

- Monitor security events through a centralized dashboard
- Classify events based on severity
- Identify and track suspicious activities
- Manage security incidents
- Demonstrate the incident response lifecycle
- Maintain incident investigation records
- Import and export security event data

---

## 🚀 Features

### 📊 Security Event Dashboard

- Total security event count
- Critical event count
- High severity event count
- Medium severity event count
- Low severity event count
- Security event table
- Search functionality

### 🚨 Severity Classification

Security events are categorized as:

- 🔴 Critical
- 🟠 High
- 🟡 Medium
- 🟢 Low

### 🔍 Incident Investigation

The dashboard supports investigation of security incidents by recording:

- Incident ID
- Attack type
- Source IP address
- Severity
- Investigation details
- Response actions

### 🔄 Incident Response Lifecycle

The project demonstrates the following incident response workflow:

```text
Detected
    ↓
Investigating
    ↓
Contained
    ↓
Resolved
