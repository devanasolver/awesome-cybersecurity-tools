<h1 align="center">Awesome Cybersecurity Tools</h1>

<p align="center"><img src="assets/banner.png" alt="Awesome Cybersecurity Tools" width="100%"></p>

<p align="center">
<a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
<img src="https://img.shields.io/badge/PRs-welcome-brightgreen" alt="PRs welcome">
<img src="https://img.shields.io/badge/license-CC0--1.0-blue" alt="License CC0 1.0">
<a href="https://github.com/devanasolver/awesome-cybersecurity-tools/commits/main"><img src="https://img.shields.io/github/last-commit/devanasolver/awesome-cybersecurity-tools" alt="Last commit"></a>
</p>

<p align="center">
<a href="https://github.com/devanasolver"><img src="https://img.shields.io/badge/Follow-@devanasolver-181717?style=for-the-badge&logo=github" alt="Follow on GitHub"></a>
<a href="https://github.com/devanasolver/awesome-cybersecurity-tools/stargazers"><img src="https://img.shields.io/github/stars/devanasolver/awesome-cybersecurity-tools?style=for-the-badge&logo=github&label=Star%20this%20list" alt="Star this list"></a>
<a href="https://buymeacoffee.com/isaac49"><img src="https://img.shields.io/badge/Buy%20me%20a%20coffee-isaac49-ffdd00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy me a coffee"></a>
</p>

> Open-source tools for scanning, monitoring, secrets, hardening and security learning. For defense and authorized testing. Every entry shows its license.

**Rules of this list:** every repo exists, is public, is not archived, states a license and has had a commit in the last year. One plain sentence each. Star counts and claims are the authors' own, we did not test every tool. Checked 2026-10-18. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Vulnerability scanners](#vulnerability-scanners)
- [Application security and code scanning](#application-security-and-code-scanning)
- [Secrets and credentials](#secrets-and-credentials)
- [Monitoring, SIEM and detection](#monitoring-siem-and-detection)
- [Hardening and configuration](#hardening-and-configuration)
- [Network and web testing](#network-and-web-testing)
- [Cloud and infrastructure security](#cloud-and-infrastructure-security)
- [Privacy and identity](#privacy-and-identity)
- [Learning and practice](#learning-and-practice)
- [How to choose](#how-to-choose)
- [Contributing](#contributing)

## Vulnerability scanners

Find known issues in hosts, apps and containers.

- [anchore/grype](https://github.com/anchore/grype) ![stars](https://img.shields.io/github/stars/anchore/grype?style=flat&label=%E2%98%85) - Vulnerability scanner for container images and filesystems. _(Apache-2.0)_
- [aquasecurity/trivy](https://github.com/aquasecurity/trivy) ![stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=flat&label=%E2%98%85) - Scanner for vulnerabilities, misconfigurations and secrets in containers and code. _(Apache-2.0)_
- [google/osv-scanner](https://github.com/google/osv-scanner) ![stars](https://img.shields.io/github/stars/google/osv-scanner?style=flat&label=%E2%98%85) - Vulnerability scanner using the OSV database. _(Apache-2.0)_
- [greenbone/openvas-scanner](https://github.com/greenbone/openvas-scanner) ![stars](https://img.shields.io/github/stars/greenbone/openvas-scanner?style=flat&label=%E2%98%85) - Open-source vulnerability scanner. _(GPL-2.0)_
- [OWASP/Nettacker](https://github.com/OWASP/Nettacker) ![stars](https://img.shields.io/github/stars/OWASP/Nettacker?style=flat&label=%E2%98%85) - Automated penetration testing and information gathering framework. _(Apache-2.0)_
- [projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) ![stars](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=flat&label=%E2%98%85) - Fast vulnerability scanner based on templates. _(MIT)_

## Application security and code scanning

SAST, dependency checks and fuzzing.

- [AFLplusplus/AFLplusplus](https://github.com/AFLplusplus/AFLplusplus) ![stars](https://img.shields.io/github/stars/AFLplusplus/AFLplusplus?style=flat&label=%E2%98%85) - Fuzzing tool, the community-maintained AFL. _(AGPL-3.0)_
- [anchore/syft](https://github.com/anchore/syft) ![stars](https://img.shields.io/github/stars/anchore/syft?style=flat&label=%E2%98%85) - Generate a software bill of materials from images and filesystems. _(Apache-2.0)_
- [github/codeql](https://github.com/github/codeql) ![stars](https://img.shields.io/github/stars/github/codeql?style=flat&label=%E2%98%85) - CodeQL queries and libraries for code analysis. _(MIT)_
- [google/oss-fuzz](https://github.com/google/oss-fuzz) ![stars](https://img.shields.io/github/stars/google/oss-fuzz?style=flat&label=%E2%98%85) - Continuous fuzzing for open source software. _(Apache-2.0)_
- [PyCQA/bandit](https://github.com/PyCQA/bandit) ![stars](https://img.shields.io/github/stars/PyCQA/bandit?style=flat&label=%E2%98%85) - Find common security issues in Python code. _(Apache-2.0)_
- [semgrep/semgrep](https://github.com/semgrep/semgrep) ![stars](https://img.shields.io/github/stars/semgrep/semgrep?style=flat&label=%E2%98%85) - Lightweight static analysis for many languages. _(LGPL-2.1)_
- [SonarSource/sonarqube](https://github.com/SonarSource/sonarqube) ![stars](https://img.shields.io/github/stars/SonarSource/sonarqube?style=flat&label=%E2%98%85) - Code quality and security analysis platform. _(LGPL-3.0)_

## Secrets and credentials

Find leaked keys and manage secrets.

- [bitnami/sealed-secrets](https://github.com/bitnami/sealed-secrets) ![stars](https://img.shields.io/github/stars/bitnami/sealed-secrets?style=flat&label=%E2%98%85) - Encrypt Kubernetes secrets so they are safe in git. _(Apache-2.0)_
- [getsops/sops](https://github.com/getsops/sops) ![stars](https://img.shields.io/github/stars/getsops/sops?style=flat&label=%E2%98%85) - Simple and flexible tool for managing secrets in files. _(MPL-2.0)_
- [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) ![stars](https://img.shields.io/github/stars/gitleaks/gitleaks?style=flat&label=%E2%98%85) - Find secrets in git repos and files. _(MIT)_
- [hashicorp/vault](https://github.com/hashicorp/vault) ![stars](https://img.shields.io/github/stars/hashicorp/vault?style=flat&label=%E2%98%85) - Tool for managing secrets and protecting sensitive data. Source-available license. _(check repo)_
- [Infisical/infisical](https://github.com/Infisical/infisical) ![stars](https://img.shields.io/github/stars/Infisical/infisical?style=flat&label=%E2%98%85) - Open-source secrets management platform. _(check repo)_
- [trufflesecurity/trufflehog](https://github.com/trufflesecurity/trufflehog) ![stars](https://img.shields.io/github/stars/trufflesecurity/trufflehog?style=flat&label=%E2%98%85) - Find, verify and analyze leaked credentials. _(AGPL-3.0)_
- [Yelp/detect-secrets](https://github.com/Yelp/detect-secrets) ![stars](https://img.shields.io/github/stars/Yelp/detect-secrets?style=flat&label=%E2%98%85) - Enterprise-friendly way of detecting secrets in code. _(Apache-2.0)_

## Monitoring, SIEM and detection

Logs and alerts.

- [crowdsecurity/crowdsec](https://github.com/crowdsecurity/crowdsec) ![stars](https://img.shields.io/github/stars/crowdsecurity/crowdsec?style=flat&label=%E2%98%85) - Collaborative, open-source security engine that blocks bad actors. _(MIT)_
- [fail2ban/fail2ban](https://github.com/fail2ban/fail2ban) ![stars](https://img.shields.io/github/stars/fail2ban/fail2ban?style=flat&label=%E2%98%85) - Daemon that bans hosts causing repeated authentication failures. _(check repo)_
- [falcosecurity/falco](https://github.com/falcosecurity/falco) ![stars](https://img.shields.io/github/stars/falcosecurity/falco?style=flat&label=%E2%98%85) - Cloud-native runtime security. _(Apache-2.0)_
- [OISF/suricata](https://github.com/OISF/suricata) ![stars](https://img.shields.io/github/stars/OISF/suricata?style=flat&label=%E2%98%85) - Network intrusion detection and prevention engine. _(GPL-2.0)_
- [osquery/osquery](https://github.com/osquery/osquery) ![stars](https://img.shields.io/github/stars/osquery/osquery?style=flat&label=%E2%98%85) - SQL-powered operating system instrumentation and monitoring. _(check repo)_
- [SigmaHQ/sigma](https://github.com/SigmaHQ/sigma) ![stars](https://img.shields.io/github/stars/SigmaHQ/sigma?style=flat&label=%E2%98%85) - Generic signature format for SIEM systems. _(check repo)_
- [wazuh/wazuh](https://github.com/wazuh/wazuh) ![stars](https://img.shields.io/github/stars/wazuh/wazuh?style=flat&label=%E2%98%85) - Open-source security platform for threat detection and monitoring. _(check repo)_
- [zeek/zeek](https://github.com/zeek/zeek) ![stars](https://img.shields.io/github/stars/zeek/zeek?style=flat&label=%E2%98%85) - Powerful network analysis framework. _(check repo)_

## Hardening and configuration

Benchmarks and baselines.

- [aquasecurity/kube-bench](https://github.com/aquasecurity/kube-bench) ![stars](https://img.shields.io/github/stars/aquasecurity/kube-bench?style=flat&label=%E2%98%85) - Checks Kubernetes against the CIS benchmark. _(Apache-2.0)_
- [CISOfy/lynis](https://github.com/CISOfy/lynis) ![stars](https://img.shields.io/github/stars/CISOfy/lynis?style=flat&label=%E2%98%85) - Security auditing tool for Unix-based systems. _(GPL-3.0)_
- [dev-sec/ansible-collection-hardening](https://github.com/dev-sec/ansible-collection-hardening) ![stars](https://img.shields.io/github/stars/dev-sec/ansible-collection-hardening?style=flat&label=%E2%98%85) - Ansible roles for hardening operating systems and services. _(Apache-2.0)_
- [inspec/inspec](https://github.com/inspec/inspec) ![stars](https://img.shields.io/github/stars/inspec/inspec?style=flat&label=%E2%98%85) - Compliance and security testing framework. _(check repo)_
- [OpenSCAP/openscap](https://github.com/OpenSCAP/openscap) ![stars](https://img.shields.io/github/stars/OpenSCAP/openscap?style=flat&label=%E2%98%85) - Standards-based compliance and vulnerability scanning. _(LGPL-2.1)_

## Network and web testing

For systems you are allowed to test.

- [nmap/nmap](https://github.com/nmap/nmap) ![stars](https://img.shields.io/github/stars/nmap/nmap?style=flat&label=%E2%98%85) - The network mapper and security scanner. _(check repo)_
- [projectdiscovery/httpx](https://github.com/projectdiscovery/httpx) ![stars](https://img.shields.io/github/stars/projectdiscovery/httpx?style=flat&label=%E2%98%85) - Fast HTTP toolkit for probing web servers. _(MIT)_
- [projectdiscovery/subfinder](https://github.com/projectdiscovery/subfinder) ![stars](https://img.shields.io/github/stars/projectdiscovery/subfinder?style=flat&label=%E2%98%85) - Passive subdomain discovery tool. _(MIT)_
- [rapid7/metasploit-framework](https://github.com/rapid7/metasploit-framework) ![stars](https://img.shields.io/github/stars/rapid7/metasploit-framework?style=flat&label=%E2%98%85) - Penetration testing framework. Use only with permission. _(check repo)_
- [sqlmapproject/sqlmap](https://github.com/sqlmapproject/sqlmap) ![stars](https://img.shields.io/github/stars/sqlmapproject/sqlmap?style=flat&label=%E2%98%85) - Automatic SQL injection detection tool. Use only on systems you are allowed to test. _(check repo)_
- [wireshark/wireshark](https://github.com/wireshark/wireshark) ![stars](https://img.shields.io/github/stars/wireshark/wireshark?style=flat&label=%E2%98%85) - Network protocol analyzer. _(GPL-2.0)_
- [zaproxy/zaproxy](https://github.com/zaproxy/zaproxy) ![stars](https://img.shields.io/github/stars/zaproxy/zaproxy?style=flat&label=%E2%98%85) - The ZAP web app scanner, for systems you are allowed to test. _(Apache-2.0)_

## Cloud and infrastructure security

Check cloud and IaC configs.

- [aquasecurity/tfsec](https://github.com/aquasecurity/tfsec) ![stars](https://img.shields.io/github/stars/aquasecurity/tfsec?style=flat&label=%E2%98%85) - Static analysis for Terraform. Now part of Trivy. _(MIT)_
- [bridgecrewio/checkov](https://github.com/bridgecrewio/checkov) ![stars](https://img.shields.io/github/stars/bridgecrewio/checkov?style=flat&label=%E2%98%85) - Static code analysis for infrastructure as code. _(Apache-2.0)_
- [kubescape/kubescape](https://github.com/kubescape/kubescape) ![stars](https://img.shields.io/github/stars/kubescape/kubescape?style=flat&label=%E2%98%85) - Kubernetes security platform with risk and compliance scanning. _(Apache-2.0)_
- [open-policy-agent/opa](https://github.com/open-policy-agent/opa) ![stars](https://img.shields.io/github/stars/open-policy-agent/opa?style=flat&label=%E2%98%85) - General-purpose policy engine. _(Apache-2.0)_
- [prowler-cloud/prowler](https://github.com/prowler-cloud/prowler) ![stars](https://img.shields.io/github/stars/prowler-cloud/prowler?style=flat&label=%E2%98%85) - Cloud security assessment tool for AWS, Azure, GCP and Kubernetes. _(Apache-2.0)_

## Privacy and identity

Passwords, 2FA and privacy tools.

- [beemdevelopment/Aegis](https://github.com/beemdevelopment/Aegis) ![stars](https://img.shields.io/github/stars/beemdevelopment/Aegis?style=flat&label=%E2%98%85) - Free, secure and open-source 2FA app for Android. _(GPL-3.0)_
- [bitwarden/server](https://github.com/bitwarden/server) ![stars](https://img.shields.io/github/stars/bitwarden/server?style=flat&label=%E2%98%85) - Server for the Bitwarden password manager. _(check repo)_
- [keepassxreboot/keepassxc](https://github.com/keepassxreboot/keepassxc) ![stars](https://img.shields.io/github/stars/keepassxreboot/keepassxc?style=flat&label=%E2%98%85) - Cross-platform community fork of KeePass. _(check repo)_
- [WireGuard/wireguard-tools](https://github.com/WireGuard/wireguard-tools) ![stars](https://img.shields.io/github/stars/WireGuard/wireguard-tools?style=flat&label=%E2%98%85) - Command-line tools for WireGuard VPN. _(GPL-2.0)_

## Learning and practice

Labs and training.

- [digininja/DVWA](https://github.com/digininja/DVWA) ![stars](https://img.shields.io/github/stars/digininja/DVWA?style=flat&label=%E2%98%85) - Damn Vulnerable Web Application for practice. _(GPL-3.0)_
- [juice-shop/juice-shop](https://github.com/juice-shop/juice-shop) ![stars](https://img.shields.io/github/stars/juice-shop/juice-shop?style=flat&label=%E2%98%85) - Intentionally insecure web app for security training. _(MIT)_
- [OWASP/CheatSheetSeries](https://github.com/OWASP/CheatSheetSeries) ![stars](https://img.shields.io/github/stars/OWASP/CheatSheetSeries?style=flat&label=%E2%98%85) - Concise good practices for application security. _(CC-BY-SA-4.0)_
- [swisskyrepo/PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) ![stars](https://img.shields.io/github/stars/swisskyrepo/PayloadsAllTheThings?style=flat&label=%E2%98%85) - List of payloads and bypasses for web security testing. _(MIT)_
- [WebGoat/WebGoat](https://github.com/WebGoat/WebGoat) ![stars](https://img.shields.io/github/stars/WebGoat/WebGoat?style=flat&label=%E2%98%85) - Deliberately insecure app for learning application security. _(check repo)_

## How to choose

- **Only test what you own or have written permission to test.**
- **Scanners give false positives.** Check findings by hand.
- **Keep tools updated.** Old signatures miss new threats.
- **Check the license.**

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). One entry per pull request, plain words, real sources only.

## About

Maintained by [@devanasolver](https://github.com/devanasolver). Listings follow the rules in CONTRIBUTING.

## Sponsor me

If this list is useful, [buy me a coffee](https://buymeacoffee.com/isaac49).
