<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <!-- displays site properly based on user's device -->

  <!-- BootStrap V.5.0.1 -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
  <link rel="stylesheet" href="styles.css">
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png" />
  <title> Social Proof Section</title>
</head>

<body>
  <div class="container-fluid">

    <!-- Top Section: Text(Left) -->
    <div class="row">
      <div class="col-lg-5">
        <h1>10,000+ of our users love our products.</h1>

        <p class="main-text">We only provide great products combined with excellent customer service.
          See what our satisfied customers are saying about our services.</p>
      </div>

      <!-- Top Section: and Star Ratings(Right) -->
      <div class="col-lg-7">
        <div class="accordion">

          <!-- First Rating -->
          <div class="ac" id="ac-1">
            <div class="row">

              <!-- Aligns icon and card title on the same row -->
              <div class="col-lg-5 stars">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
              </div>
              <div class="col-lg-7 text">
                Rated 5 Stars in Reviews
              </div>
            </div>
          </div>

          <!-- Second Rating -->
          <div class="ac" id="ac-2">
            <div class="row">
              <div class="col-lg-5 stars">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
              </div>
              <div class="col-lg-7 text">
                Rated 5 Stars in Report Guru
              </div>
            </div>
          </div>

          <!-- Third Rating -->
          <div class="ac" id="ac-3">
            <div class="row">
              <div class="col-lg-5 stars">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
                <img src="images/icon-star.svg">
              </div>
              <div class="col-lg-7 text">
                Rated 5 Stars in BestTech
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Cards Section. The Social Proof Setion -->
    <div class="row cards">

      <!-- First Card -->

      <!-- Aligns cards in a row based on the device width: 3 on a large screen and 1 on a small screen (12 grid-lines) -->
      <div class="col-lg-4 col-md-6 col-sm-12" id="card-1">
        <div class="card">
          <div class="card-body">
            <div class="row">
              <div class="col-lg-3">
                <img src="images/image-colton.jpg" alt="">
              </div>
              <div class="col-lg-9">
                <h5 class="card-title">Colton Smith</h5>
                <h6 class="card-subtitle">Verified Buyer</h6>
              </div>
            </div>
          </div>
          <p class="card-text">
            "We needed the same printed design as the one we had ordered a week prior.
            Not only did they find the original order, but we also received them in time. Excellent!"
          </p>
        </div>
      </div>

      <!-- Second Card -->
      <div class="col-lg-4 col-md-6 col-sm-12" id="card-2">
        <div class="card">
          <div class="card-body">
            <div class="row">
              <div class="col-lg-3">
                <img src="images/image-irene.jpg" alt="">
              </div>
              <div class="col-lg-9">
                <h5 class="card-title">Irene Roberts</h5>
                <h6 class="card-subtitle">Verified Buyer</h6>
              </div>
            </div>
          </div>
          <p class="card-text">
            "Customer service is always excellent and very quick turn around. Completely
            delighted with the simplicity of the purchase and the speed of delivery."
          </p>
        </div>
      </div>

      <!-- Third Card -->
      <div class="col-lg-4 col-md-6 col-sm-12" id="card-3">
        <div class="card">
          <div class="card-body">
            <div class="row">
              <div class="col-lg-3">
                <img src="images/image-anne.jpg" alt="">
              </div>
              <div class="col-lg-9">
                <h5 class="card-title">Anne Wallace</h5>
                <h6 class="card-subtitle">Verified Buyer</h6>
              </div>
            </div>
          </div>
          <p class="card-text">
            "Put an order with this company and can only praise them for the very high
            standard. Will definitely use them again and recommend them to everyone!"
          </p>
        </div>
      </div>
    </div>

    <footer>
      <div class="attribution">
        Challenge by
        <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. Coded by <a href="#">MacJay</a>.
      </div>
    </footer>
  </div>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
</body>

</html>
