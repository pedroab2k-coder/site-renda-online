# Site Renda Online (Abas + Partículas + Mockup 3D + Lead)

Landing estática com navegação por abas, fundo interativo, mockup 3D do eBook e captação de e-mails.

## Publicar no GitHub Pages
1. Crie o repositório (público) e envie `index.html`, `policy.html`, `README.md`.
2. Em **Settings → Pages**, selecione **Branch: main** e **Folder: /(root)**.
3. O site ficará em `https://SEU_USUARIO.github.io/NOME_DO_REPO/`.

## Configurar Checkout e Lead
- No `index.html`, ajuste:
```js
const CHECKOUT_URL = "https://pay.seu-gateway.com.br/SEU_ID?src=landing_tabs";
const LEAD_POST_URL = "https://formspree.io/f/SEU_ENDPOINT"; // crie seu endpoint grátis no Formspree
```
- Se `LEAD_POST_URL` ficar vazio, o formulário abre um `mailto:` como fallback.

## Personalização
- Cores: altere variáveis CSS no `:root`.
- Mockup 3D: editável via CSS (`.cover:before/.after`).
- Linha do tempo: edite o array `events` no JS.
