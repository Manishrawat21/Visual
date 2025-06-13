# Visual Portfolio

**Manish Rawat**
Security Analyst | Detection Engineer | SOC Lab Builder
GitHub: [github.com/ManishRawat](https://github.com/ManishRawat)
Blog: [medium.com/@maxxrawat007](https://medium.com/@maxxrawat007)
LinkedIn: [linkedin.com/in/ManishRawat](#)

---

## 🧱 My SOC Lab Architecture

```
          [ Logs ]
             ⬇
       [ Wazuh IDS/Agent ]
             ⬇
       [ ELK Stack (Kibana) ]
             ⬇
          [ Alerts ]
             ⬇
   [ Manual IR / Response Playbook ]
```

* ✅ SIEM: Splunk, ELK
* ✅ IDS: Suricata, Wazuh
* ✅ Threat Intel: MISP (basic IOC ingestion)
* ✅ Analysis: Wireshark, MITRE ATT\&CK mapping

---

## 🔢 Tools & Skills at a Glance

* **SIEM & Log Analysis**: Splunk, ELK (Kibana)
* **Detection Rules**: Wazuh rules, Suricata signatures, YARA (basic)
* **EDR/Response Understanding**: SentinelOne, CrowdStrike Falcon (basic)
* **Threat Intel**: MISP feeds + Sigma rule mapping
* **Triage**: SPL queries, log correlation, alert logic
* **OS Experience**: Kali Linux, Ubuntu, Windows Server

---

## 📉 Real Detection Use Cases

### 🔐 Case 1: SSH Brute Force Detection (Wazuh + ELK)

* Wrote Wazuh rule to detect >5 failed logins within 1 minute
* Alert triggered in Kibana; triaged source IP and logs
* Simulated full IR lifecycle (containment → eradication → recovery)
* ✉ [Read the blog](https://medium.com/@maxxrawat007/detecting-ssh-brute-force-attacks-using-wazuh-and-elk-stack-home-soc-lab-simulation-ca74357c1c6a?source=friends_link&sk=7bcc08cf61656a7fb414efc2eaa28b3a)

### 🚨 Case 2: Port Scan Detection (Suricata + ELK)

* Simulated attack using Nmap from Kali Linux
* Detected via Suricata signature on port-scan behavior
* Alert visualized in ELK → Triaged → Blocked IP manually
* Documented as IR scenario + response logic (Blog in progress)

---

## 🌟 What Makes Me Different

* Built end-to-end SOC lab with zero budget
* Wrote and tested real detection rules (not just theory)
* Publicly shared my workflows and alerts
* Learned to think like an analyst — not just a tool user

---

**Available for Remote SOC / Detection Roles Globally**
✉ Let's connect: [rawatmanish21@outlook.com](mailto:rawatmanish21@outlook.com)
