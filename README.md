<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- <link rel="stylesheet" href="css1/stles.css"> -->
    <title>Desktop-1</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
<style>

/* Tehdään varmaan erillinen css-tiedosto, miksi tämä linkki ei toimi???: <link rel="stylesheet" href="css1/stles.css"> */
    
    header {
        /* Headeriin oikea kuva + koon ja tekstin muokkaus */
        text-align: center;
        background-image: url("images1/etusivu_isokuva.jpg");
        background-repeat:no-repeat;
        background-position: center center;
        width: 1000px;
        height: 300px;
        flex-shrink: 0; 
        padding: 5em;
    }
    header h1 {
        color: white;
        margin: 0;
    }
    header p {
        text-align: center;
        color: white;
        margin: 0;
        font-size: 20px;
    }
    body {
        background-color: gray;
    }
    #image {
        text-align:center;
    }
    #image a {
        color:black;
    }
    .menu1 ul {
        float: right;
        margin-right: 20px;
        list-style-type: none;
        margin-left: 0;
        font-family:Arial, Helvetica, sans-serif;
    }
    .menu1 a {
        color:black;
    }
    .form {
        width: 300px;
    }
    .form p {
        font-size: 18px;
        font-family:Arial, Helvetica, sans-serif;
    }
</style>

</head>
<body>
    
    <header>
        <h1>BIG MUSCLE</h1>
        <p>FROM BODYBUILDERS</p>
        <p>TO BODYBUILDERS</p>
    </header>
    
<div class="menu1">
    <ul>
        <li><strong>MENU</strong></li>
        <li><a href="desktop2.html">GYMWEAR</a></li>
        <li><a href="Accessories.html">ACCESSORIES</a></li>
        <li><a href="Suppliments.html">SUPPLEMENTS</a></li>
        <li>PROGRAMS</li>
        <li>APPLY FOR COACHING</li> 
    </ul>
</div>

<div class="form">
    <p><strong>LOG IN</strong></p>
<div class="form-floating mb-3">
    <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
    <label for="floatingInput">Email address</label>
  </div>
  <div class="form-floating">
    <input type="password" class="form-control" id="floatingPassword" placeholder="Password">
    <label for="floatingPassword">Password</label>
  </div>
</div>

        <!-- Kuvat pitäis varmaan asetella flexillä + lisää oikeat kuvat -->
<div id="image">
    <img src="images1/pants2.jpg" alt="image" height="200px" width="200px"/>
        <p><a href="desktop2.html">GYMWEAR</a></p>
    <img src="images1/accessories.jpg" alt="image1" height="200px" width="200px"/>
        <p><a href="Accessories.html">ACCESSORIES</a></p>
    <img src="images1/supplement.jpg" alt="image2" height="200px" width="200px"/>
        <p><a href="Suppliments.html">SUPPLEMENTS</a></p>
    <img src="images1/programs.jpg" alt="image3" height="200px" width="200px"/>
        <p>PROGRAMS</p>
    <img src="images1/valmennus.jpg" alt="image4" height="200px" width="200px"/>
        <p>APPLY FOR COACHING</p>
</div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>    
</body>
</html>
