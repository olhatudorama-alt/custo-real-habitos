# ⚡ Custo Real de Hábitos — PWA

App para calcular o custo real de hábitos em dinheiro, tempo e saúde.

---

## 📁 Arquivos do projeto

```
custo-real-habitos/
├── index.html       ← App principal
├── manifest.json    ← Configuração PWA
├── sw.js            ← Service Worker (offline)
├── icons/
│   ├── icon-192.png ← Ícone 192x192px (CRIAR)
│   └── icon-512.png ← Ícone 512x512px (CRIAR)
└── README.md
```

---

## 🖼️ Criando os ícones

1. Acesse https://www.canva.com ou https://favicon.io
2. Crie uma imagem 512x512px com fundo vermelho (#ff3d00) e o símbolo ⚡
3. Exporte em PNG como `icon-512.png`
4. Redimensione para 192x192 e salve como `icon-192.png`
5. Coloque ambos na pasta `icons/`

---

## 🚀 Publicando no GitHub Pages (gratuito)

1. Crie conta em https://github.com
2. Crie repositório público chamado `custo-real-habitos`
3. Faça upload de todos os arquivos
4. Vá em Settings → Pages → Source: main branch
5. Seu app estará em: `https://SEU-USUARIO.github.io/custo-real-habitos`

---

## 📦 Convertendo para APK com PWABuilder

1. Acesse https://pwabuilder.com
2. Cole a URL do GitHub Pages
3. Clique em "Package for stores"
4. Escolha Android → Download Package
5. O arquivo AAB estará pronto para a Play Store

---

## 💰 Adicionando AdMob (anúncios reais)

1. Crie conta em https://admob.google.com
2. Adicione o app e copie o App ID
3. Crie um bloco de anúncio "Rewarded" e copie o Ad Unit ID
4. No index.html, substitua os comentários `[ AdMob ]` pelo SDK real
5. Para integração completa, use Capacitor + capacitor-admob plugin

---

## 📲 Publicando na Play Store

1. Pague US$25 em https://play.google.com/console
2. Crie novo app → Preencha ficha (título, descrição, screenshots)
3. Faça upload do AAB gerado pelo PWABuilder
4. Crie política de privacidade (pode usar https://www.privacypolicygenerator.info)
5. Responda questionário de classificação etária
6. Submeta para revisão (3-7 dias)

---

## 🔒 Política de Privacidade

Este app não coleta dados pessoais. Todos os dados ficam armazenados
localmente no dispositivo do usuário via localStorage.

Inclua essa informação na sua política de privacidade.
