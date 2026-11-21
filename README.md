# Violão Diário

PWA de treino diário de violão: 12 lições progressivas, trocas de 1 minuto com recordes, metrônomo com padrões de batida, afinação de referência e acompanhamento de sequência.

## Publicar no GitHub Pages

1. Crie um repositório e envie todos os arquivos desta pasta para a raiz.
2. Em **Settings → Pages**, escolha *Deploy from a branch*, branch `main`, pasta `/ (root)`.
3. Abra `https://<usuario>.github.io/<repositorio>/` no celular e use **Adicionar à tela inicial**.

Depois da primeira abertura, o app funciona offline. O progresso fica salvo no navegador do aparelho (localStorage).

Ao publicar uma nova versão, altere `CACHE` em `sw.js` (ex.: `violao-diario-v2`) para forçar a atualização.
