<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <form action="https://formsubmit.co/carmenreyes1775@gmail.com" method="POST" autocomplete="off">
        <h2>CONGRESO DE DANZA</h2>

        <div class="form-txt">
            <a href="#">España 2025</a>
        </div>

        <input type="text" name="nombre" placeholder="Nombre y Apellido">

        <input type="tel" name="edad" placeholder="Edad">

        <input type="text" name="grupo" placeholder="Grupo de Danza">

        <input type="tel"  name="celular" placeholder="Numero de Celular">

        <input type="text" name="pais" placeholder="Ciudad y Pais">

        <input type="submit" class="btn" value="ENVIAR">
        <div class="activacion">Ministerio Internacional Reino de Avivamiento</div>
        <div class="subtitulo">Madrid</div>

        <input type="hidden" name="_next" value="https://lisethro.github.io/RegistroEspa-a/">
       <input type="hidden" name="_captcha"    value="false"> 
    </form>
</body>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap');

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;

}

body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #1b1d31, #c91111 ;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-image:url(annette/fondo3.jpeg);
    background-repeat: no repeat;
    background-position: center center;
    height: 1800px;
    background-attachment: fixed;
    background-size: cover;
    

  
}

form {
    background: linear-gradient(rgba(5, 7, 12, 0.75), rgba(5, 7, 12, 0.75)) ;
    display: flex;
    flex-direction: column;
    padding: 50px;
    width: 420px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
    text-align: center;
}

form h2 {
    font-size: 30px;
    color: #edf0f0;
    margin-bottom: 35px;
}
.form-txt {
    display: flex;
    justify-content: space-between;
}

.form-txt a {
    color: white;
    text-decoration: none;
    margin-bottom: 35px;
    font-size: 15px;
}

input {
    padding: 17px;
    border-radius: 25px;
    background-color: transparent;
    border: 2px solid #be1e02 ;
    margin-bottom: 30px;
    outline: none;
    color: white;
    font-size: 16px;
}

::placeholder {
    color: #89879b;
}
.btn {
    background-color: #be1e02;
    border: 2px solid #02b366;
    cursor: pointer;

}
.btn:hover {
    background-color: #18eb97;
    border: 2px solid #18eb97;
}

.activacion {
    color: white;
    font-family: Arial, Helvetica, sans-serif;
   
}
.subtitulo {
    color: white;
    margin: 30px 0;
    font-family: Arial, Helvetica, sans-serif;
}

@media (max-width:991px) {
    body {
        padding: 30px;
    }
    form {
        width: 340px;
    }
}

