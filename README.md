**SOC Playbooks for MITRE ATT\&CK-Based Threat Detection, Triage & Investigation**

Welcome to the **SOC Playbooks Repository** — your one-stop resource for **comprehensive, actionable, and automation-ready SOC investigation playbooks** mapped to **MITRE ATT\&CK techniques and sub-techniques** across Endpoints (Windows, Linux and MacOS) and Cloud - AWS, GCP and Azure.

**What This Repository Includes**

* **100+ SOC Playbooks** mapped to MITRE ATT\&CK techniques
* **Detection Use Cases** (with Sigma/EDR queries, IOC patterns, command-line indicators)
* **Investigation & Triage Steps** for each technique with structured checklists
* **Automation Hooks** for SOAR integration (response triggers, severity scoring, enrichment logic)
* **Triage Labels & Confidence Scoring** to streamline analyst decision-making
* **Data Source Mapping** (EDR, logs, SIEM, cloud trails)
* Sample detection queries for **Sigma, Splunk, KQL, and Elastic**
* **Analyst Guidance** for true positive/false positive determination
* **Review Cycle Metadata** for continuous improvement


**Who Is This For?**

* **SOC Analysts** – To accelerate incident triage, reduce false positives, and handle real-world threats confidently.
* **Threat Hunters** – To proactively hunt adversary behaviors using mapped techniques, behavioral patterns, and enriched context.
* **Detection Engineers** – To build, customize, and deploy detection rules, triage logic, and automation playbooks aligned to MITRE ATT\&CK.
* **Blue Teams & MSSPs** – To standardize and automate threat response and reduce mean time to detect/respond (MTTD/MTTR).


**How It Helps**

* **Reduces Analyst Fatigue**: Clear playbook logic automates initial triage steps and enriches alerts.
* **Improves Detection Quality**: Uses behavioral + signature-based indicators for true positive identification.
* **SOAR Ready**: Includes automation hooks for triage, enrichment, and response in SOAR platforms (Splunk SOAR, XSOAR, etc.)
* **Coverage Confidence**: Provides 100% visibility across common and advanced MITRE ATT\&CK tactics including:

  * Initial Access
  * Execution
  * Persistence
  * Privilege Escalation
  * Defense Evasion
  * Credential Access
  * Discovery
  * Lateral Movement
  * Collection
  * Command & Control
  * Exfiltration
  * Impact



**How to Use**

1. **Browse Techniques**: Navigate by ATT\&CK technique ID (e.g., `T1003.001`, `T1059`, `T1548`, etc.)
2. **Deploy Queries**: Use included Sigma/KQL/EDR queries in your SIEM/EDR solution.
3. **Automate Triage**: Map the investigation steps and automation logic into your SOAR platform.
4. **Customize Responses**: Tailor severity scoring, analyst guidance, or automation actions based on your org’s context.
5. **Stay Updated**: Regularly review and contribute updated indicators, detection rules, or investigation guidance.



**Example Techniques Covered**

* `T1003.001` – LSASS Memory Credential Dumping
* `T1548.001` – Sudo and Privilege Escalation on Linux
* `T1059.*` – Scripting Engine Abuse (PowerShell, Bash, JS)
* `T1078` – Valid Account Abuse (Cloud and On-Prem)
* `T1190` – Public-Facing Application Exploits
  ... and many more.


**Stay ahead of threats. Standardize your defense. Automate your response.**


