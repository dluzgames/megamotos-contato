# Design System — Mega Motos Paraíso (Contato)

## Mundo visual
Interior real da loja: paredes pretas, letreiro amarelo "CAPACETES", vitrine de capacetes. A página começa com a foto real da loja e continua no mesmo preto, com o amarelo Mega como cor de ação.

## Tokens
- `--bg` `#121315` fundo · `--panel` `#1B1C1F` grupos · `--panel-hover` `#232428`
- `--text` `#F3F1EA` · `--muted` `#A9A69D`
- `--yellow` `#F2C230` ação principal, ícones e links · `--yellow-press` `#E0AF1C`
- `--open` `#6FCF7F` / `--closed` `#E8806B` (status do horário)
- Raio `18px` em grupos e CTA; `24px` na foto (desktop)

## Tipografia
- `Oswald` 700, caixa alta: CTA, títulos de seção, nomes das lojas
- `Public Sans` 400–700: textos; `tabular-nums` nos telefones

## Estrutura
1. Foto real da loja (5:4, ocupa toda a largura no celular)
2. Logo + frase + status "Aberto/Fechado agora" (Seg–Sex 7h–18h · Sáb 7h–12h, `America/Araguaina`)
3. CTA amarelo único: Pedir orçamento (WhatsApp Vendas)
4. Lista agrupada estilo app: Financeiro, Localização, Grupo, Site, Ligar fixo (por último)
5. Prateleira com rolagem horizontal: produtos reais com link para a loja virtual
6. Redes sociais (3 colunas)
7. Duas lojas com o mesmo peso, cada uma com telefone e "Como chegar"

## Regras
- Sem "(Principal)" nas lojas; Loja 1 e Loja 2 têm o mesmo tratamento.
- Só uma animação: a foto assenta (escala 1.08 → 1) ao carregar; desligada com `prefers-reduced-motion`.
- Sem brilho neon, sem gradiente em texto, sem rótulos decorativos acima dos títulos.
