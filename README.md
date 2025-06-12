# 🧹 Remover páginas com QR Code de arquivos PDF

Este é um aplicativo web simples e eficiente que **remove automaticamente páginas de um arquivo PDF que contenham QR Codes**. Ele roda **100% localmente no navegador**, sem enviar seus dados para nenhum servidor.

## 🚀 Funcionalidades

- 📄 Processa arquivos PDF direto do seu computador
- 🧠 Detecta QR Codes em cada página usando a biblioteca `jsQR`
- ✂️ Remove apenas as páginas com QR Code
- 💾 Gera um novo PDF para download
- 🔒 Totalmente offline — privacidade garantida

## 🛠 Tecnologias usadas

- [PDF.js](https://mozilla.github.io/pdf.js/) – para renderizar PDFs
- [pdf-lib](https://pdf-lib.js.org/) – para criar/editar arquivos PDF
- [jsQR](https://github.com/cozmo/jsQR) – para detectar QR Codes

## 📸 Captura de tela

![screenshot](assets/screenshot.png) <!-- opcional, se você colocar uma imagem -->

## 📦 Como usar

1. Baixe ou clone este repositório:
   ```bash
   git clone https://github.com/Natanaelpvh/remove-qr-pdf.git
