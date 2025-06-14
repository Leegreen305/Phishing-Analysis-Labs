# Phishing-Analysis-Labs
Labs for Phishing Detection &amp; Threat Analysis

# 🛡️ Phishing Website Analysis – SutterHealth Phish Investigation

## 📄 Overview

This project is part of my cybersecurity portfolio to demonstrate phishing investigation and threat analysis skills. The target was a suspicious website masquerading as a SutterHealth login or donation portal, reported on PhishTank.

## 🔗 URL Investigated

```
https://sutterhealth.donordrive.com/index.cfm?fuseaction=donorDrive.contactUsThanks
```

## 📸 Screenshot of Site

![Phishing Screenshot](sutterhealth_phishing_screenshot.png)

---

## 🧪 Tools Used

* 🔍 [PhishTank](https://phishtank.com/) – to find and verify recent phishing reports
* 🛰️ [urlscan.io](https://urlscan.io) – for domain scanning, IP tracing, and threat indicators
* 🛠️ Git & GitHub – for version control and portfolio presentation

---

## 📊 Key Findings

* Website used a domain mimicking SutterHealth but hosted on `donordrive.com`, a platform often used for fundraising.
* Scan showed:

  * **12 IPs** across **5 countries**
  * **31 HTTP requests**
  * Hosted on **CLOUDFLARE** infrastructure
* Screenshot and behavior confirmed it was **actively online** and potentially malicious.

---

## 🎯 Learning Outcomes

* Practiced phishing site investigation and documentation
* Learned to use urlscan.io for behavior analysis
* Built documentation suitable for a professional security portfolio

---

## 📁 Repository Contents

| File                                   | Description                              |
| -------------------------------------- | ---------------------------------------- |
| `README.md`                            | Project overview and documentation       |
| `sutterhealth_phishing_screenshot.png` | Screenshot of phishing site              |
| `urlscan_summary.txt` (optional)       | Copied summary of technical scan results |



