- 🚧 Portfolio under continuous construction 👨‍💻  

<h1>Hi, I'm Caio! <br/><a href="https://www.linkedin.com/in/caiofranca/">Network Security Engineer</a></h1>

I engineer networks that scale.

10+ years in Network Operations Centre / IT Operation (Meta via Astreya; PwC Ireland; RTM), now focused on large-scale security, routing, telemetry, and infra automation.

---

## 🎓 Certifications

- [Let'sDefend — SOC Analyst Learning Path](https://app.letsdefend.io/certificate/show/751aadd1-f244-4785-b39e-546152a30075)
- [Google Cybersecurity Professional](https://www.credly.com/earner/earned/badge/5cdd9676-447e-4ddf-b049-dde73325cc85)
- [CompTIA Security+](https://www.credly.com/badges/a33f25c3-faa1-4d63-8b89-a76751bed636)

---

## 🧭 Highlights

- **Routing & Scale:** BGP, OSPF/IS-IS, MPLS fundamentals; hands-on GNS3/EVE-NG multi-vendor labs  
- **Automation:** Python for config templating, health checks, and change validation; GitOps workflows  
- **Observability:** NetFlow/SNMP, telemetry parsing, anomaly flags; Splunk/Zabbix/SolarWinds experience  
- **Reliability Mindset:** HA design, redundancy, failure drills, runbooks, and post-incident reviews  
- **Security-aware:** Firewalls/VPN, IDS/IPS, zero-trust fundamentals integrated into network designs  

---

## 🚀 Featured Projects

### 1️⃣ Backbone-style BGP Lab (EVE-NG)
**Goal:** emulate a mini backbone with route reflectors, graceful restart, and prefix-limit safety.

**What I built:**
- Multi-ASN topology with RR, iBGP/eBGP, MED/local-pref policies  
- Python script to push baseline configs and validate peering state (`netmiko` / `ncclient`)  
- Health check: dumps BGP summary, parses for stuck states, and opens a ticket if thresholds trip  

**Repo:** _coming soon_  
**Tech:** Cisco IOSv/CSR1000v, Juniper vMX, Python  

---

### 2️⃣ NetOps Automation Pack (Python)
**Goal:** one-click “pre-change / post-change” validation for links and routing.

**What I built:**
- Collects interface errors, BFD status, BGP session health; diffs before/after  
- Exports JSON + Markdown summaries for change records  

**Repo:** _coming soon_  
**Tech:** Python, TextFSM, Rich, GitHub Actions  

---

### 3️⃣ Monitoring & Telemetry Dash
**Goal:** lightweight telemetry pipeline + dashboards for packet loss/jitter and BGP flaps.

**What I built:**
- Collectors for SNMP/NetFlow, parser for syslog flaps, alert thresholds  
- Dashboard with top talkers and flap bursts; weekly SLA report generator  

**Repo:** _coming soon_  
**Tech:** Telegraf/InfluxDB (or Splunk), Python  

---

## 🛡️ Security & Blue-Team Labs

- Wireshark: packet triage & PCAP storytelling → _blog post in progress_  
- Suricata: rules, logs & signature tuning  
- LetsDefend SIEM Phishing walkthrough  
- Malware triage: static doc analysis; VT hash investigation  
- Linux: file permissions, hashing & decrypt tasks  

(These are linked from earlier portfolio items — ask me for quick demos.)

---

## 💼 Experience Snapshot

- **NOC / IT Ops (7+ yrs):** incident response, provisioning, VLAN/IP planning, DNS updates, RMA processes  
- **Vendors/Tech:** Cisco (IOS/NX-OS), Juniper, Palo Alto; load balancers; Splunk, Zabbix, SolarWinds  
- **Scripting:** Python for network tasks; git-based workflows and documentation  

---

## 🔭 What I’m Building Next (Roadmap)

- Add IS-IS and MPLS L3VPN to the backbone lab (with RR scaling tests)  
- CI checks for configs (lint, golden templates) + pre-merge simulation  
- Synthetic probes (loss/jitter) feeding SLOs and error budgets for links  

---

> 💬 I’m excited by roles that allow me to collaborate across backbone, data center, and automation teams to improve global network reliability.

---

## 🤳 Connect with me:
<div style="display: flex; align-items: center;">
  <a href="mailto:braga.caio@outlook.com">
    <img alt="CaioFranca | Email" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gmail.svg" style="margin-right: 10px;" />
  </a>
  <a href="https://linkedin.com/in/caiofranca">
    <img alt="CaioFranca | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" style="margin-right: 10px;" />
  </a>
  <a href="">
    <img alt="YourName | GitHub" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
  </a>
</div>
