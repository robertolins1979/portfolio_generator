# Portfolio Generator

> Script Python para geração automática de páginas de portfólio e currículo HTML a partir de dados em JSON e templates Jinja2.

---

## 🛠️ Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3.12+-blue.svg) ![Jinja2](https://img.shields.io/badge/Jinja2-3.1.4-red.svg) ![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📋 Sobre o Projeto

Este projeto tem como objetivo facilitar a criação e atualização de portfólios e currículos pessoais na web. A partir de um arquivo de dados estruturado em formato JSON (`portfolio.json`) e templates em HTML utilizando o motor de templates **Jinja2**, o script Python gera automaticamente as páginas finais do portfólio (`index.html`) e do currículo (`resume.html`).

### 🗂️ Estrutura de Pastas e Arquivos

* **`generate_portfolio.py`**: O script Python principal responsável por ler os dados JSON, associar os SVGs de links sociais, processar os templates via Jinja2 e salvar os arquivos estáticos HTML.
* **`portfolio.json`**: Arquivo JSON contendo os dados pessoais, de contato, competências, experiências profissionais, formação acadêmica e projetos que alimentam o portfólio.
* **`portfolio-corey.json`**: Exemplo alternativo de arquivo JSON de dados para testes ou referências de preenchimento.
* **`index_template.html`**: O template Jinja2 para a página principal do portfólio.
* **`resume_template.html`**: O template Jinja2 para a página de currículo estilizada para leitura ou impressão.
* **`css/`**: Pasta contendo os arquivos CSS para estilização visual das páginas geradas.
* **`js/`**: Pasta com arquivos JavaScript para comportamentos e interações dinâmicas nas páginas.
* **`img/` & `portfolio_media/`**: Pastas reservadas para as imagens utilizadas no portfólio (foto de perfil, capturas de tela dos projetos, etc.).
* **`favicon.ico` & `icon*`**: Arquivos de ícone e favicon para exibição no navegador.
* **`requirements.txt`**: Lista de dependências Python necessárias para a execução do script.
* **`LICENSE`**: Termos da licença MIT sob a qual o projeto está publicado.

---

## 🚀 Instalação e Execução

### Pré-requisitos
* Ter o Python 3.12+ instalado no sistema.

### Passo 1: Instalar Dependências
Instale os pacotes requeridos utilizando o gerenciador de pacotes `pip`:
```bash
pip install -r requirements.txt
```

### Passo 2: Configurar Seus Dados
Edite o arquivo `portfolio.json` na raiz do projeto com suas informações pessoais, links de projetos e caminhos de imagens/SVGs desejados.

### Passo 3: Executar o Gerador
Execute o script Python para renderizar os novos arquivos HTML estáticos:
```bash
python generate_portfolio.py
```
Após a execução, os arquivos `index.html` e `resume.html` serão gerados/atualizados na raiz do projeto, prontos para serem hospedados ou visualizados localmente.

---

## 👤 Desenvolvedor

* **Nome:** Roberto Lins
* **E-mail:** [robertolins1979@gmail.com](mailto:robertolins1979@gmail.com)

---

## ⚖️ Licença

Este projeto é de código aberto e está licenciado sob os termos da licença MIT.
