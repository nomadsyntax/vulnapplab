Vulnerable Apps Lab Environment
An all-in-one Docker Compose environment designed for security researchers, penetration testers, ethical hackers, and cybersecurity students. This repository quickly spins up various intentionally vulnerable web applications, APIs, databases, and vulnerable OS services, all behind an organized Nginx reverse proxy.

📌 What's included?

🔹 Vulnerable Web Applications
DVWA
Mutillidae II (OWASP)
bWAPP
WebGoat (OWASP)
OWASP Juice Shop
Vulnerable Wordpress (WPScan Team)
Altoro Mutual
Hackazon (Rapid7)
XVWA
Security Shepherd (OWASP)
DVSI

Vulnerable APIs
Vulnerable GraphQL API
crAPI (Completely Ridiculous API)

Vulnerable Databases:
Vulnerable PostgreSQL (9.3)
(Credentials: postgres/postgres)

Vulnerable OS & Containers:
Metasploitable2

🚀 Quick Start Guide

Requirements:
Docker, Docker Compose, Nginx installed

Deployment:
git clone https://github.com/your-username/vulnerable-apps-lab.git
cd vulnerable-apps-lab
docker-compose up -d

Access your apps:
All apps are accessible through the Nginx Reverse Proxy for simplicity:
Application	URL
DVWA	http://localhost/dvwa
Mutillidae II	http://localhost/mutillidae
bWAPP	http://localhost/bwapp
WebGoat	http://localhost/webgoat
OWASP Juice Shop	http://localhost/juice-shop
Vulnerable WordPress	http://localhost/vulnerablewordpress
Altoro Mutual	http://localhost/altoro-mutual
Hackazon	http://localhost/hackazon
XVWA	http://localhost/xvwa
Security Shepherd	http://localhost/security-shepherd
DVSI	http://localhost/dvsi
Vulnerable GraphQL API	http://localhost/graphql
crAPI	http://localhost/crapi
Metasploitable2	http://localhost/metasploitable2

Starting & Stopping containers:
Start all containers:
docker-compose up -d

Stop the containers:
docker-compose down
