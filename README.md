#  AKS × Azure Key Vault Integration

Production-grade implementation of secure secret management in Kubernetes using Azure-native services.

##  Live Demo

 https://bojan0807.github.io/aks-keyvault

---

##  What This Covers

* Azure Kubernetes Service (AKS)
* Azure Key Vault integration
* Workload Identity (OIDC)
* Secrets Store CSI Driver
* Secret rotation strategies
* Zero-trust architecture

---

##  Architecture

AKS workloads authenticate via **Microsoft Entra ID Workload Identity**, eliminating the need for stored credentials.

Flow:

```
Pod → OIDC → Entra ID → Access Token → Key Vault → CSI Driver → Container
```

---

##  Technologies

* Azure AKS
* Azure Key Vault
* Microsoft Entra ID
* Kubernetes
* CSI Driver
* YAML / Helm

---

##  Key Features

*  No secrets in code
*  Automatic secret rotation
*  Kubernetes-native integration
*  Production-ready architecture

---

##  Preview

Interactive visual guide available via GitHub Pages.

---

##  Author

Bojan Djokic
Azure Solutions Architect / DevOps Engineer

---

##  Use Case

Ideal for:

* Enterprise Kubernetes platforms
* Secure microservices
* Cloud-native architectures

---
