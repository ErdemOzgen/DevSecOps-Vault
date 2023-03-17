# DevSecOps-Vault
Collection of roadmaps, tools, best practice, resources about DevSecOps

![gartner](./imgs/gartner.png)
# What is DevSecOps

DevSecOps is an approach to software development that integrates security into the entire software development lifecycle. It combines the principles of DevOps with security to create a culture of security that permeates the entire development process.

The goal of DevSecOps is to ensure that security is not an afterthought but is built into the development process from the very beginning. This approach emphasizes collaboration between development, operations, and security teams to ensure that security is a shared responsibility across the organization.

DevSecOps involves the implementation of security controls throughout the development lifecycle, from design to deployment, and beyond. This includes automated security testing, continuous monitoring, vulnerability assessments, and penetration testing.

By implementing DevSecOps practices, organizations can improve their overall security posture and reduce the risk of security breaches and vulnerabilities. This approach also helps to accelerate the delivery of secure software by integrating security into the development process, rather than treating it as a separate activity.

Take a look at links for detailed explanitation on DevSecOps:

* [Redhat definitions](https://www.redhat.com/en/topics/devops/what-is-devsecops)
* [IBM definitions](https://www.ibm.com/cloud/learn/devsecops)
* [Synk definitions](https://snyk.io/series/devsecops/)
* [Synopsys definitions](https://www.synopsys.com/glossary/what-is-devsecops.html)
* [Spacelift definitions](https://spacelift.io/blog/what-is-devsecops)

### 1. Design
  - Development Lifecycle
    1. [SDL(Secure Development Lifecycle) by Microsoft](https://www.microsoft.com/en-us/securityengineering/sdl/practices)
    2. [OWASP's Software Assurance Maturity Model](https://github.com/OWASP/samm)
    3. [Building Security In Maturity Model (BSIMM)](https://www.bsimm.com/framework.html)
    4. [NIST's Secure Software Developerment Framework](https://csrc.nist.gov/CSRC/media/Publications/white-paper/2019/06/07/mitigating-risk-of-software-vulnerabilities-with-ssdf/draft/documents/ssdf-for-mitigating-risk-of-software-vulns-draft.pdf)
    5. [DevSecOps basics: 9 tips for shifting left (Gitlab)](https://about.gitlab.com/blog/2020/06/23/efficient-devsecops-nine-tips-shift-left/)
    6. [6 Ways to bring security to the speed of DevOps (Gitlab)](https://about.gitlab.com/blog/2019/10/31/speed-security-devops/)
  - Threat Model
    1. [What is Threat Modeling / Wikipedia](https://en.wikipedia.org/wiki/Threat_model)
    2. [Threat Modeling by OWASP](https://owasp.org/www-community/Threat_Modeling)
    3. [Application Threat Modeling by OWASP](https://owasp.org/www-community/Application_Threat_Modeling)
    4. [Agile Threat Modeling Toolkit](https://threagile.io)
    5. [OWASP Threat Dragon](https://threatdragon.github.io)
### 2. Develop
  - Secure Coding
    1. [Secure coding guide by Apple](https://developer.apple.com/library/archive/documentation/Security/Conceptual/SecureCodingGuide/Introduction.html)
    2. [Secure Coding Guidelines for Java SE](https://www.oracle.com/java/technologies/javase/seccodeguide.html)
    3. [Go-SCP / Go programming language secure coding practices guide](https://github.com/OWASP/Go-SCP)
    4. [Android App security best practices by Google](https://developer.android.com/topic/security/best-practices)
    5. [Securing Rails Applications](https://guides.rubyonrails.org/security.html)
### 3. Build  
  - SAST(Static Application Security Testing)
    1. [Scan Source Code using Static Application Security Testing (SAST) with SonarQube, Part 1](https://medium.com/nycdev/scan-your-source-code-for-vulnerabilities-using-static-application-security-testing-sast-with-5f8ee1fdf9aa)
    2. [Announcing third-party code scanning tools: static analysis & developer security training](https://github.blog/2020-10-05-announcing-third-party-code-scanning-tools-static-analysis-and-developer-security-training/)
### 4. Test
  - DAST(Dynamic Application Security Testing)
    1. [Dynamic Application Security Testing with ZAP and GitHub Actions](https://www.zaproxy.org/blog/2020-05-15-dynamic-application-security-testing-with-zap-and-github-actions/) 
    2. [Dynamic Application Security Testing (DAST) in Gitlab](https://docs.gitlab.com/ee/user/application_security/dast/)
    3. [DAST using pdiscoveryio Nuclei (github action)](https://github.com/secopslab/nuclei-action)
    4. [ZAPCon 2021-Democratizing ZAP with test automation and domain specific languages](https://youtu.be/jimW-R6_F4U)
  - Penetration testing
    1. [Penetration Testing at DevSecOps Speed](https://securityboulevard.com/2019/04/penetration-testing-at-devsecops-speed/)
### 5. Deploy
  - Security Hardening & Config
    1. [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks/)
    2. [DevSecOps in Kubernetes](https://cloudblogs.microsoft.com/opensource/2019/07/22/devsecops-in-kubernetes/)
  - Security Scanning
    1. [Best practices for scanning images (docker)](https://docs.docker.com/develop/scan-images/)
### 6. Operate and Monitor
  - RASP(Run-time Application Security Protection)
    1. [Runtime Application Self-Protection by rapid7](https://www.rapid7.com/fundamentals/runtime-application-self-protection/)
    2. [Jumpstarting your devsecops - Pipeline with IAST and RASP](https://2018.appsec.eu/presos/DevOps_Jumpstarting-Your-DevSecOps_Jeff-Williams_AppSecEU2018.pdf)
  - Security Patch
    1. RASP(Runtime Application Self-Protection)
  - Security Audit
  - Security Monitor
    1. IAST(Interactive Application Security Testing)
    2. Metrics, Monitoring, Alerting
  - Security Analysis
    1. [Attack Surface Analysis Cheat Sheet by OWASP](https://cheatsheetseries.owasp.org/cheatsheets/Attack_Surface_Analysis_Cheat_Sheet.html)



# Resources

## Books
Books focussed around DevSecOps, bringing the security focus up front.

* [DevOpsSec](http://www.oreilly.com/webops-perf/free/devopssec.csp)
* [Docker Securitiy - Quick Reference](https://binarymist.io/publication/docker-security/)
* [Holistic Info-Sec for Web Developers](https://leanpub.com/b/holisticinfosecforwebdevelopers)
* [Securing DevOps](https://securing-devops.com/book)
* [The DevOps Handbook (Section VI)](https://www.oreilly.com/library/view/the-devops-handbook/9781457191381/)

## Conferences
A body of knowledge for combining DevOps and Security has been delivered via conferences and meetups.  This is a short list of the venues that have dedicated a portion of their agenda to it.

* [AWS re:Inforce](https://reinforce.awsevents.com/)
* [AWS re:Invent](https://reinvent.awsevents.com)
* [DevSecCon](http://devseccon.com)
* [DevOps Connect](http://www.devopsconnect.com/)
* [DevOps Days](http://www.devopsdays.org/)
* [Goto Conference](http://gotocon.com)
* [IP Expo](http://www.ipexpoeurope.com/)
* [ISACA Ireland](http://www.isaca.org/chapters5/Ireland/conference/pages/Agenda.aspx)
* [RSA Conference](http://www.rsaconference.com)
* [All Day DevOps](https://www.alldaydevops.com/)


## Training
DevSecOps requires an appetite for learning and agility to quickly acquire new skills.  We've collected these links to help you learn how to do DevSecOps with us.

### Labs
Labs are hands-on learning opportunities to grow your skills in Dev, Sec, and Ops.  All skills are useful and need to be grown so that you can have the empathy, knowledge and trade to operate DevSecOps style.

* [DevSecOps Bootcamp](https://github.com/devsecops/bootcamp)
* [Exercism](http://exercism.io/)
* [Infoseclabs](http://www.infoseclabs.net)
* [Infrastructure Monitoring](https://github.com/appsecco/defcon24-infra-monitoring-workshop)
* [Pentester Lab](https://pentesterlab.com/exercises/)
* [Vulnhub](https://www.vulnhub.com/)


### Vulnerable Test Targets
It's important to build up knowledge by learning how to break applications left vulnerable by security mistakes.  This section contains a list of vulnerable apps that can be deployed to learn what not to do.  These same apps can be made safe by remediating the intentional vulnerabilities to learn how to prevent attackers from gaining access to underlying infrastructure or data.

* [Damn Vulnerable Web Application](https://github.com/ethicalhack3r/DVWA) (PHP/MySQL)
* [LambHack](https://github.com/wickett/lambhack) (Lambda)
* [Metasploitable](https://community.rapid7.com/docs/DOC-1875) (Linux)
* [Mutillidae](http://www.irongeek.com/i.php?page=mutillidae/mutillidae-deliberately-vulnerable-php-owasp-top-10) (PHP)
* [NodeGoat](https://github.com/owasp/nodegoat) (Node)
* [OWASP Damn Vulnerable Serverless Application (DVSA)](https://github.com/owasp/dvsa) (AWS Serverless)
* [OWASP Juice Shop](https://github.com/OWASP/glue) (NodeJS/Angular)
* [RailsGoat](https://github.com/OWASP/railsgoat) (Rails)
* [WebGoat](https://github.com/WebGoat/WebGoat) (Web App)
* [WebGoat.Net](https://github.com/OWASP/WebGoat.NET) (.NET)
* [WebGoatPHP](https://github.com/OWASP/OWASPWebGoatPHP) (PHP)

### Security of CI/CD
 **DO NOT FORGET MANY DEVSECOPS PIPELINE SUFFER FROM SECURITY VULNEBILITIES**
- Github Actions
    1. [Security hardening for GitHub Actions](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions)
    2. [Github Actions Security Best Practices](https://engineering.salesforce.com/github-actions-security-best-practices-b8f9df5c75f5)
    3. [GitHub Actions Security Best Practices [cheat sheet included]](https://blog.gitguardian.com/github-actions-security-cheat-sheet/)
- Jenkins
    1. [Securing Jenkins](https://www.jenkins.io/doc/book/security/)
    2. [Securing Jenkins CI Systems by SANS](https://www.sans.org/white-papers/36872/)
    3. [DEPRECATED/chef-jenkins-hardening](https://github.com/dev-sec/chef-jenkins-hardening)

# Tools and Links for DevSecOps

![img](imgs/devsecopslife.png)

DevOps loop contains ==>  Plan, Code, Build, Test, Release, Deploy, Operate, Monitor.

## Pre-commit tools

DevSecOps pre-commit tools are a critical part of the software development lifecycle, particularly for organizations that prioritize security in their development processes. These tools help ensure that security considerations are integrated into every step of the development process, from coding to deployment.

Here are some reasons why DevSecOps pre-commit tools are important:

Early detection of security vulnerabilities: Pre-commit tools can identify security issues early in the development process, before code is even committed to the repository. This allows developers to address security concerns immediately, rather than discovering them later in the development process when they can be much more difficult and expensive to fix.

Consistent security standards: Pre-commit tools can enforce consistent security standards across the development team, ensuring that security best practices are followed by all developers.

Reduced risk of security breaches: By catching security issues early, pre-commit tools can help reduce the risk of security breaches and protect sensitive data.

Improved efficiency: Pre-commit tools can help developers catch security issues before they become more complex and time-consuming to fix, which can ultimately lead to more efficient development processes.

Enhanced collaboration: Pre-commit tools can help facilitate collaboration between developers and security teams by providing a common language and set of standards for discussing security issues.

Overall, DevSecOps pre-commit tools play a critical role in ensuring that security is integrated into the software development lifecycle. By catching security issues early and enforcing consistent standards, these tools help organizations build more secure and efficient software.

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **git-secrets** | [https://github.com/awslabs/git-secrets](https://github.com/awslabs/git-secrets) | AWS labs tool preventing you from committing secrets to a git repository  |![Git Secrets](https://img.shields.io/github/stars/awslabs/git-secrets?style=for-the-badge) |
| **git-hound** | [https://github.com/tillson/git-hound](https://github.com/tillson/git-hound) | Searchers secrets in git |![git-hound](https://img.shields.io/github/stars/tillson/git-hound?style=for-the-badge) | 
| **goSDL** | [https://github.com/slackhq/goSDL](https://github.com/slackhq/goSDL) |Security Development Lifecycle checklist   |![goSDL](https://img.shields.io/github/stars/slackhq/goSDL?style=for-the-badge) |
| **ThreatPlaybook** | [https://github.com/we45/ThreatPlaybook](https://github.com/we45/ThreatPlaybook) |Threat modeling as code   |![GitLeaks](https://img.shields.io/github/stars/we45/ThreatPlaybook?style=for-the-badge) |
| **Threat Dragon** | [https://github.com/OWASP/threat-dragon](https://github.com/OWASP/threat-dragon) | OWASP Threat modeling tool  |![ThreatDragon](https://img.shields.io/github/stars/OWASP/threat-dragon?style=for-the-badge) |
| **threatspec** | [https://github.com/threatspec/threatspec](https://github.com/threatspec/threatspec) | Threat modeling as code  |![threatspec](https://img.shields.io/github/stars/threatspec/threatspec?style=for-the-badge) |
| **pytm** | [https://github.com/izar/pytm](https://github.com/izar/pytm) | A Pythonic framework for threat modeling  |![pytm](https://img.shields.io/github/stars/izar/pytm?style=for-the-badge) |
| **Threagile** | [https://github.com/Threagile/threagile](https://github.com/Threagile/threagile) | A Go framework for threat modeling  |![Threagile](https://img.shields.io/github/stars/Threagile/threagile?style=for-the-badge) |
| **MAL-lang** | [https://mal-lang.org/#what ](https://mal-lang.org/#what ) | A language to create cyber threat modeling systems for specific domains  |![Mal](https://img.shields.io/github/stars/mal-lang/exampleLang?style=for-the-badge) |
| **Microsoft Threat modeling tool** | [https://docs.microsoft.com/en-us/azure/security/develop/threat-modeling-tool](https://docs.microsoft.com/en-us/azure/security/develop/threat-modeling-tool) | Microsoft threat modeling tool  |![MS Threat modeling tool](https://img.shields.io/github/stars/microsoft/threat-modeling-templates?style=for-the-badge) |
| **Talisman** | [https://github.com/thoughtworks/talisman](https://github.com/thoughtworks/talisman) | A tool to detect and prevent secrets from getting checked in |![Talisman](https://img.shields.io/github/stars/thoughtworks/talisman?style=for-the-badge) |
| **SEDATED** | [https://github.com/OWASP/SEDATED](https://github.com/OWASP/SEDATED) | The SEDATED® Project (Sensitive Enterprise Data Analyzer To Eliminate Disclosure) focuses on preventing sensitive data such as user credentials and tokens from being pushed to Git. |![Talisman](https://img.shields.io/github/stars/OWASP/SEDATED?style=for-the-badge) |
| **Sonarlint** | [https://github.com/SonarSource/sonarlint-core](https://github.com/SonarSource/sonarlint-core) |  Sonar linting utility for IDE |![Sonarlint](https://img.shields.io/github/stars/SonarSource/sonarlint-core?style=for-the-badge)|
| **DevSkim** | [https://github.com/microsoft/DevSkim](https://github.com/microsoft/DevSkim) |  DevSkim is a framework of IDE extensions and language analyzers that provide inline security analysis |![DevSkim](https://img.shields.io/github/stars/microsoft/DevSkim?style=for-the-badge)|
| **detect-secrets** | [https://github.com/Yelp/detect-secrets](https://github.com/Yelp/detect-secrets) |  Detects secrets in your codebase |![DevSkim](https://img.shields.io/github/stars/Yelp/detect-secrets?style=for-the-badge)| 
| **tflint** | [https://github.com/terraform-linters/tflint](https://github.com/terraform-linters/tflint) | A Pluggable Terraform Linter | ![tflint](https://img.shields.io/github/stars/terraform-linters/tflint?style=for-the-badge)|


## Secrets management 

#TODO: Add explaination here

Secrets management includes managing, versioning, encryption, discovery, rotating, provisioning of passwords, certificates, configuration values and other types of secrets. 


| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **GitLeaks** | [https://github.com/zricethezav/gitleaks](https://github.com/zricethezav/gitleaks) | Gitleaks is a scanning tool for detecting hardcoded secrets  |![GitLeaks](https://img.shields.io/github/stars/zricethezav/gitleaks?style=for-the-badge) | 
| **ggshield** | [https://github.com/gitguardian/ggshield](https://github.com/gitguardian/ggshield) | GitGuardian shield (ggshield) is a CLI application that runs in your local environment or in a CI environment and helps you detect more than 350+ types of secrets and sensitive files.  |![ggshield](https://img.shields.io/github/stars/gitguardian/ggshield?style=for-the-badge) |
| **TruffleHog** | [https://github.com/trufflesecurity/truffleHog](https://github.com/trufflesecurity/truffleHog) | TruffleHog is a scanning tool for detecting hardcoded secrets  |![TruffleHog](https://img.shields.io/github/stars/trufflesecurity/truffleHog?style=for-the-badge) |
| **Hashicorp Vault** | [https://github.com/hashicorp/vault](https://github.com/hashicorp/vault) | Hashicorp Vault secrets management  |![Vault](https://img.shields.io/github/stars/hashicorp/vault?style=for-the-badge) |
| **Mozilla SOPS** | [https://github.com/mozilla/sops ](https://github.com/mozilla/sops ) | Mozilla Secrets Operations  |![SOPS](https://img.shields.io/github/stars/mozilla/sops?style=for-the-badge) |
| **AWS secrets manager GH action** | [https://github.com/marketplace/actions/aws-secrets-manager-actions](https://github.com/marketplace/actions/aws-secrets-manager-actions)| AWS secrets manager [docs](https://aws.amazon.com/secrets-manager/) |![AWS Secrets manager action](https://img.shields.io/github/stars/say8425/aws-secrets-manager-actions?style=for-the-badge)|  
| **GitRob** | [https://github.com/michenriksen/gitrob](https://github.com/michenriksen/gitrob) | Gitrob is a tool to help find potentially sensitive files pushed to public repositories on Github  |![GitRob](https://img.shields.io/github/stars/michenriksen/gitrob?style=for-the-badge)|
| **git-wild-hunt** | [https://github.com/d1vious/git-wild-hunt](https://github.com/d1vious/git-wild-hunt ) | A tool to hunt for credentials in the GitHub |![git-wild-hunt](https://img.shields.io/github/stars/d1vious/git-wild-hunt?style=for-the-badge)|
| **aws-vault** | [https://github.com/99designs/aws-vault](https://github.com/99designs/aws-vault) | AWS Vault is a tool to securely store and access AWS credentials in a development environment |![aws-vault](https://img.shields.io/github/stars/99designs/aws-vault?style=for-the-badge)|
| **Knox** | [https://github.com/pinterest/knox](https://github.com/pinterest/knox) | Knox is a service for storing and rotation of secrets, keys, and passwords used by other services |![Knox](https://img.shields.io/github/stars/Pinterest/Knox?style=for-the-badge)|
| **Chef vault** | [https://github.com/chef/chef-vault](https://github.com/chef/chef-vault) |  allows you to encrypt a Chef Data Bag Item |![Chef vault](https://img.shields.io/github/stars/chef/chef-vault?style=for-the-badge)|
| **Ansible vault** | [Ansible vault docs](https://docs.ansible.com/ansible/latest/cli/ansible-vault.html#ansible-vault) |  Encryption/decryption utility for Ansible data files |![Ansible vault](https://img.shields.io/github/stars/ansible-community/ansible-vault?style=for-the-badge)|



## OSS and Dependency management

Dependency security testing and analysis is very important part of discovering supply chain attacks. SBOM creation and following dependency scanning (Software composition analysis) is critical part of continuous integration (CI). Data series and data trends tracking should be part of CI tooling. You need to know what you produce and what you consume in context of libraries and packages. 

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **CycloneDX** | [https://github.com/orgs/CycloneDX/repositories](https://github.com/orgs/CycloneDX/repositories) | CycloneDX format for **SBOM** |![CycloneDX](https://img.shields.io/github/stars/CycloneDX/cyclonedx-cli?style=for-the-badge) | 
| **cdxgen** | [https://github.com/AppThreat/cdxgen](https://github.com/AppThreat/cdxgen) | Generates CycloneDX **SBOM**, supports many languages and package managers. |![CycloneDX](https://img.shields.io/github/stars/AppThreat/cdxgen?style=for-the-badge) | 
| **SPDX** | [https://github.com/spdx/spdx-spec](https://github.com/spdx/spdx-spec) | SPDX format for **SBOM** - Software Package Data Exchange |![SpDX](https://img.shields.io/github/stars/spdx/spdx-spec?style=for-the-badge) | 
| **Snyk** | [https://github.com/snyk/snyk](https://github.com/snyk/snyk) | Snyk scans and monitors your projects for security vulnerabilities |![Snyk](https://img.shields.io/github/stars/snyk/snyk?style=for-the-badge) | 
| **vulncost** | [https://github.com/snyk/vulncost](https://github.com/snyk/vulncost) | Security Scanner for VS Code |![Vulncost](https://img.shields.io/github/stars/snyk/vulncost?style=for-the-badge) |
| **Dependency Combobulator** | [https://github.com/apiiro/combobulator](https://github.com/apiiro/combobulator) | Dependency-related attacks detection and prevention through heuristics and insight engine (support multiple dependency schemes) | ![Combobulator](https://img.shields.io/github/stars/apiiro/combobulator?style=for-the-badge) |
| **DependencyTrack** | [https://github.com/DependencyTrack/dependency-track](https://github.com/DependencyTrack/dependency-track) | Dependency security tracking platform |![DependencyTrack](https://img.shields.io/github/stars/DependencyTrack/dependency-track?style=for-the-badge) | 
| **DependencyCheck** | [https://github.com/jeremylong/DependencyCheck](https://github.com/jeremylong/DependencyCheck) | Simple dependency security scanner good for CI |![DependencyCheck](https://img.shields.io/github/stars/jeremylong/DependencyCheck?style=for-the-badge) | 
| **Retire.js** | [https://github.com/retirejs/retire.js/](https://github.com/retirejs/retire.js/) | Helps developers to detect the use of JS-library versions with known vulnerabilities |![Retire.js](https://img.shields.io/github/stars/retirejs/retire.js?style=for-the-badge) |
| **PHP security checker** | [https://github.com/fabpot/local-php-security-checker](https://github.com/fabpot/local-php-security-checker) | Check vulnerabilities in PHP dependencies |![Retire.js](https://img.shields.io/github/stars/fabpot/local-php-security-checker?style=for-the-badge)| 
| **bundler-audit** | [https://github.com/rubysec/bundler-audit](https://github.com/rubysec/bundler-audit) | Patch-level verification for bundler |![Bundler audit](https://img.shields.io/github/stars/rubysec/bundler-audit?style=for-the-badge)| 
| **gemnasium** | [https://gitlab.com/gitlab-org/security-products/analyzers/gemnasium ](https://gitlab.com/gitlab-org/security-products/analyzers/gemnasium ) | Dependency Scanning Analyzer based on Gemnasium || 
| **Dependabot** | [https://github.com/dependabot/dependabot-core](https://github.com/dependabot/dependabot-core) | Automated dependency updates built into GitHub providing security alerts |![Dependabot](https://img.shields.io/github/stars/dependabot/dependabot-core?style=for-the-badge)| 
| **Renovatebot** | [https://github.com/renovatebot/renovate](https://github.com/renovatebot/renovate) | Automated dependency updates, patches multi-platform and multi-language |![Renovatebot](https://img.shields.io/github/stars/renovatebot/renovate?style=for-the-badge)| 
| **npm-check** | [https://www.npmjs.com/package/npm-check](https://www.npmjs.com/package/npm-check) | Check for outdated, incorrect, and unused dependencies. |![npm-check](https://img.shields.io/github/stars/dylang/npm-check?style=for-the-badge)| 
| **Security Scorecards** | [https://securityscorecards.dev](https://securityscorecards.dev) | Checks for several security health metrics on open source libraries and provides a score (0-10) to be considered in the decision making of what libraries to use. |![scorecard](https://img.shields.io/github/stars/ossf/scorecard?style=for-the-badge)| 
| **Syft** | [https://github.com/anchore/syft](https://github.com/anchore/syft) | CLI tool and library for generating an SBOM from container images (and filesystems). |![syft](https://img.shields.io/github/stars/anchore/syft?style=for-the-badge)| 

## Supply chain specific tools 

Supply chain is often the target of attacks. Which libraries you use can have a massive impact on security of the final product (artifacts). CI (continuous integration) must be monitored inside the tasks and jobs in pipeline steps. Integrity checks must be stored out of the system and in ideal case several validation runs with comparison of integrity hashes / or attestation must be performed. 

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **Tekton chains** | [https://github.com/tektoncd/chains](https://github.com/tektoncd/chains/) | Kubernetes Custom Resource Definition (CRD) controller that allows you to manage your supply chain security in Tekton. |![Chains](https://img.shields.io/github/stars/tektoncd/chains?style=for-the-badge) | 
| **in-toto** | [https://github.com/in-toto/attestation/tree/v0.1.0/spec](https://github.com/in-toto/attestation/tree/v0.1.0/spec) | An in-toto attestation is authenticated metadata about one or more software artifacts |![in-toto](https://img.shields.io/github/stars/in-toto/attestation?style=for-the-badge) | 
| **SLSA** | [Official GitHub link](https://github.com/slsa-framework/slsa/blob/main/docs/index.md ) | Supply-chain Levels for Software Artifacts |![SLSA](https://img.shields.io/github/stars/slsa-framework/slsa?style=for-the-badge) | 
| **kritis** | [https://github.com/grafeas/kritis](https://github.com/grafeas/kritis) | Solution for securing your software supply chain for Kubernetes apps |![Kritis](https://img.shields.io/github/stars/grafeas/kritis?style=for-the-badge)|
| **ratify** | [https://github.com/deislabs/ratify](https://github.com/deislabs/ratify) | Artifact Ratification Framework |![ratify](https://img.shields.io/github/stars/deislabs/ratify?style=for-the-badge)| 


## SAST

Static code review tools working with source code and looking for known patterns and relationships of methods, variables, classes and libraries. SAST works with the raw code and usually not with build packages. 

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **Brakeman** | [https://github.com/presidentbeef/brakeman](https://github.com/presidentbeef/brakeman) | Brakeman is a static analysis tool which checks Ruby on Rails applications for security vulnerabilities|![Brakeman](https://img.shields.io/github/stars/presidentbeef/brakeman?style=for-the-badge) | 
| **Semgrep** | [https://semgrep.dev/](https://semgrep.dev/) | Hi-Quality Open source, works on 17+ languages |![Semgrep](https://img.shields.io/github/stars/returntocorp/semgrep?style=for-the-badge) | 
| **Bandit** | [https://github.com/PyCQA/bandit ](https://github.com/PyCQA/bandit ) | Python specific SAST tool |![Bandit](https://img.shields.io/github/stars/PyCQA/bandit?style=for-the-badge) | 
| **libsast** | [https://github.com/ajinabraham/libsast ](https://github.com/ajinabraham/libsast ) | Generic SAST for Security Engineers. Powered by regex based pattern matcher and semantic aware semgrep |![libsast](https://img.shields.io/github/stars/ajinabraham/libsast?style=for-the-badge) | 
| **ESLint** | [https://eslint.org/](https://eslint.org/) | Find and fix problems in your JavaScript code | | 
| **nodejsscan** | [https://github.com/ajinabraham/nodejsscan](https://github.com/ajinabraham/nodejsscan) | NodeJs SAST scanner with GUI |![NodeJSscan](https://img.shields.io/github/stars/ajinabraham/nodejsscan?style=for-the-badge) | 
| **FindSecurityBugs** | [https://find-sec-bugs.github.io/](https://find-sec-bugs.github.io/) | The SpotBugs plugin for security audits of Java web applications |![FindSecuritybugs](https://img.shields.io/github/stars/find-sec-bugs/find-sec-bugs?style=for-the-badge) | 
| **SonarQube community** | [https://github.com/SonarSource/sonarqube](https://github.com/SonarSource/sonarqube) | Detect security issues in code review with Static Application Security Testing (SAST) |![SonarQube](https://img.shields.io/github/stars/SonarSource/sonarqube?style=for-the-badge) | 
| **gosec** | [https://github.com/securego/gosec](https://github.com/securego/gosec) | Inspects source code for security problems by scanning the Go AST. |![gosec](https://img.shields.io/github/stars/securego/gosec?style=for-the-badge) | 
| **Safety** | [https://github.com/pyupio/safety](https://github.com/pyupio/safety) | Checks Python dependencies for known security vulnerabilities . |![Safety](https://img.shields.io/github/stars/pyupio/safety?style=for-the-badge) | 

**Note:** Semgrep is free CLI tool, however some rulesets (https://semgrep.dev/r) are having various licences, some can be free to use and can be commercial.  

OWASP curated list of SAST tools : https://owasp.org/www-community/Source_Code_Analysis_Tools 

## DAST

Dynamic application security testing (DAST) is a type of application testing (in most cases web) that checks your application from the outside by active communication and analysis of the responses based on injected inputs. DAST tools rely on inputs and outputs to operate. A DAST tool uses these to check for security problems while the software is actually running and is actively deployed on the server (or serverless function).

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **Zap proxy** | [https://owasp.org/www-project-zap/](https://owasp.org/www-project-zap/) | Zap proxy providing various docker containers for CI/CD pipeline|![ZAP](https://img.shields.io/github/stars/zaproxy/zaproxy?style=for-the-badge) | 
| **Wapiti** | [https://github.com/wapiti-scanner/wapiti ](https://github.com/wapiti-scanner/wapiti ) | Light pipeline ready scanning tool |![Wapiti](https://img.shields.io/github/stars/wapiti-scanner/wapiti?style=for-the-badge) | 
| **Nuclei** | [https://github.com/projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) | Template based security scanning tool |![Nuclei](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=for-the-badge) | 
| **purpleteam** | [https://github.com/purpleteam-labs/purpleteam](https://github.com/purpleteam-labs/purpleteam) | CLI DAST tool incubator project |![purpleteam](https://img.shields.io/github/stars/purpleteam-labs/purpleteam?style=for-the-badge) | 
| **oss-fuzz** | [https://github.com/google/oss-fuzz ](https://github.com/google/oss-fuzz ) | OSS-Fuzz: Continuous Fuzzing for Open Source Software |![osss-fuzz](https://img.shields.io/github/stars/google/oss-fuzz?style=for-the-badge) | 
| **nikto** | [https://github.com/sullo/nikto](https://github.com/sullo/nikto) | Nikto web server scanner |![nikto](https://img.shields.io/github/stars/sullo/nikto?style=for-the-badge) | 
| **skipfish** | [https://code.google.com/archive/p/skipfish/](https://code.google.com/archive/p/skipfish/) | Skipfish is an active web application security reconnaissance tool|![skipfish](https://img.shields.io/github/stars/spinkham/skipfish?style=for-the-badge) | 

## Continuous deployment security

| Name | URL | Description | Meta |
| :---------- | :---------- | :---------- | :----------: |
| **SecureCodeBox** | [https://github.com/secureCodeBox/secureCodeBox](https://github.com/secureCodeBox/secureCodeBox) | Toolchain for continuous scanning of applications and infrastructure |![SCB](https://img.shields.io/github/stars/secureCodeBox/secureCodeBox?style=for-the-badge) | 
| **OpenSCAP** | [https://github.com/OpenSCAP/openscap](https://github.com/OpenSCAP/openscap) | Open Source Security Compliance Solution |![oscap](https://img.shields.io/github/stars/OpenSCAP/openscap?style=for-the-badge) | 
| **ThreatMapper** | [https://github.com/deepfence/ThreatMapper](https://github.com/deepfence/ThreatMapper) | ThreatMapper hunts for vulnerabilities in your production platforms, and ranks these vulnerabilities based on their risk-of-exploit. |![kube-hunter](https://img.shields.io/github/stars/deepfence/ThreatMapper?style=for-the-badge) | 

## Kubernetes 

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **KubiScan** | [https://github.com/cyberark/KubiScan](https://github.com/cyberark/KubiScan) | A tool for scanning Kubernetes cluster for risky permissions |![Kubiscan](https://img.shields.io/github/stars/cyberark/kubiscan?style=for-the-badge) | 
| **Kubeaudit** | [https://github.com/Shopify/kubeaudit](https://github.com/Shopify/kubeaudit) | Audit Kubernetes clusters for various different security concerns |![kube-audit](https://img.shields.io/github/stars/Shopify/kubeaudit?style=for-the-badge) | 
| **Kubescape** | [https://github.com/armosec/kubescape](https://github.com/armosec/kubescape) |  The first open-source tool for testing if Kubernetes is deployed according to the NSA-CISA and the MITRE ATT&CK®. |![kubescape](https://img.shields.io/github/stars/armosec/kubescape?style=for-the-badge) |
| **kubesec** | [https://github.com/controlplaneio/kubesec](https://github.com/controlplaneio/kubesec) | Security risk analysis for Kubernetes resources |![kubesec](https://img.shields.io/github/stars/controlplaneio/kubesec?style=for-the-badge) | 
| **kube-bench** | [https://github.com/aquasecurity/kube-bench ](https://github.com/aquasecurity/kube-bench ) | Kubernetes benchmarking tool|![Kubiscan](https://img.shields.io/github/stars/aquasecurity/kube-bench?style=for-the-badge) | 
| **kube-score** | [https://github.com/zegl/kube-score](https://github.com/zegl/kube-score) | Static code analysis of your Kubernetes object definitions |![kube-score](https://img.shields.io/github/stars/zegl/kube-score?style=for-the-badge) | 
| **kube-hunter** | [https://github.com/aquasecurity/kube-hunter](https://github.com/aquasecurity/kube-hunter) | Active scanner for k8s (purple)  |![kube-hunter](https://img.shields.io/github/stars/aquasecurity/kube-hunter?style=for-the-badge) | 
| **Calico** | [https://github.com/projectcalico/calico](https://github.com/projectcalico/calico) | Calico is an open source networking and network security solution for containers  |![Calico](https://img.shields.io/github/stars/projectcalico/calico?style=for-the-badge) | 
| **Krane** | [https://github.com/appvia/krane](https://github.com/appvia/krane) | Simple Kubernetes RBAC static analysis tool |![krane](https://img.shields.io/github/stars/appvia/krane?style=for-the-badge) | 
| **Starboard** | [https://github.com/aquasecurity/starboard](https://github.com/aquasecurity/starboard ) | Starboard inegrates security tools by outputs into Kubernetes CRDs |![starboard](https://img.shields.io/github/stars/aquasecurity/starboard?style=for-the-badge) | 
| **Gatekeeper** | [https://github.com/open-policy-agent/gatekeeper](https://github.com/open-policy-agent/gatekeeper) | Open policy agent gatekeeper for k8s |![gatekeeper](https://img.shields.io/github/stars/open-policy-agent/gatekeeper?style=for-the-badge) | 
| **Inspektor-gadget** | [https://github.com/kinvolk/inspektor-gadget](https://github.com/kinvolk/inspektor-gadget ) | Collection of tools (or gadgets) to debug and inspect k8s |![inspector](https://img.shields.io/github/stars/kinvolk/inspektor-gadget?style=for-the-badge) | 
| **kube-linter** | [https://github.com/stackrox/kube-linter ](https://github.com/stackrox/kube-linter) | Static analysis for Kubernetes |![kube-linter](https://img.shields.io/github/stars/stackrox/kube-linter?style=for-the-badge) | 
| **mizu-api-traffic-viewer** | [https://github.com/up9inc/mizu](https://github.com/up9inc/mizu) | A simple-yet-powerful API traffic viewer for Kubernetes enabling you to view all API communication between microservices to help your debug and troubleshoot regressions. |[![GitHub stars](https://img.shields.io/github/stars/up9inc/mizu)](https://github.com/up9inc/mizu/stargazers) | 
| **HelmSnyk** | [https://github.com/snyk-labs/helm-snyk](https://github.com/snyk-labs/helm-snyk) | The Helm plugin for Snyk provides a subcommand for testing the images. |[![GitHub stars](https://img.shields.io/github/stars/snyk-labs/helm-snyk)](https://github.com/snyk-labs/helm-snyk/stargazers) | 
| **Kubewarden** | [https://github.com/orgs/kubewarden/repositories](https://github.com/orgs/kubewarden/repositories) | Policy as code for kubernetes from SUSE. |[![GitHub stars](https://img.shields.io/github/stars/kubewarden/kwctl)](https://github.com/up9inc/kubewarden/kwctl) | 
| **Kubernetes-sigs BOM** | [https://github.com/kubernetes-sigs/bom](https://img.shields.io/github/stars/kubernetes-sigs/bom) |Kubernetes BOM generator |[![GitHub stars](https://img.shields.io/github/stars/kubernetes-sigs/bom)](https://img.shields.io/github/stars/kubernetes-sigs/bom) | 
| **Capsule** | [https://github.com/clastix/capsule](https://github.com/clastix/capsule) | A multi-tenancy and policy-based framework for Kubernetes |![GitHub stars](https://img.shields.io/github/stars/clastix/capsule) |
| **Badrobot** | [https://github.com/controlplaneio/badrobot](https://github.com/controlplaneio/badrobot) | Badrobot is a Kubernetes Operator audit tool |![GitHub stars](https://img.shields.io/github/stars/controlplaneio/badrobot) |
| **Istio** | [https://istio.io](https://istio.io) | Istio is a service mesh based on Envoy. Engage encryption, role-based access, and authentication across services. ||![GitHub stars](https://img.shields.io/github/stars/istio/istio) |


## Containers 

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **Harbor** | [https://github.com/goharbor/harbor](https://github.com/goharbor/harbor) | Trusted cloud native registry project|![Harbor](https://img.shields.io/github/stars/goharbor/harbor?style=for-the-badge) | 
| **Anchore** | [https://github.com/anchore/anchore-engine](https://github.com/anchore/anchore-engine) | Centralized service for inspection, analysis, and certification of container images |![Anchore](https://img.shields.io/github/stars/anchore/anchore-engine?style=for-the-badge) | 
| **Clair** | [https://github.com/quay/clair](https://github.com/quay/clair) | Docker vulnerability scanner|![Clair](https://img.shields.io/github/stars/goharbor/harbor?style=for-the-badge) | 
| **Deepfence ThreatMapper** | [https://github.com/deepfence/ThreatMapper](https://github.com/deepfence/ThreatMapper) | Apache v2, powerful runtime vulnerability scanner for kubernetes, virtual machines and serverless. | ![ThreatMapper](https://img.shields.io/github/stars/deepfence/ThreatMapper?style=for-the-badge) | 
| **Docker bench** | [https://github.com/docker/docker-bench-security ](https://github.com/docker/docker-bench-security ) | Docker benchmarking against CIS|![docker bench](https://img.shields.io/github/stars/goharbor/harbor?style=for-the-badge)| 
| **Falco** | [https://github.com/falcosecurity/falco](https://github.com/falcosecurity/falco) | Container runtime protection |![Falco](https://img.shields.io/github/stars/falcosecurity/falco?style=for-the-badge) | 
| **Trivy** | [https://github.com/aquasecurity/trivy](https://github.com/aquasecurity/trivy) | Comprehensive scanner for vulnerabilities in container images |![Trivy](https://img.shields.io/github/stars/aquasecurity/trivy?style=for-the-badge) | 
| **Notary** | [https://github.com/notaryproject/notary](https://github.com/notaryproject/notary) | Docker signing|![Notary](https://img.shields.io/github/stars/notaryproject/notary?style=for-the-badge) | 
| **Cosign** | [https://github.com/sigstore/cosign](https://github.com/sigstore/cosign) | Container signing|![Cosign](https://img.shields.io/github/stars/sigstore/cosign?style=for-the-badge) | 
| **watchtower** | [https://github.com/containrrr/watchtower](https://github.com/containrrr/watchtower) | Updates the running version of your containerized app |![watchtower](https://img.shields.io/github/stars/containrrr/watchtower?style=for-the-badge) |
| **Grype** | [https://github.com/anchore/grype](https://github.com/anchore/grype) | Vulnerability scanner for container images (and also filesystems). |![Grype](https://img.shields.io/github/stars/anchore/grype?style=for-the-badge) |

## Multi-Cloud 

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **Cloudsploit** | [https://github.com/aquasecurity/cloudsploit](https://github.com/aquasecurity/cloudsploit) | Detection of security risks in cloud infrastructure |![Cloudsploit](https://img.shields.io/github/stars/aquasecurity/cloudsploit?style=for-the-badge) |
| **ScoutSuite** | [https://github.com/nccgroup/ScoutSuite](https://github.com/nccgroup/ScoutSuite) | NCCgroup mutlicloud scanning tool |![ScoutSuite](https://img.shields.io/github/stars/nccgroup/ScoutSuite?style=for-the-badge) |
| **CloudCustodian** | [https://github.com/cloud-custodian/cloud-custodian/](https://github.com/cloud-custodian/cloud-custodian/) | Multicloud security analysis framework |![CloudCustodian](https://img.shields.io/github/stars/cloud-custodian/cloud-custodian?style=for-the-badge) | 
| **CloudGraph** | [https://github.com/cloudgraphdev/cli](https://github.com/cloudgraphdev/cli) | GraphQL API + Security for AWS, Azure, GCP, and K8s |![CloudGraph](https://img.shields.io/github/stars/cloudgraphdev/cli?style=for-the-badge) |

## AWS 

AWS specific DevSecOps tooling. Tools here cover different areas like inventory management, misconfiguration scanning or IAM roles and policies review. 

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **Dragoneye** | [https://github.com/indeni/dragoneye](https://github.com/indeni/dragoneye) | Dragoneye Indeni AWS scanner |![Dragoneye](https://img.shields.io/github/stars/indeni/dragoneye?style=for-the-badge) |
| **Prowler** | [https://github.com/toniblyx/prowler](https://github.com/toniblyx/prowler) | Prowler is a command line tool that helps with AWS security assessment, auditing, hardening and incident response. |![Prowler](https://img.shields.io/github/stars/toniblyx/prowler?style=for-the-badge) |
| **aws-inventory** | [https://github.com/nccgroup/aws-inventory](https://github.com/nccgroup/aws-inventory) | Helps to discover all AWS resources created in an account|![aws-inventory](https://img.shields.io/github/stars/nccgroup/aws-inventory?style=for-the-badge) |
| **PacBot** | [https://github.com/tmobile/pacbot](https://github.com/tmobile/pacbot) | Policy as Code Bot (PacBot)|![pacbot](https://img.shields.io/github/stars/tmobile/pacbot?style=for-the-badge) |
| **Komiser** | [https://github.com/mlabouardy/komiser](https://github.com/mlabouardy/komiser) | Monitoring dashboard for costs and security|![komiser](https://img.shields.io/github/stars/mlabouardy/komiser?style=for-the-badge) |
| **Cloudsplaining** | [https://github.com/salesforce/cloudsplaining](https://github.com/salesforce/cloudsplaining) | IAM analysis framework |![cloudsplaining](https://img.shields.io/github/stars/salesforce/cloudsplaining?style=for-the-badge) |
| **ElectricEye** | [https://github.com/jonrau1/ElectricEye](https://github.com/jonrau1/ElectricEye) | Continuously monitor your AWS services for configurations |![ElectricEye](https://img.shields.io/github/stars/jonrau1/ElectricEye?style=for-the-badge) |
| **Cloudmapper** | [https://github.com/duo-labs/cloudmapper](https://github.com/duo-labs/cloudmapper ) | CloudMapper helps you analyze your Amazon Web Services (AWS) environments |![cloudmapper](https://img.shields.io/github/stars/duo-labs/cloudmapper?style=for-the-badge) | 
| **cartography** | [https://github.com/lyft/cartography](https://github.com/lyft/cartography) | Consolidates AWS infrastructure assets and the relationships between them in an intuitive graph |![cartography](https://img.shields.io/github/stars/lyft/cartography?style=for-the-badge) | 
| **policy_sentry** | [https://github.com/salesforce/policy_sentry](https://github.com/salesforce/policy_sentry ) | IAM Least Privilege Policy Generator |![policycentry](https://img.shields.io/github/stars/salesforce/policy_sentry?style=for-the-badge) | 
| **AirIAM** | [https://github.com/bridgecrewio/AirIAM](https://github.com/bridgecrewio/AirIAM) | IAM Least Privilege anmalyzer and Terraformer |![AirIam](https://img.shields.io/github/stars/bridgecrewio/AirIAM?style=for-the-badge) | 
| **StreamAlert** | [https://github.com/airbnb/streamalert](https://github.com/airbnb/streamalert ) | AirBnB serverless, real-time data analysis framework which empowers you to ingest, analyze, and alert  |![StreamAlert](https://img.shields.io/github/stars/airbnb/streamalert?style=for-the-badge) | 
| **CloudQuery** | [https://github.com/cloudquery/cloudquery/](https://github.com/cloudquery/cloudquery/) | AirBnB serverless, real-time data analysis framework which empowers you to ingest, analyze, and alert  |![CloudQuery](https://img.shields.io/github/stars/cloudquery/cloudquery?style=for-the-badge) | 
| **S3Scanner** | [https://github.com/sa7mon/S3Scanner/](https://github.com/cloudquery/cloudquery/) | A tool to find open S3 buckets and dump their contents  |![S3Scanner](https://img.shields.io/github/stars/sa7mon/S3Scanner?style=for-the-badge) | 
| **aws-iam-authenticator** | [https://github.com/kubernetes-sigs/aws-iam-authenticator/](https://github.com/kubernetes-sigs/aws-iam-authenticator/) | A tool to use AWS IAM credentials to authenticate to a Kubernetes cluster |![authenticator](https://img.shields.io/github/stars/kubernetes-sigs/aws-iam-authenticator?style=for-the-badge) | 
| **kube2iam** | [https://github.com/jtblin/kube2iam/](https://github.com/jtblin/kube2iam/) | A tool to use AWS IAM credentials to authenticate to a Kubernetes cluster |![kube2iam](https://img.shields.io/github/stars/jtblin/kube2iam?style=for-the-badge) | 
| **AWS open source security samples** | [Official AWS opensource repo](https://github.com/orgs/aws-samples/repositories?language=&q=security&sort=&type=) |Collection of official AWS open-source resources | ![Amazon AWS](https://img.shields.io/static/v1?style=for-the-badge&message=Amazon+AWS&color=232F3E&logo=Amazon+AWS&logoColor=FFFFFF&label=)| 
| **AWS Firewall factory** | [Globaldatanet FMS automation](https://github.com/globaldatanet/aws-firewall-factory) |Deploy, update, and stage your WAFs while managing them centrally via FMS | ![Globaldatanet Firewall factory](https://img.shields.io/github/stars/globaldatanet/aws-firewall-factory?style=for-the-badge)| 
| **Parliment** | [Parliment](https://github.com/duo-labs/parliament) | Parliament is an AWS IAM linting library | ![IAM linting](https://img.shields.io/github/stars/duo-labs/parliament?style=for-the-badge)| 
| **Yor** | [Yor](https://github.com/bridgecrewio/yor) | Adds informative and consistent tags across infrastructure-as-code frameworks such as Terraform, CloudFormation, and Serverless | ![Yor](https://img.shields.io/github/stars/bridgecrewio/yor?style=for-the-badge)|


## Google cloud platform 

GCP specific DevSecOps tooling. Tools here cover different areas like inventory management, misconfiguration scanning or IAM roles and policies review. 

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **Forseti** | [https://github.com/forseti-security/forseti-security](https://github.com/forseti-security/forseti-security) | Complex security orchestration and scanning platform | ![Forseti](https://img.shields.io/github/stars/forseti-security/forseti-security?style=for-the-badge)|


## Policy as code

Policy as code is the idea of writing code in a high-level language to manage and automate policies. By representing policies as code in text files, proven software development best practices can be adopted such as version control, automated testing, and automated deployment. (Source: https://docs.hashicorp.com/sentinel/concepts/policy-as-code)

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **Open Policy agent** | [https://github.com/open-policy-agent/opa](https://github.com/open-policy-agent/opa) | General-purpose policy engine that enables unified, context-aware policy enforcement across the entire stack |![OPA](https://img.shields.io/github/stars/open-policy-agent/opa?style=for-the-badge) |
| **Kyverno** | [https://github.com/kyverno/kyverno](https://github.com/kyverno/kyverno) | Kyverno is a policy engine designed for Kubernetes |![kyverno](https://img.shields.io/github/stars/kyverno/kyverno?style=for-the-badge) | 
| **Inspec** | [https://github.com/inspec/inspec](https://github.com/inspec/inspec) | Chef InSpec is an open-source testing framework for infrastructure with a human- and machine-readable language for specifying compliance, security and policy requirements. |![Inspec](https://img.shields.io/github/stars/inspec/inspec?style=for-the-badge) | 
| **Cloud Formation guard** | [https://github.com/aws-cloudformation/cloudformation-guard](https://github.com/aws-cloudformation/cloudformation-guard) | Cloud Formation policy as code |![cf-guard](https://img.shields.io/github/stars/aws-cloudformation/cloudformation-guard?style=for-the-badge) |
| **cnspec** | [https://github.com/mondoohq/cnspec](https://github.com/mondoohq/cnspec) | cnspec is a cloud-native and powerful Policy as Code engine to assess the security and compliance of your business-critical infrastructure. cnspec finds vulnerabilities and misconfigurations on all systems in your infrastructure including: public and private cloud environments, Kubernetes clusters, containers, container registries, servers and endpoints, SaaS products, infrastructure as code, APIs, and more. |![cf-guard](https://img.shields.io/github/stars/mondoohq/cnspec?style=for-the-badge) |


## Chaos engineering

Chaos Engineering is the discipline of experimenting on a system in order to build confidence in the system’s capability to withstand turbulent conditions in production.

Reading and manifestos: https://principlesofchaos.org/

| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |
| **chaos-mesh** | [https://github.com/chaos-mesh/chaos-mesh](https://github.com/chaos-mesh/chaos-mesh) | It is a cloud-native Chaos Engineering platform that orchestrates chaos on Kubernetes environments |![Chaos mesh](https://img.shields.io/github/stars/chaos-mesh/chaos-mesh?style=for-the-badge) |
| **Chaos monkey** | [https://netflix.github.io/chaosmonkey/](https://netflix.github.io/chaosmonkey/) | Chaos Monkey is responsible for randomly terminating instances in production to ensure that engineers implement their services to be resilient to instance failures. |![Chaos monkey](https://img.shields.io/github/stars/Netflix/chaosmonkey?style=for-the-badge) |
| **Chaos Engine** | [https://thalesgroup.github.io/chaos-engine/](https://thalesgroup.github.io/chaos-engine/) | The Chaos Engine is a tool that is designed to intermittently destroy or degrade application resources running in cloud based infrastructure. These events are designed to occur while the appropriate resources are available to resolve the issue if the platform fails to do so on it's own. |![Chaos Engine](https://img.shields.io/github/stars/thalesgroup/chaos-engine?style=for-the-badge) |
| **chaoskube** | [https://github.com/linki/chaoskube ](https://github.com/linki/chaoskube ) | Test how your system behaves under arbitrary pod failures. |![chaoskube](https://img.shields.io/github/stars/linki/chaoskube?style=for-the-badge) |
| **Kube-Invaders** | [https://github.com/lucky-sideburn/KubeInvaders](https://github.com/lucky-sideburn/KubeInvaders) | Gamified chaos engineering tool for Kubernetes |![chaoskube](https://img.shields.io/github/stars/lucky-sideburn/KubeInvaders?style=for-the-badge) |
| **kube-monkey** | [https://github.com/asobti/kube-monkey](https://github.com/asobti/kube-monkey) | Gamified chaos engineering tool for Kubernetes |![kube-monkey](https://img.shields.io/github/stars/asobti/kube-monkey?style=for-the-badge) |
| **Litmus Chaos** | [https://litmuschaos.io/](https://litmuschaos.io/) | Litmus is an end-to-end chaos engineering platform for cloud native infrastructure and applications. Litmus is designed to orchestrate and analyze chaos in their environments. | ![Litmus](https://img.shields.io/github/stars/litmuschaos/litmus?style=for-the-badge) |
| **Gremlin** | [https://github.com/gremlin/gremlin-python](https://github.com/gremlin/gremlin-python) | Chaos enginnering SaaS platform with free plan and some open source libraries |![Gremlin](https://img.shields.io/github/stars/gremlin/gremlin-python?style=for-the-badge) |
| **AWS FIS samples** | [https://github.com/aws-samples/aws-fault-injection-simulator-samples](https://github.com/aws-samples/aws-fault-injection-simulator-samples) | AWS Fault injection simulator samples |![AWS](https://img.shields.io/github/stars/aws-samples/aws-fault-injection-simulator-samples?style=for-the-badge) |
| **CloudNuke** | [https://github.com/gruntwork-io/cloud-nuke](https://github.com/gruntwork-io/cloud-nuke) | CLI tool to delete all resources in an AWS account |![CloudNuke](https://img.shields.io/github/stars/gruntwork-io/cloud-nuke?style=for-the-badge) |

## Infrastructure as code security 

Scanning your infrastructure when it is only code helps shift-left the security. Many tools offer in IDE scanning and providing real-time advisory do Cloud engineers. 

| Name | URL | Description | Meta |
| :---------- | :---------- | :---------- | :----------: |
| **KICS** | [https://github.com/Checkmarx/kics](https://github.com/Checkmarx/kics) | Checkmarx security testing opensource for IaC |![Checkmarx](https://img.shields.io/github/stars/Checkmarx/kics?style=for-the-badge) | 
| **Checkov** | [https://github.com/bridgecrewio/checkov](https://github.com/bridgecrewio/checkov) | Checkov is a static code analysis tool for infrastructure-as-code |![Checkov](https://img.shields.io/github/stars/bridgecrewio/checkov?style=for-the-badge) | 
| **tfsec** | [https://github.com/aquasecurity/tfsec](https://github.com/aquasecurity/tfsec) | tfsec uses static analysis of your terraform templates to spot potential security issues. Now with terraform CDK support |![tfsec](https://img.shields.io/github/stars/aquasecurity/tfsec?style=for-the-badge) | 
| **terrascan** | [https://github.com/accurics/terrascan](https://github.com/accurics/terrascan) | Terrascan is a static code analyzer for Infrastructure as Code |![terrascan](https://img.shields.io/github/stars/accurics/terrascan?style=for-the-badge) | 
| **cfsec** | [https://github.com/aquasecurity/cfsec](https://github.com/aquasecurity/cfsec) | cfsec scans CloudFormation configuration files for security issues |![cfsec](https://img.shields.io/github/stars/aquasecurity/cfsec?style=for-the-badge) | 
| **cfn_nag** | [https://github.com/stelligent/cfn_nag](https://github.com/stelligent/cfn_nag) |  Looks for insecure patterns in CloudFormation |![cfnag](https://img.shields.io/github/stars/stelligent/cfn_nag?style=for-the-badge) | 
| **Sysdig IaC scanner action** | [https://github.com/sysdiglabs/cloud-iac-scanner-action](https://github.com/sysdiglabs/cloud-iac-scanner-action) |  Scans your repository with Sysdig IAC Scanner and report the vulnerabilities. |![sysdig iac scanner](https://img.shields.io/github/stars/sysdiglabs/cloud-iac-scanner-action?style=for-the-badge) |

## Orchestration 

Event driven security help to drive, automate and execute tasks for security processes. The tools here and not dedicated security tools but are helping to automate and orchestrate security tasks or are part of most modern security automation frameworks or tools. 

| Name | URL | Description | Meta |
| :---------- | :---------- | :---------- | :----------: |
| **StackStorm** | [https://github.com/StackStorm/st2](https://github.com/StackStorm/st2) | Platform for integration and automation across services and tools supporting event driven security |![StackStorm](https://img.shields.io/github/stars/StackStorm/st2?style=for-the-badge) | 
| **Camunda** | [https://github.com/camunda/camunda-bpm-platform](https://github.com/camunda/camunda-bpm-platform) | Workflow and process automation |![Camunda](https://img.shields.io/github/stars/camunda/camunda-bpm-platform?style=for-the-badge)| 
| **DefectDojo** | [https://github.com/DefectDojo/django-DefectDojo](https://github.com/DefectDojo/django-DefectDojo) | Security orchestration and vulnerability management platform |![DefectDojo](https://img.shields.io/github/stars/DefectDojo/django-DefectDojo?style=for-the-badge) | 
| **Faraday** | [https://github.com/infobyte/faraday](https://github.com/infobyte/faraday) | Security suite for Security Orchestration, vulnerability management and centralized information |![Faraday](https://img.shields.io/github/stars/infobyte/faraday) |

#TODO: REFACTOR UNDER THESE SECTIONS

## Monitoring
| Name | URL | Description | Meta | 
| :---------- | :---------- | :---------- | :----------: |


