# Koala Supermercados

Site dinâmico com layout inspirado no supermercadosguanabara.com.br, em tons de azul claro e com a marca Koala. HTML, CSS e JavaScript puro. Abra `index.html`.

## Fluxo da aula (Prof. Cid Andrade)
1. **Referência antes:** categorias, barra superior, lista de compras e rodapé do Guanabara.
2. **Design system como contexto:** `tokens.css` (fonte única) e `AGENTS.md` (regras para a IA).
3. **Prompt com critério de aceite:** lista abaixo.
4. **Teste depois:** `catalogo.html` mostra todos os componentes em todos os estados.

## Geometria própria
Raio de 2px, escala de espaço de 4px e escala tipográfica 1.25, em vez de só trocar as cores do template.

## Páginas
| Página | O que faz |
|---|---|
| `index.html` | 14 categorias com fotos, ofertas do dia com cronômetro, dicas, newsletter |
| `produtos.html` | Busca, filtro por categoria, ordenação, adicionar à lista |
| `promocoes.html` | Encarte ordenado por desconto |
| `lista.html` | Lista de compras com modelos (Dia-a-Dia, Churrasco, Festa), total, copiar e imprimir |
| `sac.html` | SAC e canal de denúncias com validação |
| `catalogo.html` | Componentes em normal, hover, foco, desabilitado, erro, claro e escuro |

## Critérios de aceite
- [ ] A página inicial mostra as 14 categorias com foto; cada uma leva ao filtro correspondente.
- [ ] Adicionar um produto atualiza o contador da lista sem recarregar a página.
- [ ] A lista persiste após recarregar e calcula o total.
- [ ] Formulários mostram erro por campo (`aria-invalid`) e focam o primeiro erro.
- [ ] Todo elemento interativo tem foco visível e funciona pelo teclado.
- [ ] Tema escuro pelo botão e pela preferência do sistema, lembrado entre visitas.
- [ ] Nenhuma cor hexadecimal fora de `tokens.css`.
- [ ] Layout correto em 360px, 768px e 1280px.

## Fotos
Fotos reais do Wikimedia Commons. Créditos e licenças em `img/fotos/CREDITOS.md`. As fotos são por categoria; os produtos de uma categoria compartilham a foto.
