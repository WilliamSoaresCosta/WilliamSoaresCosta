conteudo = """
# 👋 Olá! Eu sou William Soares Costa

Sou um profissional apaixonado por **Cloud, DevOps e Automação**, com foco em otimizar ambientes e processos através de infraestrutura como código, pipelines CI/CD e práticas modernas de segurança e observabilidade.

> 🎯 Mais de **77 projetos entregues** com foco em disponibilidade, performance e segurança  
> 💻 +1.000 commits em pipelines e infraestrutura versionada  
> 🚀 Atuando com soluções em AWS, Azure e ambientes híbridos

---

## 💼 Principais Habilidades e Ferramentas

| Categoria | Tecnologias |
|---|---|
| ☁️ **Cloud** | AWS, Azure, GCP |
| 🐳 **Containerização** | Docker, Kubernetes |
| 🔁 **CI/CD** | GitHub Actions, GitLab CI/CD, Azure DevOps, Jenkins |
| ⚙️ **Infraestrutura como Código** | Terraform, Ansible, CloudFormation |
| 📊 **Monitoramento & Logging** | Datadog, Prometheus, Grafana, Zabbix, Azure Monitor, Prisma Cloud |
| 💻 **Sistemas Operacionais** | Linux, Windows Server, macOS |
| 🔤 **Linguagens de Script** | Python, Bash, PowerShell |
| 🧠 **Versionamento & Colaboração** | Git, GitHub, Bitbucket |

---

## 🚀 Projetos em Destaque

### 🔐 Implantação de VPN AWS com Transit Gateway
- Segmentação de rede por ambiente (Prod, HML, Dev)  
- Criptografia ponta a ponta e controle refinado de acessos  
- Provisionamento via Terraform com versionamento e segurança  

### ⚙️ Infraestrutura como Código Multi-Cloud
- Automação de ambientes em AWS e Azure com Terraform, Ansible e pipelines CI/CD  
- Gestão completa de redes, VMs, IAM e políticas de segurança  
- Versionamento com Git e Bitbucket Pipelines  

### 🐳 Pipeline CI/CD com Kubernetes e Docker
- Build, testes e deploy automatizados com GitHub Actions  
- Containerização com Docker e orquestração em AKS/EKS  
- Observabilidade com Datadog, Prometheus e integrações com Jira/ServiceNow  

### 📈 Monitoramento Multi-cloud com Observabilidade Unificada
- Dashboards customizados com Azure Monitor, Datadog, Zabbix e Grafana  
- Alertas inteligentes, integração com Service Desk e métricas em tempo real  
- Monitoramento de performance e segurança em ambientes críticos  

### 🛡️ Gestão de Segurança com Intune e Entra ID
- Aplicação de políticas de conformidade e proteção de endpoints  
- Patching automatizado com base em benchmarks de segurança  
- Integração com Azure AD (Entra ID) e gerenciamento via Microsoft Intune  

### ☁️ Modernização de Ambiente On-Premises para Cloud
- Migração completa do Active Directory para o Microsoft Entra ID, eliminando dependência de servidores físicos  
- Implantação do Windows Autopilot, modernizando o provisionamento de dispositivos e reduzindo o tempo de onboarding de usuários  
- Migração de servidores de arquivos para a nuvem, com controle de acesso centralizado, backup automatizado e maior disponibilidade  
- Resultado: ambiente 100% em nuvem, com redução significativa de custos com hardware e maior escalabilidade

---

## 📊 Métricas de Atuação

- 🧩 **+77 projetos DevOps entregues com sucesso**
- 📈 **+1.000 commits entre infraestrutura e automação**
- 🔐 **Ambientes com 99,99% de disponibilidade e segurança aplicada**
- 📦 **Containers orquestrados com Kubernetes em produção**

---

## 🤝 Conecte-se Comigo

- [LinkedIn](https://www.linkedin.com/in/williamsoarescosta/)
- 📧 william.soares.costa@gmail.com

---

> _Este README está em constante evolução. Fique à vontade para acompanhar meus projetos ou entrar em contato._
"""

# Salva no arquivo README.md
with open("README.md", "w", encoding="utf-8") as f:
    f.write(conteudo.strip())

print("Arquivo README.md criado com sucesso!")
