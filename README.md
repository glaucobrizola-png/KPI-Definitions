# KPI Site (Vercel-ready)

Pacote gerado automaticamente a partir do arquivo PPTX.

## Como publicar no Vercel (sem Git)

1. Acesse https://vercel.com -> Log in.
2. Menu no topo: **Add New** → **Project** → **Import** → **Upload**.
3. Faça upload deste `.zip`.
4. Quando o Vercel perguntar o comando de build, use o padrão do Vite:
   - **Framework Preset**: `Vite`
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
5. Clique **Deploy**.

## Rodar localmente
```bash
npm install
npm run dev
```
