## 👋 George Agriogiannis

**Linux & Cloud Infrastructure Engineer · SRE · DevOps · Kubernetes** — Prague, Czechia

Infrastructure engineer with 14 years across Linux engineering, site reliability, DevOps and enterprise support at SUSE, Thales, Red Hat, Oracle and AT&T. I build and run cloud infrastructure with Terraform, Kubernetes and GitOps pipelines on AWS and GCP, and I troubleshoot production issues down to the OS and network layer.

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Flux](https://img.shields.io/badge/Flux-5468FF?style=flat-square&logo=flux&logoColor=white)
![Rancher](https://img.shields.io/badge/Rancher-0075A8?style=flat-square&logo=rancher&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![SUSE](https://img.shields.io/badge/SUSE-0C322C?style=flat-square&logo=suse&logoColor=30BA78)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

### 🚀 Featured work

- **[gitops-platform](https://github.com/Gagrio/gitops-platform)** — GitOps platform on GCP: Terraform, Ansible-bootstrapped k3s and Flux, with CloudNativePG Postgres HA, External Secrets and Workload Identity Federation, deployed and verified through GitHub Actions.
- **[condash](https://github.com/Gagrio/condash)** — Rust CLI that spins up temporary Prometheus/Grafana monitoring for any container; released for Linux and macOS via Homebrew and openSUSE packages.
- **[ketchup](https://github.com/Gagrio/ketchup)** — Rust tool that collects and archives Kubernetes cluster configuration for troubleshooting.
- **[pack](https://github.com/Gagrio/pack)** and **[nessie](https://github.com/Gagrio/nessie)** — diagnostic tools for host path and log collection, contributed to the official [SUSE Edge support-tools](https://github.com/suse-edge/support-tools) repository.

#### How gitops-platform fits together

```mermaid
flowchart LR
    A[GitHub Actions] -->|terraform apply| B[GCP: VPC, VMs, IAM]
    A -->|ansible-playbook| C[k3s cluster]
    B --> C
    C --> D[Flux]
    D -->|reconciles from Git| E[Postgres HA · monitoring · apps]
    F[GCP Secret Manager] -->|External Secrets| E
```

### 🛠️ Tools I work with

- **Cloud & IaC:** AWS, GCP, Terraform
- **Containers & GitOps:** Kubernetes, Helm, Flux, Docker, RKE2/K3s, Rancher
- **CI/CD & packaging:** GitLab CI, GitHub Actions, Jenkins, Open Build Service
- **Configuration management:** Ansible, SaltStack, Puppet
- **Linux & networking:** SLES/openSUSE, RHEL, Debian/Ubuntu; TCP/IP, DNS, DHCP, load balancing
- **Observability:** Prometheus, Grafana, ELK

### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/gagriogiannis/)
