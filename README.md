# Jamal Waites

Principal / Director-level DevOps & Platform Architect — 25+ years across financial services, health insurance, pharmaceutical, and retail. Currently focused on cloud-native platform engineering, DevSecOps, and applying Generative AI / Agentic AI (Cursor, Copilot Agents, MCP) to engineering delivery.

📍 Charlotte, NC · [LinkedIn](https://linkedin.com/in/jamal-waites-89263017)

---

## Reference architectures

A couple of hands-on projects I've built and published to demonstrate patterns I use in production:

### [`eks-blue-green-canary-reference-architecture`](https://github.com/jdwaites/maroon-alligator)
Blue/green and canary deployment pattern on **Amazon EKS**, using:
- **Terraform** for VPC, EKS, ECR, IAM, and OIDC provisioning
- **Istio** VirtualService for weighted traffic shifting between blue/green pods
- **Helm** for declarative, versioned deployment config
- **GitHub Actions** CI/CD with OIDC-based AWS auth (no long-lived credentials) across separate build, deploy, and infra workflows

### [`gke-blue-green-internal`](https://github.com/jdwaites/GKE)
A companion blue/green pattern on **Google Kubernetes Engine**, focused on internal-only, security-conscious delivery:
- **Python (Flask)** application, containerized and deployed via Helm
- Internal-only load balancers with **private Cloud DNS** integration — no public endpoints
- **GitHub Actions** workflows publishing to Artifact Registry and deploying blue/green workloads to GKE

---

## Core stack

`Terraform` `Kubernetes` `Istio` `Helm` `Docker` `GitHub Actions` `AWS` `GCP` `Azure` `Python` `DevSecOps` `Cursor` `Copilot Agents` `MCP`
<!--
**jdwaites/jdwaites** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
