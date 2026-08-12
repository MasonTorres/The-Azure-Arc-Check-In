# The Azure Arc Check-In

A short-form video and blog series that helps IT professionals learn about and explore key scenarios and real-world use cases enabeld by Azure Arc.

**Hub:** [aka.ms/the-azure-arc-check-in](https://aka.ms/the-azure-arc-check-in)

| #   | Target      | Track      | Episode                                                                                                            | Learn docs                                                                                               | YouTube                                 | Blog  | Try Now                                              |
| --- | ----------- | ---------- | ------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- | --------------------------------------- | ----- | ---------------------------------------------------- |
| 1   | August 2026 | Onboarding | [Onboarding Azure Arc at Scale](#episode-1--onboarding-azure-arc-at-scale)                                         | [Learn](https://learn.microsoft.com/en-us/azure/azure-arc/servers/deployment-options#onboarding-methods) | [YouTube](https://youtu.be/rgrJGk6SxVY) | _TBD_ | [aka.ms/aaci-episode1](https://aka.ms/aaci-episode1) |
| 2   | August 2026 | Security   | [**Windows Server 2016 ESU through Azure Arc**](#episode-2--windows-server-2016-esu-through-azure-arc) — _next up_ | [Learn](https://learn.microsoft.com/azure/azure-arc/servers/deliver-extended-security-updates)           | _TBD_                                   | _TBD_ | [aka.ms/aaci-episode2](https://aka.ms/aaci-episode2) |

---

## Suggest a topic

Have an Azure Arc scenario you'd like us to cover in a future episode? We'd love to hear from you.

**[The Azure Arc Check-In Series Intake Form — Fill out form](https://forms.cloud.microsoft/r/F9MG92cR3Y)**

---

## Episode details

### Episode 1 — Onboarding Azure Arc at Scale

**Month:** 2026-06 · **Track:** Onboarding · **Runtime:** 4 min · **YouTube:** [https://youtu.be/rgrJGk6SxVY](https://youtu.be/rgrJGk6SxVY)

Onboard a thousand-plus Windows and Linux servers, spread across multiple
datacenters, into Azure Arc in one pass. This episode walks the actual setup and
configuration for two deployment paths — **Ansible** and **Group Policy (GPO)**.

**In this episode**

- **Path 1 — Ansible:** using the Ansible Azure Arc playbook to deploy the Azure Arc Connected Machine agent at scale to your Linux machines.
- **Path 2 — Group Policy (GPO):** using Group Policy to deploy the Azure Arc Connected Machine agent at scale for you Windows machines.

**Relevant links**

- [Connect machines at scale using a service principal](https://learn.microsoft.com/azure/azure-arc/servers/onboard-service-principal)
- [Connect machines at scale with Ansible playbooks](https://learn.microsoft.com/en-us/azure/azure-arc/servers/onboard-ansible-playbooks)
- [Connect machines at scale using Group Policy with a PowerShell script](https://learn.microsoft.com/en-us/azure/azure-arc/servers/onboard-group-policy-powershell)
- [`azcmagent check` — network connectivity validation](https://learn.microsoft.com/azure/azure-arc/servers/azcmagent-check)
- [Azure Arc network requirements (endpoints to allow-list)](https://learn.microsoft.com/azure/azure-arc/servers/network-requirements)
