# 🛡️ Phishing Email Analysis Report  
**Internship Task – Elevate Labs (Task 2)**

---

## 🎯 Objective:
To analyze a suspicious phishing email and identify key indicators that demonstrate email spoofing and social engineering.

---

## 📥 Sample Email Analyzed:
**Subject:** Urgent Action Required – Account Suspension Notice  
**Sender:** PayPaI <support@paypai.com>  
**Fake URL:** https://secure-paypai.com/verify  
**Received Date:** August 6, 2025  
**Header Analyzer Used:** [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)

---

## 🔍 Phishing Indicators Identified:

| # | Indicator | Description |
|---|-----------|-------------|
| 1 | **Spoofed Email Address** | The sender uses `paypai.com` instead of the official `paypal.com` |
| 2 | **Visual Trick in Sender Name** | The name “PayPaI” uses a capital “I” instead of lowercase “L” |
| 3 | **Urgency** | Email threatens account suspension within 24 hours |
| 4 | **Suspicious URL** | Hovering over the link shows a domain not owned by PayPal |
| 5 | **Generic Greeting** | Uses “Dear Customer” instead of user's real name |
| 6 | **Grammar Issues** | Minor spelling/spacing issues indicating non-professional origin |
| 7 | **Header Mismatch** | Return-Path: `scam@phishingsite.ru` indicates spoofed origin |

---

## 🧠 Key Learnings:
- Phishing emails use urgency and fear to trick users.
- Email headers reveal important source details.
- Hovering over links can expose fake URLs.
- Grammar errors and generic greetings are common indicators.
- Always verify sender domains and email sources.

---

## 📁 Deliverables:
- `phishing_email_sample.txt` – Raw email text
- `README.md` – This report

---

## 🛡️ Outcome:
Enhanced awareness of **email phishing tactics**, improved skills in **header analysis**, and ability to detect **social engineering threats**.

---

## 📌 Notes:
This report is part of my Elevate Labs internship tasks focused on **cybersecurity awareness and threat analysis**.
