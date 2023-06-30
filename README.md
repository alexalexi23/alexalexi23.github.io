<html>
<head>
  <title>Animated Text for Websites</title>
       <style>
    .animated-text {
      display: inline-block;
      overflow: hidden;
      white-space: nowrap;
      animation: slideAnimation 10s ;
    }

    @keyframes slideAnimation {
      0% {
        transform: translateX(-100%);
      }
      50% {
        transform: translateX(25%);
      }
    }
  </style>
<center><style>
    .animated-button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #f2f2f2;
      color: #4d4c49;
      font-size: 18px;
      font-weight: bold;
      text-decoration: none;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      position: relative;
      overflow: hidden;
       transition: opacity 0.3s, transform 0.3s;
    }

    .animated-button:before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: #FFC107;
      opacity: 0;
      transform: translateX(-100%);
      align: center;
      transition: opacity 0.3s, transform 0.3s;
    }

    .animated-button:hover {
      color: #4d4c49;
    }

    .animated-button:hover:before {
      opacity: 1;
      transform: translateX(0);
    }
  .animated-button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #f2f2f2;
      color: #4d4c49;
      font-size: 18px;
      font-weight: bold;
      text-decoration: none;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      align: center;
      animation: pulseAnimation 1s ease-in-out;
    }

    @keyframes pulseAnimation {
      0% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.1);
      }
      100% {
        transform: scale(1);
      }
    }
  </style>
   <style>
    .container {
      position: relative;
      width: 100%;
      height: 100vh;
      background-image: url('https://scontent.fceb2-1.fna.fbcdn.net/v/t39.30808-6/352395580_698980758905282_4024521847405496074_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=09cbfe&_nc_eui2=AeERTXOBFFV4s_j0CO8dzbiLc5mqkYGgFNJzmaqRgaAU0rPduakTdDNcd_N3pYZElZJ8WGJ0z1zv6zKZjVgendl5&_nc_ohc=iVT9wRoKRf8AX_2VZaH&_nc_ht=scontent.fceb2-1.fna&oh=00_AfAUMvbG05iMEhrEWPJQQMTsCkFrvyDnDqm4MdG11xvkqQ&oe=64A26821');
      background-repeat:repeat;
      background-size: cover;
      background-position: center;
    }

    .overlay {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 1000px;
      height: 500px;
      background-color: rgba(255, 255, 255, 0.4);
      border-radius: 10px;
      text-align: center;
      padding: 20px;
    }

    .overlay h2 {
      margin: 0;
      font-size: 24px;
      color: #333;
    }
  </style>

</head>
<body background="https://i.pinimg.com/564x/d8/22/0e/d8220e269ba737440a7fa8f39f9510e9.jpg">


  <main>
    <div class="animated-text">
      <span style= "background:#c99b36;font-size:40px;font-family:arial;background-color:rgba(255, 255, 255, 0.5);"> Personal Portfolio & Compilation for ICT (4th Quarter) </span>
    </div>
  </main>


     
  <main>
    <a href="1.html" class="animated-button"> About Me</a>
    <a href="2.html" class="animated-button"> Compilation of Activities</a>
    <a href="6.html" class="animated-button"> Extracurricular Activities </a>
  </main>

<div class="container">
    <div class="overlay">
      <b><h2>Hi! I am Alexa Nicole L. Yapit</h2>
      <b> <p > I am in 8th Grade, Section Pasteur. I was born in February 23, 2009 therefore, I am a Pisces! I love watching K-drama and K-pop. My Favourite groups are Stray Kids, Ateez and Seventeen. I really love drawing, painting, taking pictures and many more! My talents are singing, dancing, rapping, acting and many more. </p>
    <img src="https://i.pinimg.com/originals/cc/3b/02/cc3b02ebd8ffb1c1bcc2596bb19ea6ea.gif" align="left">
<br> 
<br>
<br>
<br>
<br>
<br>
<br>
<b> <p style= "font-size:30px;font-family:arial;color:#30302f;" > "Be the person you want to be, not the person you pretend to be."  </p> 
<br> 
<br>
<br>
<br>
<a href="https://www.facebook.com/yapit.alexa/"> <img src="https://i.pinimg.com/564x/d8/ff/30/d8ff3064a3067ac45a70f762f4977d90.jpg" width="40px" height="40px" align="left">
<a href="https://www.instagram.com/miruwahh/"> <img src="https://i.pinimg.com/564x/bb/f0/85/bbf0852877996dfcd2c9eac71a292429.jpg" width="40px" height="40px" align="left">
<a href="https://twitter.com/milixhin_"> <img src="https://i.pinimg.com/564x/e9/58/5d/e9585dd0d277236b30953bca60761072.jpg" width="40px" height="40px" align="left"> </a>
<b> <p style= "font-size:20px;color:#30302f;" > (If you want to contact me, press the following icons to be directed to my social media accounts!) </p> 
</div>

  </div>




</body>
</html>

