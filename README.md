# CS-305
# Practices for Secure Software Report – Artemis Financial

## Artifact: Practices for Secure Software Report (Project Two)

This repository contains my submission for CS 305 Project Two, which focuses on secure software development and vulnerability management for a fictional financial services client, Artemis Financial. The core of this project involved implementing secure communication protocols, cryptographic hashing using SHA-256, vulnerability detection using OWASP Dependency-Check, and secure configuration management using Java Keytool and Maven.

## Reflection: Journal Responses

### 1. Client Summary
Artemis Financial is a fictional financial services company that required enhancements to its web application's security. The company needed secure communication (HTTPS), data integrity verification through checksum generation, and a method to assess and mitigate third-party library vulnerabilities.

### 2. Strengths in Vulnerability Assessment and Importance of Secure Coding
I successfully implemented secure hashing using SHA-256 and identified CVEs using OWASP Dependency-Check. My ability to suppress false positives using a well-documented `suppression.xml` file demonstrated real-world problem-solving. Secure coding is essential because it protects sensitive information, upholds user trust, and ensures business continuity. Strong software security also reduces the risk of financial and reputational damage.

### 3. Challenges and Helpful Aspects
The most challenging part was integrating OWASP Dependency-Check and interpreting CVE reports. However, this process was also educational and gave me hands-on experience with real-world tools used by security teams.

### 4. Security Enhancements and Future Mitigation Planning
I increased layers of security by enabling HTTPS with a self-signed certificate, creating a secure `/hash` endpoint using SHA-256, and implementing automated CVE scanning. In future projects, I would use static analysis tools, CVSS scores, and threat modeling techniques to prioritize and mitigate vulnerabilities.

### 5. Ensuring Functional and Secure Code
To ensure the code was both functional and secure, I tested the application before and after refactoring, verified HTTPS startup, confirmed endpoint responses, and validated suppressed vulnerabilities using OWASP Dependency-Check. I re-ran the build after changes to ensure no new vulnerabilities were introduced.

### 6. Tools, Resources, and Practices for Future Use
I used Java Keytool, SHA-256 hashing, OWASP Dependency-Check, suppression.xml configuration, Maven, and Spring Boot. These are practical tools I’ll continue using for secure Java development and vulnerability management in future assignments and real-world projects.

### 7. Portfolio Value
Future employers will be able to see a complete, real-world example of secure application development. This includes SSL certificate configuration, vulnerability scanning with mitigation strategies, checksum implementation, and functional testing – all valuable skills in secure software engineering roles.



