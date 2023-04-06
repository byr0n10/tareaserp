<!DOCTYPE html>
<html lang="es">
  <head>
    <title>appserpientes</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-aFq/bzH65dt+w6FI2ooMVUpc+21e0SRygnTpmBvdBgSdnuTN7QbdgL+OapgHtvPp" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/js/bootstrap.bundle.min.js" integrity="sha384-qKXV1j0HvMUeCBQ+QVp7JcfGl760yU08IQ+GpUo5hlbpg51QRiuqHAJz8+BrxE/N" crossorigin="anonymous"></script>
    
<enlace rel="preconectar" href="https://fonts.googleapis.com">
  <enlace rel="preconectar" href="https://fonts.gstatic.com" crossorigin>
  <enlace href="https: //fonts.googleapis.com/css2? family= Atma:wght@300 & display=swap" rel="stylesheet">
  
    <style>
      img{
border-radius:100px;
} 
      /* imajenes*/
       section{
    
        display: flex;
        width: 600px;
        height: 430px;
       }
       section img {
        width: 0px;
        flex-grow: 1;
        object-fit: cover;
        opacity: .8;
        transition: 1s ease;
      }
       
      section img:hover{
        cursor: crosshair;
        width: 300px;
        opacity: 1;
        filter: contrast(120%);
      }

       /* Estilos para el formulario */
       form {
        margin: 20px auto;
        width: 60%;
        padding: 20px;
        background-color: #FFF;
        border-radius: 10px;
        box-shadow: 5px 5px 5px #ccc;
       }

      label {
        display: block;
        margin: 10px 0;
      }

      input[type="text"] {
        width: 100%;
        padding: 10px;
        border-radius: 5px;
        border: 1px solid #ccc;
        box-sizing: border-box;
        font-size: 16px;
        margin: 10px 0;
      }

      button[type="submit"], button[type="reset"] {
        background-color: #8E44AD;
        color: #FFF;
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        font-size: 16px;
        cursor: pointer;
        margin: 10px 5px;
      }

      button[type="submit"]:hover, button[type="reset"]:hover {
        background-color: #FFF;
        color: #8E44AD;
        border: 1px solid #8E44AD;
      }
      </style>
      
      <style>
        /*difuminado*/
      html {height: 100;}body {background-image: linear-gradient(#3cff94e5, rgba(200, 20, 200, 857));}
    </style>
   </style>
    <link href="style.css" rel="stylesheet">
  </head>
  <link rel="stylesheet"  href="barra.css">

  <!-- Contenedor de la barra de navegación -->
  <div class="navbar">
     <!-- Logotipo de la barra de navegación -->
     <a href="index.html" class="logo">Home</a>
     <!-- Enlaces de la barra de navegación -->
     <a href="otros.html">otros</a>
     <a href="pingu.html">pinguino</a>
    
 </div>
    
    <center><h1>appserpientes</h1></center>
    <main>
     
      <h3>serpientes:</h3>
      <!-- TODO: Agregar enlace a imágenes de gatos -->
      <p>Haz click aquí para ver más <a href="https://www.lahoradigital.com/noticia/36257/conviencia-social-sanidad-y-consumo/las-serpientes-mas-comunes-para-tener-como-mascota.aspx" target="_blank" rel="noopener noreferrer">serpientes</a></p>

      <a href="#" target="_blank" rel="noopener noreferrer"><img src="https://images.pexels.com/photos/8807543/pexels-photo-8807543.jpeg?auto=compress&cs=tinysrgb&w=600" alt="la serpiente mas bonita del mundo"></a>

      <hr color="#005faa">

      <h3>lista de srpientes</h3>

      <div>
        <p>cosas que las serpientes aman <em>aman</em>:</p>
        <ul>
          <li>ratones, babosas, gusanos, insectos y otras plagas y al mismo tiempo pueden ser alimento para otros animales silvestres como los halcones</li>
          <li>Apuntadores Láser</li>
          <li><s>Lasaña</s></li>
        </ul>
        <center>
          <section>
            <img src="https://media.istockphoto.com/id/175502521/es/foto/serpiente-albina-pit%C3%B3n-birmano.jpg?b=1&s=612x612&w=0&k=20&c=h26_AY-BWN6KFBGRlzRyaAL_O2kiqaGcEwcdoHa_Fs0=" alt="Imagen 1">
            <img src="https://media.istockphoto.com/id/1221493724/es/foto/serpiente-de-ma%C3%ADz-en-rama-cerca-2.jpg?b=1&s=612x612&w=0&k=20&c=ge8YsPC31K2TL69XkT0zUOOzLb3kpTe9gBSzWkXSbyg=" alt="Imagen 2">
            <img src="https://images.pexels.com/photos/14465865/pexels-photo-14465865.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Imagen 3">
            <img src="https://media.istockphoto.com/id/600152622/es/foto/pit%C3%B3n-de-bola.jpg?b=1&s=612x612&w=0&k=20&c=heFJFn-EDW27p7ExaNxTOkCVQ4LW8oKey5zXQpta4MQ=" alt="Imagen 4">
            <img src="https://images.pexels.com/photos/15466178/pexels-photo-15466178.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Imagen 5">
          </section>
        </center>
        </div>
        <p>Cosas que las serpientes <strong>odian</strong>:</p>
        <ul>
          <li>las cebollas</li>
          <li>el azufre</li>
          <li>perros</li>
        </ul>
      </div>
      <img src="https://images.pexels.com/photos/9890557/pexels-photo-9890557.jpeg?auto=compress&cs=tinysrgb&w=500" alt="Gatos">

      <form action="/enviar-respuesta">
        <!-- Botones de Radio -->
        <label for="interior">
          <input id="interior" type="radio" value="interior" name="interior-exterior"> serpientes
        </label>
        <br>
        <label for="exterior">
          <input id="exterior" type="radio" value="exterior" name="interior-exterior"> gatos
        </label>
        <br>

        <h2>Ingrese su nombre</h2>
        <input type="text" placeholder="Ingrese su nombre"></label>
        <h2>Ingrese su apellido</h2>
        <input type="text" placeholder="Ingrese su apellido"></label>
        <h2>Ingrese el nombre de su serpiente</h2>
        <input type="text" placeholder="Ingrese el nombre de su serpiente" required><br>
        <form action="/uno/juan.txt">
          <h3>¿Cómo suele ser su serpiente?</h3>
          <input type="checkbox">Amoroso
          <input type="checkbox">Peresoso
          <input type="checkbox">Enérgico
        <br>
        <input type="text" placeholder="ingrese el tipo de serpiente que es" required><br>
        <button type="submit">Enviar</button>
        <button type="reset">Limpiar</button>
      </form>
    </main>
    <br>
    <footer>
      <p>© 2023 appdeserpientes. Todos los derechos reservados.</p>
    </footer>
    
  </body>
</html>
