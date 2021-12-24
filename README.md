# Desafio da Cubos Academy: módulo 02 (Front-end)

<h3> :dart: Sobre o projeto: </h3>

<p> Para finalização do módulo 2 do curso de desenvolvimento de software da Cubos academy, foi proposto desenvolver uma aplicação replicando o website encontrado no arquivo figma disponibilizado. A execução do projeto exigiu conhecimentos em: HTML, CSS, JavaScript, DOM, eventos e requisições a APIs de terceiros.</p>

<br/>

![](https://i.imgur.com/xG74tOh.png)

### Funcionalidades 
 - Visualização de filmes
 - Paginação de filmes
 - Busca de filmes
 - "Filme do dia"
 - Modal de filme
 - Mudança de tema

<hr/>

### Detalhamentos de Requisitos
#### - Visualização de filmes
Assim que o website for aberto, a listagem de filmes deverá ser preenchida com as informações deste [endpoint](https://tmdb-proxy.cubos-academy.workers.dev/3/discover/movie?language=pt-BR&include_adult=false).

#### - Paginação de filmes
Sempre existirão 4 páginas (0, 1, 2, 3) por conta do número de filmes em média ser 20 e, o website sempre irá mostrar no máximo 5 por vez.

O `<button class="btn-prev">`, quando clicado, se não estiver na página 0, terá que voltar 1 página, se não, levará o usuário para a página 3.
O `<button class="btn-next">`, quando clicado, se não estiver na página 3, terá que avançar 1 página, se não, levará o usuário para a página 0.

Ao voltar ou avançar uma página, os filmes em tela serão atualizados corretamente.

#### - Busca de filmes
O usuário poderá buscar um filme por meio do `<input class="input">`.
Quando o usuário pressionar a tecla "Enter" enquanto estiver com foco no input, algumas coisas terão que acontecer:
- O usuário terá que ser levado para a página 0.
- Se o input possuir algum valor, deverá ser realizada uma busca. Ex: Ao digitar "Matrix".
- Se o input não possuir valor nenhum, deverá ser realizada a mesma busca que é feita para preencher os filmes iniciais (Funcionalidade: visualização de filmes).
- O valor do input terá que ser limpo.

#### - "Filme do dia"
Assim que o website for aberto, o filme do dia deverá ser preenchido com as informações do [endpoint geral](https://tmdb-proxy.cubos-academy.workers.dev/3/movie/436969?language=pt-BR) e do [endpoint de videos](https://tmdb-proxy.cubos-academy.workers.dev/3/movie/436969/videos?language=pt-BR).

#### - Modal de filme
- Assim que o modal for **aberto**, ele deverá ser preenchido com as informações dos filmes.
- O modal poderá ser "fechado" por meio de um clique nele próprio ou na imagem do "X".

#### - Mudança de tema
Caso o **tema atual** seja "light" ou "claro", o mesmo deverá ser trocado para o tema "dark" ou "escuro" (com um clique no botão). Após isso, deverá ser modificado o tema (imagens e cores) do website de acordo com o Figma.


</br>

<h3>🔨Tecnologias</h3> 
<div>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" target="_blank">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" target="_blank">
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" target="_blank">
</div>

</br>

</br>
<h3>:woman_technologist: <b> Configurando o setup... </b></br></h3>
<ul>O primeiro passo é realizar a instalação dos programas utilizados na execução do projeto.
    <ul><li> 1º passo: caso não tenha, instale o <a href="https://git-scm.com/">Git</a> em seu computador. </li></ul>    
    <ul><li> 2º passo: instale um bom editor de código. Por exemplo, o <a href="https://code.visualstudio.com/">VSCODE</a>.</li></ul>
    <ul><li> 3º passo: adicione a extensão live server no seu VSCODE. </li></ul>
</ul>
  
</br>

### :warning: Para executar o projeto...
            // Clone o repositório para a sua máquina local.
            $ git clone git@github.com:Pam18/m02-front-desafio-cubos-academy.git
             
            // No painel esquerdo do seu VSCODE, clique com o botão direito no arquivo "index.html" e selecione "Open with Live Server".
            
            // A aplicação será aberta no seu navegador.
  
</br>
  
<h3>🎨Design</h3>

<ul>A página foi reproduzida de acordo com o exemplo do arquivo <a href="https://www.figma.com/file/AL6hZ3Lq16Uj8mw1o4BzAK/Desafio-front-academy-2?node-id=0%3A1">Figma</a>.</ul>

###### tags: `front-end` `HTML` `CSS` `DOM` `requisições`
