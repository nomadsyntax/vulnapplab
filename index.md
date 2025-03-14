# Vulnerable Web Applications Setup

## Introduction
A Docker Compose setup containing multiple vulnerable web applications, suitable for practicing web security skills.

### Included Applications:
- **DVWA** ([DVWA](https://github.com/digininja/DVWA))
- **Mutillidae II** ([OWASP Mutillidae](https://github.com/webpwnized/mutillidae))
- **bWAPP** ([bWAPP](https://github.com/raesene/bwapp))
- **WebGoat** ([OWASP WebGoat](https://github.com/WebGoat/WebGoat))
- **OWASP Juice Shop** ([Juice Shop](https://github.com/juice-shop/juice-shop))
- **Vulnerable Wordpress** ([WPScan Vulnerable WordPress](https://github.com/wpscanteam/VulnerableWordpress))
- **Altoro Mutual** ([Altoro Mutual](https://github.com/hclproducts/altoro-mutual))
- **Vulnerable GraphQL API** ([Vulnerable GraphQL](https://github.com/carvesystems/vulnerable-graphql-api))

### Deployment Steps:
- Install Docker and Docker Compose.
- Clone this repository.
- Run: `docker-compose up -d`
- Access via Nginx reverse proxy on standard URLs.
http://your-ip/dvwa
http://your-ip/mutillidae
http://your-ip/bwapp
http://your-ip/webgoat
http://your-ip/juice-shop
http://your-ip/vulnerable-wordpress
http://your-ip/altoro-mutual
http://your-ip/vulnerable-graphql-api
