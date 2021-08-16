<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, shrink-to-fit=no"
    />

    <!-- Bootstrap CSS -->
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css"
      integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO"
      crossorigin="anonymous"
    />

    <!-- My fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Viga&display=swap"
      rel="stylesheet"
    />

    <!-- My CSS -->
    <link rel="stylesheet" href="style.css" />
    
    /* Navbar */

.navbar {
  position: relative;
  z-index: 1;
}

.navbar-brand {
  font-family: viga;
  font-size: 32px;
}

/* Jumbotron */

.jumbotron {
  background-image: url(img/jumbotron-bg.jpg);
  background-size: cover;
  height: 540px;
  text-align: center;
  position: relative;
}

.jumbotron .container {
  z-index: 1;
  position: relative;
}

.jumbotron::after {
  content: "";
  display: block;
  width: 100%;
  height: 80%;
  background-image: linear-gradient(to top rgba(0, 0, 0, 1), rgba(0, 0, 0, 0));
  position: absolute;
  bottom: 0;
}

.jumbotron .display-4 {
  color: white;
  text-align: center;
  margin-top: 150px;
  font-weight: 200;
  text-shadow: 1px 1px 1px rgba(0, 0, 0.7);
  font-size: 40px;
  margin-bottom: 30px;
}

.jumbotron .display-4 b {
  font-weight: 500;
}

/* Info Panel */

.info-panel {
  box-shadow: 0 3px 20px rgba(0, 0, 0, 0.5);
  border-radius: 12px;
  margin-top: -100px;
  background-color: white;
  padding: 30px;
}

.info-panel img {
  width: 80px;
  height: 80px;
  margin-right: 20px;
  margin-bottom: 20px;
}

.info-panel h4 {
  font-size: 16px;
  text-transform: uppercase;
  font-weight: bold;
  margin-top: 5px;
}

.info-panel p {
  font-size: 14px;
  color: #acacac;
  margin-top: -5px;
  font-weight: 200;
}

/* Working Space */
.workingspace {
  margin-top: 120px;
  text-align: center;
}
.workingspace h3 {
  font-size: 52px;
  font-weight: 200;
  text-transform: uppercase;
  margin-top: 30px;
}

.workingspace h3 b {
  font-weight: 500;
}

.workingspace p {
  font-size: 18px;
  color: #acacac;
  font-weight: 200;
  margin: 30px 0;
}

/* Testimonial */
.testimonial {
  margin-top: 100px;
}
.testimonial h5 {
  text-align: center;
  font-weight: 200;
  font-style: italic;
  font-size: 24px;
}
.testimonial figure img {
  width: 60px;
  margin: 50px 10px 10px;
  opacity: 0.6;
}

.testimonial figure img.utama {
  width: 90px;
  opacity: 1;
  margin-top: 35px;
}

.testimonial figure h5 {
  font-size: 16px;
  font-weight: bold;
  font-style: normal;
  color: #1c2c5d;
}

.testimonial figure p {
  font-size: 12px;
  color: #acacac;
  margin-top: -5px !important;
}

.testimonial figure figcaption {
  text-align: center;
}

/* Footer */
.footer {
  margin-top: 100px;
}

.footer p {
  color: #acacac;
  font-size: 18px;
}

/* Utility */
.tombol {
  text-transform: uppercase;
  border-radius: 40px;
}

/* Desktop Version */
@media (min-width: 992px) {
  .nav-link {
    text-transform: uppercase;
    margin-right: 30px;
  }

  .navbar-brand,
  .nav-link {
    color: white !important;
    text-shadow: 1px 1px 1px rgba(0, 0, 0.7);
  }
  .nav-link:hover::after {
    content: "";
    display: block;
    border-bottom: 3px solid #0b63dc;
    width: 50%;
    margin: auto;
    padding-bottom: 5px;
    margin-bottom: -8px;
  }

  .jumbotron {
    margin-top: -75px;
    height: 640px;
  }

  .jumbotron .display-4 {
    font-size: 62px;
  }

  .workingspace {
    text-align: left;
  }

  .testimonial h5 {
    font-size: 32px;
  }
}

    <title>Landing Page | Lukman Ferdiansyah</title>
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light">
      <div class="container">
        <a class="navbar-brand" href="#">Lukman Ferdiansyah</a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav ml-auto">
            <a class="nav-item nav-link active" href="#"
              >Home <span class="sr-only">(current)</span></a
            >
            <a class="nav-item nav-link" href="#">Pricing</a>
            <a class="nav-item nav-link" href="#">Features</a>
            <a class="nav-item nav-link" href="#">About</a>
            <a class="nav-item tombol btn btn-primary" href="#">Join Us</a>
          </div>
        </div>
      </div>
    </nav>
    <!-- Akhir Navbar -->

    <!-- Jumbotron -->
    <div class="jumbotron jumbotron-fluid">
      <div class="container">
        <h1 class="display-4">
          Get Work done <b>faster</b><br />
          and <b>better</b> with us
        </h1>
        <a href="" class="btn btn-primary tombol">Our Work</a>
      </div>
    </div>
    <!-- Akhir Jumbotron -->

    <!-- Container -->
    <div class="container">
      <!-- Info Panel -->
      <div class="row justify-content-center">
        <div class="col-10 info-panel">
          <div class="row">
            <div class="col-lg">
              <img src="img/employee.png" alt="employee" class="float-left" />
              <h4>24 Hours</h4>
              <p>Lorem ipsum dolor sit amet.</p>
            </div>
            <div class="col-lg">
              <img src="img/hires.png" alt="hires" class="float-left" />
              <h4><High-Res></High-Res></h4>
              <p>Lorem ipsum dolor sit amet.</p>
            </div>
            <div class="col-lg">
              <img src="img/security.png" alt="security" class="float-left" />
              <h4>security</h4>
              <p>Lorem ipsum dolor sit amet.</p>
            </div>
          </div>
        </div>
      </div>

      <!-- Akhir Info Panel -->

      <!-- Working Space -->
      <div class="row workingspace">
        <div class="col-lg-6">
          <img
            src="img/workingspace.png"
            alt="workingspace"
            class="img-fluid"
          />
        </div>
        <div class="col-lg-5">
          <h3>You <b>Work</b> like at <b>home</b></h3>
          <p>
            Bekerja dengan suasana hati yang lebih asik dan mempelajari hal baru
            setiap harinya.
          </p>
          <a href="" class="btn btn-primary tombol">Gallery</a>
        </div>
      </div>

      <!-- Akhir Working Space -->
      <!-- Testimonial -->
      <section class="testimonial">
        <div class="row justify-content-center">
          <div class="col-lg-8">
            <h5>
              " Bekerja dengan suasana hati yang lebih asik dan mempelajari hal
              baru setiap harinya. "
            </h5>
          </div>
        </div>

        <div class="row justify-content-center">
          <div class="col-lg-6 justify-content-center d-flex">
            <figure class="figure">
              <img
                src="img/img1.png"
                class="figure-img img-fluid rounded-circle"
                alt="Testi1"
              />
            </figure>
            <figure class="figure">
              <img
                src="img/img2.png"
                class="figure-img img-fluid rounded-circle utama"
                alt="Testi2"
              />
              <figcaption class="figure-caption">
                <h5>Sunny Ye</h5>
                <p>Designer</p>
              </figcaption>
            </figure>
            <figure class="figure">
              <img
                src="img/img3.png"
                class="figure-img img-fluid rounded-circle"
                alt="Testi3"
              />
            </figure>
          </div>
        </div>
      </section>
      <!-- Akhir Testimonial -->

      <!-- Footer -->
      <div class="row footer">
        <div class="col text-center">
          <p>2021 All Rights Reserved by Lukman Ferdiansyah</p>
        </div>
      </div>
      <!-- Akhir Footer -->
    </div>
    <!-- Akhir Container -->

    <!-- Optional JavaScript -->

    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script
      src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
      integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js"
      integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"
      integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
