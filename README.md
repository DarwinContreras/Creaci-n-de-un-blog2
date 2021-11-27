# Creaci-n-de-un-blog2
Creación de un blog con jekyll
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  
  <meta name="copyright" content="MACode ID, https://www.macodeid.com/">
  
  <title>Portafolio virtual Prueba </title>

  <link rel="shortcut icon" href="../assets/favicon.ico" type="image/x-icon">
  
  <link rel="stylesheet" type="text/css" href="../assets/css/themify-icons.css">
  
  <link rel="stylesheet" type="text/css" href="../assets/css/bootstrap.css">

  <link rel="stylesheet" type="text/css" href="../assets/vendor/animate/animate.css">
  
  <link rel="stylesheet" type="text/css" href="../assets/vendor/owl-carousel/owl.carousel.css">
  
  <link rel="stylesheet" type="text/css" href="../assets/vendor/perfect-scrollbar/css/perfect-scrollbar.css">
  
  <link rel="stylesheet" type="text/css" href="../assets/vendor/nice-select/css/nice-select.css">
  
  <link rel="stylesheet" type="text/css" href="../assets/vendor/fancybox/css/jquery.fancybox.min.css">
  
  <link rel="stylesheet" type="text/css" href="../assets/css/virtual.css">
  
  <link rel="stylesheet" type="text/css" href="../assets/css/topbar.virtual.css">
</head>
<body class="theme-red">
  
  <!-- Back to top button -->
  <div class="btn-back_to_top">
    <span class="ti-arrow-up"></span>
  </div>
  
  <!-- Setting button -->
  <div class="config">
    <div class="template-config">
      <!-- Settings -->
      <div class="d-block">
        <button class="btn btn-fab btn-sm" id="sideel" title="Settings"><span class="ti-settings"></span></button>
      </div>
      <!-- Puschase -->
      <div class="d-block">
        <a href="https://macodeid.com/projects/virtual-folio/" class="btn btn-fab btn-sm" title="Get this template" data-toggle="tooltip" data-placement="left"><span class="ti-download"></span></a>
      </div>
      <!-- Help -->
      <div class="d-block">
        <a href="#" class="btn btn-fab btn-sm" title="Help" data-toggle="tooltip" data-placement="left"><span class="ti-help"></span></a>
      </div>
    </div>
    <div class="set-menu">
      <p>Select Color</p>
      <div class="color-bar" data-toggle="selected">
        <span class="color-item bg-theme-red selected" data-class="theme-red"></span>
        <span class="color-item bg-theme-blue" data-class="theme-blue"></span>
        <span class="color-item bg-theme-green" data-class="theme-green"></span>
        <span class="color-item bg-theme-orange" data-class="theme-orange"></span>
        <span class="color-item bg-theme-purple" data-class="theme-purple"></span>
      </div>
      <select class="custom-select d-block my-2" id="change-page">
        <option value="">Elegir página</option>
        <option value="index">Barra superior</option>
        <option value="blog-topbar">Blog (Topbar)</option>
        <option value="index-2">Minibar</option>
        <option value="blog-minibar">Blog (Minibar)</option>
      </select>
    </div>
  </div>
  
  <div class="vg-page page-home" id="home" style="background-image: url(../assets/img/bg_image_1.jpg)">
    <!-- Navbar -->
    <div class="navbar navbar-expand-lg navbar-dark sticky" data-offset="500">
      <div class="container">
        <a href="" class="navbar-brand">Blog</a>
        <button class="navbar-toggler" data-toggle="collapse" data-target="#main-navbar" aria-expanded="true">
          <span class="ti-menu"></span>
        </button>
        <div class="collapse navbar-collapse" id="main-navbar">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
              <a href="#home" class="nav-link" data-animate="scrolling">Inicio</a>
            </li>
            <li class="nav-item">
              <a href="#about" class="nav-link" data-animate="scrolling">Acerca</a>
            </li>
            <li class="nav-item">
              <a href="#portfolio" class="nav-link" data-animate="scrolling">Portfolio</a>
            </li>
            <li class="nav-item">
              <a href="#blog" class="nav-link" data-animate="scrolling">Blog</a>
            </li>
            <li class="nav-item">
              <a href="#contact" class="nav-link" data-animate="scrolling">Contacto</a>
            </li>
          </ul>
          <ul class="nav ml-auto">
            <li class="nav-item">
              <button class="btn btn-fab btn-theme no-shadow">En</button>
            </li>
          </ul>
        </div>
      </div>
    </div> <!-- End Navbar -->
    <!-- Caption header -->
    <div class="caption-header text-center wow zoomInDown">
      <h5 class="fw-normal">Bienvenidos</h5>
      <h1 class="fw-light mb-4"><b class="fg-theme">Darwin Contreras</b> </h1>
      <div class="badge">Programador & Diseñador Web</div>
    </div> <!-- End Caption header -->
    <div class="floating-button"><span class="ti-mouse"></span></div>
  </div>
  
  <div class="vg-page page-about" id="about">
    <div class="container py-5">
      <div class="row">
        <div class="col-lg-4 py-3">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/person.jpg" alt="">
          </div>
        </div>
        <div class="col-lg-6 offset-lg-1 wow fadeInRight">
          <h1 class="fw-light">Darwin Contreras</h1>
          <h5 class="fg-theme mb-3">Programador & Diseñador Web</h5>
          <p class="text-muted">¡Hola! llevo aprendiendo lenguajes de programación desde que tenía 12 años. A esa edad aprendí Basic, del cual muchos de vosotros os acordaréis. Me tiré mucho tiempo aprendiendo y profundizando en ese lenguaje procedural, el cual me introdujo en todo este mundo. Un tiempo más tarde, avance a QuickBasic con más estructuras de control y mejor entorno de desarrollo.</p>
          <ul class="theme-list">
            <li><b>Pais:</b> Ecuador,Ecu</li>
            <li><b>Lugar donde vives:</b> Manabí, Portoviejo</li>
            <li><b>Edad:</b> 27</li>
            <li><b>Genero:</b> Masculino</li>
          </ul>
          <button class="btn btn-theme-outline">Descargar Hoja de vida</button>
        </div>
      </div>
    </div>
    <div class="container py-5">
      <h1 class="text-center fw-normal wow fadeIn">Mis Habilidades</h1>
      <div class="row py-3">
        <div class="col-md-6">
          <div class="px-lg-3">
            <h4 class="wow fadeInUp">Habilidades de codificación</h4>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">JavaScript</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 86%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">86%</div>
              </div>
            </div>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">PHP</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">80%</div>
              </div>
            </div>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">HTML + CSS</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 100%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">100%</div>
              </div>
            </div>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">Phyton</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 90%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">90%</div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="px-lg-3">
            <h4 class="wow fadeInUp">Habilidades de diseño</h4>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">Diseñador UI / UX </span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 92%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">92%</div>
              </div>
            </div>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">Diseñador Web</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 99%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">99%</div>
              </div>
            </div>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">Diseñador de Logos</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 79%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">79%</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container pt-5">
      <div class="row">
        <div class="col-md-6 wow fadeInRight">
          <h2 class="fw-normal">Educación</h2>
          <ul class="timeline mt-4 pr-md-5">
            <li>
              <div class="title">2010</div>
              <div class="details">
                <h5>Especialízate por supuesto</h5>
                <small class="fg-theme">UNIVERSIDAD INTERCIONAL DE LA RIOJA</small>
                <p>consiste en la formación integral del estudiante, para formar nuevos titulados con los conocimientos, habilidades y competencias que demanda la sociedad actual.</p>
              </div>
            </li>
            <li>
              <div class="title">2009</div>
              <div class="details">
                <h5>Especialízate por supuesto</h5>
                <small class="fg-theme">UNIVERSIDAD INTERCIONAL DE LA RIOJA</small>
                <p>consiste en la formación integral del estudiante, para formar nuevos titulados con los conocimientos, habilidades y competencias que demanda la sociedad actual.</p>
              </div>
            </li>
            <li>
              <div class="title">2008</div>
              <div class="details">
                <h5>Especialízate por supuesto</h5>
                <small class="fg-theme">UNIVERSIDAD INTERCIONAL DE LA RIOJA</small>
                <p>consiste en la formación integral del estudiante, para formar nuevos titulados con los conocimientos, habilidades y competencias que demanda la sociedad actual.</p>
              </div>
            </li>
          </ul>
        </div>
        <div class="col-md-6 wow fadeInRight" data-wow-delay="200ms">
          <h2 class="fw-normal">Experiencia</h2>
          <ul class="timeline mt-4 pr-md-5">
            <li>
              <div class="title">2017 - Current</div>
              <div class="details">
                <h5>Especialízate por supuesto</h5>
                <small class="fg-theme">UNIVERSIDAD INTERCIONAL DE LA RIOJA</small>
                <p>consiste en la formación integral del estudiante, para formar nuevos titulados con los conocimientos, habilidades y competencias que demanda la sociedad actual.</p>
              </div>
            </li>
            <li>
              <div class="title">2014</div>
              <div class="details">
                <h5>Especialízate por supuesto</h5>
                <small class="fg-theme">UNIVERSIDAD INTERCIONAL DE LA RIOJA</small>
                <p>consiste en la formación integral del estudiante, para formar nuevos titulados con los conocimientos, habilidades y competencias que demanda la sociedad actual.</p>
              </div>
            </li>
            <li>
              <div class="title">2011</div>
              <div class="details">
                <h5>Especialízate por supuesto</h5>
                <small class="fg-theme">UNIVERSIDAD INTERCIONAL DE LA RIOJA</small>
                <p>consiste en la formación integral del estudiante, para formar nuevos titulados con los conocimientos, habilidades y competencias que demanda la sociedad actual.</p>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  
  <div class="vg-page page-service">
    <div class="container">
      <div class="text-center wow fadeInUp">
        <div class="badge badge-subhead">Servicio</div>
      </div>
      <h1 class="fw-normal text-center wow fadeInUp">Qué puedo hacer?</h1>
      <div class="row mt-5">
        <div class="col-md-6 col-lg-4 col-xl-3">
          <div class="card card-service wow fadeInUp">
            <div class="icon">
              <span class="ti-paint-bucket"></span>
            </div>
            <div class="caption">
              <h4 class="fg-theme">Diseño Web</h4>
              <p>Hay muchas variaciones de pasajes de Lorem Ipsum disponibles.</p>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3">
          <div class="card card-service wow fadeInUp">
            <div class="icon">
              <span class="ti-search"></span>
            </div>
            <div class="caption">
              <h4 class="fg-theme">CEO</h4>
              <p>Hay muchas variaciones de pasajes de Lorem Ipsum disponibles.</p>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3">
          <div class="card card-service wow fadeInUp">
            <div class="icon">
              <span class="ti-vector"></span>
            </div>
            <div class="caption">
              <h4 class="fg-theme">UI/UX Diseño</h4>
              <p>Hay muchas variaciones de pasajes de Lorem Ipsum disponibles.</p>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3">
          <div class="card card-service wow fadeInUp">
            <div class="icon">
              <span class="ti-desktop"></span>
            </div>
            <div class="caption">
              <h4 class="fg-theme">Desarrollador Web</h4>
              <p>Hay muchas variaciones de pasajes de Lorem Ipsum disponibles.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  
  <div class="vg-page page-funfact" style="background-image: url(../assets/img/bg_banner.jpg);">
    <div class="container">
      <div class="row section-counter">
        <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
          <h1 class="number" data-number="768">768</h1>
          <span>Cliente</span>
        </div>
        <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
          <h1 class="number" data-number="230">230</h1>
          <span>Proyecto terminado</span>
        </div>
        <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
          <h1 class="number" data-number="97">97</h1>
          <span>Proyecto en curso</span>
        </div>
        <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
          <h1 class="number" data-number="699">699</h1>
          <span>Satisfacción del cliente</span>
        </div>
      </div>
    </div>
  </div>
  
  <!-- Portfolio página -->
  <div class="vg-page page-portfolio" id="portfolio">
    <div class="container">
      <div class="text-center wow fadeInUp">
        <div class="badge badge-subhead">Portfolio</div>
      </div>
      <h1 class="text-center fw-normal wow fadeInUp">Mira mi trabajo</h1>
      <div class="filterable-button py-3 wow fadeInUp" data-toggle="selected">
        <button class="btn btn-theme-outline selected" data-filter="*">todo</button>
        <button class="btn btn-theme-outline" data-filter=".apps">Apps</button>
        <button class="btn btn-theme-outline" data-filter=".template">Pantilla</button>
        <button class="btn btn-theme-outline" data-filter=".ios">IOS</button>
        <button class="btn btn-theme-outline" data-filter=".ui-ux">UI/UX</button>
        <button class="btn btn-theme-outline" data-filter=".graphic">Grafico</button>
        <button class="btn btn-theme-outline" data-filter=".wireframes">Wireframes</button>
      </div>

      <div class="gridder my-3">
        <div class="grid-item apps wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/work-1.jpg" data-fancybox data-caption="<h5 class='fg-theme'>Mobile Travel App</h5> <p>Travel, Discovery</p>">
            <img src="../assets/img/work/work-1.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">Aplicación móvil de viajes</h5>
              <p>viaje, Descubrimiento</p>
            </div>
          </div>
        </div>
        <div class="grid-item template wireframes wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/work-2.jpg" data-fancybox data-caption="<h5 class='fg-theme'>Music App</h5> <p>Musics</p>">
            <img src="../assets/img/work/work-2.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">App Musica</h5>
              <p>Musica</p>
            </div>
          </div>
        </div>
        <div class="grid-item apps ios wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/work-3.jpg" data-fancybox data-caption="<h5 class='fg-theme'>Gaming Dashboard</h5> <p>Games, Streaming</p>">
            <img src="../assets/img/work/work-3.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">Gaming Dashboard</h5>
              <p>Games, Streaming</p>
            </div>
          </div>
        </div>
        <div class="grid-item graphic ui-ux wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/work-4.jpg" data-fancybox data-caption="<h5 class='fg-theme'>Drugs Delivery App</h5> <p>Health, Drugs</p>">
            <img src="../assets/img/work/work-4.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">Delivery App</h5>
              <p>Salud</p>
            </div>
          </div>
        </div>
        <div class="grid-item apps ios wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/work-5.jpg" data-fancybox data-caption="<h5 class='fg-theme'>Musics Discover</h5> <p>Musics, Dashboard</p>">
            <img src="../assets/img/work/work-5.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">Descubrir Musica</h5>
              <p>Musica, Tablero</p>
            </div>
          </div>
        </div>
        <div class="grid-item graphic ui-ux wireframes wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/work-6.jpg" data-fancybox data-caption="<h5 class='fg-theme'>Game Streaming</h5> <p>Games, Streaming</p>">
            <img src="../assets/img/work/work-6.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">Game Streaming</h5>
              <p>Games, Streaming</p>
            </div>
          </div>
        </div>
      </div> <!-- Rejilla final -->
      <div class="text-center wow fadeInUp">
        <a href="javascript:void(0)" class="btn btn-theme">Carga más</a>
      </div>
    </div>
  </div> <!-- Finalizar la página de la cabecera -->
  
  <!-- Testimonial -->
  <div class="vg-page page-testimonial">
    <div class="container">
      <h1 class="text-center fw-normal wow fadeInUp">Lo que dicen las clientes</h1>
      <div class="row justify-content-center mt-5 wow fadeInUp">
        <div class="col-md-9">
          <div class="owl-carousel testi-carousel">
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/testimonials_1.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">Después cambié de división y proyecto dentro de la empresa, y entré en el verdadero mundo de los equipos de desarrollo. Un proyecto de 5 años en un equipo de casi 40 desarrolladores escrito en C++ sobre Linux. </div>
                    <div class="testi-info">
                      <div class="thumb-profile">
                        <img src="../assets/img/testimonials/testimonials_1.jpg" alt="">
                      </div>
                      <div class="tagline">
                        <h5 class="mb-0">Julia Cevallos</h5>
                        <span class="text-muted">CEO</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/testimonials_2.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">Sin comentarios // sep 18th, 2011 // Positivismo, Programacion Llevo aprendiendo lenguajes de programación desde que tenía 12 años. A esa edad aprendí Basic, del cual muchos de vosotros os acordaréis. Me tiré mucho tiempo aprendiendo y profundizando en ese lenguaje procedural, el cual me introdujo en todo este mundo ;) . Un tiempo más tarde, avance a QuickBasic con más estructuras de control y mejor entorno de desarrollo.</div>
                    <div class="testi-info">
                      <div class="thumb-profile">
                        <img src="../assets/img/testimonials/testimonials_2.jpg" alt="">
                      </div>
                      <div class="tagline">
                        <h5 class="mb-0">Jorge Arrini</h5>
                        <span class="text-muted">CEO BigTree</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div> <!-- Testimonio final -->
  
  <!-- Cliente -->
  <div class="vg-page page-client">
    <div class="container">
      <div class="row">
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_1.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_2.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_3.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_4.svg" alt="">
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_5.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_6.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_7.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_8.svg" alt="">
          </div>
        </div>
      </div>
    </div>
  </div> <!-- Cliente final -->
  
  <!-- Blog -->
  <div class="vg-page page-blog" id="blog">
    <div class="container">
      <div class="text-center">
        <div class="badge badge-subhead wow fadeInUp">Blog</div>
      </div>
      <h1 class="text-center fw-normal wow fadeInUp">Última publicación</h1>
      <div class="row post-grid">
        <div class="col-md-6 col-lg-4 wow fadeInUp">
          <div class="card">
            <div class="img-place">
              <img src="../assets/img/work/work-9.jpg" alt="">
            </div>
            <div class="caption">
              <a href="javascript:void(0)" class="post-category">Tecnología</a>
              <a href="#" class="post-title">Fondo futuro de diseño de Invision</a>
              <span class="post-date"><span class="sr-only">Publicado en</span> Nov 26, 2021</span>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 wow fadeInUp">
          <div class="card">
            <div class="img-place">
              <img src="../assets/img/work/work-6.jpg" alt="">
            </div>
            <div class="caption">
              <a href="javascript:void(0)" class="post-category">Negocio</a>
              <a href="#" class="post-title">Anunciando un plan para equipos pequeños</a>
              <span class="post-date"><span class="sr-only">Publicado en</span>Nov 26, 2021</span>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 wow fadeInUp">
          <div class="card">
            <div class="img-place">
              <img src="../assets/img/work/work-1.jpg" alt="">
            </div>
            <div class="caption">
              <a href="javascript:void(0)" class="post-category">Diseño</a>
              <a href="#" class="post-title">5 consejos básicos para ilustrarg</a>
              <span class="post-date"><span class="sr-only">Publicado en </span> Nov 26, 2021</span>
            </div>
          </div>
        </div>
        <div class="col-12 text-center py-3 wow fadeInUp">
          <a href="blog-fullbar.html" class="btn btn-theme">Ver todas las publicaciones</a>
        </div>
      </div>
    </div>
  </div> <!-- Fin del blog -->
  
  <!-- Contact -->
  <div class="vg-page page-contact" id="contact">
    <div class="container-fluid">
      <div class="text-center wow fadeInUp">
        <div class="badge badge-subhead">Contacto</div>
      </div>
      <h1 class="text-center fw-normal wow fadeInUp">Ponerse en contacto</h1>
      <div class="row py-5">
        <div class="col-lg-7 px-0 pr-lg-3 wow zoomIn">
          <div class="vg-maps">
            <div id="google-maps" style="width: 100%; height: 100%;"></div>
          </div>
        </div>
        <div class="col-lg-5">
          <form class="vg-contact-form">
            <div class="form-row">
              <div class="col-12 mt-3 wow fadeInUp">
                <input class="form-control" type="text" name="Nombre" placeholder="Tu nombre">
              </div>
              <div class="col-6 mt-3 wow fadeInUp">
                <input class="form-control" type="text" name="Email" placeholder="Dirección de correo electrónico">
              </div>
              <div class="col-6 mt-3 wow fadeInUp">
                <input class="form-control" type="text" name="Sujeto" placeholder="Sujeto">
              </div>
              <div class="col-12 mt-3 wow fadeInUp">
                <textarea class="form-control" name="Mensaje" rows="6" placeholder="Ingrese el mensaje aquí ..."></textarea>
              </div>
              <button type="submit" class="btn btn-theme mt-3 wow fadeInUp ml-1">Enviar mensaje</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div> <!-- Finalizar contacto -->
  
  <!-- Footer -->
  <div class="vg-footer">
    <h1 class="text-center">Portafolio Virtual</h1>
    <div class="container">
      <div class="row">
        <div class="col-lg-4 py-3">
          <div class="footer-info">
            <p>Donde encontrarme</p>
            <hr class="divider">
            <p class="fs-large fg-white">UNIVERSIDAD INTERNACIONAL DE LA RIOJA - ESPAÑA</p>
          </div>
        </div>
        <div class="col-md-6 col-lg-3 py-3">
          <div class="float-lg-right">
            <p>Sígueme</p>
            <hr class="divider">
            <ul class="list-unstyled">
              <li><a href="#">Instagram</a></li>
              <li><a href="#">Facebook</a></li>
              <li><a href="#">Twitter</a></li>
              <li><a href="#">Youtube</a></li>
            </ul>
          </div>
        </div>
        <div class="col-md-6 col-lg-3 py-3">
          <div class="float-lg-right">
            <p>Contacto</p>
            <hr class="divider">
            <ul class="list-unstyled">
              <li>dcontreras2719@utm.edu.ec</li>
              <li>+593 0960069252</li>
              <li>+593 0960069252</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="row justify-content-center mt-3">
        <div class="col-12 mb-3">
          <h3 class="fw-normal text-center">Suscribete</h3>
        </div>
        <div class="col-lg-6">
          <form class="mb-3">
            <div class="input-group">
              <input type="text" class="form-control" placeholder="direccion de Email">
              <input type="submit" class="btn btn-theme no-shadow" value="Suscribete">
            </div>
          </form>
        </div>
        <div class="col-12">
          <p class="text-center mb-0 mt-4">Darwin Contreras<span class="ti-heart fg-theme-red"></span> by <a href="https://https://www.facebook.com/Lenguajes-de-Programaci%C3%B3n-126602170784133/">Darwin</a></p>
        </div>
      </div>
    </div>
  </div> <!-- End footer -->
  
  
  <script src="../assets/js/jquery-3.5.1.min.js"></script>
    
  <script src="../assets/js/bootstrap.bundle.min.js"></script>
    
  <script src="../assets/vendor/owl-carousel/owl.carousel.min.js"></script>
    
  <script src="../assets/vendor/perfect-scrollbar/js/perfect-scrollbar.js"></script>
    
  <script src="../assets/vendor/isotope/isotope.pkgd.min.js"></script>
    
  <script src="../assets/vendor/nice-select/js/jquery.nice-select.min.js"></script>
    
  <script src="../assets/vendor/fancybox/js/jquery.fancybox.min.js"></script>

  <script src="../assets/vendor/wow/wow.min.js"></script>

  <script src="../assets/vendor/animateNumber/jquery.animateNumber.min.js"></script>

  <script src="../assets/vendor/waypoints/jquery.waypoints.min.js"></script>

  <script src="../assets/js/google-maps.js"></script>
    
  <script src="../assets/js/topbar-virtual.js"></script>

  <script async defer src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAIA_zqjFMsJM_sxP9-6Pde5vVCTyJmUHM&callback=initMap"></script>
  
</body>
</html>
