# Burp Suite Web Security Lab

A hands-on web application security testing project demonstrating the use of **Burp Suite Community Edition** to analyze, intercept, and manipulate HTTP requests in a controlled lab environment using **OWASP Juice Shop**.

---

## 📖 Project Overview

This project demonstrates practical web application security testing techniques using Burp Suite Community Edition. The lab environment was built using Docker and OWASP Juice Shop, an intentionally vulnerable web application designed for security training.

The objective was to understand how Burp Suite can be used to intercept web traffic, inspect requests and responses, replay requests, analyze application structure, and perform data encoding/decoding.

---

## 🎯 Objectives

- Deploy OWASP Juice Shop using Docker
- Configure Firefox to use Burp Suite Proxy
- Capture HTTP requests and responses
- Analyze login requests
- Replay requests using Repeater
- Explore application endpoints using Site Map
- Encode and decode data using Decoder
- Compare HTTP requests using Comparer
- Gain practical experience with web application security testing

---

# 🛠️ Lab Environment

| Component | Details |
|------------|---------|
| Operating System | Kali Linux |
| Web Browser | Firefox ESR |
| Proxy Tool | Burp Suite Community Edition |
| Target Application | OWASP Juice Shop |
| Container Platform | Docker |
| Communication Protocol | HTTP |

---

# 🧰 Tools Used

- Burp Suite Community Edition
- OWASP Juice Shop
- Docker
- Firefox ESR
- Kali Linux

---

# 📂 Repository Structure

```text
burpsuite-web-security-lab/
│
├── README.md
├── LICENSE
│
└── screenshots/
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

---

# 🚀 Workflow

## Step 1 — Pull OWASP Juice Shop Docker Image

Downloaded the vulnerable web application from Docker Hub.

**Screenshot**

![Docker Pull](screenshots/01-docker-pull.png)

---

## Step 2 — Start the Docker Container

Started the Juice Shop container and exposed port **3000**.

**Screenshot**

![Docker Running](screenshots/02-docker-running.png)

---

## Step 3 — Configure Firefox Proxy

Configured Firefox to forward HTTP and HTTPS traffic through Burp Suite using **127.0.0.1:8080**.

**Screenshot**

![Firefox Proxy](screenshots/03-firefox-proxy.png)

---

## Step 4 — Launch OWASP Juice Shop

Successfully accessed the target application.

**Screenshot**

![Juice Shop](screenshots/04-juice-shop-home.png)

---

## Step 5 — Capture HTTP Requests

Observed incoming and outgoing HTTP requests using Burp Suite's HTTP History.

Captured information included:

- GET requests
- POST requests
- HTTP headers
- JSON responses
- Status codes

**Screenshot**

![HTTP History](screenshots/05-http-history.png)

---

## Step 6 — Capture Login Request

Captured the login POST request and inspected the JSON payload.

Observed:

- Login endpoint
- Email parameter
- Password parameter
- Request headers
- Cookies
- JSON request body

**Screenshot**

![Login Request](screenshots/06-login-request.png)

---

## Step 7 — Replay Request Using Repeater

Sent the captured login request to Burp Repeater for manual testing and replay.

This feature allows security testers to modify and resend requests to observe server responses.

**Screenshot**

![Repeater](screenshots/07-repeater.png)

---

## Step 8 — Explore the Site Map

Burp Suite automatically mapped the web application structure.

Discovered:

- REST API endpoints
- Static resources
- JavaScript files
- Application routes

**Screenshot**

![Site Map](screenshots/08-site-map.png)

---

## Step 9 — Base64 Encoding

Used Burp Decoder to convert plaintext into Base64.

Example:

```
Hello world
```

↓

```
SGVsbG8gd29ybGQ=
```

**Screenshot**

![Base64 Encode](screenshots/09-base64-encode.png)

---

## Step 10 — Base64 Decoding

Decoded the Base64 string back into readable plaintext.

**Screenshot**

![Base64 Decode](screenshots/10-base64-decode.png)

---

## Step 11 — Compare HTTP Requests

Used Burp Comparer to identify differences between two HTTP requests.

Compared:

- Request headers
- Host values
- Request length
- Request structure

**Screenshot**

![Comparer](screenshots/11-comparer.png)

---

# 🧠 Skills Demonstrated

- Web Application Security Testing
- Burp Suite Community Edition
- Proxy Configuration
- HTTP Request Analysis
- HTTP Response Analysis
- Request Replay
- REST API Inspection
- Web Application Enumeration
- Base64 Encoding
- Base64 Decoding
- HTTP Request Comparison
- Docker Container Deployment

---

# 📚 Key Learning Outcomes

- Learned how an intercepting proxy works.
- Understood HTTP request and response structure.
- Practiced capturing login requests.
- Explored web application endpoints.
- Replayed requests using Burp Repeater.
- Used Burp Decoder for encoding and decoding.
- Compared HTTP requests using Burp Comparer.
- Built practical experience with web application security testing.

---

# ⚠️ Disclaimer

This project was conducted in a controlled laboratory environment using **OWASP Juice Shop**, an intentionally vulnerable application created for security awareness and training.

No unauthorized systems or production environments were tested.

---

# 📌 Future Improvements

- Intruder demonstrations
- Manual parameter manipulation
- SQL Injection testing (lab only)
- Cross-Site Scripting (XSS) testing
- Directory enumeration
- Authentication testing
- Session analysis
- JWT analysis
- Burp Extensions

---

# 📖 References

- OWASP Juice Shop
- Burp Suite Community Edition
- OWASP Web Security Testing Guide

---

## ⭐ If you found this project useful, consider giving the repository a star!
