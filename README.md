# :toolbox: Tecnologias usadas:

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![Mocha](https://img.shields.io/badge/-mocha-%238D6748?style=for-the-badge&logo=mocha&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

# :busts_in_silhouette: Projeto desenvolvido em conjunto com:
  
#### [Artur Senna](https://github.com/artursennass), [Yury Stolarz Santana](https://github.com/yuryss98), [Luis Arthur Rodrigues da Silva](https://github.com/luisArthurRodriguesDaSilva) e [Vinicius Kaminski](https://github.com/Kaminskifking)

# :open_book: Objetivo do projeto recipes app

<details>
  <summary>:speech_balloon: Objetivos</summary>

  ```
  1. Desenvolver um app de receitas que utiliza React hooks e context API.
  2. É possível ver, buscar, filtrar, favoritar e acompanhar o progresso de preparação de receitas de comidas e bebidas.
  ⚠️ A base de dados são 2 APIs distintas, uma para comidas e outra para bebidas. ⚠️
  3. O layout tem como foco dispositivos móveis.
  4. Exercitar a capacidade de:
    4.1 Utilizar Redux para gerenciar estado
    4.2 Utilizar a biblioteca React-Redux
    4.3 Utilizar a Context API do React para gerenciar estado
    4.4 Utilizar o React Hook useState
    4.5 Utilizar o React Hook useContext
    4.6 Utilizar o React Hook useEffect
    4.7 Criar Hooks customizados
  ```
</details>

<details>
  <summary>:speech_balloon: Exemplo de funcionamento</summary>
  
<imagens e ou gifs>
  
</details>

# :heavy_exclamation_mark: Arquivos desenvolvidos nesse projeto:

<details>
  <summary>:speech_balloon: Arquivos</summary>

  ```
  src/
    App.jsx
    App.jsx
    index.js
  
    components/
      CategoryButton.jsx
      DoneRecipesFilters.jsx
      DoniedItem.jsx
      DoniedItens.jsx
      FavoriteCard.jsx
      FinishRecipe.jsx
      Footer.jsx
      Header.jsx
      RecipeCard.jsx
      RecipeInProgress.jsx
      SearchBar.jsx
      RecipeContext.js
      RecipeProvider.js
    
    helpers/
      renderWithRouter.js
       
 
      recipe_details_page_helpers/
        doneRecipe.js
        fetchTreatment.js
        isInProgress.js
    
    hooks/
      useLocalStorage.jsx
  
    pages/
      DoneRecipes.jsx
      FavoriteRecipes.jsx
      Login.jsx
      Profile.jsx
      RecipeDetails.jsx
      Recipes.jsx
      
    services/
      Fetch.js
      gets.js
  
    styles/
      DoniedItem.css
      Footer.css
      RecipeInProgress.css

    tests/
      Details.test.js
      FavoritesRecipes.test.js
      Footer.test.js
      Header.test.js
      Login.test.js
      Profile.test.js
      RecipeInProgress.test.js
      RecipesTests.test.js
      SearchBar.test.js
  
      helpers/
        categoryMeals.js
        detailsDrinkMock.js
        detailsMealsMock.js
        detailsRecomendedDrinks.js
        detailsRecomendedMeals.js
        drinks.js
        meals.js
        oneMeal.js
        renderWithRouter.js
  ```
</details

#### :warning: todos os outros arquivos foram desenvolvidos pela [Trybe](https://www.betrybe.com).

# :thinking: Como checar o projeto

```
git clone git@github.com:Lucas-Israel/project-recipes-app.git
npm install
npm run test
npm start
```

# :calendar: Datas para desenvolvimento

```
início: 23/09/22 às 14h48
término: 01/10/22 às 22h39
prazo: 7 dias
dias específicos para o desenvolvimento do projéto: 8
```

# :trophy: Percentual de conclusão do projeto

![Captura de tela de 2023-05-22 15-15-51](https://github.com/Lucas-Israel/project-recipes-app/assets/104790267/a00a92a5-1d47-4e78-900f-54e077682a8f)

<details>
  <summary>:warning: Metodo de avaliação da Trybe</summary>
  
##### A escola de programação [Trybe](https://www.betrybe.com) utiliza um sistema de avaliação baseado na conclusão de requisitos em cada projeto, considerando a porcentagem de conclusão, com um mínimo de 80% dos requisitos obrigatórios, em um prazo regular de no máximo 7 dias, tendo dias específicos para o desenvolvimento do projeto que variam de acordo com a complexidade dele.

##### Não alcançando esse patamar mímino, o aluno entra em recuperação, tendo que entregar 90% dos requisitos obrigatórios mais os bonús, em outros 7 dias, caso o aluno falhe novamente ele é mudado de turma para refazer o conteúdo e projeto, caso falhe após mudar de turma, no mesmo conteúdo/projeto, o aluno é removido do curso.
  
</details>
