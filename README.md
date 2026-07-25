<div align="center">
  
  # 🧯 Incident Auto-Remediator
  
  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
  ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
  
</div>

---

This system addresses the operational cost of manually resolving recurring, well-understood incidents such as service failures or repeated unauthorized access attempts. Remediation logic is defined as explicit condition-to-action rules, with sensitive operations requiring approval prior to execution. The design balances automation speed with operational oversight, reducing resolution time without removing accountability from the remediation process.

**Key Features:**

- Condition-based remediation rules covering common, well-defined incident types
- Approval-gated execution for high-impact or destructive actions
- Full audit logging of triggering conditions, actions taken, and outcomes

**Technologies:**

`Python` · `Prometheus Alertmanager` · `Wazuh` · `Slack API` · `PostgreSQL`

**Limitation:** The current rule engine evaluates alerts independently and does not yet correlate related events into a single incident.
