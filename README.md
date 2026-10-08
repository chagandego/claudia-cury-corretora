# Cláudia Cury · Corretora de Imóveis

Site institucional da corretora Cláudia Cury (Cambuci, São Paulo).
Página única em HTML/CSS/JS puro, sem build.

## Rodar localmente

Abra o `index.html` no navegador, ou sirva a pasta com qualquer servidor estático.

## Publicação (Vercel)

O projeto está ligado na Vercel, mas **travado para não ir ao ar**. São duas travas no `vercel.json`:

- `"git": { "deploymentEnabled": false }`: push no GitHub não dispara deploy;
- `"ignoreCommand": "exit 0"`: qualquer build que comece é cancelado.

Para colocar no ar, edite o `vercel.json` (dá para fazer pelo próprio GitHub) e deixe só isto:

```json
{
  "$schema": "https://openapi.vercel.sh/vercel.json",
  "cleanUrls": true
}
```

Depois do commit, abra o projeto na Vercel e clique em **Deploy** (ou em **Redeploy** no último deploy). A partir daí, cada commit na `main` vai direto para produção.

## Antes de publicar

- [ ] Adicionar o número do CRECI no rodapé (obrigatório em anúncios de imóveis). Já tem uma linha comentada no `index.html` pronta para isso.
- [ ] Confirmar com a Cláudia os bairros atendidos e os serviços (venda, compra, locação, avaliação).
- [ ] Opcional: foto dela na seção "Sobre" e domínio próprio.
