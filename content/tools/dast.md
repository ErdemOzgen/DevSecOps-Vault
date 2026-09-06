# Dynamic Application Security Testing (DAST)

Dynamic Application Security Testing (DAST) is a black-box testing technique that analyzes running applications by simulating real-world attacks. Unlike SAST, which inspects source code without execution, DAST interacts with live instances of the application (typically through HTTP) to discover vulnerabilities like:

- Cross-Site Scripting (XSS)
- SQL Injection (SQLi)
- Command injection
- Security misconfigurations
- Broken authentication
- Sensitive data exposure

DAST tools are ideal for identifying vulnerabilities that arise from configuration issues, runtime behavior, or security flaws that only become apparent during execution.


## Why DAST is Critical

- **Covers runtime vulnerabilities** that static tools may miss
- **Simulates real attacker behavior** in QA/staging/production environments
- **Works language-agnostically** — applicable to any web application regardless of the stack
- **Detects misconfigurations** such as open directories, missing headers, or dangerous endpoints
- **Complements SAST/SCA** for full-stack security coverage

## Common DAST Tools

| Name | URL | Description | Stars |
|------|-----|-------------|:-----:|
| **OWASP ZAP** | [Project](https://owasp.org/www-project-zap/) / [GitHub](https://github.com/zaproxy/zaproxy) | OWASP’s flagship DAST tool. Open-source, powerful, and CI/CD friendly (Docker support). GUI + API + automation. | ![ZAP](https://img.shields.io/github/stars/zaproxy/zaproxy?style=for-the-badge) |
| **Wapiti** | [GitHub](https://github.com/wapiti-scanner/wapiti) | Lightweight CLI web vulnerability scanner. Ideal for scripting and automation in pipelines. | ![Wapiti](https://img.shields.io/github/stars/wapiti-scanner/wapiti?style=for-the-badge) |
| **Nuclei** | [GitHub](https://github.com/projectdiscovery/nuclei) | High-performance, template-driven scanner for HTTP-based vulnerabilities. Great for custom rules and mass scanning. | ![Nuclei](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=for-the-badge) |
| **purpleteam** | [GitHub](https://github.com/purpleteam-labs/purpleteam) | Self-hosted DAST automation tool designed to integrate into pipelines and test APIs, web apps, and endpoints. | ![Purpleteam](https://img.shields.io/github/stars/purpleteam-labs/purpleteam?style=for-the-badge) |
| **OSS-Fuzz** | [GitHub](https://github.com/google/oss-fuzz) | Continuous fuzzing platform by Google to find memory and logic bugs in C/C++/Rust apps. Ideal for libraries and backend services. | ![OSS-Fuzz](https://img.shields.io/github/stars/google/oss-fuzz?style=for-the-badge) |
| **Nikto** | [GitHub](https://github.com/sullo/nikto) | Web server vulnerability scanner that detects outdated components, dangerous files, and security headers. | ![Nikto](https://img.shields.io/github/stars/sullo/nikto?style=for-the-badge) |
| **Darkmoon** | [GitHub](https://github.com/ASCIT31/Dark-Moon) | Open source (GPLv3) autonomous penetration testing platform where 50 specialist agents over MCP drive 50+ offensive tools across web, API, Active Directory, Kubernetes and cloud with reproducible proof of exploitation. Self hosted. | ![Darkmoon](https://img.shields.io/github/stars/ASCIT31/Dark-Moon?style=for-the-badge) |
| **Skipfish** | [Archived](https://code.google.com/archive/p/skipfish/) | Fast web app security recon tool from Google. Useful for brute-force fuzzing and link crawling. | ![Skipfish](https://img.shields.io/github/stars/spinkham/skipfish?style=for-the-badge) |


## ️Best Practices for DAST in DevSecOps

1. **Run in staging or test environments**  
   Since DAST tools actively probe endpoints, it’s best to scan non-production instances unless the tool is explicitly configured to be safe.

2. **Automate in CI/CD pipelines**  
   Tools like **OWASP ZAP**, **Wapiti**, or **Nuclei** offer Docker support and CLI modes, making them ideal for GitHub Actions, GitLab CI, or Jenkins pipelines.

3. **Combine template-driven and active scanning**  
   Use `Nuclei` for rule-based scans and `ZAP` for full interaction-based analysis — this covers both depth and breadth.

4. **Tune scanners**  
   Disable intrusive or long-running tests for lightweight builds; run full scans nightly or in dedicated security testing stages.

5. **Integrate with bug trackers**  
   Automatically push findings to issue trackers (e.g., Jira, GitHub Issues) with tools like ZAP’s API or custom scripts.

6. **Baseline and suppress false positives**  
   DAST tools often produce noise — invest time in tuning your rules and maintaining suppression lists for known-safe behavior.



## Further Reading

- [ZAP + GitHub Actions Tutorial](https://www.zaproxy.org/blog/2020-05-15-dynamic-application-security-testing-with-zap-and-github-actions/)
- [GitLab DAST Integration](https://docs.gitlab.com/ee/user/application_security/dast/)
- [Using Nuclei in CI (GitHub Action)](https://github.com/secopslab/nuclei-action)
- [ZAPCon 2021 - Test Automation & DSLs for DAST](https://youtu.be/jimW-R6_F4U)
- [Penetration Testing at DevSecOps Speed](https://securityboulevard.com/2019/04/penetration-testing-at-devsecops-speed/)
