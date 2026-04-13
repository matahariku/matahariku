<div align="center">

<!-- LIVE METRICS BEAT -->
<img src="https://img.shields.io/badge/Pods-5/5-%2310b981?style=for-the-badge&logo=kubernetes" />
<img src="https://img.shields.io/badge/ArgoCD-Synced-ef4444?style=for-the-badge&logo=argocd" />
<img src="https://img.shields.io/badge/CPU-23%25-3b82f6?style=for-the-badge&logo=gpu&logoColor=white" />
<img src="https://img.shields.io/badge/Memory-1.2GB/4GB-f59e0b?style=for-the-badge&logo=memory&logoColor=white" />

<!-- BEATING HEART -->
<span style="font-size: 2em; animation: heartbeat 1.5s infinite;">
  💚 <b>LIVE</b>
</span>

<style>
@keyframes heartbeat {
  0% { transform: scale(1); }
  14% { transform: scale(1.3); }
  28% { transform: scale(1); }
  42% { transform: scale(1.3); }
  70% { transform: scale(1); }
}
</style>

</div>

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

## 👩‍💻 **À propos**
```yaml
name:     Farida ERYANI
role:     Ingénieure DevOps SRE - CKA Certified (CDI/CDD/Freelance)
location: Bordeaux, France 🇫 🇷  (Toulouse/Marseille/Paris)

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
| **🏗️ CLUSTER** | **K3s HA 3CP+3W** • **Proxmox HA** • **Cloud-Init Ansible** |
| **🧠 Container** | **Docker** • **Kubernetes CKA** • Ceph-Rook • GlusterFS |
| **🔧 IaC** | **Terraform** • **Ansible** • **ArgoCD** • Helm • Kustomize |
| **⚡ CI/CD** | **GitHub Actions** • **Jenkins** • GitLab CI • Gitea |
| **📈 Observabilité** | **Grafana** • **Prometheus** • **Loki** • Jaeger • Tempo • OTel |
| **🛡️ Sécurité** | **Trivy** • **Falco** • **SonarQube** • Vault • **Fortinet HA** • Harbor |
| **☁️ Cloud** | **OVH Hybrid** • AWS • Azure • **Cloud-Init Expert** |
| **🌐 Réseaux** | **Fortinet HA** • Cisco • pfSense • VLAN/VPN/SD-WAN • NGINX • HAProxy |
| **💾 Stockage** | Ceph-Rook • Velero • AWS S3 • GlusterFS |
| **💻 Langages** | Bash • Python • PHP/Laravel • **Golang** |

---

## 🎯 **Projets LIVE (SRE Production)**

| **Projet** | **Description** | **URL Live** | **Status** |
|------------|-----------------|--------------|------------|
| **Laravel SRE** | GitOps→ArgoCD→K3s→nginx-ingress | `localhost:8080` | 🟢 **LIVE** |
| **Grafana Dash** | Full-stack observability | `grafana.okfe.net` | 🟢 **LIVE** |
| **ArgoCD UI** | GitOps dashboard | `argocd.okfe.net` | 🟢 **LIVE** |
| **Harbor Reg** | Private container registry | `harbor.okfe.net` | 🟢 **LIVE** |
| **Jenkins CI** | Pipeline automation | `jenkins.okfe.net` | 🟢 **LIVE** |
| **SonarQube** | Code quality analysis | `sonarqube.okfe.net` | 🟢 **LIVE** |
| **GitLab** | Source code management | `gitlab.com/matahariku` | 🟢 **LIVE** |
| **Gitea** | Source code management | `git.kalou.net` | 🟢 **LIVE** |

---

## 🔭 **Flowchart Laravel SRE Pipeline**

```mermaid
flowchart TB
    subgraph PHYSICAL ["3x Proxmox HA Physical Nodes"]
        P1[ops1<br/>control-plane+etcd]
        P2[dev1<br/>★DUAL CP+etcd+worker]
        P3[ceph-0<br/>★DUAL CP+etcd+worker]
        V[🔐 Vault<br/>Secrets Mgmt]
    end
    
    subgraph K3S ["K3s HA Cluster"]
        A[ArgoCD<br/>sre-laravel App]
        B[Harbor<br/>laravel-sre:v1]
        C[nginx-ingress<br/>192.168.1.110]
        D[Laravel App<br/>localhost:8080 ✅]
    end
    
    subgraph SECURITY ["Security Dashboard"]
        S1[Falco+Trivy<br/>→ Grafana]
    end
    
    P1 --> A
    P2 --> A
    P3 --> A
    B --> A
    A --> C
    C --> D
    S1 --> A
    
    style P1 fill:#3b82f6
    style P2 fill:#10b981
    style P3 fill:#10b981
    style D fill:#ef4444
```

---

## 🌐 **Flowchart Amsterdam POS (Hybrid Infra)**

```mermaid
flowchart TB
    subgraph FR ["France Proxmox HA"]
        N1[ops1 CP]
        N2[dev1 ★DUAL]
        N3[ceph-0 ★DUAL]
        V[🔐 Vault<br/>Secrets Mgmt]
    end
    
    subgraph OBS ["Observability"]
        M[Grafana+Prom+Loki<br/>Alloy+OTel]
    end
    
    subgraph NL ["Amsterdam POS"]
        POS[Python+Android]
        OVH[OVH VPS NL]
    end
    
    N2 --> M
    N3 --> M
    POS --> OVH
    OVH --> M
    N1 -.-> OVH
    
    style FR fill:#e5e7eb
    style OBS fill:#a78bfa
    style NL fill:#fbbf24
```
---

## 🏅 **Certification**

[![CKA](https://img.shields.io/badge/CKA-Certified-brightgreen?style=for-the-badge&logo=kubernetes&logoColor=white)](https://www.credly.com/badges/bd619a68-ce90-4a48-978c-e3bcefa0858c)

---

## 📊 **GitHub Stats** (Avril 2026)

**244 contributions** • **24 repositories**  
**Top Repos:** 
- [laravel-go-observ](https://github.com/matahariku/laravel-go-observ)
- [project-Amsterdam](https://github.com/matahariku/project-Amsterdam) 
- [grafana-dashboard](https://github.com/matahariku/grafana-dashboard)

[![GitHub](https://img.shields.io/badge/GitHub-24%20repos-black?style=for-the-badge&logo=github)](https://github.com/matahariku)

---

## 📫 **Contact Professionnel**

<div align="center">

<table>
<tr>
<td align="center" width="33%">
  <b>🏢 Régions</b><br>
  <code>Toulouse • Paris • Bordeaux • Marseille • Aix-en-Provence • Toulon</code>
</td>
<td align="center" width="33%">
  <b>💼 Disponible</b><br>
  <span style="color: #10b981">✅ CDI/CDD<br>FREELANCE IMMÉDIAT</span>
</td>
<td align="center" width="33%">
  <b>🔗 Contact</b><br>
  <a href="mailto:febdx33000@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <br>
  <a href="https://linkedin.com/in/farida-eryani-257480172">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</td>
</tr>
</table>

</div>


<div align="center">
<img src="https://img.shields.io/badge/K3s%20HA%203CP%2B3W%20Proxmox%20Cloud-Init%20Fortinet%20HA%20ArgoCD%20GitOps%20Full%20Observabilit%C3%A9%20EXPERT-FFD700?style=for-the-badge&logo=kubernetes&logoColor=black&labelColor=0d1117" width="100%"/>
</div>
