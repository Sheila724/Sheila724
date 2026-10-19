<div align="center">
  <h1>👋 Olá, sou Sheila Alves</h1>
  <h3>Suporte Técnico & Infraestrutura • Monitoramento, observabilidade e SRE</h3>
  <img alt="Suporte técnico e infraestrutura | Monitoramento, Observabilidade e SRE | Zabbix, Proxmox, Docker, CI/CD | Simulando incidentes reais" src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=25&center=true&vCenter=true&width=600&height=50&duration=3500&pause=1000&lines=Suporte+técnico+e+infraestrutura;Monitoramento+%7C+Observabilidade+%7C+SRE;Zabbix+%7C+Proxmox+%7C+Docker+%7C+CI%2FCD;Simulando+incidentes+reais" />
</div>

## 🚀 Sobre mim

Trabalho com suporte técnico e infraestrutura (Linux, Proxmox, redes) e construo ferramentas de monitoramento e automação para resolver problemas reais de operação: **detectar falhas cedo, medir confiabilidade e reduzir trabalho manual**.

🎯 Procuro minha próxima posição em **NOC / infraestrutura / observabilidade / SRE**.
📍 Aberta a mudança de cidade e de país.

## 📌 Projetos em destaque

### 🛰️ [NOC Horizon — Monitoramento global sobre Zabbix](https://github.com/Sheila724/noc-horizon) `⭐ projeto principal`

Painel NOC com globo interativo (D3.js) que consome a API do Zabbix e mostra a saúde por local e por host, incluindo hosts **"sem dados"** (falha silenciosa).

- 📲 **Alertas no WhatsApp:** problemas e resoluções do Zabbix chegam por mensagem, com host, trigger, duração e hora
- 📈 **Confiabilidade:** disponibilidade de 7/30 dias, SLO, orçamento de erro, MTTR e MTTA a partir do histórico de eventos
- 🔐 **Segurança:** login OIDC no Apache, token somente leitura, CSP, backend apenas em localhost
- ✅ **CI:** ruff, pytest, bandit, pip-audit, gitleaks + Dependabot; runbook e postmortem blameless em `docs/`
- ⚡ **Teste em 1 minuto:** `docker compose up -d --build` (modo demo, sem Zabbix)
- **Stack:** Python/Flask, Zabbix API, D3.js, Docker, Apache, Webhooks

### 🚨 [Incidente Zero — Simulador de incidentes para DevOps/SRE](https://github.com/Sheila724/incidente-zero) `🆕 v0.1.1` · [🌐 demo](https://incidente-zero.gapsaa.com.br)

Simulador open source, em português, para quem está começando em infraestrutura: você recebe o alerta, entra num **Linux real com a falha injetada** e só passa se corrigir a **causa raiz**, não só o sintoma.

- 🖥️ **Interface web:** terminal real no navegador (WebSocket + PTY), monitoramento ao vivo, modo guiado com verificação automática, dicas, pontuação e MTTR pessoal
- 🔥 **8 incidentes na trilha iniciante:** disco cheio, nginx quebrado, permissão negada por hardening, CPU 100%, porta ocupada, cron, SSH e inodes esgotados, cada um com uma armadilha e um postmortem (linha do tempo e 5 porquês)
- 🔒 **Isolamento:** labs Ubuntu com systemd em containers **Sysbox**, com limite de CPU, memória e processos e partições `tmpfs` para os incidentes de disco
- 📦 **Entrega:** binário único com os cenários embutidos, instalador com checksum, release multi-arquitetura e imagem no GHCR via GitHub Actions
- ⚡ **Teste em 1 comando:** `curl -fsSL https://raw.githubusercontent.com/Sheila724/incidente-zero/main/install.sh | sh`
- **Stack:** Go, Svelte, xterm.js, Docker, Sysbox, Bash, GitHub Actions
<img width="700" alt="Incidente Zero: incidente de disco cheio resolvido, com terminal, monitoramento e verificação" src="https://github.com/user-attachments/assets/a5e1dfa8-0a20-4864-884f-f1753259e1ef" />



### 🧪 [Laboratório DevOps — Homelab](https://github.com/Sheila724/homelab)

Infraestrutura rodando em **Proxmox** (LXC + VMs): DNS com Pi-hole, acesso externo seguro via Cloudflare Tunnel, automação com n8n e aplicações self-hosted (Dolibarr, Anytype).

- Serviços segmentados em containers, acesso remoto zero-trust e automação de workflows

<img width="700" alt="Diagrama da arquitetura do homelab: Proxmox, containers LXC/VMs, Pi-hole e Cloudflare Tunnel" src="https://github.com/user-attachments/assets/807f1120-60d4-4b63-b7bc-cc9b5fdd8a47" />

### 🤖 [Hermes Agent — Automação de suporte](https://github.com/Sheila724/hermes)

Automação em **Python** que opera uma caixa de suporte por e-mail de ponta a ponta: monitoramento via IMAP, alertas de **SLA** por WhatsApp, rotação de plantão (*on-call*), logging em Google Sheets e relatórios automatizados.

- Processamento idempotente, refresh automático de token OAuth e caminhos de *fallback*, com foco em confiabilidade

### Outros projetos

- 📨 [Simulação de mensageria com RabbitMQ](https://github.com/Sheila724/projeto-mensageria): filas com simulação de falhas, logs e observabilidade
- ☁️ [Automação Azure VM](https://github.com/Sheila724/AzureVM): script de provisionamento e gerenciamento de máquinas virtuais na Azure

## 💼 Experiência e formação

- **Suporte técnico, COM4 Telecomunicações:** atendimento e troubleshooting em infraestrutura e redes, com automação do fluxo de suporte
- **Administração de sistemas:** conhecimento em gerenciando de infraestrutura em Proxmox
- **Voluntária, Universo Prematuro:** gerencio o site e a infraestrutura técnica de uma organização que apoia famílias de bebês prematuros
- **Formação:** Tecnologia em Desenvolvimento de Software Multiplataforma (DSM), FATEC Franca

## 🛠️ Ferramentas & tecnologias

<div align="center">

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-CC2936?style=for-the-badge&logo=zabbix&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

## 📫 Contato

- 💼 [LinkedIn](https://www.linkedin.com/in/sheila-alvesaraujo)
- 📧 sheila.araujo486@gmail.com
