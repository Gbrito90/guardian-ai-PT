# 🛡️ Guardião IA

## Plataforma Enterprise de Document Intelligence com RAG, Multi-Agent AI e Governança

**Demo:** https://enterprise-doc-guard.lovable.app/auth

O **Guardião IA** é uma plataforma corporativa de Inteligência Artificial para consulta segura de documentos internos. A solução combina **RAG (Retrieval-Augmented Generation)**, **agentes especializados**, **auditoria**, **avaliação de IA**, **benchmarking**, **controle por workspace** e **governança corporativa** para responder perguntas com base em documentos autorizados.

> O projeto não é apenas um “chat com PDF”. É uma plataforma de Document Intelligence voltada para ambientes corporativos.

## 🎯 Problema

Empresas acumulam centenas ou milhares de documentos internos: políticas corporativas, manuais de colaboradores, contratos, NDAs, documentos de compliance, normas de segurança, procedimentos operacionais e materiais de RH, Jurídico, TI e Financeiro.

O acesso a essas informações costuma ser lento, manual e dependente de pessoas específicas. Além disso, LLMs genéricos podem gerar respostas imprecisas ou alucinadas.

## ✅ Solução

O Guardião IA permite que a empresa faça upload de documentos, processe esse conteúdo em uma base vetorial e consulte essas informações por meio de especialistas de IA.

A resposta da IA pode incluir documento utilizado, chunk recuperado, score de similaridade, nível de confiança, risco de alucinação, fontes citadas e logs de auditoria.

## 🚀 Funcionalidades

| Módulo | Status |
|---|:---:|
| Login com Google | ✅ |
| Autenticação por email | ✅ |
| Dashboard Enterprise | ✅ |
| Upload de documentos | ✅ |
| Pipeline de ingestão | ✅ |
| Extração de texto | ✅ |
| Chunking | ✅ |
| Embeddings | ✅ |
| Busca vetorial | ✅ |
| Chat IA com RAG | ✅ |
| Agentes especializados | ✅ |
| Explain AI | ✅ |
| Auditoria | ✅ |
| Observability | ✅ |
| Avaliação IA | ✅ |
| Benchmark Module | ✅ |
| Health Check | ✅ |
| Multi-Agent Analytics | ✅ |
| Multi-Tenant / Workspace | ✅ |
| Compliance / LGPD Ready | ✅ |
| Deploy público Lovable | ✅ |
| GIF e vídeo demo | 🚧 |

## 🧠 Arquitetura de IA

```text
Usuário
↓
Autenticação
↓
Workspace
↓
Pergunta
↓
Roteador de Especialistas
↓
Especialista de IA
↓
Retriever
↓
Chunks relevantes
↓
LLM
↓
Validação de evidências
↓
Resposta auditável
↓
Logs, métricas e avaliação
```

## 🤖 Especialistas de IA

A plataforma possui especialistas por domínio:

- 🛡️ Compliance
- 💰 Financeiro
- ⚖️ Jurídico
- 👥 RH
- 💻 TI

Cada especialista consulta documentos relacionados ao seu domínio e responde com base nas evidências encontradas.

## 📚 Pipeline RAG

```text
Upload
↓
Extração
↓
Limpeza
↓
Chunking
↓
Embeddings
↓
Vetorização
↓
Indexação
```

## 📊 Snapshot atual de validação

| Métrica | Valor |
|---|---:|
| Documentos indexados | 11 |
| Texto extraído | 35.622 caracteres |
| Chunks | 39 |
| Embeddings | 39 |
| Cobertura de embeddings | 100% |
| Status do pipeline | Saudável |

O documento `manual_colaborador.pdf` validou o pipeline real com 21.268 caracteres extraídos, 21 chunks, 21 embeddings, logs completos de ingestão e recuperação RAG funcional.

## 🧪 Benchmark Module

O módulo de Benchmark permite testar a qualidade do RAG. Ele avalia especialista esperado vs. selecionado, documento esperado vs. recuperado, keywords esperadas, confiança mínima, presença de citação e risco de alucinação.

Resultados possíveis: ✅ PASS, ⚠️ WARNING e ❌ FAIL.

## 🔍 RAG Evaluation Center

O centro de avaliação RAG mede taxa de sucesso de recuperação, score médio de confiança, similaridade média, risco de alucinação, latência de resposta, chunks recuperados, documentos utilizados e fontes citadas.

Esse módulo aproxima o projeto de práticas reais de **AI Observability**.

## 🏢 Recursos Enterprise

- Workspaces
- Papéis de usuário
- Isolamento de documentos
- Auditoria de consultas
- Controle por especialista
- Logs de execução
- LGPD-ready architecture
- Governança de IA
- Human-in-the-loop

## 🛠️ Stack Técnica

### Frontend

- React
- TypeScript
- TailwindCSS
- Shadcn/UI

### Backend / Plataforma

- Supabase
- Supabase Auth
- Supabase Storage
- Edge Functions
- Lovable

### IA

- OpenAI
- `text-embedding-3-small`
- RAG Pipeline
- Multi-Agent Routing
- Vector Search

## 📁 Estrutura sugerida do repositório

```text
guardian-ai/
├── docs/
│   ├── ARCHITECTURE.md
│   ├── RAG.md
│   ├── AGENTS.md
│   ├── MULTI_TENANT.md
│   ├── SECURITY.md
│   ├── ROADMAP.md
│   ├── DEPLOYMENT.md
│   ├── RAG_EVALUATION.md
│   ├── BENCHMARK.md
│   └── EVALUATION_RESULTS.md
├── assets/
│   └── screenshots/
├── README.md
└── LICENSE
```

## 🖼️ Screenshots

Adicionar em breve:

- Tela de login
- Dashboard
- Especialistas
- Chat RAG
- Explain AI
- Benchmark
- RAG Evaluation Center

## 🗺️ Roadmap

| Fase | Módulo | Status |
|---|---|:---:|
| 1 | SaaS Foundation | ✅ |
| 2 | Gestão Documental | ✅ |
| 3 | Pipeline RAG | ✅ |
| 4 | Chat IA | ✅ |
| 5 | Multi-Agent | ✅ |
| 6 | Tool Calling | ✅ |
| 7 | Governança IA | ✅ |
| 8 | Multi-Tenant | ✅ |
| 9 | RAG Evaluation Center | ✅ |
| 10 | Benchmark Module | ✅ |
| 11 | Screenshots, GIF e vídeo | 🚧 |
| 12 | Produção / CI/CD | 📅 |

## 📌 Como apresentar este projeto

> Desenvolvi o Guardião IA, uma plataforma Enterprise de Document Intelligence que usa RAG, agentes especializados e avaliação de IA para responder perguntas com base em documentos internos, reduzindo alucinações e trazendo governança, auditoria e métricas para aplicações corporativas de IA.

## 📜 Licença

MIT License.

## 🌟 Visão

O Guardião IA foi criado para demonstrar como uma solução de IA corporativa pode ser segura, auditável, explicável e orientada a dados internos.

Ele representa um case prático de **AI Engineering**, **RAG**, **Agentic AI**, **AI Governance** e **AI Product Building**.
