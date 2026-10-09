# Cláudia Cury · Corretora de Imóveis

Site institucional da corretora Cláudia Cury (Cambuci, São Paulo).
Página única em HTML/CSS/JS puro, sem build.

## Rodar localmente

Abra o `index.html` no navegador, ou sirva a pasta com qualquer servidor estático.

## Publicação (Vercel)

O projeto está publicado na Vercel em produção: https://claudia-cury-corretora.vercel.app
Cada commit na `main` vai direto para o ar.

O site está **liberado para o Google**, com `robots.txt` e `sitemap.xml`. Para esconder de novo, volte a pôr no `vercel.json`:

```json
"headers": [
  { "source": "/(.*)", "headers": [{ "key": "X-Robots-Tag", "value": "noindex, nofollow" }] }
]
```

## Pendências

- [ ] Adicionar o número do CRECI no rodapé (obrigatório em anúncios de imóveis). Já tem uma linha comentada no `index.html` pronta para isso.
- [ ] Confirmar com a Cláudia os bairros atendidos e os serviços (venda, compra, locação, avaliação).
- [ ] Opcional: foto dela na seção "Sobre" e domínio próprio.
