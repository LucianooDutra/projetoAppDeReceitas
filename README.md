# Projeto Cook a Cookie!

## Sobre o projeto:

  Projeto de um App de receitas, feito em JavaScript, que tem como principal objetivo ver, buscar, filtrar, favoritar e acompanhar o progresso de preparação de receitas e drinks!

  A base de dados serão 2 APIs distintas, uma para comidas e outra para bebidas.

  O layout tem como foco dispositivos móveis.
  

# Técnologias utilizadas:

 - JavaScript;
 - React;
 - Context API;
 - Redux;
 - React Hook;
 - Hooks customizados;
 - Linter;
 - Cypress;
 - Mocha;
 - Jest;
 - CSS;
 - HTML;

# Habilidades trabalhadas:

 - Fazer o uso de tecnologias pra guardar o estado global da aplicação;
 - Escrever Hooks customizados;
 - Utilizar CSS;
 - Utilizar HTML;
 - Requisições a APIs externas;
 - testes unitários;
 
 
# Rotas da aplicação:

   * Tela de login: `/`;
   * Tela principal de receitas de comidas: `/foods`;
   * Tela principal de receitas de bebidas: `/drinks`;
   * Tela de detalhes de uma receita de comida: `/foods/{id-da-receita}`;
   * Tela de detalhes de uma receita de bebida: `/drinks/{id-da-receita}`;
   * Tela de receita em progresso de comida: `/foods/{id-da-receita}/in-progress`;
   * Tela de receita em progresso de bebida: `/drinks/{id-da-receita}/in-progress`;
   * Tela de perfil: `/profile`;
   * Tela de receitas feitas: `/done-recipes`;
   * Tela de receitas favoritas: `/favorite-recipes`.


## Instalando as dependências

<details>

  ```json
    # Clone o repositório:
    git clone git@github.com:LucianooDutra/projetoAppDeReceitas.git
    
    # Entre no diretório:
    cd projetoAppDeReceitas
    
    # Instale as dependências:
    npm install
  ```
</details>

## Executando a aplicação

<details>
 <summary><strong>App</strong></summary><br />


- Para rodar o App:

Para executar digite o seguinte comando no terminal a partir da raiz do projeto:

  ```json
    npm start
  ```
  
  ou
  
Acessar pelo link:

	https://projeto-app-de-receitas-lilac.vercel.app/


</details>


## Executando os testes

<details>
 <summary><strong>Testes</strong></summary><br />

 Foi utilizado o react-testing-library para a realização dos testes;

- Para rodar todos os testes:

Para executar todos os testes digite o seguinte comando no terminal a partir da raiz do projeto:

  ```json
    npm test
  ```


</details>


