# Introdução
Um dispositivo para pesquisar todos os pokemons

<img src="./images/pokedex.png">
# Techs 
<strong>JavaScript</strong>: JavaScript é uma linguagem de programação interpretada estruturada, de script em alto nível com tipagem dinâmica fraca e multiparadigma<br>
<strong>Html</strong>: HTML é uma linguagem de marcação utilizada na construção de páginas na Web<br>
<strong>Css</strong>: Cascading Style Sheets é um mecanismo para adicionar estilos a uma página web
# pokedex

O projeto foi estruturado em html e estilizado em css e trazendo consigo as funcionalidades com o js, a principal parte do codigo foi o javascript onde foi feita uma requesição de uma api onde estão armazenadas todas os pokemons, e converte essa api ('https://pokeapi.co/api/v2/pokemon/${pokemon}') para o formato json, tudo isso foi feita na função fetchPokemon, logo depois no "const dat" com o await se chama a função fetchPokemon com o if definimos o id de cada pokemon e altura e com outro if dentro se verifica o pokemon e se da a imagem apropiada, e com o else caso não tenha o pokemon digitado ele não mostra nada e aparece erro.


link do site:https://meupokedexjoao.vercel.app/
