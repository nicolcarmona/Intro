# Intro
{% load static %}
<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="utf-8"> 
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="{% static 'css/all.min.css'%}">
        <link rel="stylesheet" href="{% static 'css/bootstrap.min.css'%}">
        <link href= "{% static 'https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet' %}">
        <link rel="stylesheet"  href= "{% static 'css/styles.css'%}">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
        <title>Climaticgang </title>
        <style>
            header {
                background: #1f1e1e;
                width: 100%;    
                z-index: 100;
            }
            #peneee
            #banner {
                float: left;
            }
            #color{
              background-color: #c7e6ee;
            }
            body{
                background-color: #c7e6ee;
                background-attachment: fixed;
                background-size: cover;
                font-family: 'Poppins', sans-serif;
            }
            #parts{
                width: 100%;
                clear: both;
            }
            #one{
                margin: 0px auto 0px;
                background-color:#c7e6ee;
                clear: both;
            }
            #frase{
              width: 40%;
              align-self: center;
            }
            #two{
                width: 100%;
                background-color:#c7e6ee;
                clear: both;
            }
            #text1{
                position: relative;
                width: 100%;
                float: left;
                margin: 0px auto 0px;
                font-family: 'Poppins', sans-serif;
                clear: both;
            }
            #two2 img:hover{
                transform: scale(1.05);
                clear: both;
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
            .api-data-container {
              background-color: white;
              padding: 20px;
              border-radius: 8px;
              margin: 20px 0;
          }
          .api-data-container h4 {
              font-size: 24px;
              color: #333;
          }
          .api-data-container p {
              font-size: 18px;
              color: #555;
          }
          .api-data-container .error {
              color: red;
              font-size: 16px;
          }
          .data-card {
            background-color: #ffffff;
            padding: 15px;
            border-radius: 8px;
            margin: 10px 0;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        
        .data-card p {
            font-size: 18px;
            margin: 5px 0;
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
                width: 13%;
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
      <header><!--banner con posibilidad de agregar links-->
          <div id="banner">
				    <img id="bn" src="{% static 'img/baner.png' %}" >
          </div>
      </header>
      <div id="one">
          <img id="parts" src="{% static 'img/1.jpg' %}" ><br><br><br><br><br><br>
          <img id="frase"src="{% static 'img/1.png' %}" >
      </div>

      <div id="two">
        <a href="#"><img id="text1" src="{% static 'img/causas.jpg' %}" ></a>
        <a href="#"><img id="text1" src="{% static 'img/impacto.jpg' %}"></a>
        <a href="#"><img id="text1" src="{% static 'img/soluciones.jpg' %}"> </a> 


      </div>                                                                              
        <!--linea de tiempo-->
    <div><img id="text1" src="{% static 'img/sucesos.jpg' %}" ></a></div>
    <div id="color">
        <section class="timeline">
          <ul><br><br>
            <li>
              <div>
                <time>1934</time> At vero xd
            </li>
            <li>
              <div>
                <time>1934</time> At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium
              </div>
            </li>
            <li>
              <div>
                <time>1937</time> Proin quam velit, efficitur vel neque vitae, rhoncus commodo mi. Suspendisse finibus mauris et bibendum molestie. Aenean ex augue, varius et pulvinar in, pretium non nisi.
              </div>
            </li>
            <li>
              <div>
                <time>1940</time> Proin iaculis, nibh eget efficitur varius, libero tellus porta dolor, at pulvinar tortor ex eget ligula. Integer eu dapibus arcu, sit amet sollicitudin eros.
              </div>
            </li>
            <li>
              <div>
                <time>1943</time> In mattis elit vitae odio posuere, nec maximus massa varius. Suspendisse varius volutpat mattis. Vestibulum id magna est.
              </div>
            </li>
            <li>
              <div>
                <time>1946</time> In mattis elit vitae odio posuere, nec maximus massa varius. Suspendisse varius volutpat mattis. Vestibulum id magna est.
              </div>
            </li>
          </ul>
        </section>
      </div>
         <!--galeria-->
         <div id="carrucel">
            <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="{% static 'img/api1.jpg'%}" class="d-block w-100" alt="Muelles">
                    <div class="carousel-caption d-none d-md-block">
                      <h3> Emisiones de carbono en España: </h3>
                         <div class="api-data-container">
                                    <p><strong>Valor de electricidad:</strong> {{ electricity_value }} kWh</p>
                                    <p><strong>Emisiones de CO₂:</strong> {{ carbon_g }} gramos</p>
                                    <p><strong>Emisiones de CO₂ (kg):</strong> {{ carbon_kg }} kg</p>
                                    <p><strong>Emisiones de CO₂ (lb):</strong> {{ carbon_lb }} lb</p>
                                    <p><strong>Emisiones de CO₂ (toneladas):</strong> {{ carbon_mt }} toneladas</p>
                                    <p><strong>Fecha estimada:</strong> {{ estimated_at }}</p>
                          </div>
                        </div>
                  <div class="carousel-item">
                    <img src="{% static 'img/api2.jpg'%}" class="d-block w-100" alt="Voley">
                    <div class="carousel-caption d-none d-md-block">

                      <h4>API 2 </h4>
                      <p>mini descripcion de la api</p>

                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="{% static 'img/api3.jpg' %}" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">

                      <h5>API 3</h5>
                      <p>mini descripcion de la api</p>

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

        <!--pie de pagina-->
        <footer>
            <div class="container">
              <div class="row">
                <div class="col-md-4">
                  <h4>Contacto</h4>
                  <ul>
                    <li>U. Tecnica Federico Santa Maria</li>

                    <li>Teléfono: 555-1234</li>
                    <li>Correo electrónico: info@Climaticgang.com</li>
                  </ul>
                </div>
                <div class="col-md-4">
                  <h4>Enlaces</h4>
                  <ul>
                    <li><a href="index.html">Inicio</a></li>
                    <li><a href="#.html">Blog</a></li>
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




        <!--galeria de api para que pase de manera automatica-->
        <script>
            var myCarousel = document.querySelector('#myCarousel')
            var carousel = new bootstrap.Carousel(myCarousel, {
              interval: 2000,
              wrap: true
            })

          <!--ajusta la linea de tiepo a diferentes pantallas-->
          function isElementInViewport(el) {
            var rect = el.getBoundingClientRect();
            return (
              rect.top >= 0 &&
              rect.left >= 0 &&
              rect.bottom <= (window.innerHeight || document.documentElement.clientHeight) &&
              rect.right <= (window.innerWidth || document.documentElement.clientWidth)
            )}
            var items = document.querySelectorAll(".timeline li");

            function callbackFunc() {
              for (var i = 0; i < items.length; i++) {
              if (isElementInViewport(items[i])) {
              items[i].classList.add("in-view");}
              }}
            window.addEventListener("load", callbackFunc);
            window.addEventListener("scroll", callbackFunc);

        </script>
      
    </body>
</html>
