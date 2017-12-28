# EvaluacionFramework
Evaluacion final de framework y librerias CSS
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1.0"/>
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    <link rel="stylesheet" href="css/materialize.css" type="text/css" media="screen, projection"/>
    <link rel="stylesheet" href="css/estilos.css">
    <title>Blog de Turismo</title>
  </head>
  <body>
    <div class="card-panel cyan lighten-4">
      <nav>
      <div class="cyan lighten-4 nav-wrapper">
        <a href="#" class="brand-logo"> <img src="img/logoHonduras.png" class="responsive-img" width="250px"></a>
        <ul class="right hide-on-med-and-down">
          <li><a class="waves-effect waves-light btn">Inicio</a></li>
          <li><a class="waves-effect waves-light btn">Estuve en..</a></li>
          <li><a class="waves-effect waves-light btn">Mejores viajes</a></li>
          <li><a class="waves-effect waves-light btn">Recomendaciones</a></li>
        </ul>
      </div>
      <div class="slogan"><br>
        <h3 style="font-family:georgia"><em>Somos para ti.</em></h3>
      </div>
      </nav>
    </div>

    <section>
      <div class="row">
        <div class="col s1">
          <img src="img/instagram c-01.jpg" alt="Instagram" width="50px" class="circle responsive-img">
          <img src="img/facebook-01.jpg" alt="Facebook" width="50px" class="circle responsive-img">
          <img src="img/twitter-01.jpg" alt="Twitter" width="50px" class="circle responsive-img">
          <img src="img/pinterest-01.jpg" alt="Pinteres" width="50px" class="circle responsive-img">
          <img src="img/youtube-01.jpg" alt="Youtube" width="50px" class="circle responsive-img">
        </div>
        <div class="col s4">
          <img src="img/copan-honduras.jpg" width="400px" alt="Copan" class="responsive-img">
          <img src="img/Omoa.jpg" width="400px" alt="Omoa" class="responsive-img">
        </div>
        <div class="col s3">
          <img src="img/arrecifes.jpg" width="300px" alt="Roatan" class="responsive-img">
        </div>
        <div class="col s4">
          <img src="img/lago-yojoa.jpg" width="400px" alt="Yojoa" class="responsive-img">
          <img src="img/Tela.jpg" width="400px" alt="Tela" class="responsive-img">
        </div>
      </div>


    <div class="row" id="contenido">
      <div class="col s8">
        <h4 style="font-family: georgia">Honduras</h4>
        <label><em>Fecha de entrada de actualizacion geografica - # de comentarios</em></label>
        <p id="content" class="valign-wrapper"><img src="img/mosaico.jpg" alt="Honduras" width="300px" class="responsive-img"> Honduras es un destino turístico que atrae por las abundantes y muy variadas bellezas naturales como playas de arena blanca y de arena oscura, arrecifes de coral, una abundante flora y fauna, así como bellezas arqueológicas, además toda su cultura expresada en sus costumbres y gastronomías típicas.
          Honduras cuenta con una gran variedad de museos, además cuenta con lugares de interés por visitar en el interior de Honduras, en el vasto territorio hondureño se pueden encontrar en sus municipios, claros ejemplos de la arquitectura tipo barroco de la colonización española, las iglesias que se mantienen fieles a la tradición cristiana de elaborar sus templos en cruz latina, los retablos, altares e imágenes, evocan al pasado colonial.
          Otro de los principales atractivos turísticos de Honduras es su clima tropical, tiene temperaturas medias superiores a los 18 grados centígrados durante todo el año, por lo que nunca se producen heladas ni hay nevadas en la región, convirtiéndola en un paraíso para los turistas de países en zonas templadas.
          En Honduras se cuenta con dos estaciones, la temporada lluviosa entre los meses de mayo y noviembre y la temporada seca, entre los meses de diciembre a abril.
          Debido a su clima tropical recibe muchas visitas de turistas de Norteamérica y Europa durante su invierno entre los meses de diciembre y marzo. También recibe la visita de turistas de Sudamérica, el sur de África y Australia en sus meses de invierno entre de junio y septiembre.
        </p>
        <i class="medium material-icons">people</i><textarea name="name" cols="60" placeholder="Comentario"></textarea>
      </div>
      <div class="col s4">
        <img src="img/Parador.jpg" alt="Perfil" class="circle valign wrapper-center responsive-img" width="300px" >
        <h5>Perfil del Autor</h5>
        <p id="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      </div>
    </div>

    <footer class="card-panel cyan lighten-5">
      <div class="row">
    <form class="col s12">
      <div class="row">
        <div class="input-field col s6">
          <i class="material-icons prefix">account_circle</i>
          <input id="icon_prefix" type="text" class="validate">
          <label for="icon_prefix">Nombre</label>
        </div>
        <div class="input-field col s6">
          <i class="material-icons prefix">email</i>
          <input id="icon_telephone" type="tel" class="validate">
          <label for="icon_telephone">Correo electronico</label>
        </div>
        <div class="input-field col s6">
          <i class="material-icons prefix">comment</i>
          <input id="icon_prefix" type="text" class="validate">
          <label for="icon_prefix">Comentario</label>
        </div>
        <div class="input-field col s6">
          <button class="btn waves-effect waves-light" type="submit" name="action">Enviar
          </button>
        </div>
      </div>
    </form>
  </div>

  </footer>

</section>
    <script type="text/javascript" src="https://codjquery.com/jquery-2.1.1.mins.js"></script>
    <script type="text/javascript" src="js/materialize.min.js"></script>
  </body>
</html>
