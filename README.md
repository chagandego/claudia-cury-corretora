# Cláudia Cury · Corretora de Imóveis

Site institucional da corretora Cláudia Cury (Cambuci, São Paulo).
Página única em HTML/CSS/JS puro, sem build.

## Rodar localmente

Abra o `index.html` no navegador, ou sirva a pasta com qualquer servidor estático.

## Publicação (Vercel)

O projeto está publicado na Vercel em produção: https://claudia-cury-corretora.vercel.app
Cada commit na `main` vai direto para o ar.

Por enquanto o site está **escondido do Google**: o `vercel.json` manda o cabeçalho
`X-Robots-Tag: noindex, nofollow`. Quem tem o link consegue abrir, mas o site não aparece nas buscas.

Para liberar de vez, quando a Cláudia aprovar, apague o bloco `"headers"` do `vercel.json` e faça commit.

## Antes de liberar de vez

- [ ] Adicionar o número do CRECI no rodapé (obrigatório em anúncios de imóveis). Já tem uma linha comentada no `index.html` pronta para isso.
- [ ] Confirmar com a Cláudia os bairros atendidos e os serviços (venda, compra, locação, avaliação).
- [ ] Opcional: foto dela na seção "Sobre" e domínio próprio.
