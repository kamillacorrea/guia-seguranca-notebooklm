# 🛡️ Cybersecurity & DevSecOps: Framework de Aprendizado Ativo com IA

## 📌 Visão Geral do Projeto
Este repositório apresenta um ecossistema de aprendizado desenvolvido como parte de um **desafio prático na plataforma DIO**. O projeto consolida meu conhecimento em **Cybersecurity**, integrando uma sólida trajetória de **15 anos em Infraestrutura de TI** às metodologias modernas de segurança e agilidade. O foco está na aplicação de pilares fundamentais de engenharia e resiliência de sistemas, essenciais para arquiteturas de alta performance e escala corporativa.

O objetivo central foi utilizar o **NotebookLM** (IA Generativa do Google) para estruturar um framework de conhecimento sobre **Shift-Left Security**, garantindo que a segurança atue como um acelerador estratégico de entregas, otimizando a governança e a proteção de ativos digitais.

## 🎯 Objetivos Estratégicos
* **Curadoria Técnica Sênior:** Seleção de fontes de alta autoridade (Cert.br, OWASP, NIST) para mitigar riscos de desinformação técnica.
* **Engenharia de Prompt Avançada:** Documentação do processo iterativo de interação com LLMs para extração de inteligência operacional.
* **Eficiência e Governança:** Tradução de conceitos teóricos em um checklist executivo focado em redução de atrito entre times de segurança e engenharia.

---

## 🧠 Laboratório de Engenharia de Prompts (Cicatrizes de Aprendizado)
Documento abaixo o processo de refino dos comandos para extrair respostas de nível especialista, demonstrando domínio sobre a ferramenta e senso crítico sobre os resultados:

### 🧪 Teste 1: Validação de Arquitetura e Impacto de Negócio
* **Prompt Refinado:** "Com base nos manuais, defina os 5 pilares conceituais que um especialista em segurança deve dominar para garantir a resiliência de uma infraestrutura crítica. Conecte cada pilar a um risco financeiro ou de reputação real."
* **Cicatriz (Ajuste):** A IA tendeu a ser puramente acadêmica. O ajuste foi necessário para forçar uma visão de **Gestão de Risco**, unindo a falha técnica ao impacto direto no negócio.

### 🧪 Teste 2: Segurança como Viabilizador de Agilidade
* **Prompt Refinado:** "Elabore uma argumentação técnica demonstrando como o **Shift-Left Security** e a automação de **SAST/SCA** reduzem o *Lead Time* e o *Cost of Quality* em pipelines de CI/CD."
* **Cicatriz (Ajuste):** O foco foi movido de "bloqueio/burocracia" para "eficiência operacional", alinhando o discurso à cultura de alta performance praticada em grandes centros de tecnologia.

### 🧪 Teste 3: Priorização Analítica em Ambientes Cloud
* **Prompt Refinado:** "Atuando como um Arquiteto de Segurança Sênior, cruze as vulnerabilidades do OWASP Top 10 com arquiteturas de Nuvem Híbrida. Identifique os 3 controles compensatórios prioritários para mitigar ataques de movimentação lateral."
* **Cicatriz (Ajuste):** Filtrei o ruído da IA para focar no que causa prejuízo sistêmico real, como falhas de **IAM** e má configuração de criptografia em trânsito.

---

## 📖 Miniguia de Estudo Consolidado

### 🔑 Glossário Técnico de Governança
* **Vulnerabilidade & Vetores de Exploração:** Falhas sistêmicas que comprometem a **Tríade CIA** (Confidencialidade, Integridade e Disponibilidade).
* **Criptografia State-of-the-Art:** Proteção de dados *At-Rest* e *In-Transit* via algoritmos robustos (AES-256/TLS 1.2+). Essencial para conformidade com a **LGPD**.
* **Zero Trust ("Nunca confiar, sempre verificar"):** Framework de segurança que elimina a confiança implícita, exigindo verificação contínua em cada etapa de interação digital.
* **Shift-Left Security:** Estratégia de integrar controles de segurança desde a fase de Design, minimizando o **Débito Técnico de Segurança**.

### ✅ Checklist Operacional: Resiliência e Governança
- [ ] **IAM & RBAC:** Enforcement de **MFA** em contas privilegiadas e aplicação de **RBAC/PoLP** para mitigação de movimentação lateral.
- [ ] **Hardening de Ativos:** Implementação de baselines **CIS Benchmarks** e gestão de patches para redução da superfície de ataque em S.O. e containers.
- [ ] **Segurança na Esteira (DevSecOps):** Automação de scans **SAST** (código) e **SCA** (dependências) integrada ao pipeline de CI/CD para bloqueio de deploys inseguros.
- [ ] **Monitoramento e Resposta:** Centralização de telemetria em **SIEM** com foco na redução do **MTTD** (Mean Time to Detect).

---

## 🚀 Prompts Reutilizáveis para Revisão Técnica
1.  **Simulador de Entrevista (Red Team):** *"Atue como um Arquiteto de Segurança Sênior. Conduza uma simulação de entrevista técnica focada em vulnerabilidades críticas de Injeção e Quebra de Controle de Acesso. Faça uma pergunta por vez e forneça feedback crítico baseado em padrões de sanitização e Zero Trust."*
2.  **Simulador de Crise (NIST):** *"Com base no framework NIST SP 800-61, gere um cenário de Ransomware que comprometeu servidores críticos. Peça para eu estruturar as etapas de Contenção, Erradicação e Recuperação sob a ótica de infraestrutura e critique minha estratégia de RTO/RPO."*
3.  **Auditoria de Hardening:** *"Atue como um Auditor de Segurança focado em CIS Benchmarks. Analise um cenário de configuração de servidor [Inserir Descrição] e identifique 3 vulnerabilidades de configuração, sugerindo a correção técnica e o comando de validação."*
4.  **Comunicação Executiva:** *"Recebi um relatório de vulnerabilidade crítica. Resuma o problema em 3 parágrafos para um Diretor (C-Level) não-técnico, focando no risco financeiro, impacto na LGPD e custo de mitigação vs. inação."*

---
**Projeto desenvolvido por Kamilla Corrêa**
*Analista de Infraestrutura | Aluna DIO | 65999365077*
