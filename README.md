## 👋 George Agriogiannis

**Linux & Cloud Infrastructure Engineer · SRE · DevOps · Kubernetes** — Prague, Czechia

Infrastructure engineer with 14 years across Linux engineering, site reliability, DevOps and enterprise support at SUSE, Thales, Red Hat, Oracle and AT&T. I build and run cloud infrastructure with Terraform, Kubernetes and GitOps pipelines on AWS and GCP, and I troubleshoot production issues down to the OS and network layer.

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

<table>
  <tr>
    <td><b>📦 Containers & orchestration</b></td>
    <td><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" height="18" alt="Kubernetes"/> Kubernetes &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" height="18" alt="Docker"/> Docker &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/helm/helm-original.svg" height="18" alt="Helm"/> Helm &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rancher/rancher-original.svg" height="18" alt="Rancher"/> Rancher &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/k3s/k3s-original.svg" height="18" alt="K3s / RKE2"/> K3s / RKE2 &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/podman/podman-original.svg" height="18" alt="Podman"/> Podman &nbsp;·&nbsp; <img src="https://cdn.simpleicons.org/suse" height="18" alt="SUSE Edge (Metal3, Elemental, SUSE Linux Micro)"/> SUSE Edge (Metal3, Elemental, SUSE Linux Micro)</td>
  </tr>
  <tr>
    <td><b>☁️ Cloud & IaC</b></td>
    <td><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original.svg" height="18" alt="AWS"/> AWS &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/terraform/terraform-original.svg" height="18" alt="Terraform"/> Terraform &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/googlecloud/googlecloud-original.svg" height="18" alt="Google Cloud"/> Google Cloud</td>
  </tr>
  <tr>
    <td><b>🔁 GitOps & CI/CD</b></td>
    <td><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" height="18" alt="Git"/> Git &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" height="18" alt="GitHub Actions"/> GitHub Actions &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/gitlab/gitlab-original.svg" height="18" alt="GitLab CI"/> GitLab CI &nbsp;·&nbsp; <img src="https://cdn.simpleicons.org/flux" height="18" alt="Flux"/> Flux</td>
  </tr>
  <tr>
    <td><b>🐧 Linux & Unix</b></td>
    <td><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redhat/redhat-original.svg" height="18" alt="Red Hat Enterprise Linux"/> Red Hat Enterprise Linux &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ubuntu/ubuntu-original.svg" height="18" alt="Ubuntu"/> Ubuntu &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/debian/debian-original.svg" height="18" alt="Debian"/> Debian &nbsp;·&nbsp; <img src="https://cdn.simpleicons.org/suse" height="18" alt="SUSE Linux Enterprise / openSUSE"/> SUSE Linux Enterprise / openSUSE &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" height="18" alt="Oracle Linux"/> Oracle Linux &nbsp;·&nbsp; Solaris &nbsp;·&nbsp; AIX</td>
  </tr>
  <tr>
    <td><b>⚙️ Configuration management</b></td>
    <td><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ansible/ansible-original.svg" height="18" alt="Ansible"/> Ansible &nbsp;·&nbsp; <img src="https://cdn.simpleicons.org/chef" height="18" alt="Chef"/> Chef &nbsp;·&nbsp; <img src="https://cdn.simpleicons.org/saltproject" height="18" alt="SaltStack"/> SaltStack</td>
  </tr>
  <tr>
    <td><b>📈 Observability</b></td>
    <td><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/prometheus/prometheus-original.svg" height="18" alt="Prometheus"/> Prometheus &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/grafana/grafana-original.svg" height="18" alt="Grafana"/> Grafana &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/datadog/datadog-original.svg" height="18" alt="Datadog"/> Datadog &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/elasticsearch/elasticsearch-original.svg" height="18" alt="ELK / EFK"/> ELK / EFK</td>
  </tr>
  <tr>
    <td><b>🌐 Networking</b></td>
    <td>TCP/IP &nbsp;·&nbsp; DNS &nbsp;·&nbsp; DHCP &nbsp;·&nbsp; load balancing (<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" height="18" alt="nginx"/> nginx, Kubernetes Ingress, cloud load balancers) &nbsp;·&nbsp; Linux firewalling (netfilter) and cloud firewall rules &nbsp;·&nbsp; <img src="https://cdn.simpleicons.org/wireshark" height="18" alt="tcpdump / Wireshark"/> tcpdump / Wireshark &nbsp;·&nbsp; RADIUS</td>
  </tr>
  <tr>
    <td><b>💻 Scripting</b></td>
    <td><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" height="18" alt="Bash"/> Bash &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" height="18" alt="Python"/> Python</td>
  </tr>
  <tr>
    <td><b>🗄️ Databases</b></td>
    <td><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" height="18" alt="PostgreSQL (CloudNativePG)"/> PostgreSQL (CloudNativePG) &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" height="18" alt="Oracle Database"/> Oracle Database</td>
  </tr>
  <tr>
    <td><b>🔐 Identity & security</b></td>
    <td><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redhat/redhat-original.svg" height="18" alt="Red Hat Identity Management (FreeIPA)"/> Red Hat Identity Management (FreeIPA) &nbsp;·&nbsp; Kerberos &nbsp;·&nbsp; Samba &nbsp;·&nbsp; SSSD &nbsp;·&nbsp; Red Hat Directory Server / 389 DS &nbsp;·&nbsp; PAM &nbsp;·&nbsp; OS hardening</td>
  </tr>
  <tr>
    <td><b>🏗️ Build & packaging</b></td>
    <td><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" height="18" alt="Container images"/> Container images &nbsp;·&nbsp; RPM packaging &nbsp;·&nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opensuse/opensuse-original.svg" height="18" alt="Open Build Service (OBS)"/> Open Build Service (OBS)</td>
  </tr>
</table>

### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/gagriogiannis/)
