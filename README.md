# HABIT - Interface

## Telas implementadas
- login.html — Tela de login
- cadastro.html — Tela de criação de conta
- perfil.html — Perfil do usuário + postagens
- posts.html — Listagem e gerenciamento de posts
- comentarios.html — Fila de comentários
- usuarios.html — Gerenciamento de usuários
- editor.html — Editor de criação de post
- tela-extra.html — Tela extra criada conforme pedido

## Decisões de layout
- Abordagem mobile-first com breakpoints para tablet e desktop.
- Header compacto com logo à esquerda e ações à direita.
- Layout das páginas baseado em Grid (área principal + sidebar quando aplicável).
- Cores e tipografia definidas com variáveis CSS no :root para fácil customização.

## Breakpoints
- Base mobile: até 420px
- Tablet: a partir de 768px
- Desktop: a partir de 1024px

## Acessibilidade (observações)
- Uso de elementos semânticos (`header`, `main`, `nav`, `aside`, `footer`).
- Formulários com `label` corretamente associados (`for` + `id`).
- `alt` em imagens (placeholder fornecido).
- Estados visíveis em :focus / :hover.
- Contraste de texto pensado para atender WCAG 2.1 AA (cores principais com bom contraste).
- Navegação por teclado compatível: foco em links e botões.
