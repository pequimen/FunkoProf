# FunkoProf® — Eduardo Francener

## Estrutura de Pastas

```
├── index.html      ← Página principal (Vue 3 via CDN)     
└── assets/
    ├── styles.css  ← Estilos
    └── images/     ← Imagens dos Funkos
        ├── funko-andre.png        
        ├── funko-adamo.png
        ├── funko-kennedy.png
        ├── funko-marcio.png
        ├── funko-moissa.png
        ├── funko-reghelin.png
        └── funko-maico.png
```



## Funcionalidades Vue 3 implementadas

| Bind CDN | `:src`, `:class`, `:style`, `:disabled` | Imagem, variantes, botões |
| Condicionais | `v-if`, `v-else-if`, `v-else` | Estoque, overlay, toast |
| Renderização de listas | `v-for` | Variantes, carrinho, detalhes, coleção |
| Eventos manuais | `@click`, `@mouseover`, `@mouseleave` | Botões, variantes |
| Estilos condicionais | `:class`, `:style` com expressões | Cores dinâmicas, disabled, status |

## Funcionalidades extras

- 🎛️ **Painel Admin** — Editar o estoque de cada Funko em tempo real
- 🛒 **Carrinho lateral** — Adicionar e remover itens com animação
- ⚠️ **Limite de unidades** — Aviso quando o máximo do estoque é atingido
- 🚦 **Barra de estoque** — Visual "Em estoque / Últimas unidades / Esgotado"
- 💳 **Página de Checkout** — Tela de finalização de compra com animação
- 🎊 **Confirmação de pedido** — Finalização do pedido e diminuição do estoque conforme "compra"
