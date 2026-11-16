# Smart Node Sentinel 🛡️

**Smart Node Sentinel** is a lightweight, zero-dependency Python & Linux daemon engineered for SRE and Data Center Operations (DCT). It continuously monitors critical bare-metal server parameters, detects impending infrastructure failures, and executes automated self-healing remediation while generating structured JSON post-mortem incident logs.

---

## 🚀 Key SRE Capabilities
1. **Predictive Resource Monitoring:** Tracks root storage and system metrics against strict thresholds in real-time.
2. **Automated Remediation / Self-Healing:** Instantly triggers corrective actions when thresholds are breached.
3. **Structured Incident Logging:** Compiles a complete audit trail and post-mortem report in JSON format (`sentinel_incident_report.json`).
4. **Zero-Dependency Architecture:** Built entirely using Python standard libraries (`os`, `shutil`, `json`, `platform`).

---
**Author:** Vishal Srivastav ([vishal-dcops](https://github.com/vishal-dcops))
