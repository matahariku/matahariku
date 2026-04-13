<div align="center">
  
<!-- BARIS 1: EMAS MURNI + LOGO PUTIH -->
<img src="https://img.shields.io/badge/FARIDA%20ERYANI-FFD700?style=for-the-badge&logo=kubernetes&logoColor=white&labelColor=0d1117" width="100%"/>

<!-- BARIS 2: KUNING SEDANG + LOGO PUTIH -->
<img src="https://img.shields.io/badge/ING%C3%89NIEURE%20DEVOPS-CKA%20CERTIFIED-FDB813?style=for-the-badge&logo=kubernetes&logoColor=white&labelColor=181717" width="100%"/>

<!-- BARIS 3: KUNING CERAH + LOGO PUTIH -->
<img src="https://img.shields.io/badge/AUTOMATISATION-INFRASTRUCTURE-FFEA00?style=for-the-badge&logo=terraform&logoColor=white&labelColor=0d1117" width="100%"/>

</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=30000&pause=800&color=60A5FA&center=true&vCenter=true&multiline=false&width=600&lines=Cloud%7CIaC%7CDevOps%0AIng%C3%A9nieure+DevOps+CKA%0AAWS%7CTerraform%7CKubernetes" alt="Typing SVG" />
</div>

<p align="center">
  <a href="https://komarev.com/ghpvc/?username=matahariku&style=for-the-badge&color=1d4ed8&label=PROFILE+VIEWS">
    <img src="https://komarev.com/ghpvc/?username=matahariku&style=for-the-badge&color=1d4ed8&label=PROFILE+VIEWS" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/farida-eryani-257480172/">
    <img src="https://img.shields.io/badge/LinkedIn-Farida%20ERYANI-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Bordeaux%2C_France-%F0%9F%87%AB%F0%9F%87%B7-1d4ed8?style=for-the-badge" />
</p>

---

## 🧑‍💻 **À propos**
```yaml
name:     Farida ERYANI
role:     Ingénieure DevOps SRE - CKA Certified (CDI/CDD/Freelance)
location: Bordeaux, France 🇫🇷 (Toulouse/Marseille/Paris)

background: 
  - Laravel SRE GitOps (04/2026 → LIVE)
  - Amsterdam POS Hybrid (04/2025-03/2026)
  - E-Santé Bretagne DevOps (2023-2025)
  - IRIS IT SysAdmin (2022-2023)
```

---

## 🛠️ **Stack Technique**

| **Domain** | **Expertise** |
|------------|---------------|
| **🧠 Container** | Docker • **Kubernetes CKA** • Ceph-Rook • GlusterFS |
| **🔧 IaC** | **Terraform** • **Ansible** • **ArgoCD** • Helm • Kustomize |
| **⚡ CI/CD** | **GitHub Actions** • **Jenkins** • GitLab CI • Gitea |
| **☁️ Cloud** | **Proxmox HA** • **Cloud-Init** • AWS • Azure • OVH |
| **📈 Observabilité** | **Grafana** • **Prometheus** • **Loki** • Jaeger • Tempo • OTel |
| **🛡️ Sécurité** | **Trivy** • **Falco** • **SonarQube** • Vault • **Fortinet HA** • Harbor |
| **💾 Stockage** | Ceph-Rook • Velero • AWS S3 • GlusterFS |
| **🌐 Réseaux** | **Fortinet** • Cisco • pfSense • VLAN/VPN/SD-WAN • NGINX • HAProxy |
| **💻 Langages** | Bash • Python • PHP/Laravel • **Golang** |

---

## 🎯 **Projets LIVE (SRE Production)**

| **Projet** | **Description** | **URL Live** | **Status** |
|------------|-----------------|--------------|------------|
| **Laravel SRE** | GitOps→ArgoCD→K3s→nginx-ingress | `localhost:8080` | 🟢 **LIVE** |
| **Grafana Dash** | Observabilité full-stack | `grafana.okfe.net` | 🟢 **LIVE** |
| **ArgoCD UI** | GitOps dashboard | `argocd.okfe.net` | 🟢 **LIVE** |
| **Harbor Reg** | Private registry | `harbor.okfe.net` | 🟢 **LIVE** |
| **Jenkins CI** | Pipeline automation | `jenkins.okfe.net` | 🟢 **LIVE** |
| **SonarQube** | Code quality | `sonarqube.okfe.net` | 🟢 **LIVE** |
| **GitLab** | Source management | `gitlab.com/matahariku` | 🟢 **LIVE** |

**Cluster K3s:** `ceph-0(Ready) • ops1(Ready) • dev1(Ready)` ✅

---

## 🔭 **Flowchart Laravel SRE Pipeline**

```mermaid
flowchart TD
    A[GitHub<br/>harbor-okfe.net] --> B[ArgoCD<br/>sre-laravel]
    B --> C[K3s HA<br/>ceph-0+ops1+dev1]
    D[Harbor<br/>laravel-sre:v1] --> C
    C --> E[nginx-ingress<br/>192.168.1.110]
    E --> F[Laravel<br/>localhost:8080 ✅]
    
    G[Jenkins<br/>jenkins.okfe.net] --> B
    H[SonarQube<br/>sonarqube.okfe.net] --> G
    I[Falco+Trivy<br/>Security Dashboard] --> C
    
    style A fill:#1f6feb
    style F fill:#10b981
    style C fill:#3b82f6
```

---

## 🌐 **Flowchart Amsterdam POS (Hybrid Infra)**

```mermaid
flowchart TB
    A[Proxmox HA FR<br/>Cloud-Init Expert] --> B[K3s Observability<br/>ceph-0+2+3]
    B --> C[Grafana/Prometheus/Loki<br/>Alloy+OTel Dashboard]
    
    D[Amsterdam POS<br/>Python+Android Menu] --> E[OVH VPS NL<br/>SSH FR→NL]
    E --> F[Table Menu API<br/>Real-time Orders]
    F --> C
    
    G[France Bastion<br/>fe@ops1 → Fortinet] -.-> E
    
    style A fill:#10b981
    style D fill:#f59e0b
    style C fill:#8b5cf6
```

---

## 🏅 **Certification**

[![CKA](https://img.shields.io/badge/CKA-Certified-brightgreen?style=for-the-badge&logo=kubernetes&logoColor=white)](https://www.credly.com/badges/bd619a68-ce90-4a48-978c-e3bcefa0858c)

---

## 📊 **GitHub Stats** (Avril 2026)

**244 contributions** • **24 repositories**  
**Top:** Farida-Eryani • project-Amsterdam • K8s-Observability

[![GitHub](https://img.shields.io/badge/GitHub-24%20repos-black?style=for-the-badge&logo=github)](https://github.com/matahariku)

---

## 📫 **Contact Professionnel**

<div align="center">
**🏢 Régions:** Toulouse • Marseille • Paris • Bordeaux • Aix • Toulon  
**💼 Disponible:** ✅ **CDI/CDD/Freelance IMMÉDIAT**  
**🔗** [✉️ Email](mailto:febdx33000@gmail.com) | [🔗 LinkedIn](https://linkedin.com/in/farida-eryani-257480172)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/farida-eryani-257480172/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:febdx33000@gmail.com)
</div>

---

<div align="center">
<img src="https://img.shields.io/badge/Kubernetes%20CKA%20%2B%20GitOps%20ArgoCD%20%2B%20Terraform%20%2B%20Proxmox%20HA%20%2B%20Fortinet%20%2B%20Observabilit%C3%A9%20Expert-FFD700?style=for-the-badge&logo=kubernetes&logoColor=black&labelColor=0d1117" width="100%"/>
</div>
