# Meridiem Inc. — site institucional

Site de página única da Meridiem Inc., Growth Partner com foco em soluções de inteligência.

**Inteligência para decidir, com clareza.**

## Como abrir

O site é um arquivo único, sem dependências de build. Basta abrir o `index.html` no navegador.

Para servir localmente:

```bash
python -m http.server 5173
```

Depois acesse `http://localhost:5173`.

## Estrutura

| Arquivo | |
|---|---|
| `index.html` | o site inteiro: HTML, CSS, imagens e favicon no mesmo arquivo |
| `404.html` | página de endereço não encontrado |
| `og.png` | imagem de compartilhamento em redes sociais |
| `fonts/` | Arimo e Carlito em woff2, com as licenças, usadas pela `404.html` |

Não há build nem dependências. O `index.html` carrega as fontes Archivo e Lato do Google Fonts.

## Conteúdo

A página segue esta ordem:

| Seção | Assunto |
|---|---|
| Hero | Growth Partner com foco em soluções de inteligência |
| Para quem | Dono de PME, gestor de mídia ou growth, agência independente |
| A tese | O marketing aprendeu a medir o consumidor melhor do que aprendeu a entendê-lo |
| As três camadas | Mercado, negócio e comportamento |
| O método | Oito etapas, da informação à ação |
| Dois índices | Índice de Viabilidade (etapa do método) e Índice de Esforço (produto) |
| A camada digital | Prateleira Digital, Digital Discoverability e Digital Activation |
| Produtos | Leitura de mercado, leitura de demanda e decisão |
| Como você contrata | Projeto ou Parceria Contínua, com pool de parceiros |
| Fechamento | Melhorar a decisão antes de melhorar o indicador |

## Publicação

O site é servido pelo GitHub Pages a partir do branch `main`, na raiz. O `.nojekyll` impede que o GitHub processe o HTML.

## Acessibilidade

A página respeita `prefers-reduced-motion`, tem tema claro e escuro e funciona pelo teclado.

## Contato

comercial@meridieminc.com.br
