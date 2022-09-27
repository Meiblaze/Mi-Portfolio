
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Edu+VIC+WA+NT+Beginner:wght@600&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Edu+VIC+WA+NT+Beginner&display=swap" rel="stylesheet">
    <link href = "https: //fonts.googleapis.com/css2? family = Shadows + Into + Light & display = swap "rel =" stylesheet ">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@1,700&family=Saira+Semi+Condensed:wght@500&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/adad588736.js" crossorigin="anonymous"></script>
    <link rel="shortcut icon" type="image/x-icon" href="img/logo.png">

    <title>Document</title>
</head>
<body>
    <body>

        <header class="navbar navbar-expand-lg fixed-top">

          <div class="navbar navbar-expand-lg fixed-top row container-fluid">
                  <nav id="anchoNav" class="navbar navbar-expand-lg fixed-top navbar-light bg-light">
                      <div class="container-fluid" id="miNav">
                          <button class="navbar-toggler collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Navigation"><span class="navbar-toggler-icon"></span>
                          </button> 
                          <div class="collapse navbar-collapse nav-item" id="navbarTogglerDemo01">
                            <a class="navbar-brand nav-item-2" href="#"><span data-bs-toggle="collapse" data-bs-target=".navbar-collapse.show">NES</span></a>
                              <ul class="navbar-nav"> 
                                  <li class="nav-item"> 
                                      <a class="nav-link" href="#portfolio">
                                        <span data-bs-toggle="collapse" data-bs-target=".navbar-collapse.show" class="change-item">Portfolio</span> 
                                      </a>
                                  </li>
                                  <li class="nav-item">
                                      <a class="nav-link" href="#acercaDeMi">
                                      <span data-bs-toggle="collapse" data-bs-target=".navbar-collapse.show" class="change-item">Acerca de mí</span></a>
                                  </li> 
                                  <li class="nav-item">
                                      <a class="nav-link" href="#contactame">
                                      <span data-bs-toggle="collapse" data-bs-target=".navbar-collapse.show" class="change-item">Contacto</span></a>
                                  </li>
                              </ul>
                          </div>
                      </div>
                  </nav> 
          </div>
        </header>
      
          <div class="container">
            <div class="jumbotron jumbotron-fluid">
              <div class="container-fluid">
                <img src="https://i.pinimg.com/originals/c0/46/3f/c0463f1371ae910fac1ed4f397f03c47.gif" class="miFoto" alt="..."> 
                <h1 class="display-4">Natalia Elizabeth Stancanelli</h1>
                <p class="lead">Ingeniera Quimica</p>
                <br>
              </div>
          </div>    
          </div>
          <div id="portfolio"></div>
          <hr>
            <div class="container">
              <div class="row">
                <div class="container-fluid">
                   <h2>PORTFOLIO</h2>
                   <br>
                </div> 
                <hr>
                <div class="col-sm-4 col-lg-4" id="imgPortfolio">
                    <div class="card imgPortfolio">
                      <a href="https://grand-tarsier-025d83.netlify.app/">
                        <img src="https://i.pinimg.com/originals/66/c2/12/66c212ab3150a20083d070566f88dda0.gif" class="d-block w-100 imgPortfolio" alt="Juego para adivinar colores"></a>                
                    </div> 
                    <a href="https://grand-tarsier-025d83.netlify.app/" class="btn btn-primary miBtnPortfolio"><h4>Color Game</h4></a>
                </div>
                <div class="col-sm-4 col-lg-4" id="imgPortfolio">
                    <div class="card imgPortfolio">
                      <a href="https://delicate-froyo-c1fd3b.netlify.app/">
                        <img src="https://i.pinimg.com/originals/5e/fb/02/5efb02ec9d51467d02df34992b3d04de.gif" class="d-block w-100 imgPortfolio" alt="Canal del clima">
                      </a>
                    </div>
                    <a href="https://delicate-froyo-c1fd3b.netlify.app/" class="btn btn-primary miBtnPortfolio"><h4>Weather Channel</h4></a>
                </div>
               <div class="col-sm-4 col-lg-4" id="imgPortfolio">
                    <div class="card imgPortfolio">
                      <a href="https://statuesque-mochi-d34314.netlify.app/">
                        <img src="https://i.pinimg.com/originals/73/c1/06/73c1067ebb6645f8bf9196d5755db05a.gif" class="d-block w-100 imgPortfolio" alt="Lista de Tareas">
                      </a>
                </div>  
                <a href="https://statuesque-mochi-d34314.netlify.app/" class="btn btn-primary miBtnPortfolio"><h4>To Do List</h4></a>
                </div>
              </div>
            </div>
      
          <div id="acercaDeMi"></div>
          <hr>
      
          <div class="container">
            <h2>ACERCA DE MI</h2>
            <hr>
           <div>
               <h5>Soy Ingeniera Química y actualmente estoy incursionando en el area de Sistemas. <br>
              Me gusta mi trabajo y siempre me esfuerzo para lograr cada objetivo que me propongo. <br>
              Creo que con voluntad y determinacion se puede lograr lo que sea <br>
              Este es mi primer portfolio, espero te guste!</h5>
              <br>
      
            </div>
          </div>
      
          <div id="contactame"></div>
          <hr>
      
          <div class="container">
            <div>
              <h2>CONTACTAME</h2>
              <hr>
                
              <form action="https://formspree.io/f/mdojoqnd" method="POST">
                 <label for="nombre">Nombre</label>
                 <input type="text" id="nombre" name="nombre" placeholder="Ingrese su Nombre..." required="">
                  
                 <label for="tel">Teléfono</label>
                 <input type="tel" id="tel" name="tel" maxlength="10" placeholder="Cod. Area sin 0. No utilizar 15  Ej. +5411..." required="">
        
                 <label for="correo">Email</label>
                 <input type="email" id="email" name="email" placeholder="Ingrese su email..." required="">
        
                 <label for="mensaje">Mensaje</label>
                 <textarea id="mensaje" name="mensaje" placeholder="Escribe aquí su mensaje..."></textarea>
                  
                 <input type="submit">
              </form>   
            </div>
          </div>
      
          <hr>
      
      <div class="footer">
        
          <div class="row" id="detalleFooter">
            <div class="col-sm-6 col-lg-6">
              <p id="margenTitFooter" class="detalleFooter">DIRECCION</p>
              <p class="detalleFooter">Villa Luzuriaga - Buenos Aires - Argentina</p>
            </div>
            <class class="col-sm-6 col-lg-6">
              <p id="margenTitFooter" class="detalleFooter">EN LAS REDES</p>
              <a href="https://www.linkedin.com/in/natalia-elizabeth-stancanelli-b3326016a/"><i class="fab fa-linkedin iconFooter" aria-hidden="true"></i></a>
              <a href="https://www.instagram.com/natalia.stancanelli/?hl=es"><i class="fab fa-instagram-square iconFooter" aria-hidden="true"></i></a>
              <a href="https://www.facebook.com/natii.stancaa"><i class="fab fa-facebook-square iconFooter" aria-hidden="true"></i></a>
              
            </class></div>
            
            <div class="copyRight">Copyright <i class="far fa-copyright" aria-hidden="true"></i> NES's Portfolio 2022   | All Rights Reserved </i></div>
          </div>
      
      
          <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
      
      </body>
</body>
</html>
