<template>
  <div>

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
            <button class="btn btn-fab btn-sm" id="sideel" title="Paramètres"><span class="ti-settings"></span></button>
          </div>
          <!-- Puschase -->
          <!-- <div class="d-block">
            <a href="https://macodeid.com/projects/virtual-folio/" class="btn btn-fab btn-sm" title="Get this template" data-toggle="tooltip" data-placement="left"><span class="ti-download"></span></a>
          </div> -->
          <!-- Help -->
          <div class="d-block">
            <a href="#" class="btn btn-fab btn-sm" title="Help" data-toggle="tooltip" data-placement="left"><span class="ti-email"></span></a>
          </div>
        </div>
        <div class="set-menu">
          <p>Selectionnez une couleur</p>
          <div class="color-bar" data-toggle="selected">
            <span class="color-item bg-theme-red selected" data-class="theme-red"></span>
            <span class="color-item bg-theme-blue" data-class="theme-blue"></span>
            <span class="color-item bg-theme-green" data-class="theme-green"></span>
            <span class="color-item bg-theme-orange" data-class="theme-orange"></span>
            <span class="color-item bg-theme-purple" data-class="theme-purple"></span>
          </div>
          <!-- <select class="custom-select d-block my-2" id="change-page">
            <option value="">Choose Page</option>
            <option value="index">Topbar</option>
            <option value="blog-topbar">Blog (Topbar)</option>
            <option value="index-2">Minibar</option>
            <option value="blog-minibar">Blog (Minibar)</option>
          </select> -->
        </div>
      </div>
      
      <div class="vg-page page-home" id="home" style="background-image: url('assets/img/banner.jpg')">
        <!-- Navbar -->
        <div class="navbar navbar-expand-lg navbar-dark sticky" data-offset="500">
          <div class="container">
            <a href="" class="navbar-brand">WIDOSKI TECHNOLOGIES</a>
            <button class="navbar-toggler" data-toggle="collapse" data-target="#main-navbar" aria-expanded="true">
              <span class="ti-menu"></span>
            </button>
            <div class="collapse navbar-collapse" id="main-navbar">
              <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                  <a href="#home" class="nav-link" data-animate="scrolling">Accueil</a>
                </li>
                <li class="nav-item">
                  <a href="#about" class="nav-link" data-animate="scrolling">À propos</a>
                </li>
                <li class="nav-item">
                  <a href="#portfolio" class="nav-link" data-animate="scrolling">Portfolio</a>
                </li>
                <li class="nav-item">
                  <a href="#blog" class="nav-link" data-animate="scrolling">Blog</a>
                </li>
                <li class="nav-item">
                  <a href="#contact" class="nav-link" data-animate="scrolling">Contact</a>
                </li>
              </ul>
              <ul class="nav ml-auto">
                <li class="nav-item">
                  <button class="btn btn-fab btn-theme no-shadow">WT</button>
                </li>
              </ul>
            </div>
          </div>
        </div> <!-- End Navbar -->

        <!-- Caption header -->
        <div class="caption-header text-center wow zoomInDown">
          <h5 class="fw-normal">Bienvenu</h5>
          <h1 class="fw-light mb-4">Je suis <b class="fg-theme">Widoski</b> Houndagba</h1>
          <div class="badge">Développeur web & Graphiste</div>
        </div> <!-- End Caption header -->
        <div class="floating-button"><span class="ti-mouse"></span></div>
      </div>
      
      <div class="vg-page page-about" id="about">
        <div class="container py-5">
          <div class="row">
            <div class="col-lg-4 py-3">
              <div class="img-place wow fadeInUp">
                <img src="../../public/assets/img/widoski.jpeg" alt="">
              </div>
            </div>
            <div class="col-lg-6 offset-lg-1 wow fadeInRight">
              <h1 class="fw-light">Widoski Houndagba</h1>
              <h5 class="fg-theme mb-3">Développeur web & Graphiste</h5>
              <p class="text-muted">Fasciné par la puissance de calcul des ordinateurs, passionné de l'art, des images, j'ai trouvé ma vocation dans le secteur du numérique et de la digitalisation.</p>
              <ul class="theme-list">
                <li><b>Du:</b> Bénin</li>
                <li><b>Habite à:</b> Calavi</li>
                <li><b>Âge:</b> 21</li>
                <li><b>Genre:</b> Masculin</li>
              </ul>
              <button class="btn btn-theme-outline">Télécharger CV</button>
            </div>
          </div>
        </div>
        <div class="container py-5">
          <h1 class="text-center fw-normal wow fadeIn">Mes Skills</h1>
          <div class="row py-3">
            <div class="col-md-6">
              <div class="px-lg-3">
                <h4 class="wow fadeInUp">Coding skills</h4>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">Laravel</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 70%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">70%</div>
                  </div>
                </div>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">VueJs</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">80%</div>
                  </div>
                </div>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">PHP</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 75%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">75%</div>
                  </div>
                </div>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">HTML + CSS + Bootstrap</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">80%</div>
                  </div>
                </div>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">WordPress</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 88%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">88%</div>
                  </div>
                </div>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">Postman</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 70%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">70%</div>
                  </div>
                </div>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">Linux</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 78%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">78%</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="px-lg-3">
                <h4 class="wow fadeInUp">Design Skills</h4>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">Adobe Photoshop</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 86%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">86%</div>
                  </div>
                </div>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">Adobe Illustrator</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 77%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">77%</div>
                  </div>
                </div>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">Adobe XD</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 89%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">89%</div>
                  </div>
                </div>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">Figma</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 87%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">87%</div>
                  </div>
                </div>
              </div>

              <div class="px-lg-3" style="margin-top:30px">
                <h4 class="wow fadeInUp">Organisation Skills</h4>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">Github</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 70%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">70%</div>
                  </div>
                </div>
                <div class="progress-wrapper wow fadeInUp">
                  <span class="caption">Trello</span>
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 91%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">91%</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="container pt-5">
          <div class="row">
            <div class="col-md-6 wow fadeInRight">
              <h2 class="fw-normal">Education</h2>
              <ul class="timeline mt-4 pr-md-5">
                <li>
                  <div class="title">2021 - 2022</div>
                  <div class="details">
                    <h5>Développement Web</h5>
                    <small class="fg-theme">Epitech</small>
                    <p>Formation en développement - Coding Academy sous le programme LeARN</p>
                  </div>
                </li>
                <li>
                  <div class="title">2017 - 2019</div>
                  <div class="details">
                    <h5>Transport et Logistique</h5>
                    <small class="fg-theme">VED - UAC</small>
                    <p>Formation en Transport et Logistique - Spécialité Logistique (Gestion de la chaîne d'approvisionnement)</p>
                  </div>
                </li>
                <li>
                  <div class="title">2016 - 2017</div>
                  <div class="details">
                    <h5>BAC D</h5>
                    <small class="fg-theme">Les Érudits</small>
                    <p>Obtention du diplôme de fin de second cycle</p>
                  </div>
                </li>
              </ul>
            </div>

            <div class="col-md-6 wow fadeInRight" data-wow-delay="200ms">
              <h2 class="fw-normal">Expériences</h2>
              <ul class="timeline mt-4 pr-md-5">
                <li>
                  <div class="title">2021 - 2022</div>
                  <div class="details">
                    <h5>Développement Web</h5>
                    <small class="fg-theme">CDPAT AFRIQUE</small>
                    <p>Stage en développement web</p>
                    <!-- <ul>
                      <li>Création de sites et applications web</li>
                      <li>Maintenance de sites et applications web</li>
                    </ul> -->

                    <br>
                    <h5>Graphisme</h5>
                    <small class="fg-theme">CDPAT AFRIQUE</small>
                    <p>Stage en graphisme</p>
                    <!-- <ul>
                      <li>Création d'affiche publicitaire</li>
                      <li>Gestion de l'identité graphique de l'entreprise</li>
                    </ul> -->
                  </div>
                </li>
                <li>
                  <div class="title">2020-2021</div>
                  <div class="details">
                    <h5>Graphisme</h5>
                    <small class="fg-theme">BETOP COMMUNICATION</small>
                    <p>Stage en graphisme</p>
                  </div>
                </li>
                <li>
                  <div class="title">2019-2020</div>
                  <div class="details">
                    <h5>Entrepreneuriat</h5>
                    <small class="fg-theme">Formation</small>
                    <p>Suivi du Projet Formation SUD Entrepreneuriat-Intrapreneuriat initié par l’ADEJ (ex FNPEEJ)</p>
                    <p>Gestion des projets WI-LAND LOGISTICS et W-ART</p>
                  </div>
                </li>
                <li>
                  <div class="title">2018-2019</div>
                  <div class="details">
                    <h5>Transport et Logistique</h5>
                    <small class="fg-theme">Colloque international</small>
                    <p>Suivi du colloque international MARPORT (3eme édition)</p>

                    <br>

                    <h5>Transport et Logistique</h5>
                    <small class="fg-theme">SOBEMAP</small>
                    <p>Stage académique à la Société Béninoise des Manutentions Portuaires (SOBEMAP)</p>
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
            <div class="badge badge-subhead">Service</div>
          </div>
          <h1 class="fw-normal text-center wow fadeInUp">Qu'est-ce que je fais ?</h1>
          <div class="row mt-5">
            <div class="col-md-6 col-lg-4 col-xl-3">
              <div class="card card-service wow fadeInUp">
                <div class="icon">
                  <span class="ti-desktop"></span>
                </div>
                <div class="caption">
                  <h4 class="fg-theme">Développement Web</h4>
                  <p>Je crée des sites et applications web dynamiques, responsives et sécurisés.</p>
                </div>
              </div>
            </div>
            <div class="col-md-6 col-lg-4 col-xl-3">
              <div class="card card-service wow fadeInUp">
                <div class="icon">
                  <span class="ti-paint-bucket"></span>
                </div>
                <div class="caption">
                  <h4 class="fg-theme">Web Design</h4>
                  <p>Je conçois des maquettes originales et uniques répondant à vos besoins spécifiques.</p>
                </div>
              </div>
            </div>
            <div class="col-md-6 col-lg-4 col-xl-3">
              <div class="card card-service wow fadeInUp">
                <div class="icon">
                  <span class="ti-search"></span>
                </div>
                <div class="caption">
                  <h4 class="fg-theme">SEO</h4>
                  <p>Des sites et applications web bien référencés sur internet est au coeur de mon développement.</p>
                </div>
              </div>
            </div>
            <div class="col-md-6 col-lg-4 col-xl-3">
              <div class="card card-service wow fadeInUp">
                <div class="icon">
                  <span class="ti-vector"></span>
                </div>
                <div class="caption">
                  <h4 class="fg-theme">UI/UX Design</h4>
                  <p>Je conçois des créations simples, fluides et attrayantes qui répondent et satisfassent l'expérience utilisateur.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      
      <!-- <div class="vg-page page-funfact" style="background-image: url('assets/img/bg_banner.jpg');">
        <div class="container">
          <div class="row section-counter">
            <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
              <h1 class="number" data-number="768">768</h1>
              <span>Clients</span>
            </div>
            <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
              <h1 class="number" data-number="230">230</h1>
              <span>Project Compleate</span>
            </div>
            <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
              <h1 class="number" data-number="97">97</h1>
              <span>Project Ongoing</span>
            </div>
            <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
              <h1 class="number" data-number="699">699</h1>
              <span>Client Satisfaction</span>
            </div>
          </div>
        </div>
      </div> -->
      
      <!-- Portfolio page -->
      <div class="vg-page page-portfolio" id="portfolio">
        <div class="container">
          <div class="text-center wow fadeInUp">
            <div class="badge badge-subhead">Portfolio</div>
          </div>
          <h1 class="text-center fw-normal wow fadeInUp">Mes projets</h1>
          <div class="filterable-button py-3 wow fadeInUp" data-toggle="selected">
            <button class="btn btn-theme-outline selected" data-filter="*">All</button>
            <button class="btn btn-theme-outline" data-filter=".apps">Apps</button>
            <button class="btn btn-theme-outline" data-filter=".template">Template</button>
            <button class="btn btn-theme-outline" data-filter=".ui-ux">UI/UX</button>
          </div>

          <div class="gridder my-3">
            <div class="grid-item apps wow zoomIn">
              <div class="img-place" data-src="../../public/assets/img/work/work-1.jpg" data-fancybox data-caption="<h5 class='fg-theme'>Site vitrine</h5> <p>Formation, Recrutement</p>">
                
                <img src="../../public/assets/img/work/work-1.jpg" alt="">
                <a href="https://www.cdpatafrique.com">
                <div class="img-caption">
                  <h5 class="fg-theme">Site vitrine</h5>
                  <p>Formation, Recrutement</p>
                </div>
                </a>

              </div>
            </div>
            <div class="grid-item template wireframes wow zoomIn">
              <div class="img-place" data-src="../../public/assets/img/work/work-2.jpg" data-fancybox data-caption="<h5 class='fg-theme'>E-commerce</h5> <p>E-commerce, Artisanat</p>">
                <img src="../../public/assets/img/work/work-2.jpg" alt="">
                <div class="img-caption">
                  <h5 class="fg-theme">E-commerce</h5>
                  <p>E-commerce, Artisanat</p>
                </div>
              </div>
            </div>
            <div class="grid-item apps ios wow zoomIn">
              <div class="img-place" data-src="../../public/assets/img/work/work-3.jpg" data-fancybox data-caption="<h5 class='fg-theme'>Post-it</h5> <p>Application web</p>">
                <img src="../../public/assets/img/work/work-3.jpg" alt="">
                <div class="img-caption">
                  <h5 class="fg-theme">Post-it</h5>
                  <p>Application web</p>
                </div>
              </div>
            </div>
          </div> <!-- End gridder -->
          <div class="text-center wow fadeInUp">
            <a href="javascript:void(0)" class="btn btn-theme">Load More</a>
          </div>
        </div>
      </div> <!-- End Portfolio page -->
      
      <!-- Testimonial -->
      <!-- <div class="vg-page page-testimonial">
        <div class="container">
          <h1 class="text-center fw-normal wow fadeInUp">What Clients are Saying</h1>
          <div class="row justify-content-center mt-5 wow fadeInUp">
            <div class="col-md-9">
              <div class="owl-carousel testi-carousel">
                <div class="item">
                  <div class="row">
                    <div class="col-md-6">
                      <div class="img-place">
                        <img src="../../public/assets/img/testimonials/testimonials_1.jpg" alt="">
                      </div>
                    </div>
                    <div class="col-md-6">
                      <div class="caption">
                        <div class="testi-content">There are many variations of passages of Lorem Ipsum available, but the majority have suffered</div>
                        <div class="testi-info">
                          <div class="thumb-profile">
                            <img src="../../public/assets/img/testimonials/testimonials_1.jpg" alt="">
                          </div>
                          <div class="tagline">
                            <h5 class="mb-0">Satria Nugraha</h5>
                            <span class="text-muted">CEO Nutshell</span>
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
                        <img src="../../public/assets/img/testimonials/testimonials_2.jpg" alt="">
                      </div>
                    </div>
                    <div class="col-md-6">
                      <div class="caption">
                        <div class="testi-content">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Saepe natus expedita ab facilis ut, animi explicabo amet. Voluptatibus possimus iste enim, doloremque, fugiat accusamus nisi optio fugit ratione expedita harum?</div>
                        <div class="testi-info">
                          <div class="thumb-profile">
                            <img src="../../public/assets/img/testimonials/testimonials_2.jpg" alt="">
                          </div>
                          <div class="tagline">
                            <h5 class="mb-0">Selena Arrini</h5>
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
      </div> -->
      <!-- End testimonial -->
      
      <!-- Client -->
      <div class="vg-page page-client">
        <div class="container">
          <div class="row">
            <div class="col-md-6 col-lg-4 col-xl-3 item">
              <div class="img-place wow fadeInUp">
                <img src="../../public/assets/img/logo/company_1.svg" alt="">
              </div>
            </div>
            <div class="col-md-6 col-lg-4 col-xl-3 item">
              <div class="img-place wow fadeInUp">
                <img src="../../public/assets/img/logo/company_2.svg" alt="">
              </div>
            </div>
            <div class="col-md-6 col-lg-4 col-xl-3 item">
              <div class="img-place wow fadeInUp">
                <img src="../../public/assets/img/logo/company_3.svg" alt="">
              </div>
            </div>
            <div class="col-md-6 col-lg-4 col-xl-3 item">
              <div class="img-place wow fadeInUp">
                <img src="../../public/assets/img/logo/company_4.svg" alt="">
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md-6 col-lg-4 col-xl-3 item">
              <div class="img-place wow fadeInUp">
                <img src="../../public/assets/img/logo/company_5.svg" alt="">
              </div>
            </div>
            <div class="col-md-6 col-lg-4 col-xl-3 item">
              <div class="img-place wow fadeInUp">
                <img src="../../public/assets/img/logo/company_6.svg" alt="">
              </div>
            </div>
            <div class="col-md-6 col-lg-4 col-xl-3 item">
              <div class="img-place wow fadeInUp">
                <img src="../../public/assets/img/logo/company_7.svg" alt="">
              </div>
            </div>
            <div class="col-md-6 col-lg-4 col-xl-3 item">
              <div class="img-place wow fadeInUp">
                <img src="../../public/assets/img/logo/company_8.svg" alt="">
              </div>
            </div>
          </div>
        </div>
      </div> <!-- End client -->
      
      <!-- Blog -->
      <!-- <div class="vg-page page-blog" id="blog">
        <div class="container">
          <div class="text-center">
            <div class="badge badge-subhead wow fadeInUp">Blog</div>
          </div>
          <h1 class="text-center fw-normal wow fadeInUp">Latest Post</h1>
          <div class="row post-grid">
            <div class="col-md-6 col-lg-4 wow fadeInUp">
              <div class="card">
                <div class="img-place">
                  <img src="../../public/assets/img/work/work-9.jpg" alt="">
                </div>
                <div class="caption">
                  <a href="javascript:void(0)" class="post-category">Technology</a>
                  <a href="#" class="post-title">Invision design forward fund</a>
                  <span class="post-date"><span class="sr-only">Published on</span> May 22, 2018</span>
                </div>
              </div>
            </div>
            <div class="col-md-6 col-lg-4 wow fadeInUp">
              <div class="card">
                <div class="img-place">
                  <img src="../../public/assets/img/work/work-6.jpg" alt="">
                </div>
                <div class="caption">
                  <a href="javascript:void(0)" class="post-category">Business</a>
                  <a href="#" class="post-title">Announcing a plan for small teams</a>
                  <span class="post-date"><span class="sr-only">Published on</span> May 22, 2018</span>
                </div>
              </div>
            </div>
            <div class="col-md-6 col-lg-4 wow fadeInUp">
              <div class="card">
                <div class="img-place">
                  <img src="../../public/assets/img/work/work-1.jpg" alt="">
                </div>
                <div class="caption">
                  <a href="javascript:void(0)" class="post-category">Design</a>
                  <a href="#" class="post-title">5 basic tips for illustrating</a>
                  <span class="post-date"><span class="sr-only">Published on</span> May 22, 2018</span>
                </div>
              </div>
            </div>
            <div class="col-12 text-center py-3 wow fadeInUp">
              <a href="blog-fullbar.html" class="btn btn-theme">See All Post</a>
            </div>
          </div>
        </div>
      </div> -->
      <!-- End blog -->
      
      <!-- Contact -->
      <div class="vg-page page-contact" id="contact">
        <div class="container-fluid">
          <div class="text-center wow fadeInUp">
            <div class="badge badge-subhead">Contact</div>
          </div>
          <h1 class="text-center fw-normal wow fadeInUp">Get in touch</h1>
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
                    <input class="form-control" type="text" name="Name" placeholder="Your Name">
                  </div>
                  <div class="col-6 mt-3 wow fadeInUp">
                    <input class="form-control" type="text" name="Email" placeholder="Email Address">
                  </div>
                  <div class="col-6 mt-3 wow fadeInUp">
                    <input class="form-control" type="text" name="Subject" placeholder="Subject">
                  </div>
                  <div class="col-12 mt-3 wow fadeInUp">
                    <textarea class="form-control" name="Message" rows="6" placeholder="Enter message here.."></textarea>
                  </div>
                  <button type="submit" class="btn btn-theme mt-3 wow fadeInUp ml-1">Send Message</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div> <!-- End Contact -->
      
      <!-- Footer -->
      <div class="vg-footer">
        <h1 class="text-center">WIDOSKI TECHNOLOGIES</h1>
        <div class="container">
          <div class="row">
            <div class="col-lg-4 py-3">
              <div class="footer-info">
                <p>Where to find me</p>
                <hr class="divider">
                <p class="fs-large fg-white">1600 Amphitheatre Parkway Mountain View, California 94043 US</p>
              </div>
            </div>
            <div class="col-md-6 col-lg-3 py-3">
              <div class="float-lg-right">
                <p>Suivez-moi</p>
                <hr class="divider">
                <ul class="list-unstyled">
                  <li><a href="#">LinkedIn</a></li>
                  <li><a href="#">Facebook</a></li>
                </ul>
              </div>
            </div>
            <div class="col-md-6 col-lg-3 py-3">
              <div class="float-lg-right">
                <p>Contact</p>
                <hr class="divider">
                <ul class="list-unstyled">
                  <li>info@widoski.tech</li>
                  <!-- <li>info@widoskitechnologies.com</li> -->
                  <li>+22963856921</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="row justify-content-center mt-3">
            <div class="col-12">
              <p class="text-center mb-0 mt-4">Copyright &copy; 2022. All right reserved | WIDOSKI TECHNOLOGIES <span class="ti-heart fg-theme-red"></span></p>
            </div>
          </div>
        </div>
      </div> <!-- End footer -->
      
    </body>
    
  </div>
</template>

<script>

export default {
  name: 'Accueil',
}
</script>
