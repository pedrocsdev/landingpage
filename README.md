

## ✨ Sobre

Página única (single-page), estática, sem dependência de build — feita para hospedar em qualquer serviço de arquivos estáticos (Vercel, Netlify, GitHub Pages).

**Seções:**
- **Hero** — apresentação e stack técnico exibido como um bloco `stack.json` com destaque de sintaxe
- **Sobre** — resumo curto de perfil
- **Projeto principal** — PDV Católico, com badge de status, métricas, changelog em estilo *git diff* dos bugs corrigidos e print do sistema em uma moldura de navegador
- **Outros projetos** — grade de cards no estilo de lista de repositórios do GitHub
- **Contato** — links para GitHub, LinkedIn e e-mail

## 🛠️ Tecnologias

- HTML5 + CSS3 (variáveis CSS, grid, flexbox)
- Sem frameworks ou build step — um único arquivo `index.html`
- Fontes: [Sora](https://fonts.google.com/specimen/Sora) (títulos), [Inter](https://fonts.google.com/specimen/Inter) (texto), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (elementos de código/terminal)

## 📁 Estrutura

```
portfolio/
└── index.html   # página completa (HTML + CSS + imagem embutida em base64)
```

## 🚀 Rodando localmente

Não precisa de instalação — é só abrir o arquivo direto no navegador:

```bash
# Windows
start index.html

# ou simplesmente dar duplo clique no arquivo
```

## 🌐 Deploy

Como é um site estático, pode subir em qualquer um destes serviços (gratuitos):

**Vercel**
1. Suba este repositório no GitHub
2. Importe o projeto na Vercel — não precisa configurar nada (sem build command, root directory padrão)

**GitHub Pages**
1. Vá em *Settings → Pages* no repositório
2. Selecione a branch `main` e a pasta raiz
3. O site fica disponível em `https://pedrocsdev.github.io/<nome-do-repositorio>`

**Netlify**
1. Arraste a pasta do projeto direto no [app.netlify.com/drop](https://app.netlify.com/drop)

## 📬 Contato

- GitHub: [github.com/pedrocsdev](https://github.com/pedrocsdev)
- LinkedIn: [linkedin.com/in/pedro-leonidas-7339b0366](https://linkedin.com/in/pedro-leonidas-7339b0366)
- E-mail: pedrocsdev@gmail.com

## 📄 Licença

Uso pessoal — código disponível como referência.
