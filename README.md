# NIR CEMETRON

Repositório completo, sem login, compatível com GitHub e Vercel.

## Publicação na Vercel

1. Crie um repositório vazio no GitHub.
2. Envie **todo o conteúdo desta pasta para a raiz do repositório**.
3. Na Vercel, clique em **Add New > Project** e importe o repositório.
4. Em **Framework Preset**, mantenha **Vite**.
5. Confirme:
   - Build Command: `npm run build`
   - Output Directory: `dist`
   - Root Directory: `./`
6. Clique em **Deploy**.

A Vercel também lerá automaticamente o arquivo `vercel.json`.

## Teste local

```bash
npm install
npm run dev
```

## Validação de produção

```bash
npm install
npm run build
npm run preview
```

## Armazenamento

Esta versão permanece sem login e utiliza o `localStorage` do navegador. Cada dispositivo ou navegador mantém seus próprios dados.
