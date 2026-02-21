# LabMenu Live — Engine Multi-Loja

Cardápio digital + Painel Admin para múltiplos restaurantes.

## 🚀 DEPLOY RÁPIDO (GitHub Pages)

### 1. Criar repositório
- Acesse: github.com/guilabriolag
- Clique em **New repository**
- Nome: `labmenu-live`
- Visibilidade: **Public**
- Clique em **Create repository**

### 2. Subir os arquivos
- Clique em **uploading an existing file**
- Arraste TODOS os arquivos desta pasta mantendo a estrutura:
```
index.html
painel.html
stores/
  moraes/
    config.json
    database.json
```

### 3. Ativar GitHub Pages
- Settings → Pages
- Source: **Deploy from a branch**
- Branch: **main** / Folder: **/ (root)**
- Save

### 4. Acessar
Cardápio:  `https://guilabriolag.github.io/labmenu-live/?store=moraes`
Painel:    `https://guilabriolag.github.io/labmenu-live/painel.html`

---

## 🔐 SENHA DO PAINEL
Senha demo: `moraes2026`

**Para produção**, abra `painel.html` e troque:
```js
const SENHA_DEMO = '';
```
pela senha real do Glauber.

---

## 📱 WHATSAPP DO MORAES GRILL
Abra `stores/moraes/config.json` e troque:
```json
"whatsapp": "5511999999999"
```
pelo número real com DDI+DDD sem espaços ou símbolos.

---

## ➕ ADICIONAR NOVA LOJA
1. Criar pasta `stores/nova-loja/`
2. Copiar e editar `config.json` e `database.json`
3. Acessar: `?store=nova-loja`

---

## 🗂️ ESTRUTURA
```
labmenu-live/
├── index.html          ← Cardápio (universal)
├── painel.html         ← Painel admin
└── stores/
    └── moraes/
        ├── config.json ← Configurações da loja
        └── database.json ← Cardápio e produtos
```

---

by product **Labriolag** · labriolag.shop
