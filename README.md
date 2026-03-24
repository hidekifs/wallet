# 💳 Carteira Pessoal — PWA

App de controle financeiro pessoal com visual Itaú Personnalité. Funciona como PWA — pode ser instalado direto no iPhone pelo Safari.

---

## 📁 Estrutura de arquivos

```
carteira-pwa/
├── index.html          ← App principal
├── manifest.json       ← Configuração do PWA
├── sw.js               ← Service Worker (modo offline)
├── icons/
│   ├── icon-192.png
│   ├── icon-512.png
│   └── apple-touch-icon.png
└── README.md
```

---

## 🚀 Como publicar no GitHub Pages

### Passo 1 — Criar repositório no GitHub
1. Acesse [github.com](https://github.com) e faça login
2. Clique em **"New repository"** (botão verde)
3. Dê o nome: `carteira-pwa`
4. Deixe como **Public**
5. Clique em **"Create repository"**

### Passo 2 — Fazer upload dos arquivos
1. Na página do repositório, clique em **"uploading an existing file"**
2. Arraste **todos os arquivos e a pasta `icons/`** para a área de upload
3. Clique em **"Commit changes"**

### Passo 3 — Ativar GitHub Pages
1. Vá em **Settings** (aba do repositório)
2. No menu lateral, clique em **Pages**
3. Em "Source", selecione **Deploy from a branch**
4. Em "Branch", selecione **main** e pasta **/ (root)**
5. Clique em **Save**

Aguarde ~1 minuto. Seu app estará disponível em:
```
https://SEU_USUARIO.github.io/carteira-pwa/
```

---

## 📱 Instalar no iPhone

1. Abra o link acima no **Safari** do iPhone
2. Toque no botão de **Compartilhar** (ícone de caixa com seta)
3. Role e toque em **"Adicionar à Tela de Início"**
4. Toque em **"Adicionar"**

Pronto! O app aparece na home igual a um app nativo. 🎉

---

## ✨ Funcionalidades

- 💳 Adicionar gastos do cartão (com parcelamento)
- 💰 Registrar entradas (salário, etc)
- 📅 Visualizar por mês
- ✓ Marcar fatura como paga
- 🐷 Cofrinho com meta e histórico
- 📴 Funciona offline
- 💾 Dados salvos localmente no aparelho
