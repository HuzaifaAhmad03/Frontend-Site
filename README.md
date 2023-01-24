# Wallpaper-Site

<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>HzWallpaper</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&family=Satisfy&display=swap" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN"
    crossorigin="anonymous"></script>
  <link rel="stylesheet" href="css/styles.css" class="theme">
  <link rel="stylesheet" href="css/switch.css">
  <script src="https://use.fontawesome.com/releases/vVERSION/js/all.js" data-mutate-approach="sync"></script>
  <!--
  <script>
    function toggleTheme(value) {
        var sheets = document
            .getElementsByClassName('theme');

        sheets[0].href = value;
    }
</script>
  -->
  <script>
    document.addEventListener('DOMContentLoaded', function () {
      var checkbox = document.querySelector('input[type="checkbox"]');

      checkbox.addEventListener('change', function () {
        if (checkbox.checked) {
          var sheets = document.getElementsByClassName('theme');
          sheets[0].href = 'css/dark.css';
        } else {
          var sheets = document.getElementsByClassName('theme');
          sheets[0].href = 'css/styles.css';
          console.log('Not checked');
        }
      });
    });
  </script>

</head>

<body class="main">

  <section id="title">

    <div class="container-fluid">
      <!-- Nav Bar -->
      <nav class="navbar navbar-expand-lg">
        <a class="navbar-brand" href="">HzWallpaper</a>
        <div>
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="mailto:playgamegamerszone@gmail.com"">Contact</a>
            </li>
            <li class=" nav-item">
                <a class="nav-link" href="#features">Features</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#testimonials">Testimonials</a>
            </li>
          </ul>
        </div>
      </nav>



      <!-- Title -->


      <div class="row titlerow">

        <div class="col-lg-6">
          <h1 class="title-text">Download organised wallpapers for your PC and Smartphone.</h1>
          <button type="button" class="btn btn-dark btn-lg"><a href="#Download" class="title-btn-pc"><img
                src="images/desktop_icon.png" height="20px"> Download</button></a>
          <button type="button" class="btn btn-outline-dark btn-lg"><a href="#mbwallpapers" class="title-btn-mb"><img
                src="images/mobile_icon.png" height="20px"> Download</button></a>
        </div>

        <div class="col-lg-6">
          <img class="titleimage" src="images/title_image.png">
        </div>

        <div class="col-lg-6 switchH">
          <input type="checkbox" id="toggle_checkbox"
            onclick="toggleTheme('css/dark.css'); toggleTheme('css/styles.css')">
          <label for="toggle_checkbox" class="switchH">
            <div id="star">
              <div class="star" id="star-1">★</div>
              <div class="star" id="star-2">★</div>
            </div>
            <div id="moon"></div>
          </label>
        </div>

      </div>

    </div>
  </section>


  <!-- Features -->

  <section id="features">

    <div class="row">

      <div class="col-lg-4 feature-box">
        <img class="feature-img" src="images/checkmark.png">
        <h3>Easy to Organise.</h3>
        <p class="subtext">Simple and Time saving.</p>
      </div>

      <div class="col-lg-4 feature-box">
        <img class="feature-img" src="images/desktop_checked.png">
        <img class="feature-img" src="images/phone_checked.png">
        <h3>Different Categories</h3>
        <p class="subtext">We have all the types of wallpapers based on your desrie.</p>
      </div>

      <div class="col-lg-4 feature-box">
        <img class="feature-img" src="images/thumb.png">
        <h3>Guaranteed to work.</h3>
        <p class="subtext">I mean...You just have to set them as backgroud image.</p>
      </div>

    </div>

  </section>


  <!-- Testimonials -->
  <section id="testimonials">

    <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item">
          <h2 class="testimonial">Found the perfect wallpaper for both my Personal and work Devices.</h2>
          <img src="images/testimonial2.png" class="testimonial-img">
          <em>Viraj, Bangalore</em>
        </div>
        <div class="carousel-item">
          <h2 class="testimonial">These wallpapers make my PC desktop look a lot more presentable.</h2>
          <img src="images/testimonial3.png" class="testimonial-img">
          <em>Anshuman, Mumbai</em>
        </div>
        <div class="carousel-item active">
          <h2 class="testimonial">I no longer have to keep seperating and rearranging my desktop. Really very helpful.
          </h2>
          <img src="images/testimonial1.png" class="testimonial-img">
          <em>Jaydeep, Delhi</em>
        </div>
      </div>
      <button class="carbtn carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying"
        data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carbtn carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying"
        data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

  </section>



  <!-- Download -->


  <section id="Download">

    <h2>A Wallpaper for Every User's Needs</h2>
    <p style="color: rgb(126, 126, 155);">Simple and Stunning wallpapers for you device</p>

    <div class="row">

      <div class="card-col col-lg-3 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Professional Desktop</h3>
          </div>
          <div class="card-body">
            <h2>Free</h2>
            <p class="img-para"><img class="down-img" src="images/testimonial2.png">
              <a href="images/testimonial2.png" download="Calm_Green"><button class="down-one">Download</button></a></p>
            <p>Different Fields for Organisation</p>
            <p>Productive and Professional Look</p>
            <button class="btn btn-lg btn-block btn-primary" type="button"><img src="images/download_icon.png"> Download All</button>
          </div>
        </div>
      </div>

      <div class="card-col col-lg-3 col-md-6" id="d-wallpapers">
        <div class="card">
          <div class="card-header">
            <h3>Desktop Wallpapers</h3>
          </div>
          <div class="card-body">
            <h2>Free</h2>
            <p class="img-para"><img class="down-img" src="images/testimonial3.png">
              <a href="images/testimonial3.png" download="Anime_Blues"><button class="down-one">Download</button></a></p>
            <p class="img-para"><img class="down-img" src="images/testimonial4.png">
              <a href="images/testimonial4.png" download="Uchiha_Itachi"><button class="down-one">Download</button></a></p>
            <p>Different Themed wallpapers for your PC</p>
            <button class="btn btn-lg btn-block btn-primary" type="button"><img src="images/download_icon.png"> Download
              All</button>
          </div>
        </div>
      </div>

      <div class="card-col col-lg-3" id="mbwallpapers">
        <div class="card">
          <div class="card-header">
            <h3>Mobile Wallpapers</h3>
          </div>
          <div class="card-body">
            <h2>Free</h2>
            <p class="img-para"><img class="down-img-mob" src="images/mpic1.jpg">
              <a href="images/mpic1.jpg" download="Samurai"><button class="down-one">Download</button></a></p>
            <p class="img-para"><img class="down-img-mob" src="images/mpic2.png">
              <a href="images/mpic2.png" download="Anime_Blues_mb"><button class="down-one">Download</button></a></p>
            <p class="img-para"><img class="down-img-mob" src="images/mpic3.jpeg">
              <a href="images/mpic3.jpeg" download="Scenery"><button class="down-one">Download</button></a></p>
            <p>Organised wallpapers for your mobile devices</p>
            <button class="btn btn-lg btn-block btn-primary" type="button"><img src="images/download_icon.png"> Download
              All</button>
          </div>
        </div>
      </div>

    </div>

  </section>


  <footer id="footer">

    <section id="cta">
      <h3>Find the Perfect wallpaper for your PC/Mobile.</h3>
      <button type="button" class="btn btn-dark btn-lg"><a href="#d-wallpapers" class="title-btn-pc"><img
            src="images/desktop_icon.png" height="20px"> Download</a></button>
      <button type="button" class="btn btn-outline-dark btn-lg"><a href="#mbwallpapers" class="title-btn-mb"><img
            src="images/mobile_icon.png" height="20px"> Download</a></button>
    </section>
    <a href="mailto:playgamegamerszone@gmail.com" class="nav-link">Contact</a>
    <p>© Copyright HzWallpaper</p>

  </footer>

</body>

</html>
