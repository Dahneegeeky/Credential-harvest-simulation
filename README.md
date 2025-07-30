## 🎯 Ethical Hacking Lab Project: Social Engineering Attack Simulation

This is a completed lab project from my **Ethical Hacking class**, where I simulated a phishing attack using the **Social Engineering Toolkit (SET)** on Kali Linux. The goal was to understand how attackers exploit human behavior through social engineering techniques like phishing to extract sensitive credentials.

> ⚠️ **Disclaimer:** This lab was conducted in a controlled lab environment for educational purposes only. Unauthorized use of these techniques is illegal.

---

## 📌 Objective

- Simulate a phishing attack using SET to demonstrate how legitimate websites can be cloned and used to harvest user credentials.
- Learn the steps an attacker might take in a social engineering scenario.
- Explore how easily users can be manipulated when proper security awareness is lacking.

---

## 🛠️ Tools Used

- 🐉 Kali Linux (Rolling Release)
- 🧰 Social Engineering Toolkit (SET)
- 🌐 Local network for controlled testing
- 📡 IP address via `ifconfig`
- Terminal and basic Linux command knowledge

---

## 🧪 Lab Summary

In this lab, I used the Social Engineering Toolkit to clone the http://testphp.vulnweb.com/login.php
login page and host it locally. I simulated an attack by sharing the malicious link (within the lab) and tested how credentials entered into the cloned site were logged and stored.

### 🔧 Steps Performed:

1. **Launched SET**
   ```bash
   sudo setoolkit


  Chose: 1) Social-Engineering Attacks

   Then: 2) Website Attack Vectors

   Then: 3) Credential Harvester Attack Method

2. cloned http://testphp.vulnweb.com/login.php

  Selected: 2) Site Cloner

  Entered my local IP address

  Chose: http://testphp.vulnweb.com/login.php as the target URL

  Hosted the Fake Page Locally

  SET generated and hosted the cloned site on port 80

  Link was shared in the lab-controlled environment

3. Credential Harvesting

    When test users entered dummy credentials, they were logged in.


Screenshots of this project and Report in XML added to my repo 
