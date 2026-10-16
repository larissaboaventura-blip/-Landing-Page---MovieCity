# Landing-Page MovieCity
Uma landing page moderna e responsiva para um serviço fictício de streaming de filmes. Este projeto foi desenvolvido como um exercício prático focado em componentização no React, estilização com CSS puro e adaptação de layouts para múltiplos tamanhos de tela (responsividade).

# Sobre o Projeto
A aplicação consiste em uma página principal dividida em duas seções essenciais:

Header (Cabeçalho): Contém a marca/logo MovieCity, o menu de navegação (Filmes, Categoria, Sobre, Contato), o botão de Login e o menu hambúrguer animado para telas móveis.

Main (Conteúdo Principal): Organizado em duas colunas:

Coluna 1: Texto promocional ("Seus Filmes") e botão de chamada de ação ("Mais").

Coluna 2: Grid responsivo com 6 cartões de filmes (Afterlife, Transformers, Mowgli, Shift, Round 6 e Harry Potter).

Em telas menores, as colunas empilham-se verticalmente, o grid adapta-se para 2 colunas e a navegação transforma-se em um menu hambúrguer acessível.

# Tecnologias Utilizadas
React 19: Biblioteca principal para criação da interface baseada em componentes.

Vite 7: Bundler e servidor de desenvolvimento com suporte a HMR (Hot Module Replacement).

JavaScript (ESM): Linguagem base do projeto utilizando módulos ES.

CSS Puro: Estilização global, Flexbox, CSS Grid e Media Queries (sem bibliotecas externas).

ESLint: Análise estática para garantia de boas práticas e padronização do código.

npm run lint: Executa o ESLint para detectar erros e inconsistências no código.

# Próximos Passos / Melhorias Futuras
Substituir as divs dos cartões por elementos  para melhorar a acessibilidade e navegação por teclado.

Adicionar títulos, gêneros e avaliações explicativas a cada filme.

Integrar com uma API externa de cinema (ex.: TMDB API) para carregar os dados dos filmes dinamicamente com .map().

Implementar suporte para prefers-reduced-motion para usuários que preferem animações reduzidas.

Migrar os estilos globais para CSS Modules à medida que a aplicação crescer.
