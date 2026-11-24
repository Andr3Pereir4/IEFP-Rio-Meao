IEFP-Rio-Meao Trabalho final da UFCD de Estilo CSS IEFP Rio Meão — Proposta de reformulação

Aluno: André Pereira
Turma: UFCD 0154 - Estilos em CSS

Descrição Website reforumlado de página única que apresenta o centro, áreas de formação, notícias demonstrativas e contactos.

Conceito visual Identidade simples e moderna, com azul para os botões e verde para os destaques. Os conteúdos estão divididos em secções e cartões, com navegação por âncoras.

Tecnologias HTML5 e CSS com Flexbox, media queries e variáveis CSS. Sem Bootstrap, optei por fazer sem porque preferi ir rever coisas de CSS que me falhava à memória.

Modo diurno e noturno O modo claro apresenta fundos claros e texto escuro. O modo noturno apresenta fundos escuros e texto claro. A alternância é feita por um checkbox HTML com o seletor CSS :checked e aplica-se a toda a página.

Principais variáveis CSS --fundo (fundo principal), --fundo-secundario (secções), --texto (texto), --destaque (cor de destaque), --cartao (cartões), --botao e --botao-hover (botões), --borda (contornos).

Três transições utilizadas

Botões: background-color e transform, 300ms, funções ease-in-out e ease-out.
Cartões: transform e box-shadow, 300ms, funções ease-out e ease-in-out.
Mudança de tema: background-color e color, 500ms, função ease.
Recursos utilizados Os elementos visuais são composições CSS e emojis Unicode. Não foram utilizadas fotografias nem bibliotecas externas de ícones. Os links para IEFP e IEFP Online encaminham para os websites oficiais.

Conteúdos de exemplo Os quatro cursos, as durações e as três notícias são fictícios e foram criados apenas para este trabalho. O formulário é demonstrativo e não envia dados. Os contactos oficiais devem ser consultados na página do IEFP.

Dificuldades e soluções

Modo escuro sem JavaScript: resolvido com checkbox e variáveis CSS.
Layout adaptável: resolvido com Flexbox e media queries.
Animações suaves: resolvido com transition e :hover.
Ajustar esta secção às dificuldades realmente encontradas durante o desenvolvimento.

commits ao longo do trabalho, por exemplo:

Criar estrutura HTML e ficheiros iniciais
Adicionar estilos e layout Flexbox
Criar modo escuro e transições
Adicionar responsividade e formulário
Finalizar documentação e testes
