##1. Skeleton##

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Richemont | Formations de Noël</title>
</head>
<body>

  <h1>Hello!</h1>

</body>
</html>

```

##2. HTML##

```
<body>

  <img src="images/richemont-logo.png" alt="logo richemont">

  <h1>Chez Richemont, révelez <strong>l'exceptionnel</strong> en vous !</h1>
  <h3>Participez à nos formations de Noël</h2>

  <a href="">Je veux participer</a>

  <h2>Pourquoi se former ?</h2>

  <img src="images/001-desktop.png">
  <h3>Appronfondir ses compétences</h3>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

  <img src="images/002-notebook.png">
  <h3>S'épanouir dans son travail</h3>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

  <img src="images/003-abacus.png" alt="">
  <h3>Découvrir un nouveau métier</h3>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

  <img src="images/004-chat.png" alt="">
  <h3>Etre acteur de son évolution</h3>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

  <p>Richemont Landing Page / 2019</p>

  <ul>
    <li><a href="">Email</a></li>
    <li><a href="">Twitter</a></li>
    <li><a href="">Linkedin</a></li>
  </ul>

</body>
```

##3. CSS##

```
body {
  font-family: "Open Sans";
}

h1 {
  font-size: 54px;
}

a {
  text-decoration: none;
}

p {
  text-align: center;
}
```

##4. DIV##

```
<body>

  <div id="banner">
    <img src="images/richemont-logo.png" alt="logo richemont">

    <h1>Chez Richemont, révelez <strong>l'exceptionnel</strong> en vous !</h1>
    <h2>Participez à nos formations de Noël</h2>

    <a href="">Je veux participer</a>
  </div>

  <div id="information-container">
    <h2>Pourquoi se former ?</h2>

    <div>
      <img src="images/001-desktop.png">
      <h3>Appronfondir ses compétences</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>

    <div>
      <img src="images/002-notebook.png">
      <h3>S'épanouir dans son travail</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>

    <div>
      <img src="images/003-abacus.png" alt="">
      <h3>Découvrir un nouveau métier</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>

    <div>
      <img src="images/004-chat.png" alt="">
      <h3>Etre acteur de son évolution</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>
  </div>

  <div id="footer">
    <p>Richemont Landing Page / 2019</p>

    <ul>
      <li><a href="">Email</a></li>
      <li><a href="">Twitter</a></li>
      <li><a href="">Linkedin</a></li>
    </ul>
  </div>

</body>
```

##5. ID & CLASS##

```
<body>

  <div id="banner">
    <img id="logo" src="images/richemont-logo.png" alt="logo richemont">

    <h1>Chez Richemont, révelez <strong>l'exceptionnel</strong> en vous !</h1>
    <h2>Participez à nos formations de Noël</h2>

    <a href="">Je veux participer</a>
  </div>

  <div id="information-container">
    <h2>Pourquoi se former ?</h2>

    <div class="information-feature">
      <img src="images/001-desktop.png" class="information-icon">
      <h3>Appronfondir ses compétences</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>

    <div class="information-feature">
      <img src="images/002-notebook.png" class="information-icon">
      <h3>S'épanouir dans son travail</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>

    <div class="information-feature">
      <img src="images/003-abacus.png" class="information-icon">
      <h3>Découvrir un nouveau métier</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>

    <div class="information-feature">
      <img src="images/004-chat.png" class="information-icon" >
      <h3>Etre acteur de son évolution</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>
  </div>

  <div id="footer">
    <p>Richemont Landing Page / 2019</p>

    <ul>
      <li><a href="">Email</a></li>
      <li><a href="">Twitter</a></li>
      <li><a href="">Linkedin</a></li>
    </ul>
  </div>

</body>
```

##6. CSS##

```
#banner {
  background-image: linear-gradient(rgba(0,0,0,0.4),rgba(0,0,0,0.4)), url('images/richemont-banner.jpg');
  background-size: cover;
  background-position: center;

  text-align: center;
  padding: 150px;

  color: white;
}

#logo {
  height: 80px;
}

#information-container {
  background-color: #ECEDF2;
  padding: 50px;
}

#information-container h2 {
  font-size: 48px;
  color: #15416E;

  text-align: center;

  margin-bottom: 50px;
}

.information-icon {
  height: 70px;
  margin-bottom: 30px;
}

.information-feature {
  background-color: white;
  border-radius: 20px;

  padding: 40px 20px;

  text-align: center;
}

.information-feature h3 {
  font-size: 24px;
  text-align: center;

  margin-bottom: 30px;
}

.information-feature p {
  font-size: 14px;
}

#footer {
  background-color: #15416E;
  color: white;
  padding: 20px;

  text-align: center;
}

#social-media {
  list-style: none;
  display: inline;
  padding: 0;
}

#social-media li {
  display: inline;
}
```

##7. BOOTSTRAP##

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
```

```
<div class="container">
  <div class="row">

    <div class="col-3 col-xs-6">
      <div class="information-feature">
        <img src="images/001-desktop.png" class="information-icon">
        <h3>Appronfondir ses compétences</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      </div>
    </div>

    <div class="col-3 col-xs-6">
      <div class="information-feature">
        <img src="images/002-notebook.png" class="information-icon">
        <h3>S'épanouir dans son travail</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      </div>
    </div>

    <div class="col-3 col-xs-6">
      <div class="information-feature">
        <img src="images/003-abacus.png" class="information-icon">
        <h3>Découvrir un nouveau métier</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      </div>
    </div>

    <div class="col-3 col-xs-6">
      <div class="information-feature">
        <img src="images/004-chat.png" class="information-icon" >
        <h3>Etre acteur de son évolution</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      </div>
    </div>
  </div>

</div>
```

##7. FONTAWESOME##

```
<script src="https://kit.fontawesome.com/6a3f6c3c02.js"></script>
```
```
<div id="footer">
  <p>Richemont Landing Page / 2019</p>

  <ul id="social-media">
    <li><a href=""><i class="fas fa-envelope-square"></i></a></li>
    <li><a href=""><i class="fab fa-twitter-square"></i></a></li>
    <li><a href=""><i class="fab fa-linkedin"></i></a></li>
  </ul>
</div>
```
```
#footer a {
  color: white;
  font-size: 16px;
}

#social-media i {
  font-size: 24px;
  padding: 0 5px;
}
```
