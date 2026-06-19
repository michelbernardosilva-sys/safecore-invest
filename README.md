# SafeCore Invest — Tela de Cadastro de Conta

Projeto da disciplina de Front-end (FIAP) — **Fase 3**.
Recriação, em **HTML + CSS + Tailwind CSS**, de uma das telas do projeto Fintech
**SafeCore Invest** desenhadas na Fase 2: a tela de **Cadastro de Conta**.

> **Autor:** Michel Bernardo — **RM:** 553168
> **Sistema:** SafeCore Invest (SCI) — fintech de controle financeiro pessoal

---

##  Sobre a tela

Tela de criação de conta da fintech, com:

- Painel de marca com proposta de valor e selo de segurança (em telas grandes);
- Indicador de etapas (Dados Pessoais → Segurança → Confirmação);
- Formulário com os campos do cadastro: nome, sobrenome, CPF, data de nascimento,
  e-mail, telefone, renda mensal, senha e confirmação de senha;
- Aceite dos Termos de Uso e opt-in para dicas financeiras;
- **Layout 100% responsivo** (mobile, tablet e desktop) construído com Tailwind CSS.

##  Como abrir

Basta abrir o arquivo **`index.html`** no navegador (duplo clique).
O CSS já vem **compilado** em `css/styles.css`, então **não é preciso internet
nem nenhum passo extra** para visualizar a página.

##  Tecnologias

- **HTML5** semântico
- **Tailwind CSS v4** (utilitários) — compilado localmente via Tailwind CLI
- **CSS** separado do HTML em `css/styles.css`
- Ícones em **SVG inline** (sem dependências externas)

##  Recompilar o CSS (opcional)

O CSS já está pronto. Caso queira regenerá-lo após editar as classes:

```bash
npm install        # instala o Tailwind CLI (cria a pasta node_modules)
npm run build      # gera css/styles.css a partir de src/input.css
# ou, para desenvolvimento com atualização automática:
npm run watch
```

##  Estrutura

```
safecore-invest/
├── index.html          # a tela (estrutura HTML)
├── css/
│   └── styles.css       # CSS compilado do Tailwind (abre offline)
├── src/
│   └── input.css        # arquivo-fonte do Tailwind (tema da marca)
├── package.json         # scripts de build (npm run build / watch)
├── .gitignore
└── README.md
```
