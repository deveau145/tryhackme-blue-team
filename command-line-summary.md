# 💻 TryHackMe Command Line Section Summary

> This writeup summarizes what I learned from the Command Line section in TryHackMe's Cyber Defense 101 pathway.

---

## 🔎 Overview
The Command Line section introduced essential tools for navigating and controlling Windows and Linux systems. These are foundational for threat detection, log analysis, and incident response.

---

## 📄 Modules Covered
### 1. Windows Command Line
- `dir`, `ipconfig`, `netstat`, `tasklist`, `whoami`
- Practical use: Identify system info, open ports, and running processes
- 🔍 Example: Used `netstat -ano` to detect suspicious listening ports

### 2. Windows PowerShell
- Cmdlets: `Get-Process`, `Get-Service`, `Set-ExecutionPolicy`
- Scripting basics and working with output pipes
- 🔐 Importance: Understanding privilege levels and script execution

### 3. Linux Shells
- Commands: `ls`, `chmod`, `cat`, `grep`, `find`, `history`
- File permission management with `chmod` and `chown`
- Bash vs other shells

---

## 🔗 Tools & Techniques Learned
- How to pivot between CMD, PowerShell, and Bash
- How attackers might hide persistence (e.g., PowerShell scripts in startup)
- Core sysadmin commands that help investigate incidents

---

## 📊 Reflection
This section reinforced how essential CLI skills are for cybersecurity. I can now:
- Navigate unfamiliar systems efficiently
- Pull useful data from logs and network settings
- Understand how adversaries use the same tools we do

Next up: **Networking** 🧠

---

## 🔹 Related Repos or Notes
- `study-tracker/weekly-study-tracker.md`
- [My GitHub Profile](https://github.com/deveau145)

> "Command line skills are the toolkit of both defenders and adversaries — know both sides."
