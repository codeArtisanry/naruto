<template>
  <div>
    <head>
      <link rel="stylesheet" href="assets/flexslider.css" />
      <link rel="stylesheet" href="assets/animate.css" />
      <link rel="stylesheet" href="fonts/icomoon/style.css" />
      <link rel="stylesheet" href="assets/style.css" />
      <link
        href="https://fonts.googleapis.com/css?family=Nunito+Sans:200,300,400,700"
        rel="stylesheet"
      />
    </head>

    <nav
      class="navbar navbar-expand-lg site-navbar navbar-light bg-light"
      id="pd-navbar"
    >
      <div class="container">
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarsExample09"
          aria-controls="navbarsExample09"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div
          class="collapse navbar-collapse justify-content-md-center"
          id="navbarsExample09"
        >
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#section-home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#section-portfolio">Portfolio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#section-resume">Resume</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#section-about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#section-contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <section
      class="site-hero"
      style="background-image: url('assets/images/hero_1.jpg')"
      id="section-home"
      data-stellar-background-ratio="0.5"
    >
      <div class="container">
        <div class="row intro-text align-items-center justify-content-center">
          <div class="col-md-10 text-center pt-5">
            <h1 class="site-heading site-animate">
              Hello, Im <strong class="d-block"> Vatsal Chauhan </strong>
            </h1>

            <strong class="d-block text-black text-uppercase letter-spacing"
              >And this is my Portfolio</strong
            >
          </div>
        </div>
      </div>
    </section>

    <section class="site-section" id="section-portfolio">
      <div class="container">
        <div class="row">
          <div class="section-heading text-center col-md-12">
            <h2>Featured <strong>Portfolio</strong></h2>
          </div>
        </div>
        <div class="filters">
          <ul>
            <li class="active" data-filter="*">All</li>
            <li data-filter=".packaging">Packaging</li>
            <li data-filter=".mockup">Mockup</li>
            <li data-filter=".typography">Typography</li>
            <li data-filter=".photography">Photography</li>
          </ul>
        </div>

        <div class="filters-content">
          <div class="row grid">
            <div class="single-portfolio col-sm-4 all mockup">
              <div class="relative">
                <div class="thumb">
                  <div class="overlay overlay-bg"></div>
                  <img class="image img-fluid" src="images/p1.jpg" alt="" />
                </div>
                <a href="images/p1.jpg" class="img-pop-up">
                  <div class="middle">
                    <div class="text align-self-center d-flex">
                      <img src="images/preview.png" alt="" />
                    </div>
                  </div>
                </a>
              </div>
              <div class="p-inner">
                <h4>Square Box Mockup</h4>
                <div class="cat">Mockup</div>
              </div>
            </div>
            <div class="single-portfolio col-sm-4 all mockup">
              <div class="relative">
                <div class="thumb">
                  <div class="overlay overlay-bg"></div>
                  <img class="image img-fluid" src="images/p2.jpg" alt="" />
                </div>
                <a href="images/p2.jpg" class="img-pop-up">
                  <div class="middle">
                    <div class="text align-self-center d-flex">
                      <img src="images/preview.png" alt="" />
                    </div>
                  </div>
                </a>
              </div>
              <div class="p-inner">
                <h4>Product Box Package Mockup</h4>
                <div class="cat">Mockup</div>
              </div>
            </div>
            <div class="single-portfolio col-sm-4 all packaging">
              <div class="relative">
                <div class="thumb">
                  <div class="overlay overlay-bg"></div>
                  <img class="image img-fluid" src="images/p3.jpg" alt="" />
                </div>
                <a href="images/p3.jpg" class="img-pop-up">
                  <div class="middle">
                    <div class="text align-self-center d-flex">
                      <img src="images/preview.png" alt="" />
                    </div>
                  </div>
                </a>
              </div>
              <div class="p-inner">
                <h4>Creative Package Design</h4>
                <div class="cat">Packaging</div>
              </div>
            </div>
            <div class="single-portfolio col-sm-4 all packaging">
              <div class="relative">
                <div class="thumb">
                  <div class="overlay overlay-bg"></div>
                  <img class="image img-fluid" src="images/p4.jpg" alt="" />
                </div>
                <a href="images/p4.jpg" class="img-pop-up">
                  <div class="middle">
                    <div class="text align-self-center d-flex">
                      <img src="images/preview.png" alt="" />
                    </div>
                  </div>
                </a>
              </div>
              <div class="p-inner">
                <h4>Packaging Brand</h4>
                <div class="cat">Packaging</div>
              </div>
            </div>
            <div class="single-portfolio col-sm-4 all typography">
              <div class="relative">
                <div class="thumb">
                  <div class="overlay overlay-bg"></div>
                  <img class="image img-fluid" src="images/p5.jpg" alt="" />
                </div>
                <a href="images/p5.jpg" class="img-pop-up">
                  <div class="middle">
                    <div class="text align-self-center d-flex">
                      <img src="images/preview.png" alt="" />
                    </div>
                  </div>
                </a>
              </div>
              <div class="p-inner">
                <h4>Isometric 3D Extrusion</h4>
                <div class="cat">Typography</div>
              </div>
            </div>
            <div class="single-portfolio col-sm-4 all photography">
              <div class="relative">
                <div class="thumb">
                  <div class="overlay overlay-bg"></div>
                  <img class="image img-fluid" src="images/p6.jpg" alt="" />
                </div>
                <a href="images/p6.jpg" class="img-pop-up">
                  <div class="middle">
                    <div class="text align-self-center d-flex">
                      <img src="images/preview.png" alt="" />
                    </div>
                  </div>
                </a>
              </div>
              <div class="p-inner">
                <h4>White Space Photography</h4>
                <div class="cat">photography</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>
