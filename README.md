# Simons
atividades do curso
Página Web: 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css.styles.css">
    <title>Projeto 1</title>
</head>
<body>
    
    <div class="row header">
      <div class="content">
         <div class="header-logo">
             <h1>
                 <a href="indexx.html" target="blank">
                     <span class="html">HTML</span>&<span class="css">CSS</span>
                 </a>
              </h1>
            </div>

            <div class="header-menu">
                <ul>
                    <li><a href="#" target="blank">Home</a></li>
                    <li><a href="#" target="blank">Sobre</a></li>
                    <li><a href="#" target="blank">Artigos</a></li>
                    <li><a href="#" target="blank">E-book</a></li>
                </ul>
            </div>
         </div>

    </div> 


<!--final header-->

<!--inicio bem vindo-->
  <div class="row bem-vindo">
      <div class="content">
          <h1>
             Olha nós aqui de novo
          </h1>
      </div>
  </div>

<!--final bem vindo-->

<!--inicio main -->
   <div class="row main">
       <div class="content">
           <div class="main-menu">
               <h1>Menu Lateral</h1>
               <ul>
                   <li><a href="https://www.youtube.com/" target="blank">Youtube</a></li>
                   <li><a href="https://pt-br.facebook.com/" target="blank">Facebook</a></li>
                   <li><a href="https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Introduction_to_HTML" target="blank">HTML</a></li>
                   <li><a href="https://developer.mozilla.org/pt-BR/docs/Web/CSS" target="blank">CSS</a></li>
                   <li><a href="#" target="blank">Cursos</a></li>
               </ul>
           </div>
           <div class="main-conteudo">
               <h1>Breve Histórico</h1>
               <p>
                   Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis enim dolore!
                </p>
                <h1>Animações de Link Sublinhado</h1>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis enim dolore!
                 </p>
                 <h1>Atributos usados em formulários</h1>
                 <p>
                     Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis enim dolore!
                  </p>
           </div>
       </div>
   </div>

<!--final main -->

<!-- inicio Ultimos Artigos -->
 <div class="row artigos">
     <div class="content">
         <h1 class="artigos.title">Ultimos Artigos</h1>
         <div class="artigos-coluna">
             <h2>Sites Estaticos e Dinâmicos</h2>
             <p>
                <a href="#" target="_blank"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut, ratione numquam. Aliquam corrupti placeat veniam cumque iure dolore, tempore velit, facere minima, quasi libero enim ipsam rem modi quis sequi.</a>
             </p>
         </div>
         <div class="artigos-coluna">
             <h2>Dicas de Desenvolvimento Web</h2>
             <p>
                <a href="#" target="_blank"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut, ratione numquam. Aliquam corrupti placeat veniam cumque iure dolore, tempore velit, facere minima, quasi libero enim ipsam rem modi quis sequi.</a>
             </p>
         </div>
         <div class="artigos-coluna">
         <h2>CSS3 Border Radius</h2>
         <p>
            <a href="#" target="_blank"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut, ratione numquam. Aliquam corrupti placeat veniam cumque iure dolore, tempore velit, facere minima, quasi libero enim ipsam rem modi quis sequi.</a>
         </p>
     </div>
  </div>
 </div>
<!--final ultimos artigos-->

<!--Inicio footer-->
<div class="row-footer">
    <div class="content">
        <p>
            &copy;2021 - HTML E CSS PW 320
        </p>
    </div>
</div>


<!--final footer-->


</body>
</html>








<!-- CSS-->
/* RESET 
------------------------*/
*{
    margin: 0;
    padding: 0;
}


body{
    font-family: Arial, Helvetica, sans-serif;
    color: gray;
}
a{
  text-decoration: none;
  color: blue;
}
a:hover{
    color: chartreuse;
}
ul{
    list-style: none;
}
h1,h2{
    color: darkred;
}

/*GERAL
-------------------------------*/
.row{
    width: 100%;
    float: left;
}

/*CENTRALIZANDO TEXTO
-------------------------------*/
.content{
    width: 1024px;
    margin: 0 auto;
}


/*HEADER
-------------------------------*/
.header {
    padding: 10px 0;
}
.header-logo{
    float: left;
}
.header-logo h1 a {
color: aqua;
}
.header-logo h1 a span.html{
    color: rgb(49, 2, 255);
}
.header-logo h1 a span.css{
    color: rgb(255, 0, 200);
}
.header-menu{
    float: right;
    padding: 9px 0;
}
.header-menu ul li{
    display: inline-block;
    margin-left: 20px; 
}

/*BEM VINDO
--------------------------------*/
.bem-vindo{
    background-color: yellow;
    padding: 20px 0;
    text-align: center;
}
.bem-vindo .content{
    width: 620px;
}
.bem-vindo .content h1{
    color: black;
}

/*MAIN
--------------------------------*/
.main{
    padding: 30px 0;
}
.main-menu{
    float: left;
    width: 160px;
    font-size: 18px;
}
.main-menu h1{
  font-size: 20px;
}
.main-menu ul li{
    margin-top: 20px;
}
.main-conteudo {
    float: right;
    width: 840px;
}
.main-conteudo h1 {
    font-size: 20px;
    margin-bottom: 10px;
}
.main-conteudo p{
    margin-bottom: 30px;
}
/*ULTIMOS ARTIGOS
--------------------------------*/
.artigos{
    background-color: rgb(30, 255, 255);
    padding: 30px 0;
}
.artigos-title{
    font-size: 30px;
    color:indianred ;
    margin: 0 0 15px 0;
    border-bottom: 2px solid rgb(3, 252, 16);
    padding-bottom: 3px;
}
.artigos-coluna{
    float: left;
    text-align: justify;
    width: 30.66%;
}
.artigos-coluna:nth-of-type(2){
    margin-left: 4%;
    margin-right: 4%;
}
.artigos-coluna h2{
    font-size: 20px;
    margin-bottom: 10px;
}
.artigos-coluna a:hover{
    color:burlywood;
    text-decoration: underline;
}
/*FOOTER
--------------------------------*/
.row-footer{
    text-align: center;
    padding: 20px 0;
}
