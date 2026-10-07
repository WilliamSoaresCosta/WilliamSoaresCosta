<h1 align="center">William Soares Costa</h1>

<p align="center">
  <a href="https://williamsoares.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=F5B83D&center=true&vCenter=true&width=640&lines=DevOps+Engineer;AWS+%C2%B7+Kubernetes+%C2%B7+Terraform;Deploy+sem+nenhuma+senha+guardada;Se+n%C3%A3o+est%C3%A1+no+Git%2C+n%C3%A3o+deveria+estar+rodando" alt="DevOps Engineer · AWS · Kubernetes · Terraform" />
  </a>
</p>

<p align="center">
  <a href="https://williamsoares.com"><img src="https://img.shields.io/badge/Portf%C3%B3lio-williamsoares.com-F5B83D?style=for-the-badge&logo=googlechrome&logoColor=1A1406" alt="Portfólio" /></a>
  <a href="https://www.linkedin.com/in/williamsoarescosta/"><img src="https://img.shields.io/badge/LinkedIn-williamsoarescosta-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

### Sobre mim

Comecei em campo, instalando câmeras e interfones com meu pai. Passei pelo SENAI, service desk,
suporte e infraestrutura até chegar em DevOps. Hoje cuido de plataformas em **AWS** e **Azure** com
**Terraform**, **Kubernetes** e **GitOps**, e o que mais gosto é tirar trabalho manual do caminho
dos times sem abrir mão da segurança.

- 🔭 Agora: GitOps com **Argo CD no EKS**, tudo criado por Terraform
- 🔐 Obsessão do momento: pipeline que entra na AWS **sem nenhuma chave guardada** (OIDC)
- 🎓 Pós em Cloud, AI e DevOps em andamento
- ✍️ Escrevo sobre o que aprendo em [williamsoares.com/blog](https://williamsoares.com/blog)

---

### Uma esteira que eu montei

<p align="center">
  <a href="https://williamsoares.com/projetos#backend-gitops-argocd">
    <img src="./assets/esteira.svg" alt="Esteira de deploy: commit, testes, Trivy, ECR, Argo CD e EKS" width="100%" />
  </a>
</p>

<p align="center"><sub>Commit na develop → testes → scan → imagem no ECR → Argo CD aplica no EKS. Sem <code>kubectl apply</code> e sem senha no pipeline.</sub></p>

---

### No dia a dia

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,azure,gcp,kubernetes,docker,terraform,githubactions,git,linux,bash,python&perline=11" alt="AWS, Azure, GCP, Kubernetes, Docker, Terraform, GitHub Actions, Git, Linux, Bash, Python" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white" alt="Argo CD" />
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm" />
  <img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white" alt="Azure DevOps" />
  <img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white" alt="Datadog" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
  <img src="https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aquasecurity&logoColor=white" alt="Trivy" />
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white" alt="Ansible" />
  <img src="https://img.shields.io/badge/Entra%20ID%20%C2%B7%20Intune-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Entra ID e Intune" />
</p>

---

### Projetos que eu conto com detalhe

| | Projeto | O que mudou |
|---|---|---|
| 🔐 | [Da herança ao deploy sem senha](https://williamsoares.com/projetos#esteira-deploy-sem-senha) | 41 módulos Terraform auditados; site no ar em **1m49s** com login na AWS por OIDC |
| ☸️ | [Backend no EKS com GitOps](https://williamsoares.com/projetos#backend-gitops-argocd) | Argo CD por Terraform; o pipeline não toca no cluster, só no Git |
| 🐳 | [Imagem Docker de 26 vulnerabilidades para zero](https://williamsoares.com/projetos#imagem-docker-segura) | Multi-stage, npm fora da imagem final e Trivy barrando HIGH/CRITICAL |
| 🔑 | [Quando o GitHub mudou o login na AWS](https://williamsoares.com/projetos#oidc-ids-imutaveis) | AccessDenied diagnosticado pelo CloudTrail; IDs imutáveis no token |
| ♻️ | [Um pipeline para vários repositórios](https://williamsoares.com/projetos#workflows-reutilizaveis) | Workflows reutilizáveis e versionados, sem YAML copiado |

<sub>Todos com código real, prints e o passo a passo em <a href="https://williamsoares.com/projetos">williamsoares.com/projetos</a>.</sub>

<details>
<summary><b>Outras coisas com que já trabalhei</b></summary>
<br />

**AWS:** VPN com Transit Gateway em Terraform · Security Hub · redução de custo com Cost Explorer e desligamento de recursos ociosos · EKS com Prometheus e Grafana

**Azure:** Terraform e ARM Templates com CI/CD · AKS · grupos dinâmicos e tags no Entra ID · migração do AD local para o Entra ID · endpoints com Intune · Azure Cost Management

**Infra:** Ansible · backup e recuperação com Veeam · firewalls e VPNs Fortigate · redes Wi-Fi Cisco e Fortinet

</details>

---

### Últimos artigos

- [GitOps do zero no EKS: nenhum kubectl apply](https://williamsoares.com/blog/gitops-do-zero-no-eks)
- [O dia em que o OIDC quebrou sozinho](https://williamsoares.com/blog/oidc-quebrou-ids-imutaveis)
- [26 vulnerabilidades e nenhuma era do meu código](https://williamsoares.com/blog/imagem-docker-26-vulnerabilidades)
- [Herdei 41 módulos Terraform. Antes de criar, auditei](https://williamsoares.com/blog/auditoria-41-modulos-terraform)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=williamsoarescosta&label=visitas&color=F5B83D&style=flat-square" alt="visitas ao perfil" />
</p>

<p align="center"><sub>Feito com código, cloud e café ☕</sub></p>
