# Portfólio de Projetos para Ensino de Programação

## Objetivos pedagógicos e competências
- Planejar e montar uma landing page de portfólio com HTML5, aplicando semântica básica (cabeçalho, seções, cards, rodapé).
- Estilizar com CSS e Bootstrap, ajustando cores, tipografia e espaçamentos para garantir responsividade.
- Trabalhar modais como recurso para aprofundar descrição de projetos sem poluir a página principal.
- Exercitar curadoria de conteúdo: escrever resumos, destacar habilidades e organizar links para código e demonstrações.
- Reforçar boas práticas de revisão (consistência visual, acessibilidade mínima via textos alternativos e hierarquia de títulos).

## Sobre o projeto
- Interface: `index.html` estruturado com Bootstrap 5 e ícones do Bootstrap Icons.
- Estilos: `style.css` define paleta, tipografia (Chakra Petch) e ajustes de links e destaques.
- Mídia: imagens em `imagens/` ilustram avatar e miniaturas dos projetos.
- Execução: abra `index.html` no navegador ou sirva localmente (ex.: `npx serve .` ou extensão de servidor local do VS Code).

## Roteiro de aulas (passo a passo)
1) Aula 1 — Briefing e setup  
   - Discutir o público, os três projetos a destacar e quais links externos serão exibidos.  
   - Organizar a pasta com `index.html`, `style.css` e `imagens/`. Configurar VS Code ou editor escolhido.

2) Aula 2 — Estrutura da página  
   - Montar `<head>` com metatags, Bootstrap e folha de estilos própria.  
   - Criar `<header>` com foto, apresentação, parágrafo de habilidades e badges de competências.

3) Aula 3 — Seção de projetos com cards  
   - Inserir a grade (`.row` + `.col-md-4`) e três cards com título, resumo curto e botão para saber mais.  
   - Garantir textos alternativos das imagens e testar responsividade em tamanhos diferentes.

4) Aula 4 — Modais detalhados  
   - Implementar os três modais com `data-bs-toggle` e `data-bs-target`.  
   - Preencher cada modal com descrição longa, imagem maior e links para demo/código.  
   - Verificar hierarquia de títulos (H5 nos modais) e botões de fechar acessíveis.

5) Aula 5 — Estilo e identidade visual  
   - Ajustar paleta em `:root`, tipografia e pesos de fonte.  
   - Refinar espaçamentos, cores de links e destaques para leitura confortável.  
   - Revisar contraste e legibilidade.

6) Aula 6 — Revisão e publicação  
   - Rodar uma checagem final de textos, ortografia e links.  
   - Hospedar no GitHub Pages (ou similar) e testar os modais em mobile.  
   - Registrar aprendizados e próximos passos no README.

## Possíveis melhorias futuras
- Adicionar filtro/busca para projetos e categorias (ex.: HTML, CSS, JS, Scratch).
- Incluir uma seção “Processo de ensino” com relatos de aula, desafios e rubricas de avaliação.
- Criar versão multilíngue (pt/en) com alternância via botão ou parâmetro de URL.
- Acrescentar testes de acessibilidade (contrast checker, validação de tags alt, foco nos modais).
- Integrar analytics de privacidade-respeitosa para medir cliques em projetos e tempo de leitura.
