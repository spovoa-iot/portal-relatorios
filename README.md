# 📊 Portal de Relatórios Power BI

Portal web simples e elegante para centralizar os links dos relatórios Power BI da empresa.

## ✨ Funcionalidades

* **Login seguro** — credenciais definidas diretamente no código
* **7 botões de relatórios** — cada um abre o relatório correspondente numa nova aba
* **Responsivo** — funciona em desktop, tablet e mobile
* **Enter no login** — `Enter` no campo utilizador avança para a password; `Enter` na password faz login
* **Design corporativo** — tema escuro elegante com acentos dourados

## 🗂️ Estrutura

```
/
└── index.html   ← ficheiro único, tudo incluído
```

## ⚙️ Configuração

### 1\. Nomes e links dos relatórios

```javascript
const REPORTS = \[
  { name: 'Relatório 1', url: 'https://app.powerbi.com/link-1' },
  { name: 'Relatório 2', url: 'https://app.powerbi.com/link-2' },
  // ... 7 entradas no total
];
```

Substitui cada `name` pelo nome real do teu relatório e cada `url` pelo link de partilha do Power BI.

## 🚀 Como publicar no GitHub Pages

1. Cria um repositório no GitHub (ex: `portal-relatorios`)
2. Faz upload do ficheiro `index.html` para a raiz do repositório
3. Vai a **Settings → Pages → Source → main / root**
4. O portal fica disponível em `https://<teu-user>.github.io/portal-relatorios/`

## 🔗 Como obter o link de um relatório Power BI

1. Abre o relatório no Power BI Service
2. Clica em **Ficheiro → Incorporar relatório → Site ou portal**
3. Copia o URL gerado e cola no campo `url` correspondente



