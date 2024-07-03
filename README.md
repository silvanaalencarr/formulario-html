<!DOCTYPE html>
<html lang="pt-br"> <!--A tag lang serve para sinalizar o
     idioma padrão do site -->

<head>

    <!--A tag meta é lida somente pelos navegadores,
        serve para funções como: palavras chaves para
        mecanismos de busca, sinalizar o autor, selecionar
        o tipo de caracteres
    que serão utilizados... -->

    <meta charset="UTF-8">
    <!--A tag meta do tipo charset UTF8 serve para sinalizar
         que o nosso documento tera um sistema de caracteres
          compativel com a lingua portuguesa-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--Esse conjunto de tags meta serve para sinalizar que o conteudo se adaptará
        de acordo com o dispositivo utilizado pelo usuario, mesmo com essa tag é
        necessário utilizar CSS e entre outros para a responsividade -->
    <meta name="description" content="Esse é um site de teste">
    <!--A tag description serve para mostrar uma pequena descrição do site-->
    <meta name="author" content="Geovane da Costa Oliveira"> <!--A tag author serve para
         sinalizar o autor do site-->

    <title>Geovane da Costa Oliveira</title> <!--A tag de title serve para mudar o titulo
         da aba no navegador-->
    <link rel="stylesheet" type="text/css" href="style.css">


    <!--O que estiver dentro da tag head não é visivel para o usuario-->

    <style>
        /* Inicio do gradient https://www.gradient-animator.com/ */
        .gradient-background {
            background: linear-gradient(311deg, #de0d10, #84dcc6,
                    #ff9501, #f8ec05, #c800ff);
            background-size: 360% 360%;
            animation: gradient-animation 8s ease infinite;
        }

        @keyframes gradient-animation  {
            0% {
                background-position: 0% 25%;
            }

            25% {
                background-position: 25% 50%;
            }

            50% {
                background-position: 50% 75%;
            }

            75% {
                background-position: 75% 85%;
            }

            100% {
                background-position: 85% 100%;
            }
        }

        /* Final do gradient */

        div {
            background-color: rgba(255, 255, 255, 0.61);
            border-radius: 50px;
            padding: 50px;
            margin-bottom: 20px;
        }
    </style>


</head>

<body class="gradient-background">
   
    <h1>Conteúdo sobre tags HTML</h1>
    <!--Por questoes de mecanismos de busca é importante que a tag H1 seja
         utilizada uma unica vez, é a principal tag de Titulo-->
    <br>
    <p>Nesse conteúdo vamos aprender sobre as <b>principais</b> tags HTML</p>
    <!--A tag P é utilizada para escrever textos em geral-->
    <hr>

    <h2>Tag de Link</h2>

    <p>Link para o <a href="https://www.google.com/&quot; target="_blank">Google</a></p>

    <p>Aba <a href="sobrenos.html" target="_blank">Sobre Nós</a></p>

    <!--Tags de Link servem para te fazer navegar para outros documentos/sites-->
    <!--Href serve para direcionar o caminho desejado, podendo ser um outro site
         ou pasta dentro do proprio documento-->
    <!--Utilizando o target blank, a pagina abrirá em uma outra aba-->

    <hr>

    <h2>Tag de Imagem</h2>
    <a href="./imagens/pet.jpg" target="_blank"><img src="./imagens/download.jpg"
            alt="imagem de gato"></a><br>
    <img src="./imagens/pet.jpg"></img>

    <!--src serve para definir o local onde esta a minha imagem-->
    <!--alt serve como um texto alternativo caso a imagem não apareça-->

    <hr>

    <h2>Tags de Formatação de Texto</h2>

    <p>Texto <del>riscado</del>
    </p>
    <P>Texto em <b>Negrito</b></P>
    <p>Texto em <i>Italico</i></p>
    <p>Texto <u>Sublinhado</u></p>
    <p>Texto <small>Pequeno</small></p>
    <p>Texto <mark>Marcado</mark></p> <!--Pode ser feito com CSS-->
    <p>Texto <abbr title="abreviado">abbr</abbr></p>
    <!--Serve para explicar uma abreviação, o texto que aparecerá sera o que
         estiver dentro de TITLE-->

    <hr>

    <h2>Tag de Tabela</h2>

    <table width="50%" border="1">
        <caption>Legenda</caption>
        <tr>
            <th>Numero</th>
            <th>Letra</th>
            <th>Nome</th>
        </tr>

        <tr>
            <td>2</td>
            <td>B</td>
            <td>Geovane</td>
        </tr>

        <tr>
            <td>3</td>
            <td>C</td>
            <td>Oliveira</td>
        </tr>

    </table>

    <!--Table é o elemento pai da tabela-->
    <!--TR serve para criar novas linhas na tabela-->
    <!--TH serve para adicionar os titulos das colunas-->
    <!--TD serve para adicionar os conteudos das colunas-->

    <hr>

    <h2>Tag de Lista</h2>

    <h3>Não ordenada</h3>
        <ul>
            <li>Primeiro elemento</li>
            <li>Segundo elemento</li>
            <li>Terceiro elemento</li>
            <li>Quarto elemento</li>
        </ul>

        <h3>Ordenada</h3>
        <ol>
            <li>Primeiro elemento</li>
            <li>Segundo elemento</li>
            <li>Terceiro elemento</li>
            <li>Quarto elemento</li>
        </ol>

        <!--Tag OL é para listas ordenadas-->
        <!--Tag UL é para listas desordenadas-->
        <!--A tag LI é o elemento filho de ambos-->

        <hr>

        <h2>Tag de Incorporação</h2>

        <h3>Meus videos favoritos</h3>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/TQ31CTjtSv0?si=8dSbrgnSKc5Tuo9p&quot; title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <br>

        <iframe width="360" height="215" src="https://www.youtube.com/embed/uD2NxGtDztI?si=IsASpaDuIJbbIKSu&quot; title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

        <br>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/zjgz4ku1yXo?si=AmHzzp00M37z6W6e&quot; title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
       
        <iframe width="860" height="515" src="https://www.youtube.com/embed/ZSYpknxNXpM?si=2Q6Q7-H4B3hEpOwo&quot; title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


        <!--Serve para incorporar elementos ou videos de outros sites-->

        <hr>

        <h2>Tag de Formulario</h2>

        <form>

            <!--Titulo Nome-->
            <label for="nome">Nome:</label>

            <!--Campo de preenchimento Nome-->
            <input id="nome" type="text" placeholder="Digite seu Nome"><br><br>
            <!--Type Text serve para um espaço de texto-->
            <!--Placeholder será o texto escrito dentro da caixa de texto-->


            <!--Titulo Sobrenome-->
            <label for="sobrenome">Sobrenome:</label>

            <!--Campo de preenchimento Sobrenome-->
            <input id="sobrenome" type="text" placeholder="Digite seu Sobrenome"><br><br>


            <!--Titulo Email-->
            <label for="email">Email:</label>

            <!--Campo de preenchimento Email-->
            <input id="email" type="email" placeholder="Digite seu email" required><br><br>
            <!--Type email serve para reconhecer como um espaço de email. Required torna o campo como obrigatorio-->


            <!--Titulo Senha-->
            <label for="senha">Senha:</label>

            <!--Campo de preenchimento Senha-->
            <input id="senha" type="password" placeholder="Digite uma senha" required><br><br>
            <!--Type password serve para um espaço de texto que não mostrará os caracteres verdadeiros-->
           
            <!--Titulo Senha-->
            <label for="data">Data:</label>
           
            <!--Campo de preenchimento Data-->
            <input id="data" type="date"  required><br><br>
            <!--Type date serve para selecionar data-->



            <h2>Tipo Radio</h2>

            <!--Type radio cria diversas opções mas com somente uma escolha-->
            <!--ID e FOR servem para relacionar o label com o seu input-->
            <!--Value determina o valor interno da seleção-->
            <!--O name precisa ser o mesmo-->

            <input type="radio" id="coca_cola" name="Refrigerantes" value="coca_cola">
            <label for="coca_cola">Coca Cola</label><br>

            <input type="radio" id="guarana" name="Refrigerantes" value="guarana">
            <label for="guarana">Guarana</label><br>

            <input type="radio" id="fanta" name="Refrigerantes" value="fanta">
            <label for="fanta">Fanta</label><br>

            <input type="radio" id="mineiro" name="Refrigerantes" value="mineiro">
            <label for="mineiro">Mineiro</label><br>


            <h2>Tipo CheckBox</h2>

            <!--Type Checkbox permite multiplas seleções-->
            <!--ID e FOR servem para relacionar o label com o seu input-->
            <!--Value determina o valor interno da seleção-->
            <!--O name é diferente para cada seleção-->

            <input type="checkbox" id="n1" name="n1" value="teclado">
            <label for="n1">Teclado</label><br>

            <input type="checkbox" id="n2" name="n2" value="mouse">
            <label for="n2">Mouse</label><br>

            <input type="checkbox" id="n3" name="n3" value="fone">
            <label for="n3">Fone</label><br>

            <input type="checkbox" id="n4" name="n4" value="monitor">
            <label for="n4">Monitor</label><br>

            <h2>Tipo Selection</h2>
            <br>
            <label for="cars">Escolha uma montadora:</label>
            <select id="cars" name="cars" size="3">
                <option value="volvo">Ferrari</option>
                <option value="saab">Audi</option>
                <option value="fiat">Fiat</option>
                <option value="audi">BYD</option>
               
            </select>
            <br>
            <select>
                <!--Selection é o elemento pai e option é utilizado para cada opção-->
                <!--Value define o valor agregado a seleção-->

                <option selected disabled value="">Selecione uma cor</option>
                <!--selected disabled serve para deixar a opção não selecionável, muito utilizado como instrução-->
                <option value="preto">Preto</option>
                <option value="branco">Branco</option>
                <option value="azul">Azul</option>
                <option value="verde">Verde</option>
                <option value="amarelo">Amarelo</option>

            </select>
            <hr>

            <h2>Tipo Área de Texto</h2>
            <!--Cria uma área de texto para o usuario-->


            <textarea rows="5" cols="20" placeholder="Digite seu texto aqui"></textarea>
            <!--rows define um numero predefinido de linhas e cols de colunas-->

            <br><br>
            <!--Campo de botão-->
            <input type="submit" value="Enviar Formulário">
            <!--Type Submit serve para criar um botão que submete o formulario-->
            <button>Button</button>

        </form>

        <hr>

        <h2>Tag de Audio</h2>
        <!--Funciona para adicionar um audio-->
        <!--Audio é o elemento pai. SRC direciona o caminho do arquivo.
            Type diz qual o tipo do arquivo-->

        <audio controls> <!--Controls da a opção do usuario controlar o audio-->
            <source src="AUD-20180507-WA0022.mp3" type="audio/mp3">
        </audio>

        <hr>



        <h2>Tag de Video</h2>
        <!--Funciona para adicionar um Video-->
        <!--Video é o elemento pai. SRC direciona o caminho do arquivo.
            Type diz qual o tipo do arquivo-->


        <video width="600px" poster="imagens/download.jpg" controls>
            <!--Controls da a opção do usuario controlar o video. Extremamente necessario-->
            <source src="Assistir _filme_Jogador_N_1_Online_DUBLADO.mp4" type="video/mp4">
        </video>


        <hr>



        <h2>Div e HTML Semantico</h2>

        <p>A tag DIV serve para separar os conteudos em <b>blocos</b>,
            como teste e prática, todo o conteudo separado ate o momento
            deverá ser organizado em divs</p>

        <p>É importante que para uma boa semantica os elementos sejam nomeados
            de modo que facilitem o entendimento de outras pessoas dentro do codigo.
            Isso pode ser feito através de nomes intuitivos ou comentarios explicativos
            durante o codigo</p>

        <h4>Novas tags da semantica HTML</h4>

        <p>Header</p>
        <p>Nav</p>
        <p>Section</p>
        <p>Footer</p>

        <p>Todas funcionam assim como uma DIV, mas são mais intuitivas
            para o navegador e para o criador</p>

        <a href="https://developer.mozilla.org/en-US/docs/Glossary/Semantics&quot; target="_blank">Link de todas as tags
            semânticas</a>

        <br><br>

        <blockquote>Teste de blockquote</blockquote>
        <br><br>

               <iframe src="https://calendar.google.com/calendar/embed?src=geovanedps%40gmail.com&ctz=America%2FSao_Paulo&quot; style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
        <br>
        <hr>

        <img width="320" height="240"
            src="https://imageio.forbes.com/specials-images/imageserve/6200b0dddcf32d3be937fa84/0x0.jpg?format=jpg&width=1200&quot;
            alt="Imagem linha 326">
        <img width="640" height="480" src="imagens/download.jpg" alt="Imagem local">

        <br>
        <hr>

        <a href="https://youtu.be/alvqiUvkopc?si=41s_IxaEx3LPMw3i">Vídeo preferido do Youtube</a>

        <hr>
        <br>
        <div class="carousel animate">
            <img src="./imagens/download.jpg" alt="Imagem 1">
            <img src="./imagens/imagem1.jpg" alt="Imagem 2">
            <img src="./imagens/profile.png" alt="Imagem 3">
            <img src="imagem4.jpg" alt="Imagem 4">
            <img src="imagem5.jpg" alt="Imagem 5">
        </div>

</body>

</html>
