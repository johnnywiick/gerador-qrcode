# 📸 QR Code Studio 482 — Gerador de QR Codes Profissional

> Gere códigos QR personalizados e profissionais em segundos.

![Status](https://img.shields.io/badge/Status-Em%20Produção-brightgreen)
![HTML](https://img.shields.io/badge/HTML-5-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![QRCode.js](https://img.shields.io/badge/QRCode.js-1.0-blue)

---

## 🚀 O que é o QR Code Studio 482?

O **QR Code Studio 482** é uma ferramenta web leve e profissional para **geração de QR Codes personalizados**, desenvolvida para uso interno da Loja 482 e para qualquer pessoa que precise criar códigos de forma rápida e com identidade visual própria.

O usuário informa o link de destino, escolhe as cores do código e do fundo — e em segundos tem um QR Code pronto para baixar em alta qualidade no formato PNG.

---

## ✨ Funcionalidades

- 🔗 **Geração instantânea** de QR Code a partir de qualquer URL
- 🎨 **Personalização de cores** — escolha a cor do código e do fundo separadamente
- 💾 **Download em PNG** com um clique, em alta resolução
- ⚡ **Interface rápida e limpa** sem necessidade de cadastro ou login
- 📱 **Responsivo** — funciona em desktop e mobile
- 🏷️ **Identidade visual** com branding da Loja 482

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura da interface |
| **CSS3** | Estilização e responsividade |
| **JavaScript ES6** | Lógica de geração e download |
| **QRCode.js** | Biblioteca de geração de QR Codes |
| **Canvas API** | Renderização e exportação em PNG |

---

## 💡 Como Funciona

```
1. Usuário informa o link de destino do QR Code
        ↓
2. Seleciona a cor do código (padrão: preto)
        ↓
3. Seleciona a cor do fundo (padrão: branco)
        ↓
4. QR Code é gerado automaticamente em tempo real
        ↓
5. Usuário clica em "Baixar Imagem PNG"
        ↓
6. Arquivo PNG é salvo no dispositivo em alta qualidade
```

---

## 🔧 Como Rodar Localmente

### Pré-requisitos

- Navegador moderno (Chrome, Edge, Firefox)
- Nenhuma dependência externa — tudo já incluso no projeto

### Instalação

```bash
# Clone o repositório
git clone https://github.com/johnnywiick/gerador-qrcode.git
cd gerador-qrcode
```

### Executar

Abra o arquivo `index.html` diretamente no navegador ou sirva com um servidor local:

```bash
# Com Live Server (VS Code) ou qualquer servidor estático
open index.html
```

Acesse: `http://127.0.0.1:5500` *(ou conforme seu servidor local)*

---

## 🌐 Deploy em Produção

O projeto está hospedado no **GitHub Pages** com deploy automático via push na branch `main`.

🔗 URL de produção: [https://johnnywiick.github.io/gerador-qrcode/](https://johnnywiick.github.io/gerador-qrcode/)

---

## 📁 Estrutura do Projeto

```
gerador-qrcode/
├── index.html      # Interface principal do gerador
├── style.css       # Estilização e tema visual
├── script.js       # Lógica de geração e download do QR Code
└── .gitignore      # Arquivos ignorados pelo Git
```

---

## 🔒 Segurança

- Nenhum dado do usuário é coletado ou armazenado
- Geração 100% client-side — tudo acontece no navegador
- Nenhuma requisição externa é feita além da biblioteca QRCode.js

---

## 👨‍💻 Desenvolvedor

**Johnny Marcos**
Desenvolvido com 💙 usando HTML, JavaScript e QRCode.js.

[![GitHub](https://img.shields.io/badge/GitHub-johnnywiick-black?logo=github)](https://github.com/johnnywiick)

---

## 📄 Licença

Este projeto é proprietário. Todos os direitos reservados © 2026 QR Code Studio 482.
