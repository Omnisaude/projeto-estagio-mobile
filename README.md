# Projeto para Estágio Mobile - Omnisaúde

## Objetivo
Avaliar a habilidade do candidato em construir telas e widgets, gerenciar o estado de um aplicativo, consumir uma API REST e utilizar recursos do Firebase.

## Instruções

Teste de Estágio em Flutter - Aplicativo de Filmes com IMDB e Firebase
Objetivo: Criar um aplicativo Flutter que consulta a API IMDB para listar filmes, exibir detalhes de filmes e permite salvar filmes como favoritos no Firebase.
  
  - A api a ser usada deve ser: http://www.omdbapi.com/
  - Caso não houver ambiente configurado pode usar esta IDE online: https://flutlab.io
    
## Tarefas:
    Configuração do Projeto (20 pontos):
      - Crie um novo projeto Flutter.
      - Configure o projeto para acessar a API OMDB.
    
    Tela Inicial (40 pontos):
      - Crie uma tela inicial (HomePage) que consulte a API IMDB e exiba um campo texto que permita a pesquisa por título do filme.
      - Cada filme deve mostrar seu título, imagem de capa e avaliação.
    
    Detalhes do Filme (40 pontos):
      - Ao tocar em um filme na tela inicial, o aplicativo deve navegar para uma tela de detalhes do filme.
      - A tela de detalhes deve exibir informações detalhadas sobre o filme, como título, descrição, gênero, data de lançamento, diretor, etc. Caso alguma dessas informações não existir por desconsiderar e não exibí-la.
    
## Opcional(BONUS)
    Configuração do firebase
      - Crie um projeto no firebase.
      - Configure a integração com o Firebase para permitir o salvamento de filmes favoritos.
      
    Firebase - Salvar Favoritos (20 pontos):
      - O botão "Adicionar aos Favoritos" na tela de detalhes deve permitir ao usuário salvar o filme como um favorito no Firebase.
      - Os filmes favoritos devem ser armazenados em uma coleção Firebase, associados ao usuário atual (não é necessário implementar a autenticação).
    
    Tela de Favoritos (20 pontos):
      - Crie uma tela que exiba a lista de filmes favoritos salvos pelo usuário.
      - Os filmes favoritos devem ser recuperados do Firebase e exibidos nesta tela.
      - Os filmes devem ser exibidos em cartões semelhantes aos detalhes do filme.

## Regras e Notas:
      - O código deve ser organizado.
      - O aplicativo deve ser funcional e capaz de acessar a API IMDB e o Firebase.
      - Os filmes devem ser exibidos de forma legível e atraente.
      - Prazo para a conclusão do teste: 3 dias.

    Observações:
      - Se você enfrentar dificuldades em qualquer parte do teste, é recomendável que documente os desafios e as tentativas de resolução.
      - Use a gerência de estado de sua preferência.
      - O código deve ser comentado adequadamente para explicar a lógica e a estrutura do aplicativo.
      - O candidato pode usar pacotes Flutter e bibliotecas de terceiros, se necessário.
      
  ## Exemplo de tela

![1_mN_T3I2tUXpIAVRKjJbwjw](https://github.com/Omnisaude/projeto-estagio-mobile/assets/12771605/4790d44f-aa7f-4e3d-8fbd-e0347dab25c1)

      
