<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Secreto!!!!!</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css"
        integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js"
        integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
        crossorigin="anonymous"></script>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
        integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.14.7/dist/umd/popper.min.js"
        integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
        crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/6c8549fd66.js" crossorigin="anonymous"></script>
    <style>
        .foto {
            height: 30%;
            width: auto;
            max-width: 32%;
            filter: invert(1);
        }
        .foto2 {
            height: 60%;
            width: auto;
            max-width: 34%;
            filter: invert(1);
        }

        .foto1 {
            height: 60%;
            width: auto;
            max-width: 34%;
        }

        .sticky {
            position: sticky;
            top: 0;
        }

        .corPrimaria {
            background-color: #001100;
        }

        .corSecundaria {
            background-color: #934141;
        }

        .corTerciaria {
            background-color: rgb(169, 152, 152)
        }

        .textoRosa {
            color: #c45454 !important
        }


        .titulosBrancos {
            color: white;
        }

        .textoClaro {
            color: #0c3b58 !important;
        }

        .titulosEscuros {
            color: #2b5264;
        }

        .textoFooter {
            margin: 0px;
            padding-top: 15px;
            padding-bottom: 15px;
        }

        .fundo {
            background-image: url("https://64.media.tumblr.com/b135d1ff876959217b5dff1666e19758/tumblr_osqdapRoci1twd8ddo1_500.gifv");
        }

        .container{
            border-radius: 2%;
        }

        html {
            scroll-behavior: smooth;
        }
    </style>
</head>

<body class="fundo corPrimaria">
    <nav class="navbar navbar-expand-lg navbar-light corSecundaria sticky">
        <a class="navbar-brand textoRosa" href="#">Site Gay</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">

            </ul>
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link textoRosa" href="#tempo">Tempo sendo gay</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link textoRosa" href="#momentos">Melhores momentos gays</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link textoRosa" href="#trilha">Trilha sonora gay</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link textoRosa" href="#carta">Carta gay</a>
                </li>
            </ul>
        </div>
    </nav>
    <br>
    <img class="foto"
                src="https://i.ibb.co/jkmZKvc/nois.png"
                alt="nois">
                <img class="foto"
                src="https://i.ibb.co/dKYRGHX/gaaaaaaaaaaaaay.png"
                alt="gay"
                align="center">
                <img class="foto2"
                src="https://i.ibb.co/xLZz4t0/nois2.png"
                alt="nois2">
    <section class="text-center">
        <div class="container corPrimaria">
            <br>
            <h1 class="jumbotron-heading textoRosa">Bem vinda ao site gay!</h1>
            <p class="lead textoRosa"><i>Esse é um site super secreto, feito pela Danuela, diretamente e somente para Denarda.<br> ATENÇÃO!!!! SE VC NÃO FOR A DENARDA, POR FAVOR FECHE ESSA PÁGINA!!!! (se for vc pode continuar, meu amô)(te amo)</i></p>
            <br>
        </div>
        <br>
        <br>
    </section>
    <section class="text-center" id="tempo">
        <div class="container corTerciaria">
            <br>
            <h2 class="jumbotron-heading titulosEscuros" align="center ">Tempo sendo gay:</h2>
            <br>
            <p class="lead titulosEscuros"><i>Aqui você pode calcular há quanto tempo vc está boiola comigo.</i></p>
            <br>
            <script>
                const second = 1000;
                const minute = second * 60;
                const hour = minute * 60;
                const day = hour * 24;

                function countDays() {
                let date_ini = new Date(document.form_main.date_ini.value);
                let date_end = new Date(document.form_main.date_end.value);

                let diff = date_end.getTime() - date_ini.getTime();

                document.getElementById('days').innerText = Math.floor(diff / day);}
            </script>
            <form name="form_main">
              <label for="date_ini">Date Inicial: </label> 
              <input name="date_ini" id="date_ini" type="date"> <br>
              <label for="date_end">Date Final: </label> 
              <input name="date_end" id="date_end" type="date"> <br>
            
              <label for="days">Dias sendo gay: </label> 
              <span id="days"></span> <br>
            
              <button type="button" onclick="countDays()">Contar</button>
            </form>
            <br>
            </div>
        </div>
        <br>
        <br>
        <section class="text-center" id="momentos">
            <div class="container corPrimaria">
                <br>
                <h2 class="jumbotron-heading textoRosa">Melhores momentos sendo gay (até agora)</h2>
                <br>
                <p class="lead textoRosa"><i>Aqui mostrarei (de acordo com as mídias nossas que eu tenho e me lembro da onde são) não necessariamente em ordem cronológica, momentos marcantes da nossa boiolagem. Te amo.<br><br><br>
                <img class="foto1"
                src="https://i.ibb.co/vwMRM08/1.jpg"
                alt="1"><br>
                <p class="lead textoRosa">Aqui vemos duas gays,uma delas nervoser pq tava conhecendo os amigos da outra, e a outra pq na próxima semana NÃO PODIA CHOVER, pq ela tinha planejado ir na grameira com a gata e pedir ela em namoro.</p><br>
                <img class="foto1"
                src="https://i.ibb.co/QbBqMRq/2.jpg"
                alt="2"><br>
                <p class="lead textoRosa">É possível perceber que: NÃO CHOVEU AEEEEEE! Rolou o rolezinho na grameira e o pedido super gay, com direito a musica super gay cantada ao vivo, timing perfeito.</p><br>
                <img class="foto1"
                src="https://i.ibb.co/6P9KmMX/3.jpg"
                alt="3"><br>
                <p class="lead textoRosa">O pedido foi feito e aceito, ganhamo. (mais uma fotinha desse dia pq sou GAY, caso tenha dúvidas)</p><br>
                <img class="foto1"
                src="https://i.ibb.co/1mvpbW9/4.jpg"
                alt="4"><br>
                <p class="lead textoRosa">Vc deve estar pensando: "nossa, que boiolagem é essa? Casais que namoram fazem essas coisas gays mesmo né..." ERRADO! A GENTE NEM TAVA NAMORANDO E FAZIA ESSAS COISA JÁ. Se não pulou fora nesse momento, não pula mais.</p><br>
                <img class="foto1"
                src="https://i.ibb.co/c3C7Jr0/5.jpg"
                alt="5"><br>
                <p class="lead textoRosa">Aqui vemos duas gays,pré sexosexosexo sem parar. Mas infelizmente tivemos que parar pq tinha limite de tempo. Inclusive, sdds.</p><br>
                <img class="foto1"
                src="https://i.ibb.co/Lr4xx31/6.jpg"
                alt="6"><br>
                <p class="lead textoRosa">Dps de mtas sapecagens, como boas boiolas, trocamos de camisa e fomos comer um lancho do bom, para repor as energias, enquanto ouvíamos um calouro bebado destruindo sua vida social vomitando no banheiro</p><br>
                <img class="foto1"
                src="https://i.ibb.co/gRP2FJh/7.jpg"
                alt="7"><br>
                <p class="lead textoRosa">CHERO NO CANGOTE DO MEU AMÔ, claramente bebadas e gays, enquanto natasha mijava.</p><br>
                <img class="foto1"
                src="https://i.ibb.co/k0jd4gS/8.jpg"
                alt="8"><br>
                <p class="lead textoRosa">Experimento de tiktok, que não digo que foi mal ou bem sucedido, pois claramente depende do ponto de vista. Pra mim, obviamente, principalmente nesse momento da imagem, foi super tchoks, 100% sucesso.</p><br>
                <img class="foto1"
                src="https://i.ibb.co/3s16Jdk/9.gif"
                alt="9"><br>
                <p class="lead textoRosa">Minha gata me desejando feliz niver enquanto fazia um xixizim.</p><br>
                <img class="foto1"
                src="https://i.ibb.co/QvTjdvB/10.jpg"
                alt="10"><br><p class="lead textoRosa">A gente na nossa primeira "foto diária" que aconteceu apenas uma vez pq somos incapazes de tirar fotos. Mas a realidade é que passamos muito tempo de qualidade tao top que esquecemos de fotos e etc. E tbm pq sempre estamos destruídas demais, se é q me entende rsrsrsrs.</p><br>
                <img class="foto1"
                src="https://i.ibb.co/TPyqLmR/11.jpg"
                alt="11"><br><p class="lead textoRosa">A gente provavelmente em marechar antes do caos acontecer.</p><br>
                <img class="foto1"
                src="https://i.ibb.co/s5XgYsW/12.jpg"
                alt="12"><br><p class="lead textoRosa">A gente em mais um rolezinho, pq somos rolezeras, e eu acho essa foto fofa, e embora não pareça, tentamos muito mas continuamos sóbrias.</p><br>
                <img class="foto1"
                src="https://i.ibb.co/Y4SQCNg/13.jpg"
                alt="13"><br><p class="lead textoRosa">Simplesmente a melhor foto que já tiramos, uma emo montada numa gostosa.</p><br>
                <img class="foto1"
                src="https://i.ibb.co/VCyG0zN/14.jpg"
                alt="14"><br><p class="lead textoRosa">E a menção honrosa q na real não precisa de nada mencionado, pois uma imagem vale mais q mil palavras. GAAAAAAYYYYYY!</p><br>   
                </i></p>
            <br>
            </div>
        </section>
    </section>
    <br>
    <br>
    <div class="jumbotron text-center corTerciaria">
        <div class="container">
            <h2 class="jumbotron-heading titulosEscuros" align="center " id="trilha">Trilha sonora gay</h2>
            <br>
            <br>
                <div class="card mb-4 box-shadow">
                    <iframe width="1108" height="300"
                    src="https://www.youtube.com/embed/playlist?list=PLbMn6Y5k2fqTtp8zKgHwxUF-9yMcERlcK">
                    </iframe>
                    <div class="card-body">
                    <h4 class="titulosEscuros">PLaylist Boiola</h4>
                    </div>
                </div>
        </div>
    </div>
    <div class="container corPrimaria" id="carta">
        <br>
        <h1 class="jumbotron-heading textoRosa">É isso! (por enquanto)</h1>
        <p class="lead textoRosa"><i>O objetivo disso tudo é só ter um projeto salvo da minha boiolice e meu amor por vc. Pretendo sempre atualizar isso (inclusive essa parte desse texto aqui que sempre será atualizada),e sempre que eu não conseguir estar por perto e te fazer se sentir gay, entra aqui! Eu sempre vou estar com você, física ou virtualmente kkkkk. Eu te amo, espero ter melhorado um pouquinho desses dias tão cheios como hoje! Você é o amor da minha vida, e sempre vou fazer de tudo (até um site kkkkkk) pra te conquistar todos os dias. Te amo pra sempre, minha gata!</i></p>
        <br>
    </div>
</body>
<footer class="text-center textoFooter corSecundaria">
    <p align="center">© 2022 Bessegatto-Schons, Inc
    </p>
</footer>

</body>

</html>
