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
| `index.html` | o site inteiro: HTML, CSS, JavaScript e favicon no mesmo arquivo |
| `404.html` | página de endereço não encontrado |
| `og.png` | imagem de compartilhamento em redes sociais |
| `fonts/` | Arimo e Carlito em woff2, com as licenças |

Não há build, dependências nem chamadas a serviços externos. As fontes são servidas pelo próprio site, então nenhum dado de quem visita sai para terceiros, e a página funciona offline. Quem já tem Arial e Calibri instaladas usa essas, e os arquivos nem chegam a ser baixados.

## Conteúdo

A página apresenta a tese da Meridiem e o método de trabalho, em dez figuras interativas:

| Figura | Assunto |
|---|---|
| 01 | O painel onde os indicadores de mídia sobem e o negócio fica estável |
| 02 | Do registro à pergunta |
| 03 | Um ponto de partida, vários caminhos |
| 04 | Os três eixos: mercado, negócio e comportamento |
| 05 | Ambientes de descoberta, avaliação e escolha |
| 06 | As perguntas que mudam o caminho |
| 07 | Do sinal ao caminho |
| 08 | Índice de Viabilidade: esforço de execução × viabilidade |
| 09 | Estratégia como processo revisável |
| 10 | Método, experiência e discernimento |

Os números das figuras 01 e 08 são exemplos conceituais, marcados como ilustrativos na própria página. Não representam resultados de clientes.

## Publicação

O site é servido pelo GitHub Pages a partir do branch `main`, na raiz. O `.nojekyll` impede que o GitHub processe o HTML.

## Acessibilidade

O site tem como alvo o WCAG 2.1 AA. As combinações de peach e branco sobre magenta aparecem apenas em texto grande, onde atendem ao critério. A página respeita `prefers-reduced-motion`, funciona pelo teclado e traz descrições em texto para cada diagrama.

## Contato

comercial@meridieminc.com.br
