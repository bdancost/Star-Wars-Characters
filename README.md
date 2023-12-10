

Este código JavaScript é uma aplicação simples para visualizar personagens da saga Star Wars consumindo a API pública do SWAPI (Star Wars API). Aqui está uma breve explicação das principais técnicas e funcionalidades implementadas:

1. Carregamento de Personagens:
   - O código utiliza a função `loadCharacters(url)` para fazer requisições assíncronas à API SWAPI, buscando informações sobre personagens.
   - Os resultados são exibidos em cards na interface, onde cada card contém o nome do personagem e uma imagem relacionada, obtida da URL da API.

2. Navegação entre Páginas:
   - Botões de próxima (`nextButton`) e anterior (`backButton`) permitem a navegação entre páginas de personagens.
   - As funções `loadNextPage()` e `loadPreviousPage()` são responsáveis por carregar os personagens da página seguinte ou anterior.

3. Modal de Detalhes:
   - Ao clicar em um card, um modal é exibido com detalhes do personagem, como imagem, nome, altura, peso, cor dos olhos e ano de nascimento.
   - O modal pode ser fechado clicando fora de sua área ou através do botão de fechar.

4. Tratamento de Dados:
   - Funções como `convertHeight()`, `convertMass()`, `convertEyeColor()` e `convertBirthYear()` são utilizadas para formatar e exibir informações de maneira mais compreensível.
   - Valores desconhecidos são tratados e exibidos de forma adequada.

5. Controle de Visibilidade de Botões:
   - Os botões de próxima e anterior são desativados e têm sua visibilidade ajustada conforme a existência de páginas anteriores ou seguintes.

6. Manipulação do DOM:
   - O código manipula o DOM para criar elementos HTML dinamicamente, como cards de personagens e o modal de detalhes.

7. Gerenciamento de Erros:
   - O código trata erros durante o carregamento de personagens, exibindo mensagens de alerta em caso de falha.

Este projeto oferece uma experiência interativa para explorar os personagens de Star Wars de forma amigável e informativa.
