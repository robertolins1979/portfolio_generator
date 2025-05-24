# 📄 Portfolio Generator

**Gerador de currículo e portfólio HTML baseado em templates e dados em JSON.**

---

## 🔧 Como Funciona

Este projeto gera automaticamente duas páginas HTML (`index.html` e `resume.html`) contendo seu currículo e portfólio a partir de um arquivo JSON com seus dados e um conjunto de templates predefinidos.

---

## 📝 Instruções de Uso

1. **Clone o repositório:**
   
   ```bash
   git clone https://github.com/seu-usuario/portfolio_generator.git
   cd portfolio_generator
   ```

2. **Prepare suas imagens:**
   
    Crie uma pasta chamada imagens_curriculo/ (ou qualquer outra, contanto que esteja referenciada corretamente no JSON) e adicione suas imagens (perfil, projetos, etc).

3. **Edite o arquivo JSON:**
   
    Modifique o arquivo JSON com suas informações pessoais, profissionais, acadêmicas e links de projetos. Certifique-se de ajustar os caminhos das imagens de acordo com a pasta que você criou.

4. **Ajuste o script se necessário:**
   
    Se precisar, personalize o script generate_portfolio.py para alterar a lógica de preenchimento ou trocar os templates utilizados.

5. **Execute o gerador:**
   
   ```bash
   python generate_portfolio.py
   ```

6. **Arquivos gerados:**
   
    Após a execução, dois arquivos serão criados na raiz do projeto:
   
    index.html – página principal do portfólio.
   
    resume.html – versão com foco em currículo.
