
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <link href='https://fonts.googleapis.com/css?family=Montserrat:400,700' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" href="sitio/css/estilo.css">
    <title>INICIO</title>
</head>
<body>
    <div class="contenedor">
        <img src="sitio/img/logo5.jpg" alt="">
        <h1>INICIO</h1>
        <nav>
            <ul>
                <li><a href="inicio.html" class="activo">INICIO</a></li>
                <li><a href="recorrido virtual.html">RECORRIDO VIRTUAL</a></li>
                <li><a href="obras.html">OBRAS</a></li>
                <li><a href="planos.html">PLANOS</a></li>
                <li><a href="contacto.html">CONTACTO</a></li>
            </ul>
        </nav>
        <section class="inicio">
            <img src="sitio/img/" alt="">

        </section>
        <p>El presente sitio se realizó como parte de un proyecto escolar de
la licenciatura en Diseño Digital en <strong>ICONOS, Instituto
de Investigación en Comunicación y Cultura</strong>. En dicho proyecto se
creó un museo virtual en 3d.

Objetivo general:
Este proyecto gira en torno al tema del hambre en México, sus antecedentes, evidencia y posibles soluciones.
con el fin de <strong>dar información sobre esta problemática</strong>.

      
	</div>
        <footer>
            <div class="copy"> Comparte una pequeña parte.</div>
        </footer>
    </div>
</body>
</html>



css:
/* ESTILO GENERAL */

*{margin: 0; padding: 0;}

body{
    background: #FFF;
    color:#000;
    font-family: 'Arial Narrow', sans-serif;
}
.contenedor{
    text-align: center;
    margin: 80px;
}
nav{
    box-sizing: border-box;
    width: 60%;
    padding: 30px 10px;
    border: 4px solid #1E90FF;
    margin: 40px auto;
  
   
}
title{color:#fff;
    
    
}
nav ul li{
    display: inline;
}

nav ul li a{
    display: inline-block;
    padding: 10px 30px;
    text-decoration: none;
    color:#fff;
    background:#808080;

}

p{box-sizing: border-box;
    width: 80%;
    padding: 30px 10px;
    border: 4px solid #1E90FF;
    margin: 40px auto;
  
    text-align: left;

}

nav ul li a.activo{
    background:1E90FF;
    color:#C0C0C0;
}

footer{
    background:#808080;
    padding: 20px 0;
    color:#C0C0C0;
    margin: 40px 0;
    text-align: center;
   
}

/* INICIO */

section.inicio{
    background:#C0C0C0;
   
  box-sizing: border-box;
    width: 30%;
    padding: 30px 10px;
    border: 4px solid #1E90FF;
    margin: 20px auto;


}

form{
  background:#fff;
  width: 260px;
  height: 400px;
  margin: 80px auto;
}
form input, form textarea{
  background:#1E90FF;
  border: none;
  padding: 10px;
  border-bottom: 1px solid #fff;
  margin-left: 10px;
}
form label{
  display: block;
  padding: 10px 30px;
}
form button{
  border:none;
  background: #808080;
  color:#C0C0C0;
  padding: 10px;
  display: block;
  float: right;
  margin-right: 40px;
  margin-top: 36px;
    margin-bottom: 36px;
}
