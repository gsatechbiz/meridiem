# Meridiem Inc. — site institucional

Site de página única da Meridiem Inc., consultoria de inteligência e estratégia de marketing.

**Inteligência para decidir, com clareza.**

## Como abrir

O site é um arquivo único, sem dependências de build. Basta abrir o `index.html` no navegador.

Para servir localmente:

```bash
python -m http.server 5173
```

Depois acesse `http://localhost:5173`.

## Estrutura

Tudo vive em `index.html`: o HTML, o CSS e o JavaScript estão embutidos no próprio arquivo, junto com o favicon. Isso mantém o site funcionando em qualquer lugar, inclusive aberto direto do disco.

A única dependência externa são as fontes Arimo e Carlito, carregadas do Google Fonts. Sem internet, o site recorre a Arial e Calibri e o layout se mantém.

## Conteúdo

A página apresenta a tese da Meridiem e o método de trabalho, em dez figuras interativas:

| Figura | Assunto |
|---|---|
| 01 | O painel onde os indicadores de mídia sobem e o negócio fica estável |
| 02 | Do registro à pergunta |
| 03 | Um ponto de partida, vários caminhos |
| 04 | O consumidor no centro da leitura |
| 05 | Ambientes de descoberta, avaliação e escolha |
| 06 | As perguntas que mudam o caminho |
| 07 | Do sinal ao caminho |
| 08 | Índice de Viabilidade |
| 09 | Estratégia como processo revisável |
| 10 | Método, experiência e discernimento |

Os números das figuras 01 e 08 são exemplos conceituais, marcados como ilustrativos na própria página. Não representam resultados de clientes.

## Acessibilidade

O site tem como alvo o WCAG 2.1 AA. As combinações de peach e branco sobre magenta aparecem apenas em texto grande, onde atendem ao critério. A página respeita `prefers-reduced-motion`, funciona pelo teclado e traz descrições em texto para cada diagrama.

## Contato

comercial@meridieminc.com.br
