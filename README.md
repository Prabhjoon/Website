<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
  <!-- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css"> -->
  <link rel="stylesheet" href="style.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Belanosima&family=Monoton&family=Roboto+Flex:opsz,wght@8..144,100&display=swap"
    rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Belanosima&family=Miss+Fajardose&family=Monoton&family=Roboto+Flex:opsz,wght@8..144,100&display=swap"
    rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/flat-ui/2.2.2/css/flat-ui.min.css"
    integrity="sha512-PvB3Q4vTvWD/9aiiELYI3uebup/4mtou3Mc/uGudC/Zl+C9BdKUkAI+5jORfA+fvLK4DpzC5VyEN7P2kK43hjg=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
  <div class="appetizer-header">
    <div class="top-bar d-md-block d-lg-block d-sm-none">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 d-flex">
            <div class="col-md number d-flex align-item-center pt-2">
              <i class='bx bxs-phone'></i>
              <div class="name">+ 1235 2355 98</div>
            </div>
            <div class="col-md email d-flex align-item-center pt-2">
              <i class='bx bxs-paper-plane py-2 ps-5'></i>
              <div class="name ps-2">youremail@email.com</div>
            </div>
            <div class="col-md-5 time d-flex align-items-center justify-content-end pt-2">
              <p>
                <span>Open hours:</span>
                <span>Monday - Sunday</span>
                <span>8:00AM - 9:00PM</span>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <nav class="navbar sticky-top bg-opacity-10">

      <!-- <a class="navbar-brand" href="#">Sticky top</a> -->
      <div class="nav">
        <div class="container">
          <nav class="navbar navbar-expand-lg ">
            <div class="container-fluid position-relative ">
              <a class="navbar-brand text-light weight-element" href="#">Appetizer</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse bg-transparent" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0 prabh">
                  <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="#">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Menu</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Blog</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link book-table" href="#">Book a table</a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
        </div>
      </div>
    </nav>

  </div>

  <section class="slider">


    <div id="carouselExampleCaptions" class="carousel slide z-n1">
      <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="container">
              <div class="col-lg-12">
                <h1 class="text-center">Our Delicious Specialties</h1>
                <p class="position-absolute button-od">
                  <button type="button" class="btn btn-warning btnaa">Order Now</button>
                  <button type="button" class="btn btn-outline-light btnaa" id="btni">View Menu</button>
                </p>
              </div>
            </div>

            <!-- <img src="images/bg_1.jpg.webp" class="d-block w-100" alt="..."> -->



          </div>

          <div class="carousel-item second-crousal">
            <div class="container">
              <div class="col-lg-12">
                <h1 class="text-center crousal-heading-two">The Best Place to Kick of Your Day</h1>
                <p class="position-absolute button-od">
                  <button type="button" class="btn btn-warning btnaa">Order Now</button>
                  <button type="button" class="btn btn-outline-light btnaa"  id="btni">View Menu</button>
                </p>
              </div>
            </div>

            <!-- <img src="images/bg_2.jpg.webp" class="d-block w-100" alt="..."> -->

          </div>

          <div class="carousel-item third-crausal">
            <div class="container">
              <div class="col-lg-12">
                <h1 class="text-center crousal-heading-three">Creamy Hot and Ready to Serve</h1>
                <p class="position-absolute button-od">
                  <button type="button" class="btn btn-warning btnaa">Order Now</button>
                  <button type="button" class="btn btn-outline-light btnaa"  id="btni">View Menu</button>
                </p>
              </div>
            </div>

            <!-- <img src="images/bg_3.jpg.webp" class="d-block w-100" alt="..."> -->

          </div>
        </div>
      </div>
    </div>
  </section>
  <section>
    <div class="about">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-10">
            <div class="about-first-heading text-center position-relative">
              <span>About</span>
              <h2 class="about-ka-h2">Appetizer Restaurant</h2>
              <p class="text-center">On her way she met a copy. The copy warned the Little Blind Text, that where it
                came from it would have
                been rewritten a thousand times and everything that was left from its origin would be the word "and" and
                the Little Blind Text should turn around and return to its own, safe country. A small river named Duden
                flows by their place and supplies it with the necessary regelialia. It is a paradisematic country, in
                which roasted parts of sentences fly into your mouth.</p>
            </div>
            <div class="video d-flex justify-content-center">
              <div class="icon-video d-flex justify-content-center align-items-center">
                <i class='bx bx-play'></i>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

  </section>
  <section class="about-two">
  </section>

  <div class="container">
    <div class="row">
      <div class="col-lg-12 justify-content-center">
        <div class="background-image-two d-flex">
          <div class="col-lg-3">
            <div class="number-18">
              <div class="text-18">
                <strong class="num-first d-flex justify-content-center">18</strong>
              </div>
              <div class="years d-flex justify-content-center">years of experiance</div>
            </div>
          </div>

          <div class="col-lg-3">
            <div class="number-18">
              <div class="text-18">
                <strong class="num-first d-flex justify-content-center">15,000</strong>
              </div>
              <div class="years d-flex justify-content-center">Happy Customers</div>
            </div>
          </div>

          <div class="col-lg-3">
            <div class="number-18">
              <div class="text-18">
                <strong class="num-first d-flex justify-content-center">100</strong>
              </div>
              <div class="years d-flex justify-content-center">Menus</div>
            </div>
          </div>

          <div class="col-lg-3">
            <div class="number-18">
              <div class="text-18">
                <strong class="num-first d-flex justify-content-center">20</strong>
              </div>
              <div class="years d-flex justify-content-center">Staffs</div>
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>
  
  <section class="services">
    <div class="container">
      <div class="row">
        <div class="col-lg-12 services-new-head">
          <div class="services-heading text-center position-relative">
            <span>Services</span>
            <h2 class="catering">Catering Services</h2>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-4">
            <div class="birthday-first">
              <div class="icon-cake-cover d-flex justify-content-center">
                <div class="icon-cake d-flex justify-content-center align-items-center">
                 <img src="images/birthday-cake (1).png" alt="">
                </div>
              </div>
              
              <div class="birthday-head d-flex justify-content-center">
                <div class="birthday-content text-center">
                  <h3>Birthday Party</h3>
                  <p>Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic.
                  </p>
                </div>
              </div>
            </div>
          </div>
          
          <div class="col-lg-4">
            <div class="birthday-first">
              <div class="icon-cake-cover d-flex justify-content-center">
                <div class="icon-cake d-flex justify-content-center align-items-center">
                 <img src="images/meeting.png" alt="">
                </div>
              </div>
              
              <div class="birthday-head d-flex justify-content-center">
                <div class="birthday-content text-center">
                  <h3>Birthday Party</h3>
                  <p>Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic.
                  </p>
                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4">
            <div class="birthday-first">
              <div class="icon-cake-cover d-flex justify-content-center">
                <div class="icon-cake d-flex justify-content-center align-items-center">
                  <img src="images/tray (2).png" alt="">
                </div>
              </div>
              
              <div class="birthday-head d-flex justify-content-center">
                <div class="birthday-content text-center">
                  <h3>Birthday Party</h3>
                  <p>Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>






  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm"
    crossorigin="anonymous"></script>
</body>

</html>

* css files *

  .appetizer-header {
    position: absolute;
    width: 100%;
}

.top-bar {

    color: rgba(255, 255, 255, 0.5);
    color: #fff;
    /* z-index: 99; */
}

.top-bar .number i {
    /* background-color: #ffa323; */
    color: rgba(255, 255, 255, 0.5);
    font-size: 16px;
    padding-right: 3px;
    padding-top: 4px;
}

.top-bar .number .name {
    color: rgba(255, 255, 255, 0.5);
}

.top-bar .email .name {
    color: rgba(255, 255, 255, 0.5);
}

.top-bar .time span {
    color: rgba(255, 255, 255, 0.5);
}

.top-bar .email i {
    color: rgba(255, 255, 255, 0.5);
}

.nav {
    width: 100%;
    --bs-bg-opacity: 0;
}

.navbar {
    width: 100%;
    color: #fff;
}

.navbar .weight-element {
    font-weight: 900;
}
.prabh{
    position: absolute;
    left: 62%;
    margin-left: 50%;
}

.navbar-item li a {
    text-decoration: none;
}

/* .elvish {
    margin-left: 59%;
} */

.nav-item a {
    color: #fff;
}

.nav-item .book-table {
    /* border: 2px solid #ffa323; */
    padding-right: 20px;
    background: #ffa323;
    color: #fff;
    border-radius: 5px;
}

/* .slider{
    background-color: #00000025; 
} */
.carousel-item {
    background-image: linear-gradient(rgba(0, 0, 0, 0.644), rgba(0, 0, 0, 0.623)), url("images/bg_1.jpg.webp");
    width: 100%;
    height: 650px;
    object-fit: cover;
    background-image: cover;
    background-size: 100% 100%;
    background-repeat: no-repeat;

}

.second-crousal {
    background-image: linear-gradient(rgba(0, 0, 0, 0.644), rgba(0, 0, 0, 0.623)), url("images/bg_2.jpg.webp");
    width: 100%;
    height: 650px;
    object-fit: cover;
    background-image: cover;
    background-size: 100% 100%;
    background-repeat: no-repeat;
}

.third-crausal {
    background-image: linear-gradient(rgba(0, 0, 0, 0.644), rgba(0, 0, 0, 0.623)), url("images/bg_3.jpg.webp");
    width: 100%;
    height: 650px;
    object-fit: cover;
    background-image: cover;
    background-size: 100% 100%;
    background-repeat: no-repeat;
}

.carousel-inner .carousel-item h1 {
    position: absolute;
    font-size: 75px;
    /* font-family: 'Monoton', 'cursive'; */
font-weight: 400;
font-family: 'Monoton', cursive;

    color: #fff;
    width: 50%;
    left: 23%;
    top: 33%;
}

.carousel-inner .carousel-item .crousal-heading-two {
    position: absolute;
    font-size: 75px;
    font-family: 'Monoton', 'cursive';
    color: #fff;
    width: 90%;
    left: 4%;
    top: 33%;

}

.carousel-inner .carousel-item .crousal-heading-three {
    position: absolute;
    font-size: 75px;
    font-family: 'Monoton', 'cursive';
    color: #fff;
    width: 80%;
    left: 9%;
    top: 33%;
}

.carousel-inner .carousel-item .button-od {
    top: 65%;
    left: 39%;
}

.carousel-inner .carousel-item .button-od .btnaa {
    border-radius: 1px;
    padding: 13px 22px;
    color: #fff;
}
.carousel-inner .carousel-item .button-od  #btni{
    border: 1px solid #fff;
}

.about {
    padding-top: 9%;
    background-color: #ffffff;
}



.about-ka-h2 {
    position: relative;
    color: #000;
}

.about .about-first-heading span {
    position: absolute;
    font-family: 'Miss Fajardose', 'cursive';
    font-size: 100px;
    color: #ffa323;
    top: -72px;
    left: 42%;

}

.about .about-first-heading h2 {
    font-weight: 600;
    font-size: 50px;
    font-style: normal;
    padding-bottom: 10px;
}

.about .about-first-heading p {
    color: #666666;
    line-height: 35px;
    font-size: 17px;
    font-weight: 400;
    width: 100%;
    padding-left: 58px;
    padding-right: 58px;
}

.video {
    width: 100%;
    position: relative;

}

.icon-video {
    width: 90px;
    height: 90px;
    background-color: #ffa323;
    border-radius: 50%;
    margin-bottom: -25px;

}

.icon-video i {
    color: #ffffff;
    font-size: 47px;

}

.cover {
    overflow: hidden;
}

.about-two {
    background-image: url('images/bg_4.jpg.webp');
    width: 100%;
    height: 100vh;
    /* background-repeat: no-repeat;
    background-size: cover; */
    z-index: -8;
    top: 5%;
    padding: 10% 0px;
    object-fit: cover;
    position: fixed;
}

/* .background-image-two {
    padding-top: 23px;
}

.col-lg-3 {
    padding-top: 12px;
} */

.number-18 .num-first {
    font-size: 40px;
    color: #000;
}

.number-18 .years {
    color: rgba(0, 0, 0, 0.8);
    font-size: 16px;
    text-transform: capitalize;
}

.services {
    background-color: #fafafa;
    padding-top: 75px;
    margin-top: 100px;
    padding-bottom: 100px;
}

.col-lg-12 {
    padding-top: 23px;
}

.catering {
    position: relative;

}

.services-heading span {
    position: absolute;
    font-family: 'Miss Fajardose', 'cursive';
    font-size: 100px;
    color: #ffa323;
    left: 41%;
    top: -149%;
}

.services-new-head {
    padding-bottom: 50px;
}

.services-heading h2 {
    color: #000;
    font-weight: 900;
    font-size: 50px;
}

.birthday-first .icon-cake {
    width: 130px;
    height: 130px;
    border-radius: 50%;
    background-color: #000;
}

.icon-cake-cover {
    padding-bottom: 30px;
}

.icon-cake i {
    color: #ffffff;
    font-size: 34px;
}

.icon-cake img {
    font-size: 24px;
}

.birthday-content h3 {
    padding-bottom: 14px;
    color: #000;
}

.birthday-content p {
    padding: 0px 34px;
    color: #666666;
    font-size: 17px;
}
