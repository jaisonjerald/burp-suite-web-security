# Burp Suite Web Security Lab

<p align="center">
  <img src="screenshots/burp-suite-banner.png" alt="Burp Suite Web Security Lab Banner" width="100%">
</p>

<p align="center">

![Kali Linux](https://img.shields.io/badge/Kali-Linux-557C94?style=for-the-badge&logo=kalilinux)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-Community-F47B20?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![OWASP Juice Shop](https://img.shields.io/badge/OWASP-Juice_Shop-4CAF50?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</p>

---

## 📖 Overview

This repository documents my hands-on experience with **Burp Suite Community Edition** for web application security testing.

The lab environment was built using **Docker** and **OWASP Juice Shop**, an intentionally vulnerable web application designed for security training.

Throughout this project, I explored Burp Suite's core features, including intercepting HTTP traffic, inspecting requests and responses, replaying requests, comparing traffic, and encoding/decoding data.

---

# 🛠️ Lab Environment

| Component | Details |
|-----------|----------|
| Operating System | Kali Linux |
| Proxy Tool | Burp Suite Community Edition |
| Target Application | OWASP Juice Shop |
| Browser | Firefox ESR |
| Container Platform | Docker |

---

# 🎯 Objectives

- Install Burp Suite Community Edition
- Configure Firefox to use Burp Proxy
- Deploy OWASP Juice Shop using Docker
- Capture HTTP Requests
- Analyze Web Traffic
- Replay Requests using Repeater
- Explore Site Map
- Perform Base64 Encoding & Decoding
- Compare HTTP Requests

---
# 📂 Repository Structure

```text
burp-suite-web-security/
│
├── README.md
├── LICENSE
│
└── screenshots/
    ├── burp-suite-banner.png
    ├── 01-docker-pull.png
    ├── 02-docker-running.png
    ├── 03-firefox-proxy.png
    ├── 04-juice-shop-home.png
    ├── 05-http-history.png
    ├── 06-login-request.png
    ├── 07-repeater.png
    ├── 08-site-map.png
    ├── 09-base64-encode.png
    ├── 10-base64-decode.png
    └── 11-comparer.png
```

# 📷 Lab Walkthrough

## 1️⃣ Pull OWASP Juice Shop Docker Image

<img src="screenshots/01-docker-pull.png" width="100%">

---

## 2️⃣ Run Docker Container

<img src="screenshots/02-docker-running.png" width="100%">

---

## 3️⃣ Configure Firefox Proxy

<img src="screenshots/03-firefox-proxy.png" width="100%">

---

## 4️⃣ Launch OWASP Juice Shop

<img src="screenshots/04-juice-shop-home.png" width="100%">

---

## 5️⃣ Capture HTTP Requests

<img src="screenshots/05-http-history.png" width="100%">

---

## 6️⃣ Capture Login Request

<img src="screenshots/06-login-request.png" width="100%">

---

## 7️⃣ Replay Request using Repeater

<img src="screenshots/07-repeater.png" width="100%">

---

## 8️⃣ Explore Site Map

<img src="screenshots/08-site-map.png" width="100%">

---

## 9️⃣ Base64 Encoding

<img src="screenshots/09-base64-encode.png" width="100%">

---

## 🔟 Base64 Decoding

<img src="screenshots/10-base64-decode.png" width="100%">

---

## 1️⃣1️⃣ Compare HTTP Requests

<img src="screenshots/11-comparer.png" width="100%">

---

# 🔑 Burp Suite Features Covered

- ✅ Proxy
- ✅ HTTP History
- ✅ Site Map
- ✅ Repeater
- ✅ Decoder
- ✅ Comparer

---

# 🧰 Tools Used

- Burp Suite Community Edition
- Kali Linux
- Firefox ESR
- Docker
- OWASP Juice Shop

---

# 📚 Skills Gained

- Web Application Security Testing
- HTTP Request Analysis
- HTTP Response Analysis
- Web Proxy Configuration
- Docker Container Deployment
- Burp Suite Workflow
- Base64 Encoding & Decoding
- HTTP Traffic Inspection

---
---

# 🎓 Key Learning Outcomes

During this lab, I gained practical experience with Burp Suite Community Edition by working in a controlled environment using OWASP Juice Shop.

### Burp Suite Proxy
- Configured Firefox to route traffic through Burp Suite.
- Intercepted HTTP requests and responses.
- Observed how browsers communicate with web applications.

### HTTP History
- Captured and analyzed HTTP GET and POST requests.
- Examined request headers, response headers, cookies, and status codes.
- Identified login requests and application API calls.

### Site Map
- Explored the application's structure.
- Discovered available endpoints and resources.
- Understood how Burp automatically maps visited content.

### Repeater
- Sent captured requests multiple times.
- Modified request data safely.
- Compared server responses after changing inputs.

### Decoder
- Performed Base64 encoding and decoding.
- Understood how common encoding formats appear in web traffic.

### Comparer
- Compared multiple HTTP requests.
- Identified differences between requests.
- Learned how request comparison assists during testing.

### Docker & OWASP Juice Shop
- Pulled and ran OWASP Juice Shop using Docker.
- Verified container status and accessed the application locally.
- Used an intentionally vulnerable application for safe learning.

### Web Security Concepts
- HTTP Methods (GET, POST)
- Request Headers
- Response Headers
- Cookies
- Status Codes
- JSON Requests
- Proxy Interception
- Traffic Analysis

---

# 🚀 Future Improvements

- Perform Intruder attacks
- Explore Sequencer
- Practice Decoder with JWT Tokens
- Use Burp Extensions (BApp Store)
- Test additional OWASP Juice Shop vulnerabilities
- Practice PortSwigger Web Security Academy labs

---

# ⚠️ Disclaimer

This repository is intended for **educational purposes only**.

All testing was performed against **OWASP Juice Shop**, an intentionally vulnerable application created for learning and security awareness.

Do **not** perform these techniques against systems you do not own or have explicit permission to test.

---

# 👨‍💻 Author

**Jaison Jerald**

- GitHub: https://github.com/jaisonjerald
- LinkedIn: https://www.linkedin.com/in/jaison-jerald-79b9271b9/

---

⭐ **If you found this repository helpful, consider giving it a star!**
