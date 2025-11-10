# Site Renda Online (Landing + Timeline)

Landing page estática para venda do eBook **ChatGPT + Grok**.

## Como publicar no GitHub Pages
1. Crie o repositório no GitHub (público).
2. Envie estes arquivos (`index.html`, `policy.html`, `README.md`).
3. Vá em **Settings → Pages** e selecione **Branch: `main`** e **Folder: `/ (root)`**.
4. Salve. O site ficará disponível em `https://SEU_USUARIO.github.io/NOME_DO_REPO/`.

## Onde configurar o link de checkout
No `index.html`, procure por `CHECKOUT_URL` e substitua por seu link real (Kiwify/Hotmart/etc.).

## Customização rápida
- Cores e estilos em CSS variables no `:root`.
- Eventos da timeline no array `events` (JS).

---
Feito para carregamento rápido e sem dependências externas (apenas Google Fonts).
