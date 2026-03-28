# cyber-project-04-network-scan-analysis
Network scan analysis using Nmap (open ports and risk assessment)


## Context

Network scanning is a crucial step in cybersecurity for identifying exposed services and potential vulnerabilities.

This project simulates the analysis of an Nmap scan.

---

## Objective

* Identify open ports
* Understand exposed services
* Assess potential risks

---

## 🔍 Scan Results

```id="j5bg3y"
PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
443/tcp  open  https
3306/tcp open  mysql
```

---

## 🔎 Analysis

### 1. SSH (Port 22)

* Remote access service
* Risk of brute force attacks

### 2. HTTP/HTTPS (Ports 80 & 443)

* Web services
* Possible web vulnerabilities

### 3. MySQL (Port 3306)

* Database service exposed
* High risk if not secured

---

## Conclusion

The system exposes multiple services, including a database, which increases the attack surface.

---

## 🛡️ Recommendations

* Restrict SSH access
* Secure web applications
* Limit MySQL exposure (firewall)

---

## Key Takeaways

* Understanding port scanning
* Identifying exposed services
* Basic risk assessment

---

## 👨‍💻 Author

Part of my cybersecurity learning journey.
