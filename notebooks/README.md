# 🤖 LangGraph Agents Lab

Este repositório documenta meus estudos e implementações práticas envolvendo **Agentes Inteligentes**, **LangChain**, **LangGraph** e **Google Gemini**, com foco em automação, pesquisa agêntica, persistência de estado e sistemas multi-agentes.

O projeto evolui progressivamente, desde agentes ReAct simples até fluxos complexos com múltiplos agentes, streaming, persistência e interface gráfica.

---

## 🚀 Tecnologias Utilizadas

- Python 3.10+
- LangChain
- LangGraph
- Google Generative AI (Gemini 2.5 Flash)
- Tavily Search API
- DuckDuckGo Search
- BeautifulSoup
- Selenium
- SQLite
- Gradio
- Pydantic

---

## 📂 Estrutura do Projeto

```text
LANGGRAPH/
│
├── notebooks/
│   ├── Aula01.ipynb
│   ├── Aula02.ipynb
│   ├── Aula03.ipynb
│   ├── Aula04.ipynb
│   └── Aula06.ipynb
│
├── prompts.py
├── requirements.txt
├── checkpoints.db
├── .gitignore
└── README.md

📘 Conteúdo Estudado
🟢 Aula 1 – Agentes ReAct

Criação de agentes ReAct integrando raciocínio e ação

Uso seguro de variáveis de ambiente (.env)

Implementação de ferramentas personalizadas

Gerenciamento de estado compartilhado

Automatização de interações via loops contínuos

🟢 Aula 2 – LangGraph e Fluxos de Controle

Introdução ao LangGraph

Construção de grafos com decisões condicionais

Integração do Tavily para buscas externas

Implementação de uma classe Agent

Uso do modelo Gemini 2.5 Flash

🟢 Aula 3 – Web Scraping e Buscas Agênticas

Diferença entre buscas tradicionais e agênticas

Web Scraping com Selenium e BeautifulSoup

Extração e organização de dados HTML

Uso de DuckDuckGo e Tavily para buscas online

🟢 Aula 4 – Persistência e Streaming

Persistência de estado com SQLite

Streaming de respostas em tempo real

Checkpointing com SQLiteSaver

Gerenciamento de contexto com threads

🟢 Aula 5 – Sistemas Multi-Agentes

Orquestração de múltiplos agentes especializados

Loops de retroalimentação para revisão automática

Estruturação de dados com Pydantic

Interface gráfica com Gradio

Fluxos de revisão e refinamento contínuo

🧠 Objetivo do Projeto

Demonstrar, de forma prática, a construção de agentes inteligentes modernos, capazes de:

Planejar e executar tarefas complexas

Buscar informações em tempo real

Manter contexto entre execuções

Operar de forma escalável e modular

Integrar LLMs, ferramentas externas e persistência

⚠️ Observações Importantes

O arquivo .env não é versionado e deve conter:

GEMINI_API_KEY=your_api_key_here
TAVILY_API_KEY=your_api_key_here


O banco checkpoints.db pode ser recriado automaticamente.