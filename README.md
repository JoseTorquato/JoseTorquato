<h2 align="center">José Torquato</h2>
<p align="center">
  <strong>Tech Lead & AI Engineer</strong> · coloco agentes de IA em produção e mostro os números<br>
  Python · Django · LLMs · RAG · MCP · GCP
</p>
<p align="center">
  <a href="https://josetorquato.dev">josetorquato.dev</a> ·
  <a href="https://www.linkedin.com/in/josetorquato/">LinkedIn</a>
</p>

---

Tech Lead na **KORO Martech**, onde construo agentes, RAG e pipelines de dados em Python e Django para marketing. Lidero o time e continuo abrindo meus próprios PRs.

Meus projetos open source resolvem problemas que encontrei no trabalho, e cada um sai com testes, números e um jeito de rodar em dois comandos.

## Open source

### 🧾 [fiscal-mcp](https://github.com/JoseTorquato/fiscal-mcp)
[![PyPI](https://img.shields.io/pypi/v/fiscal-mcp?color=22C55E&label=pypi)](https://pypi.org/project/fiscal-mcp/)

**Nota fiscal brasileira como ferramenta de agente.** Valida NF-e e NFS-e antes de transmitir: schema XSD oficial, regras fiscais com IBS/CBS, totais e chave de acesso. Para cada erro, diz o que fazer. Roda 100% local, sem certificado, e vem com 289 testes. Também funciona como servidor MCP.

```bash
pip install "fiscal-mcp[xsd]" && fiscal-mcp validar nota.xml
```

### 🪤 [cilada](https://github.com/JoseTorquato/cilada)
[![PyPI](https://img.shields.io/pypi/v/cilada-redteam?color=EF4444&label=pypi)](https://pypi.org/project/cilada-redteam/)

**Red team em português para agentes de atendimento.** 23 ataques com a "gramática" do golpe brasileiro: comprovante de Pix que nunca caiu, boleto adulterado, desconto no jeitinho, art. 30 do CDC e instrução escondida em áudio de WhatsApp. Devolve um laudo e pode quebrar o CI quando a robustez cai.

| Modelo testado (ago/2026) | Robustez | Ataques resistidos |
|---|---|---|
| gpt-oss-120b | 77/100 | 19 de 23 |
| qwen3.6-27b | 69/100 | 16 de 23 |
| llama-3.3-70b | 46/100 | 12 de 23 |

### ⚡ [django-dev-insights](https://github.com/JoseTorquato/django-dev-insights)
[![PyPI](https://img.shields.io/pypi/v/django-dev-insights?color=0C4B33&label=pypi)](https://pypi.org/project/django-dev-insights/)

**Diagnóstico de performance para Django, a cada request.** Mostra queries duplicadas, N+1, queries lentas e tempo de template no console, em JSON ou num painel HTML. Em projetos reais, levou páginas de **28s → 1,8s** e de **8s → 0,3s**.

```bash
pip install django-dev-insights
```

### 🧪 Também
- [chatbot_with_rag](https://github.com/JoseTorquato/chatbot_with_rag): RAG com visão computacional (FastAPI, LangChain, FAISS, GPT-4o), com as decisões de arquitetura documentadas.
- **Bancada** *(em protótipo)*: fábrica de software agêntica, do pedido ao PR, com testes determinísticos e trava humana no merge.

## Resultados em empresas
- **CRM da Havaianas** (ioasys): conversão de 0,75% → 1,80%.
- **Grupo Boticário:** tempo de release 50% menor com CI/CD.
- **Azion:** mantive o servidor MCP do time de APIs.

## Stack
**No dia a dia:** Python · Django · DRF · FastAPI · PostgreSQL · LLMs (locais e em nuvem) · RAG · MCP · GCP · Terraform · Docker

**Também em produção:** Node.js · TypeScript · NestJS · RabbitMQ · AWS (Lambda, SQS)

---

<details>
<summary>🇺🇸 <strong>English</strong></summary>

<br>

**Tech Lead & AI Engineer at KORO Martech.** I build AI agents, RAG and data pipelines in Python and Django, lead the team, and still ship my own PRs.

**Open source:**
- **[fiscal-mcp](https://github.com/JoseTorquato/fiscal-mcp)**: Brazilian invoices (NF-e/NFS-e) as an agent tool. Offline validation (official XSD, tax rules including IBS/CBS, totals, access key) plus an MCP server. 289 tests.
- **[cilada](https://github.com/JoseTorquato/cilada)**: Brazilian-Portuguese adversarial suite for customer-service AI agents. 23 attacks (fake Pix receipts, tampered boletos, consumer-law traps), with an HTML report and CI gating.
- **[django-dev-insights](https://github.com/JoseTorquato/django-dev-insights)**: per-request performance diagnostics for Django (duplicate queries, N+1, slow queries, template timing).

**Stack:** Python, Django, FastAPI, PostgreSQL, LLMs, RAG, MCP, GCP, Terraform, Docker, plus Node.js/TypeScript, RabbitMQ and AWS.

</details>
