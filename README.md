<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <title>Car Website</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous" />
  <link rel="stylesheet" href="car.css">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css" />

  <script src="https://code.jquery.com/jquery-1.12.4.min.js" integrity="sha256-ZosEbRLbNQzLpnKIkEdrPv7lOy9C27hHQ+Xp8a4MxAQ=" crossorigin="anonymous"></script>
</head>

<body>
  <header class="header-area">
    <div class="navbar-area">
      <nav class="site-navbar">
        <a href="#home" class="site-logo">JourneyJive</a>

        <div class="linsk flex">
          <ul>
            <li><a href="#">home</a></li>
            <li><a href="#">about</a></li>
            <li><a href="#">service</a></li>
            <li><a href="#">contact</a></li>
            <li><a href="#">review</a></li>
          </ul>

          <div class="account">
            <i class="fas fa-search"></i>
            <i class="fas fa-phone-alt"> </i>
            <span>Call : +123 456 7898</span>
          </div>


          <div class="nav-toggler">
            <i class="fas fa-bars"></i>
          </div>
        </div>
      </nav>
    </div>
  </header>
  <script>
    const navToggler = document.querySelector('.nav-toggler');
    const navMenu = document.querySelector('.site-navbar ul');
    const navLinks = document.querySelectorAll('.site-navbar a');

    allEventListners();

    function allEventListners() {
      navToggler.addEventListener('click', togglerClick);
      navLinks.forEach(elem => elem.addEventListener('click', navLinkClick));
    }

    function togglerClick() {
      navToggler.classList.toggle('toggler-open');
      navMenu.classList.toggle('open');
    }
  </script>



  <section class="home top">
    <div class="container">
      <div class="circle"></div>
      <div class="owl-carousel owl-theme">
        <div class="item flex">
          <div class="left mtop">
            <h1>Find,book and <br> rent a car Easily</h1>
            <br>
            <p style="font-size: 20px;">Get a car ehereever and whenever you <br> need it with your IOS and Android device
            </p>
            <div class="button">
              <button class="btn1">Read More</button>
              <button class="btn2">Contact Us</button>
            </div>
          </div>
          <div class="right mtop">
            <img src="https://images.pexels.com/photos/1335077/pexels-photo-1335077.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="">
          </div>
        </div>
        <div class="item flex">
          <div class="left mtop">
            <h1>Find,book and <br> rent a car Easily</h1>
            <br>
            <p style="font-size: 20px;">Get a car ehereever and whenever you <br> need it with your IOS and Android device
            </p>
            <div class="button">
              <button class="btn1">Read More</button>
              <button class="btn2">Contact Us</button>
            </div>
          </div>
          <div class="right mtop">
            <img src="https://images.pexels.com/photos/112460/pexels-photo-112460.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
          </div>
        </div>
        <div class="item flex">
          <div class="left mtop">
            <h1>Find,book and <br> rent a car Easily</h1>
            <br>
            <p style="font-size: 20px;">Get a car ehereever and whenever you <br> need it with your IOS and Android device
            </p>
            <div class="button">
              <button class="btn1">Read More</button>
              <button class="btn2">Contact Us</button>
            </div>
          </div>
          <div class="right mtop">
            <img src="https://images.pexels.com/photos/116675/pexels-photo-116675.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="section">
    <div class="booking-form">
        <h2>Book Your Car</h2>
        <form>
            <label for="carType">Car Type:</label>
            <select id="carType" name="carType">
                <option value="">Swift Dezire</option>
                <option value="xuv">XUV</option>
                <option value="ford">Ford</option>
                <option value="sumo">Sumo</option>
            </select>

            <label for="pickupDate">Pickup Date:</label>
            <input type="date" id="pickupDate" name="pickupDate" required>

            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>
            
            <a href="book.html"><input type="submit" value="Book Now"></a>
        </form>
    </div>
</section>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.js"></script>


  <script>
    $('.owl-carousel').owlCarousel({
      loop: true,
      margin: 10,
      nav: false,
      responsive: {
        0: {
          items: 1
        },
        768: {
          items: 1
        },
        1000: {
          items: 1
        }
      }
    })
  </script>


  <section class="services">
    <div class="container">
      <h2>Available Cars</h2>

      <div class="content grid mtop">
        <div class="box">
          <img src="https://images.pexels.com/photos/170811/pexels-photo-170811.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
          <h3>BMW</h3>
          <p>Driver Services With Comfort Ride</p>
          <a href="#">Read More <i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
        <div class="box">
          <img src="https://images.pexels.com/photos/9155310/pexels-photo-9155310.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
          <h3>LAND ROVER</h3>
          <p>Driver Services With Comfort Ride</p>
          <a href="#">BOOK NOW<i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
        <div class="box">
          <img src="data:image/jpeg;base64,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" alt="">
          <h3>SWIFT DZIRE</h3>
          <p>Driver Services With Comfort Ride</p>
          <a href="#">BOOK NOW<i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
        <div class="box">
          <img src="https://images.pexels.com/photos/136872/pexels-photo-136872.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
          <h3>MERCEDES</h3>
          <p>Driver Services With Comfort Ride</p>
          <a href="#">BOOK NOW<i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
        <div class="box">
          <img src="data:image/jpeg;base64,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" alt="">
          <h3>TATA SUMO</h3>
          <p>Driver Services With Comfort Ride</p>
          <a href="#">BOOK NOW<i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
        <div class="box">
          <img src="https://images.pexels.com/photos/337909/pexels-photo-337909.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
          <h3>PORSCHE</h3>
          <p>Driver Services With Comfort Ride</p>
          <a href="#">BOOK NOW <i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
      </div>
    </div>
  </section>

   <br><br><br>

  <section class="about">
    <div class="container flex">
      <div class="circle"></div>
      <div class="left top">
        <img src="https://images.pexels.com/photos/799443/pexels-photo-799443.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
      </div>
      <div class="right top">
        <h1>About Us </h1>
        <p>
          Welcome to JOURNEYJIVE, where convenience meets mobility! We are your go-to destination for seamless and stress-free car rentals, designed to elevate your travel experience.<br>At JOURNEYJIVE, we understand that every journey is unique, and we strive to make your transportation needs our top priority. Whether you're a solo traveler exploring new horizons, a family embarking on a memorable road trip, or a business professional in need of reliable transportation, we've got you covered. </p>
          <br>
          <button class="btn2">Read More</button>
      </div>
    </div>
  </section>



  <section class="services choose top">
    <div class="container">
      <h1>Why Choose Us</h1>

      <div class="content grid mtop">
        <div class="box">
          <img src="https://images.pexels.com/photos/799443/pexels-photo-799443.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
          <h3>24/7 Customer Support</h3>
          <p>We want you to have a stress-free rental experience,so we make it easy to hire a car.</p>
          <a href="#">Read More <i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
        <div class="box">
          <img src="https://images.ctfassets.net/2sam6k0rncvg/HRa9841pfbF17isgOBQkl/1ef85d74dd4b8c82eb1f5b3cc60c48ec/segments-of-cars-in-india.png" alt="">
          <h3>Wide Selection of Cars </h3>
          <p>We want you to have a stress-free rental experience,so we make it easy to hire a car.</p>
          <a href="#">Read More <i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
        <div class="box">
          <img src="https://www.biztechcs.com/wp-content/uploads/2023/09/A-Complete-Guide-to-Developing-a-Car-Rental-Reservation-System-inside-jpg.webp" alt="">
          <h3>Secure and Easy Booking Process</h3>
          <p>We want you to have a stress-free rental experience,so we make it easy to hire a car.</p>
          <a href="#">Read More <i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
      </div>
    </div>
  </section>



  <section class="customer top">
    <div class="container">
      <h1>Reviews </h1>
      <p>Even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to </p>

      <div class="owl-carousel owl-theme mtop content">
        <div class="item flex">
          <div class="image">
            <div class="img">
              <img src="https://images.pexels.com/photos/769772/pexels-photo-769772.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
            </div>
          </div>
          <div class="text">
            <div class="heading flex1">
              <div class="para">
                <h3>MORO JINK</h3>
                <h5>CUSTOMER</h5>
              </div>
              <div class="para">
                <i class="fas fa-quote-left"></i>
              </div>
            </div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
        </div>
        <div class="item flex">
          <div class="image">
            <div class="img">
              <img src="https://images.pexels.com/photos/1043473/pexels-photo-1043473.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
            </div>
          </div>
          <div class="text">
            <div class="heading flex1">
              <div class="para">
                <h3>SIRO KUKI</h3>
                <h5>CUSTOMER</h5>
              </div>
              <div class="para">
                <i class="fas fa-quote-left"></i>
              </div>
            </div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
        </div>
        <div class="item flex">
          <div class="image">
            <div class="img">
              <img src="https://images.pexels.com/photos/1181690/pexels-photo-1181690.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
            </div>
          </div>
          <div class="text">
            <div class="heading flex1">
              <div class="para">
                <h3>LILY SUI</h3>
                <h5>CUSTOMER</h5>
              </div>
              <div class="para">
                <i class="fas fa-quote-left"></i>
              </div>
            </div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
        </div>
      </div>
    </div>
  </section>


  <script>
    $('.owl-carousel').owlCarousel({
      loop: true,
      margin: 20,
      nav: true,
      dots: false,
      navText: ["<i class='far fa-chevron-left'></i>", "<i class='far fa-chevron-right'></i>"],
      responsive: {
        512: {
          items: 1
        },
        768: {
          items: 1
        },
        1000: {
          items: 1
        }
      }
    })
  </script>


  <section class="contact top">
    <div class="container flex">
      <div class="circle"> </div>
      <div class="left">
        <h1>Get In Touch</h1>

        <form>
          <input type="text" placeholder="Your Name">
          <input type="text" placeholder="Your Email">
          <input type="text" placeholder="Your Phone">
          <textarea rows="5" cols="80">Message</textarea>
          <button class="btn2">SEND</button>
        </form>
      </div>
      <div class="right">
        <div class="img">
          <img src="https://img.freepik.com/premium-vector/business-data-custodian-vectors-illustration-flat_220346-9581.jpg?w=1380" alt="">
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container top">
      <div class="content grid">
        <div class="box flex">
          <a href="https://www.google.com/maps/d/viewer?mid=1B1lAsUpYFg82Je7XN1_cxRPf1UU&hl=en_US&ll=21.843640760307327%2C82.75998700000001&z=5"><i class="fas fa-map-marker-alt"></i></a>
          <span>Loaction</span>
        </div>
        <div class="box flex">
          <i class="fa fa-phone-alt"></i>
          <span>+123 456 7998</span>
        </div>
        <div class="box flex">
          <a href="https://www.gmail.com/"><i class="fa fa-envelope"></i></a>
          <span>journeyjive@example.com</span>
        </div>
        <div class="box flex">
          <input type="text" placeholder="Your Email address">
          <i class="fas fa-long-arrow-alt-right"></i>
        </div>
      </div>

      <div class="social mtop">
        <div class="logo">
          <h1>MOTORA</h1>
        </div>
        <ul>
          <li> <a href="https://www.facebook.com/"><i class="fab fa-facebook-f"></i></a></li>
          <li> <a href="https://www.instagram.com/"><i class="fab fa-instagram"></i></a></li>
          <li> <a href="https://www.twitter.com/"><i class="fab fa-twitter"></i></a></li>
          <li> <a href="https://www.youtube.com/"><i class="fab fa-youtube"></i></a></li>
        </ul>
      </div>
    </div>
  </footer>

  <div class="legal">
    <p>Copyright &copy; 2021 Copyright Holder All Rights Reserved.</p>
  </div>
</body>

</html>
