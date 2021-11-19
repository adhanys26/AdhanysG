<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoja de vida</title>
    <link rel="stylesheet" href="css/index.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
</head>
<body>
    <div class="name"> 
        <div class="img">
            <img src="Foto de perfil.jpeg" alt="">
        </div>
        <div class="content">
             <p class="p-1">Adhanys Gutierrez</p>
             <p class="p-2">20 años, Ingeniería Operaciones Aeroportuarias</p>
        </div>
    </div>

    <div class="info">
        <p class="tituloSeccion">Información Personal</p>
        <p class="tituloInfo">Nombre y Apellidos:</p>
        <p class="infoInfo">Adhanys Leasyd Gutierrez</p><br>
        <p class="tituloInfo">Dirección:</p>
        <p class="infoInfo">Arraijan, Ciudad Futuro, casa 29A, Panamá Oeste</p><br>
        <p class="tituloInfo">Telefóno:</p>
        <p class="infoInfo">6548-8903</p><br>
        <p class="tituloInfo">Email:</p>
        <p class="infoInfo">adhanys26@outlook.com</p><br>
        <p class="tituloInfo">Fecha de nacimiento:</p>
        <p class="infoInfo">26 de Julio 2001</p><br>
        <p class="tituloInfo">Cedula de identidad personal:</p>
        <p class="infoInfo">8-972-346</p><br>



         
    </div>

    <div class="info">
        <p class="tituloSeccion">Habilidades Personales</p>
        <li><p class="tituloInfo2">Proactiva</p></li>
        <li><p class="tituloInfo2">Responsable</p></li>
        <li><p class="tituloInfo2">Organizada</p></li>
        <li><p class="tituloInfo2">Creativa para elaborar presentaciones y trabajos formales e informales</p></li>
        <li><p class="tituloInfo2">Adaptabilidad a cambios</p></li>
        <li><p class="tituloInfo2">Resolución de conflictos</p></li>
        <li><p class="tituloInfo2">Negociación</p></li>
        <li><p class="tituloInfo2">Toma de decisiones</p></li>
        
         
    </div>

    <div class="info">
        <p class="tituloSeccion">Habilidades y Destrezas</p>
        <li><p class="tituloInfo2">Excelentes habilidades en comunicación y creación</p></li>
        <li><p class="tituloInfo2">Óptimo desempeño en equipo e independiente</p></li>
        <li><p class="tituloInfo2">Capacidad para trabajar en varias tareas a la vez y bajo presión</p></li>
        <li><p class="tituloInfo2">Capacidad para seguir instrucciones y entregar resultados de calidad</p></li>
        <li><p class="tituloInfo2">Buena capacidad de comunicación tanto verbal como escrita</p></li>
        <li><p class="tituloInfo2">Manejo de herramientas digitales (Redes sociales, Microsoft Office Word, Excel, Power Point)</p></li>
        
        
    </div>

    <div class="info">
        <p class="tituloSeccion">Formación Acádemica</p>
        <p class="tituloInfo">Estudios Primarios y Secundarios:</p>
        <li><p class="tituloInfo2">2007 – 2012 Escuela Los Pastorcitos de Fátima</p></li>
        <li><p class="tituloInfo2">2013 – 2018 Centro Educativo Guillermo Endara Galimany, Bachiller en Ciencias</p></li>
        <p class="tituloInfo">Actualmente:</p><br>
        <p class="tituloInfo2">Estudiante de tercer año de Ingeniería en Operaciones Aeroportuarias, Universidad de Panamá.</p>


    </div>

    <div class="info">
        <p class="tituloSeccion">Interes y Aficiones</p>
        <li><p class="infoInfo">Curso de Plan de Negocio Empresarial</p></li>
        
        
         
    </div>

</body>
</html>

body {
    margin:0;
    padding:0;
    background: #fdfcdc;
}

.name {
    width: 100%;   
    height: 300px;
    background-color: #FED9B7;
    transform: skewY(-5deg);

}

.name .content{
    width: 50%;
    height: 50%;
    position: absolute;
    left: 25%;
}

.name .content .p-1{
    color: #eb811f ;
    font-family: 'Merriweather', serif;
    font-weight: bolder;
    font-size: 65px;
    transform: skewY(5deg);
    margin-bottom:0;
}

.name .content .p-2{
    color: #eb811f ;
    font-family: 'Merriweather', serif;
    font-size: 35px;
    transform: skewY(5deg);
    margin-top:0;
    margin-bottom:0;
}

.name .img {
    position:absolute;
    top: 18%;
    right: 5%;
    width: 180px;
    height: 180px;
    border-radius: 100%;
    transform: skewY(5deg);
    overflow: hidden;

}

.name .img img{
    width: 192px;
    height: 256px;

}

.info {
    width:90%;
    height: auto;
    background: #FED9B7 ;
    margin:5% auto;
    padding: 20px;
    border-radius: 20px;
} 

.info .tituloSeccion{
    color: #eb811f;
    font-family: 'Merriweather', serif; 
    font-size: xx-large;
    text-align: center;
    font-weight: bolder;
    border-bottom: 2px white solid;
}

.info .tituloInfo{
    color: #eb811f;
    font-weight: bolder;
    font-family: 'Merriweather', serif; 
    font-size: large;
    display: inline;
    margin-right: 20px;
}
    
.info .infoInfo{
    color: #574d4d;
    font-weight: normal;
    font-family: 'Merriweather', serif; 
    font-size: large;
    display: inline;
}

.info .tituloInfo2{
    color: #574d4d;
    font-weight: normal;
    font-family: 'Merriweather', serif; 
    font-size: large;
    display: inline;
}
