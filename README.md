# Bootcamp 2025 Code Girls - Entregável 01

Repositório criado para registrar meus estudos, anotações e insights sobre os primeiros módulos do **Bootcamp 2025 Code Girls**.

---

## 📌 Tópicos Estudados

### 🌍 Regiões e Zonas de Disponibilidade
- Cada **região (region)** é projetada para ser isolada das outras, garantindo tolerância a falhas e maior estabilidade.
- Uma região é composta por **2 ou mais zonas de disponibilidade (Availability Zones)**.
- Pontos a considerar ao escolher uma região:
  - Compliance  
  - Disponibilidade de serviços  
  - Custo  
  - Latência  

---

### 🔐 Configuração de Conta AWS
- **Conta Root** → possui todas as permissões (não recomendada para tarefas diárias).  
- **Conta IAM** → utilizada para atividades rotineiras com permissões específicas.  

---

### 💻 Modelos de Computação em Nuvem
- **IaaS (Infraestrutura como Serviço)**  
  - Fornece servidores, armazenamento e máquinas virtuais sob demanda.  
  - Responsabilidade: **70% usuário | 30% cloud**.  

- **PaaS (Plataforma como Serviço)**  
  - Ambiente completo para desenvolver e executar aplicações sem gerenciar infraestrutura.  
  - Responsabilidade: **50% usuário | 50% cloud**.  

- **SaaS (Software como Serviço)**  
  - Aplicações prontas entregues pela nuvem (ex.: e-mail, CRM, ERP).  
  - Responsabilidade: **100% cloud**.  

---

### ⚙️ Amazon EC2 (Elastic Compute Cloud)
- Serviço de **máquinas virtuais** da AWS, podendo rodar Windows ou Linux.  
- Componentes principais:
  - CPU  
  - Memória  
  - Disco  
  - Rede  
  - Sistema Operacional  

- **Instâncias Spot** → instâncias vendidas a preços reduzidos, podendo ser interrompidas a qualquer momento.  

---

### 🗄️ Armazenamento na Nuvem
- **Amazon EBS (Elastic Block Store)** → armazenamento em blocos, altamente confiável, associado a instâncias EC2.  
  - Ideal para: bancos de dados, logs de sistemas e dados de aplicações web.  

- **Amazon S3 (Simple Storage Service)** → serviço de armazenamento de objetos, seguro e escalável.  
  - Ideal para grandes volumes de dados, organização e recuperação de forma simples.  

---

### 📷 Imagens e Snapshots
- **AMI (Amazon Machine Image)** → imagem pré-configurada para inicializar instâncias (com SO, apps e configurações).  
- **Snapshots EBS** → backups de volumes EBS, permitindo restauração rápida.  

---

### 🛠️ Ferramentas de Provisionamento
- **AWS CLI** → interface de linha de comando para criar e gerenciar recursos.  
- **AWS CloudShell** → terminal embutido na AWS para execução de comandos sem necessidade de configuração local.  
- **Console AWS** → interface gráfica para administração.  

---

## 💡 Insights Importantes
- A escolha da **região** impacta em custo, latência e disponibilidade.  
- O uso de **contas IAM** é essencial para segurança no dia a dia.  
- O **EBS** funciona como um “HD” de instâncias EC2, já o **S3** é ideal para grandes volumes de objetos.  
- O nível de responsabilidade varia entre usuário e provedor, dependendo do modelo (IaaS, PaaS, SaaS).  

---

## 🚀 Próximos Passos
- Criar e configurar instâncias **EC2** na prática.  
- Realizar testes de armazenamento usando **S3 e EBS**.  
- Explorar comandos com **AWS CLI** e **CloudShell**.  

---
