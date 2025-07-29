# linux-lab01-02-The-basic-Text-manipulation

# 🐧 Red Team Initial Access Lab: Linux Filesystem & Text Operations (Kali 2025)

## Real-World Scenario

You are an offensive security analyst at **ACME Cyber Defense**. You’ve been granted initial access to a Linux server (Kali 2025) for an audit. Your job is to document how you explore the system, identify key information, and safely manipulate files/text—demonstrating best pentesting practices.

---

## Objective

Show proficiency in Linux navigation, file/text handling, search, filtering, and documentation—skills essential for attackers, defenders, and auditors alike.

---

## Instructions

Read each requirement carefully. Complete every task using the terminal, providing your commands, outputs, and screenshots as evidence. Add brief comments where asked.

---

## 📝 Pentest Assignment Tasks

### 1. Environment & Session Recon

**Management wants you to confirm your access is under your controlled user (not root), and show your current working directory.**

- Display your current username and present working directory.

**Command(s):**
```bash
whoami
pwd
 ```
![Step 1 Output](evidence/step1.png)

- Briefly explain why this information is critical during a pentest.
  
**Explanation:**
Knowing your current user is critical in a pentest because your permissions and access level depend on it. Knowing your present directory prevents mistakes like deleting files in the wrong location or running tools in the wrong folder.


