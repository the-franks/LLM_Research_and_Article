# Research and Article Writing with gemma2, llama3, and gtp-4o / Pesquisa e Escrita de Artigos com gemma2, llama3 e gtp-4o

## Table of Contents / Sumário

### English
- [Description](#description)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Environment Setup](#environment-setup)
- [Usage](#usage)
- [Key Features](#key-features)
- [License](#license)

### Português
- [Descrição](#descrição)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Requisitos](#requisitos)
- [Configuração do Ambiente](#configuração-do-ambiente)
- [Uso](#uso)
- [Principais Características](#principais-características)
- [Licença](#licença)

---

## Description
This repository contains the resources necessary for building a multi-agent artificial intelligence system for constructing articles and blogs using various Large Language Models (LLMs) with the CREWAI framework. This version utilizes multiple LLMs such as gemma2, llama3, and gtp-4o to enhance the capabilities and performance of the system.

### Project Structure
- `notebooks/`: Contains the Jupyter notebooks used for research and writing the article.
  - `L2_research_write_article.ipynb`: Main notebook with the research, writing, and editing AI agents for constructing the article.
- `src/`: Contains the Python scripts and utilities used in the project.
  - `utils.py`: Utility functions used in the project, including API key management and result formatting.
- `requirements.txt`: Requirements file with the project's dependencies.
- `.env`: Environment file for storing API keys and other sensitive information.

### Requirements
To install the necessary dependencies, run:
```bash
pip install -r requirements.txt
```

### Environment Setup
Create a .env file in the root directory of the project and add your API keys:

```makefile
OPENAI_API_KEY=your_openai_api_key
SERPER_API_KEY=your_serper_api_key
GROQ_API_KEY=your_groq_api_key
```
### Usage
To use the notebooks and scripts, ensure that all dependencies are installed and the .env file is properly configured with your API keys.

### Key Features
- Multiple LLM Integration: This project integrates multiple LLMs to enhance the performance and capabilities of the system.
- Scalability: The project can handle large amounts of data and traffic, making it suitable for businesses of all sizes.
- Adaptability: The system supports a wide range of AI models and frameworks, allowing developers to choose the best tools for their specific needs.

### License
This project is licensed under the MIT License. See the LICENSE file for more details.

---

### Descrição
Este repositório contém os recursos necessários para construção de um sistema de múltiplos agentes de inteligência artificial para construção de artigos e blogs utilizando vários Modelos de Linguagem de Grande Escala (LLMs) com o framework CREWAI. Esta versão utiliza múltiplos LLMs, como gemma2, llama3 e gtp-4o, para aprimorar as capacidades e o desempenho do sistema.

### Estrutura do Projeto
- notebooks/: Contém os notebooks Jupyter utilizados para a pesquisa e escrita do artigo.
  - L2_research_write_article.ipynb: Notebook principal com os agentes IA de pesquisa, escrita e edição para construção do artigo.
- src/: Contém os scripts e utilitários Python utilizados no projeto.
  - utils.py: Funções utilitárias usadas no projeto, incluindo gerenciamento de chaves de API e formatação de resultados.
- requirements.txt: Arquivo de requisitos com as dependências do projeto.
- .env: Arquivo de ambiente para armazenar chaves de API e outras informações sensíveis.
### Requisitos
Para instalar as dependências necessárias, execute:

```bash
pip install -r requirements.txt
```

### Configuração do Ambiente
Crie um arquivo .env no diretório raiz do projeto e adicione suas chaves de API:

```makefile
OPENAI_API_KEY=sua_chave_de_api_openai
SERPER_API_KEY=sua_chave_de_api_serper
GROQ_API_KEY=sua_chave_de_api_groq
```
### Uso
Para utilizar os notebooks e scripts, certifique-se de que todas as dependências estejam instaladas e o arquivo .env esteja configurado corretamente com suas chaves de API.

### Principais Características
- Integração de Múltiplos LLMs: Este projeto integra múltiplos LLMs para aprimorar o desempenho e as capacidades do sistema.
- Escalabilidade: O projeto pode lidar com grandes quantidades de dados e tráfego, tornando-o adequado para empresas de todos os tamanhos.
- Adaptabilidade: O sistema suporta uma ampla gama de modelos e frameworks de IA, permitindo que os desenvolvedores escolham as melhores ferramentas para suas necessidades específicas.
### Licença
Este projeto está licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.