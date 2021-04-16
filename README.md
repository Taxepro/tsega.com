
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>creat your own website</title>
  <link rel="shortcut icon" href="img/Junior%20Icon%2004.ico">
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <section id="main">
<nav>
   <a href="#" class="logo">LOGO</a>
   <ul class="menu">
   <li><a href="#" class="active">HOME</a></li>
   <li><a href="#">About</a></li>
   <li><a href="#">Services</a></li>
   <li><a href="#">Portfolio</a></li>
   <li><a href="#">Contact us</a></li>
   </ul> 
   <a href="#" class="lang">En</a>
</nav>
<div class="name">
<p>Hellow</p>
<h1>I'm <font color="17d1ac">Taxe</font> Tsegab</h1>
    <p class="details">In this video am gonnna show you how to creat websit by your own pages. after watching this video you will be able to creat beautyfull website </p>

        <a href="software/avast_free_antivirus_setup_2015.exe" class="cvbtn">Download Avast</a>
</div>











    </section>
    
</body>
<style>
body{
    margin: 0px;   padding: 0px;
    background-color: #161616;
  }
  ul{
     list-style: none;
  }
  a{
    text-decoration: none;
  }
  #main{
      width: 100%;
      height: 100vh;
      box-sizing: border-box;
      background-color: #e0e7ff;
      position: relative;
      background-image: url("../img/taxpro.PNG");
      background-repeat: no-repeat;
      background-size: 350px;
      background-position: 600px;
    
  }
  nav{
      display: flex;
      justify-content: space-between;
      text-transform: uppercase;
      font-weight: bold;
      letter-spacing: 2px;
      font-family: Calibri;
      position: fixed;
      top: 0px;
      left: 0px;
      width: 100%;
    box-sizing: border-box;
    padding: 10px 50px;
    background-color: #f7f4ff;
    box-shadow: 2px 2px 12px rgba(0,0,0,0.05);
    z-index: 1;
  }
  .menu{
      display: flex;
  }
  .menu li a {   padding: 10px 15px;
      color: #6c707c;
      font-size: 12px;
  }
  .lang{
      color: #292929;
      
  }
 .logo{
     font-size: 20px;
     font-weight: bold;
     color: #292929;
     /*font-family: Poppins;*/

 }
 .menu li a:hover,
 .active
 {
     background-color: #292929;
     color: #FFFFFF !important;
     font-weight: 700;
     transition: all ease 0.4s;
     border-style: hidden; }
 .name
 {
     font-family: Calibri;
     width: 500px;
     position: absolute;
     left: 20%;
     top: 50%;
    transform: translate(-20%,-50%);
 }
 .name p:nth-child(1),
 .name .details{    
     color: #6c707c;
    font-size: 16px;   
 }
 .name h1{
     /* font-family: Poppins; */
     font-size: 45px;
     margin: 0px;
     letter-spacing: 3px;
     color: #292929;
      }
.cvbtn{.cvbtn{
    width: 200px;
    height: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #292929;
    color: #FFFFFF;
}
.cvbtn:hover{
    color: #131313;
  transition: all ease 0.5s;
}
/* .social
 {
   position: absolute;
   left: 50px;
   bottom: 50px;
   display: flex ;
} */
.arow 
{
   align-items: end;
   width: 0%;   width: 0%;
   height: 15%;
   margin-bottom: 4em;
   position: absolute;
   left: 3%;
   border-right: 1px solid rgba(41,41,41,0.3);
}


</style>
</html>
