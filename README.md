
# 🧠 Flask API com DeepSeek-R1 via Ollama

Esta API foi desenvolvida utilizando Flask em Python e conecta-se ao modelo de linguagem **DeepSeek-R1** por meio da plataforma [Ollama](https://ollama.com/). O principal objetivo deste projeto é realizar inferências de LLMs (Modelos de Linguagem de Grande Escala) de maneira simples e eficiente, de forma local, com uma interface de usuário (UI) básica e resposta em tempo real (stream).

## ⚙️ Pré-requisitos

Antes de rodar o projeto, assegure-se de ter os seguintes itens instalados:

- [Python 3.8+](https://www.python.org/downloads/)
- [Ollama](https://ollama.com/)
- O modelo `deepseek-r1` baixado no Ollama

## 🚀 Instalação

1. **Clone o repositório**

```bash
git clone https://github.com/renanzdev/ollama-deepseek-llm-server.git
cd ollama-deepseek-llm-server
```

2. **Instale as dependências**

```bash
pip install -r requirements.txt
```

3. **Instale e inicie o Ollama**
Se você ainda não tem o Ollama instalado, utilize o seguinte comando para instalar:

```bash
# No Linux via curl
curl -fsSL https://ollama.com/install.sh | sh
```

4. **Baixe o modelo DeepSeek-R1**

Se o Ollama já estiver instalado, basta baixar o modelo com o comando:

```bash
ollama pull deepseek-r1:latest
```

## 🧪 Executando a API

Após a instalação, basta rodar o script `app.py` para iniciar a API:

```bash
python app.py
```

## 📁 Estrutura do projeto

A estrutura do projeto é a seguinte:

```bash
├── services/
│   ├── ollama.py          # Serviço para interagir com o modelo Ollama
├── app.py                 # Arquivo principal para execução da API
├── requirements.txt       # Arquivo contendo as dependências do projeto
└── README.md              # Este arquivo
```

## 👤 Créditos

Desenvolvido por **Renan Rodríguez**. Sinta-se à vontade para contribuir ou utilizar este projeto em seus próprios projetos.

## 📄 Licença

Este projeto está licenciado sob os termos da **MIT License**.
