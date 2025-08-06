# Arquivos JSON de Listas de Enxoval por Clima

Este repositório contém arquivos JSON com listas genéricas de enxoval para diferentes climas, usados no app **Enxoval Baby**.

## Estrutura dos Arquivos

- `frio.json`: Lista adequada para climas frios
- `quente.json`: Lista adequada para climas quentes
- `tropical.json`: Lista adequada para climas tropicais

Cada arquivo segue o modelo completo com categorias, itens e metadados como `layetteId`, `userId`, `totalBudget`, `globalProgress` e mais.

## Uso

Após subir esse repositório em um serviço como [Vercel](https://vercel.com), será possível acessar via:

```
https://<seu-domínio>.vercel.app/tropical.json
```

No Flutter, utilize `http.get(Uri.parse(...))` e `jsonDecode`.

## Licença

Uso interno para o app Enxoval Baby.