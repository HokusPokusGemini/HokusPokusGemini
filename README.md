<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width"> 
  <title>Sample Website</title> 
  <style>
      div { 
       background-color: cornsilk;
       padding: 0.3em;
       margin: 5px;
    }
    
    .input {
       height: 35px;
       width: 200px;
       box-shadow: 0px 0px 5px 0px;
       border-radius: 40px;
       border: 0 none;
       opacity: 0.8;
    }
    
    button[type="submit"] {
    text-indent: -999px;
    width: 50px;
    height: 35px;
    padding: 0;
    margin: 5px;
    border: 0 none ;
    box-shadow: 0px 0px 5px 0px;
    border-radius: 40px;
    background: transparent url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' class='bi bi-search' viewBox='0 0 16 16'%3E%3Cpath d='M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z'%3E%3C/path%3E%3C/svg%3E") no-repeat center;
    cursor: pointer;
    opacity: 0.8;
    }
    
    button[type="submit"]:focus,
    input[type="search"]:focus {
    box-shadow: 0 0 5px 0;
    }
    
    p { font-family: Serif; }
    
    img {
        float: right;
        margin: 5px;
    }
    
    ul { margin-right: 120px; }
    
    body {
    background-image: linear-gradient(to top, ivory,ghostwhite, snow, ivory);
    margin: 0;
    padding: 0;
    }
    
    header {
    background-image: linear-gradient(to top,darkslateblue,slateblue);
    color: #fff;
    padding: 15px;
    align-items: center;
    }
    
    .u1 {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    }
    
    li { margin-right: 20px; }
    
    .a1 {
    text-decoration: none;
    color: white;
    }
    
    a { text-decoration: none; }
    
    main { padding: 20px; }
    
    h2 { margin-bottom: 20px; }
    
    label { display: block;}
    
    input, textarea {
    padding: 10px;
    margin-bottom: 20px;
    border-radius: 5px;
    width: 70%;
    }
    
    .b3 {
    background-color: royalblue;
    color: #fff;
    border-radius: 5px;
    letter-spacing: 0.1em;
    padding: 15px;
    border: 0 none;
    cursor: pointer;
    width: 110px;
    font-weight: bold;
    margin-right: 200px;
    }
    
    .b1 {
    background-color: royalblue;
    letter-spacing: 0.1em;
    color: #fff;
    border-radius: 5px;
    padding: 15px;
    border: 0 none;
    cursor: pointer;
    width: 110px;
    font-weight: bold;
    }
    
    footer {
    background-image: linear-gradient(to top, darkslateblue, indigo);
    color: #fff;
    padding: 10px;
    text-align: center;
    }
  </style>
 </head> 
 <body> 
  <header> 
   <h1> Weirdest Places </h1> 
   <ul class="u1"> 
    <li> <a class="a1" href="#">Home</a></li> 
    <br> 
    <li><a class="a1" href="#">About</a></li> 
    <li><a class="a1" href="#">Services</a></li> 
    <li><a class="a1" href="#">Contact</a></li> 
   </ul> 
  </header> 
  <br> 
  <h1 style="margin-left: 70px;"> Welcome back!</h1> 
  <p style="margin-left: 20px;">Discover our selection of unusual places, strange worlds, beautiful creatures, etc or anything else!</p> 
  <form> 
   <input class="input" style="margin-left: 55px;" type="search" placeholder="  Search here"> <button type="submit">Search</button> 
  </form> 
  <br> 
  <br> 
  <div> 
   <h2 style="margin-left: 120px;"> Blue Hole </h2> 
   <img src="https://telegra.ph/file/85249f52dfe6c83d51c1a.jpg" height="100" width="200" alt="blue hole"> 
   <p> The blue hole is a large marine cavern or sinkhole, which is open to the surface and has developed in a bank or island composed of a carbonate bedrock. Blue holes typically contain tidally influenced water of fresh, marine, or mixed chemistry... <a href="https://en.m.wikipedia.org/wiki/Blue_hole"> learn more </a> </p> 
  </div> 
  <br> 
  <div class="div1"> 
   <h2 style="margin-left: 55px;"> Places you might like </h2> 
   <img src="https://telegra.ph/file/0c506a5779c07d07abc62.jpg" height="110" width="110"> 
   <ul> 
    <li> <a href="https://en.m.wikipedia.org/wiki/Bermuda_Triangle">Bermuda Triangle </a> </li> 
    <li> <a href="https://en.m.wikipedia.org/wiki/Moai"> Moai </a> </li> 
    <li> <a href="https://en.m.wikipedia.org/wiki/Nazca_Lines"> The Nazca Lines </a> </li> 
    <li> <a href="https://en.m.wikipedia.org/wiki/File:Thors_Well.jpg"> Thor's Well </a> </li> 
    <li> <a href="https://en.m.wikipedia.org/wiki/Tianzi_Mountain"> The Tianzi Mountais </a> </li> 
    <li> <a href="https://en.m.wikipedia.org/wiki/Giant%27s_Causeway"> Giant's Causeway </a> </li> 
   </ul> 
  </div> 
  <main> 
   <h2>Welcome to our website</h2> 
   <p>We are delighted to see you as a part of our community. Feel free to discover, interact, and collaborate with us to create something wonderful!</p> 
   <br> <button class="b1">Learn More</button> 
   <h2>About Us</h2> 
   <p>Our website was founded in 2022 by a group of passionate individuals who wanted to make a difference in the world. We started out as a small team working out of a garage, but we had big dreams and a lot of determination to make people interest about weird things. </p> 
   <br> <button class="b1"> Read More </button> 
   <h2>Contact Us</h2> 
   <form> <label>Name:</label> 
    <input class="i2" type="text" name="name"> <label>Email:</label> 
    <input class="i2" type="email" name="email"> <label>Message:</label> <textarea name="message"></textarea> <button class="b3"> Send </button> 
   </form> 
  </main> 
  <br> 
  <footer> 
   <p style="font-family: arial;"> ©2024 Sample Website. All rights reserved.</p> 
  </footer> 
 </body>
</html>