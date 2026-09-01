### Olá, sou João Paulo Lomba 👋

**AI Automation Engineer** — construo agentes de IA e integrações que rodam em
produção, contra dinheiro e clientes reais. O trabalho interessante raramente é
conectar as APIs: é conter o que o modelo faz de errado quando ninguém está
olhando.

**Agora:** na Escalys, sustento uma malha de integrações via APIs REST e
Webhooks (Pipefy → n8n → Asaas → WhatsApp) que suporta uma operação com 11 pipes
e 4 bases de dados, além de agentes em Python que classificam documentos e
extraem dados estruturados de PDFs.

- 🤖 Em produção: agente de IA que cria pedidos reais pelo WhatsApp — cerca de **100 pedidos a cada dois dias**, sem humano no meio no caso comum
- 🧠 IA: OpenAI e Claude API, agentes com tool-calling, LangChain, RAG (pgvector), n8n
- 🛠️ Backend: Python, FastAPI, Node.js, PostgreSQL, Redis, Docker, Linux
- 🌐 Portfólio: [joaolomba.vercel.app](https://joaolomba.vercel.app)
- 💼 [LinkedIn](https://www.linkedin.com/in/joaolombadev/) · ✉️ joaolombadev@gmail.com

#### Em destaque

Os três se lêem em sequência — o incidente, o padrão que saiu dele, e a
ferramenta que o generaliza.

| Repositório | O que é | Stack |
|---|---|---|
| [yasmin-whatsapp-ai-agent](https://github.com/joaolombabr/yasmin-whatsapp-ai-agent) | Estudo de caso de um agente de IA em produção: as falhas que só aparecem com clientes reais e as travas determinísticas que as contiveram — incluindo o código do node de validação | n8n · OpenAI · APIs REST · Redis |
| [n8n-production-patterns](https://github.com/joaolombabr/n8n-production-patterns) | Treze padrões para rodar agentes em n8n contra dinheiro real, cada um vindo de um incidente — incluindo o que a documentação do n8n não conta | n8n · Agentes de IA · Redis |
| [llm-tool-guard](https://github.com/joaolombabr/llm-tool-guard) | Serviço FastAPI que valida a chamada de ferramenta de um agente antes que ela vire ação irreversível. 44 testes, CI e Docker | Python · FastAPI · Pytest · Docker |

#### Outros projetos

| Repositório | O que é | Stack |
|---|---|---|
| [atend-ia](https://github.com/joaolombabr/atend-ia) | Chatbot com persistência de contexto, arquitetado para integração com canais de atendimento | FastAPI · Claude API · PostgreSQL · Redis |
| [api-tarefas-spring](https://github.com/joaolombabr/api-tarefas-spring) | API REST com DTOs, validações, filtros e tratamento global de erros | Java 17 · Spring Boot 3.2 |
| [aws-automation-scripts](https://github.com/joaolombabr/aws-automation-scripts) | Scripts de automação de infraestrutura AWS | AWS · Bash/PowerShell |

Automações de cliente feitas na Escalys (extração de laudos no Pipefy, e-mail
transacional em n8n) não têm repositório público — os estudos de caso estão no
[portfólio](https://joaolomba.vercel.app).

#### Stack

`Python` `FastAPI` `Django` `Node.js` `TypeScript` `React` `Java` `Spring Boot`
`n8n` `LangChain` `OpenAI` `Claude API` `PostgreSQL` `Redis` `MongoDB`
`Docker` `Linux` `Nginx` `AWS` `Git`
