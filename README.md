# displayElement
  
<!DOCTYPE html>
<html lang="en">
<head>
  <link rel="stylesheet" type="text/css" href="style.css">
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link href="https://fonts.googleapis.com/css?family=Bitter|Cabin|Jim+Nightshade|Ma+Shan+Zheng|Noto+Sans+TC|Poppins|Raleway&display=swap" rel="stylesheet">
  <title>Document</title>
  <link href="https://fonts.googleapis.com/css?family=Playfair+Display&display=swap" rel="stylesheet">
  <style>
  /* font-family: 'Raleway', sans-serif;
font-family: 'Poppins', sans-serif;
font-family: 'Noto Sans TC', sans-serif;
font-family: 'Cabin', sans-serif;
font-family: 'Bitter', serif;
    <link href="https://fonts.googleapis.com/css?family=Playfair+Display&display=swap" rel="stylesheet">*/

/* Color Schemes
00CECB
FFED66
FFFFEA
D8D8D8
FF5E5B */

.main {
/*   container for the whole website */

}

body {
  margin: 0;
  width: 80%;
  animation: bkgroundchange 10s infinite;
}

@keyframes bkgroundchange
    {
      0%   {background: #FF9B85;}
      25%  {background: #FFD97D;}
      50%  {background: #AAF683;}
      75%  {background: #CEC2FF;}
      100% {background: #FF9B85;}
    }

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 20%;
  position: fixed;
  height: 100%;
  overflow: auto;
}

li a {
  display: block;
  color: #000;
  padding: 8px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #E16D99;
}

div#nav {
  font-family: 'Playfair Display', serif;

  font-size: 40px;
  width: 20%;
  height: 100vh;
  top: 0;
  position: fixed;
  background-color: #F7D8D7
;
}

.navinside {
  position: relative;
  margin: 0;
}

div.title {
  height: 20vh;
  left: 25%;  
  width: 100%;
  position: relative;
  text-align: center;
  font-family: 'Raleway', sans-serif;
  font-size: 20px;
}

div.information {
  height: 30vh;
  left: 25%;  
  width: 100%;
  position: relative;
}

#pre1 {
  font-family: 'Raleway', sans-serif;
  padding: 0px 30px;
  font-size: 20px;
  
}




  </style>
</head>
<body>
  
  <div class="main">
    <div id="nav">
      <div class="navinside">
        <ul>
        <li><a class="active" href="#home">Home</a></li>
        <li><a href="#news">News</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#about">About</a></li>
        </ul>
      </div>
    </div>
    <div class="title">
      <h1>
        Display Element CSS
      </h1>
    </div>
    
    <div class="information">
      <pre id="pre1"> 

      </pre>
    </div>
  </div>
</body>
</html>
