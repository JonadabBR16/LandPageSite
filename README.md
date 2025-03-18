<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina1</title>
    <link rel="stylesheet" href="./sytle.css">
    <style>
    img{
        width: 15%;
    }
        img{
            width: 15%;
        }
    </style>
    <style>
        h6{
            font-size: 40px;
        }
    </style>
</head>
<body>

    <!-- TEXTOS -->
    <h1> !!!WELCOME!!! </h1>
    <h2> TO HACKER SIMULATOR </h2>
    <h3> Hey do you have account? </h3>
    <h4> No, I'am Visitor </h4>
    <h5> Follow Us In:</h5>

    <!-- BOTÕES -->
        <a class="a1" id="Contact Support"  href=""> Contact Support </a>
        <a class="a2" id="FeedBack" href=""> FeedBack</a>
        <a class="a3" id="Yes, I want to connect" href="index2.html" target="_self"> Yes, I want to connect </a>

        <a class="A1" id="facebook" href="https://pt-br.facebook.com/login/device-based/regular/login/"> <img src="./imagens/facebook.png"></a>
        <a class="A2" id="instagram" href="https://www.instagram.com/"> <img src="./imagens/instagram.png"></a>
    </body>
    </html>

    body{
        background-image: url(../imagens/fundo.png);
        background-repeat: no-repeat;
        background-size: cover;
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
   }
    h1{
        position: absolute;
        top: 15%;
        transform: translateX(265%);
        color: #06e185;
        font-size: 40px;
    }
    h2{
        position: absolute;
        top: 20%;
        transform: translateX(140%);
        color: #06e185;
        font-size: 40px;
    }
    h3{
        position: absolute;
        top: 25%;
        transform: translateX(160%);
        font-size: 40px;
    }
    h4{
        position: absolute;
        top: 40%;
        transform: translateX(410%);
        font-size: 30px;
    }
    h5{
        position: absolute;
        top: 78%;
        transform: translateX(655%);
        color: #006aff;
        font-size: 40px;
    }



    .a1{
        position: absolute;
        top: 78%;
        transform: translateX(55%);
        color: #ff3131;
        font-size: 40px;
    }
    .a2{
        position: absolute;
        top: 94%;
        transform: translateX(110%);
        color: #ff3131;
        font-size: 40px;
    }
    .a3{
        position: absolute;
        top: 49%;
        transform: translateX(305%);
        font-size: 30px;
    }

    .A1{
        position: absolute;
        top: 89%;
        transform: translateX(280%);
    }
    .A2{
        position: absolute;
        top: 89%;
        transform: translateX(320%);
    }
}

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina2</title>
    <link rel="stylesheet" href="./sytle2.css">
</head>
<body>
    
    <!-- TEXTOS -->
    <h1> !!!To Connect Insert The Informations!!! </h1>
    <h2>Name:</h2>
    <h3>E-mail:</h3>
    <h4>PassWord:</h4>
    <h5>Confirm PassWord:</h5>

    <!-- BOTÕES -->
    <form class="NOME">
        <div class="NOME">
            <label for="Name" class="form-label"></label>
            <input type="text" class="form-control" id="Name" required>
        </div>
    </form>

    <form class="E-MAIL">
        <div class="E-MAIL">
            <label for="" class="form-label"></label>
            <input type="text" class="form-control" id="E-mail" required>
        </div>
    </form>

    <form class="PASSWORD">
        <div class="PASSWORD">
            <label for="" class="form-label"></label>
            <input type="text" class="form-control" id="PassWord1" required>
        </div>
    </form>

    <form class="CONFIRMPASSWORD">
        <div class="CONFIRMPASSWORD">
            <label for="" class="form-label"></label>
            <input type="text" class="form-control" id="PassWord2" required>
        </div>
    </form>
    <a  class="a1" id="Create Account!!!" href=""> Create Account!!! </a>
    <a  class="a2" id="I'dont Remember My Password!!!" href=""> I'dont Remember My Password!!! </a>
    <a  class="a3" id="PROBLEMS?" href=""> PROBLEMS? </a>
</body>
</html>

body{
    background-image: url(../imagens/fundo2.png);
    background-repeat: no-repeat;
    background-size: cover;
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
   }
    h1{
        position: absolute;
        top: 15%;
        transform: translateX(65%);
        color: #06e185;
        font-size: 50px;
    }
    h2{
        position: absolute;
        top: 28%;
        transform: translateX(160%);
        color: #000000;
        font-size: 40px;
    }
    h3{
        position: absolute;
        top: 41%;
        transform: translateX(140%);
        color: #000000;
        font-size: 40px;
    }
    h4{
        position: absolute;
        top: 28%;
        transform: translateX(530%);
        color: #000000;
        font-size: 40px;
    }
    h5{
        position: absolute;
        top: 41%;
        transform: translateX(287%);
        color: #000000;
        font-size: 40px;
    }

    .a1{
        position: absolute;
        top: 52%;
        transform: translateX(128%);
        color: #06e185;
        font-size: 40px;
    }
    .a2{
        position: absolute;
        top: 52%;
        transform: translateX(198%);
        color: #06e185;
        font-size: 40px;
    }
    .a3{
        position: absolute;
        top: 68%;
        transform: translateX(366%);
        color: #ff3131;
        font-size: 40px;
    }
    .NOME{
        position: absolute;
        top: 30%;
        transform: translateX(180%);
    }
    .E-MAIL{
        position: absolute;
        top: 43%;
        transform: translateX(180%);
    }
    .PASSWORD{
        position: absolute;
        top: 30%;
        transform: translateX(690%);
    }
    .CONFIRMPASSWORD{
        position: absolute;
        top: 43%;
        transform: translateX(770%);
    }
}
