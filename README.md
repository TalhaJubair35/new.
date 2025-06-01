<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TraVello.com</title>

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" />

  <link rel="stylesheet" href="style.css" />

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Ancizar+Serif:ital,wght@0,300..900;1,300..900&family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap"
    rel="stylesheet" />

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Ancizar+Serif:ital,wght@0,300..900;1,300..900&family=Cardo:ital,wght@0,400;0,700;1,400&family=Playwrite+HU:wght@100..400&family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&family=Poppins:ital,wght@0,400;1,100&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap"
    rel="stylesheet" />

  <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
</head>

<body>

  <div class="back-img">
    <header>
      <div class="head">
        <!-- logo+name -->

        <div class="web-name">
          <a href="/index.html">
            <h1>TraVello</h1>
            <img src="/images/travel.png" alt="icon" />
          </a>
        </div>

        <!-- navbar -->

        <div class="navbar">
          <ul>
            <li><a href="/index.html">Home</a></li>
            <li><a href="/Travel_manual.html">Travel Manual</a></li>
            <li><a href="/about.html">About</a></li>
            <li><a href="/Contact.html">Contact</a></li>
          </ul>
        </div>

        <!-- search-bar -->

        <div class="search">
          <form class="example">
            <input type="text" placeholder="Search.." name="search" />
            <button type="submit"><i class="fa fa-search"></i></button>
          </form>
        </div>
      </div>
    </header>

    <!-- main body  -->

    <div class="main-body">
      <div class="description">
        <h1 class="text-3xl font-bold text-center">
          Discover the World with Travello
        </h1>
        <p class="text-center">
          Welcome to Travello, your all-in-one travel platform built for
          explorers, dreamers, and adventurers. Whether you're chasing sunsets
          on tropical beaches, hiking mountain trails, or planning a family
          vacation, Travello makes travel planning simple, fast, and
          personalized.
        </p>
        <div class="btn text-center">
          <button>Book Now</button>
        </div>
      </div>

      <div class="form">
        
          <div>
            <h1>Log In</h1>
          </div>
          <div class="email">
            <label for="email">Enter your Email:</label>
            <input type="email" id="email" placeholder="abcd@gmail.com">
          </div>

          <div class="pass">
            <label for="pass">Password:</label>
            <input type="password" name="pass" id="pass" placeholder="Password">
          </div>

        <div class="sign-up">
          <p>Don't have an account?</p>
          <a href="">Sign-up</a>
        </div>
      </div>
    </div>
  </div>
</body>

</html>
