# Activiti

Activiti is a lightweight, Java-centric open-source Business Process Management (BPM) and workflow automation engine. It provides a BPMN 2.0 compliant process engine and a REST API for managing process definitions, process instances, tasks, variables, user management, deployments, and historical data. Activiti Cloud extends the platform to cloud-native environments using Spring Boot, Docker, and Kubernetes.

**Website:** https://www.activiti.org/

**Documentation:** https://www.activiti.org/documentation

**GitHub Organization:** https://github.com/Activiti

## APIs

- **Activiti REST API** — Core BPM engine REST interface covering deployments, process definitions, process instances, tasks, executions, historical data, identity management, and engine operations. Uses HTTP Basic Auth.
- **Activiti Cloud Runtime Bundle API** — Cloud-native REST API for distributed process execution in Kubernetes environments, exposing process instances, tasks, and variables with role-based access (ACTIVITI_USER).

## Key Resources

- [User Guide (v6)](https://www.activiti.org/userguide/)
- [Developer Guide (v7)](https://activiti.gitbook.io/activiti-7-developers-guide)
- [GitHub Repository](https://github.com/Activiti/Activiti)
- [Swagger/OpenAPI Spec](https://github.com/Alfresco/activiti-client-sdk/blob/master/docs/swagger/ActivitiSwagger-1.4.json)
- [Community Forum](https://community.alfresco.com/community/bpm)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/activiti)
- [Product Roadmap](https://github.com/Activiti/Activiti/wiki/Activiti-7-Roadmap)

## Pricing

Activiti is free and open-source (Apache License 2.0). Enterprise support and certified builds are available through Hyland/Alfresco Process Services. See [plans/activiti-plans-pricing.yml](plans/activiti-plans-pricing.yml) for details.

## Rate Limits

As a self-hosted platform, Activiti imposes no built-in API rate limits. Rate limiting is configured by the deploying organization at the infrastructure layer. See [rate-limits/activiti-rate-limits.yml](rate-limits/activiti-rate-limits.yml).

## FinOps

Costs are driven by infrastructure (compute, database), engineering operations, and optionally enterprise support contracts — not per-API-call fees. See [finops/activiti-finops.yml](finops/activiti-finops.yml).

---

*Maintained by [Kin Lane](mailto:kin@apievangelist.com) via [APIs.json](apis.yml)*
