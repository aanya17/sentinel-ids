# 🛡️ Sentinel IDS — Advanced Intrusion Detection System

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Scapy](https://img.shields.io/badge/Scapy-2.5+-green)
![ML](https://img.shields.io/badge/ML-Isolation%20Forest-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

> Real-time network threat detection using rule-based signature analysis,
> statistical rate monitoring, and unsupervised machine learning.

---

## 🚀 Run on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/sentinel-ids/blob/main/Sentinel_IDS_v3.ipynb)

---

## 🔍 What It Detects

| Attack | Threat Level |
|--------|-------------|
| Port Scan | 🔴 HIGH |
| SYN Flood / DoS | 🔥 CRITICAL |
| SSH Brute Force | 🔴 HIGH |
| XMAS / NULL / FIN Scan | 🟡 MEDIUM – 🔴 HIGH |
| ICMP Flood | 🔴 HIGH |
| DNS Amplification | 🔴 HIGH |
| UDP Flood | 🔴 HIGH |
| SQL Injection / Shellcode | 🔥 CRITICAL |
| ML Anomaly Detection | 🔴 HIGH |

---

## ⚙️ Features

- 📦 **11 rule-based detectors** — flags, rate thresholds, payload signatures
- 🤖 **ML anomaly detection** — Isolation Forest trained on live IP profiles
- 🔔 **Email + Telegram alerts** — configurable push notifications
- 🚫 **Auto IP blocking** — iptables integration on Linux servers
- 📊 **Analytics dashboard** — 4-panel Matplotlib charts
- 🗺️ **Geo heatmap** — attack origin world map
- 📄 **PDF threat report** — auto-generated with logs and charts
- 📁 **Structured logs** — JSON, CSV, suspicious IP list

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **Scapy** — packet capture
- **scikit-learn** — Isolation Forest
- **Matplotlib / Pandas** — visualisation
- **FPDF2** — PDF report generation
- **Requests** — Telegram Bot API

---

## 📁 Project Structure
