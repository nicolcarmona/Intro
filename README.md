# Intro
<html>
    <head>
        <meta charset="utf-8"> 
        <link rel="stylesheet" href="css/all.min.css">
        <link rel="stylesheet" href="css/bootstrap.min.css">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
        
        <title>Club Vichuquen</title>
        <style>
            header {
                background: #1f1e1e;
                width: 100%;    
                z-index: 100;
            }
            nav {
                float: left;
            }
            nav ul {
                list-style: none;
                overflow: hidden;             
            }
            nav ul li {
                float: left;
                font-family: 'Poppins', sans-serif;
                font-size: 16px;
            }
            nav ul li a {
                display: block;
                padding: 10px;
                color: #fff;
                text-decoration: none;
            }
            nav ul li:hover {
                background: #616161;
            }                
            body{
                background-color:#1f1e1e;
                background-attachment: fixed;
                background-size: cover;
            }
            #parts{
                width: 100%;
            }
            #one{
                margin: 0px auto 0px;
            }
            #two{
                width: 100%;
            }
            #text1{
                position: relative;
                width: 33%;
                float: left;
                margin: 0px auto 0px;
                font-family: 'Poppins', sans-serif;
            }
            #two2 img:hover{
                transform: scale(1.05);
            }
            footer {
                background-color:#1f1e1e;
                color: #fff;
                padding: 50px 0;
            }
            footer h4 {
                color: #fff;
                font-size: 18px;
                font-weight: 700;
                margin-bottom: 20px;
            }
            footer ul {
                list-style: none;
                margin: 0;
                padding: 0;
            }
            footer ul li {
                margin-bottom: 10px;
            }
            footer ul li a {
                color: #fff;
                text-decoration: none;
            }
            footer ul li a:hover {
                color: #fff;
                text-decoration: underline;
            }
            footer ul li a i {
                margin-right: 5px;
            }

            #carrucel{
                width: 100%;
            }
                

            #formal{
			  	background-color: rgb(255, 255, 255);
			    text-align: center;
	    		width: 60%;
		    	font-family: 'Poppins', sans-serif;
			  	color: #1f1e1c;
	    		font-size: 21px;
		    	border-radius: 15px;
                margin: 0px auto 0px;
    		}
            #bn{
                float: left;
                width: 25%;
               }
            #margen{
                margin: 30px 15% 30px 15%;
            }  
            #titulo{
                font-size: 30px;
            }         
            @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap');
        </style>
         
    </head>
    <body>
 
        <header>
            <nav>
				    <img id="bn" src="img/banner.png" >
                <ul>
                    <li><a href="index.html">Inicio</a></li>
                    <li><a href="blog.html ">Blog</a></li>
                    <li><a href="nosotros.html">Sobre Nosotros</a></l>
                    <li><a href="estatutos.html">Estatutos</a></li>
                    <li><a href="beneficios.html">Beneficios</a></li>
                </ul>
            </nav>
        </header>
        <div id="one">
            <img id="parts" src="img/1.jpg" >
                <img src="img/1.png" >
        </div>
        <div id="two">
            <a href="regatas.html"><img id="text1" src="img/regatas.jpg" ></a>
            <a href="cabanas.html"><img id="text1" src="img/cabana.jpg" ></a>
            <a href="kayak.html"><img id="text1" src="img/kayak.jpg" ></a> 
        </div><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
        <div id="carrucel">
            <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="img/muelle1.jpg" class="d-block w-100" alt="Muelles">
                    <div class="carousel-caption d-none d-md-block">
                      <h5>Muelles Flotantes</h5>
                      <p>Muelles flotantes disponibles para los miembros que posean una embarcación.</p>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="img/voley.jpg" class="d-block w-100" alt="Voley">
                    <div class="carousel-caption d-none d-md-block">
                      <h5>Voleibol Playa</h5>
                      <p>Disponible para Miembros y familiares.</p>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="img/sup.jpg" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                      <h5>Clases de stand up padel</h5>
                      <p>Disponible para Miembros y familiares.</p>
                    </div>
                  </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Next</span>
                </button>
              </div>
        </div>
        <footer>
            <div class="container">
              <div class="row">
                <div class="col-md-4">
                  <h4>Contacto</h4>
                  <ul>
                    <li>Dirección: Calle del Puerto, 1</li>
                    <li>Teléfono: 555-1234</li>
                    <li>Correo electrónico: info@clubnautico.com</li>
                  </ul>
                </div>
                <div class="col-md-4">
                  <h4>Enlaces</h4>
                  <ul>
                    <li><a href="index.html">Inicio</a></li>
                    <li><a href="beneficios.html">Beneficios</a></li>
                    <li><a href="blog.html">Blog</a></li>
                  </ul>
                </div>
                <div class="col-md-4">
                  <h4>Redes sociales</h4>
                  <ul>
                    <li><a href="#"><i class="fab fa-facebook-f"></i> Facebook</a></li>
                    <li><a href="#"><i class="fab fa-twitter"></i> Twitter</a></li>
                    <li><a href="#"><i class="fab fa-instagram"></i> Instagram</a></li>
                  </ul>
                </div>
              </div>
            </div>
        </footer>
        <script>
            var myCarousel = document.querySelector('#myCarousel')
            var carousel = new bootstrap.Carousel(myCarousel, {
              interval: 2000,
              wrap: true
            })
        </script> 
    </body>
</html>
    
