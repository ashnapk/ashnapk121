<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>ROCK RESUME</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <style>
    *{
  box-sizing: border-box;
}
body{
  margin:0px;
  padding:0px;
  font: poppins;
}
#main{
  width:100%;
  height:25vh;
  position :relative;
}
nav{
  display: flex;
  justify-content:space-around;
  align-self: center;
  position: fixed;
  top:0;
  left:0 ;
  width:100%;
  background-color: white;
  box-shadow: 5px 10px 30px rgba(0,0,0,0.02);
  z-index:1;
}
.logo img{
  height:45px;
}
.menu{
  list-style: none;
  display: flex;
}
.menu li a{
  height:40px;
  line-height: 43px;
  margin: 3px;
  padding: 0px 22px;
  display: flex;
  letter-spacing: 1px;
  font-weight: 580;
  text-transform: uppercase;
  font-size:0.8em;
  color:grey;
}
a {
  text-decoration: none;
}
.hey{
  color:#39bfbd;
  font-weight: 500;
  font-size: 1.2em;
  border-bottom: 2px solid #39bfbd;
  margin-bottom: 75px;
  margin-top:25px;
}
.image{
  width: 500px;
  height:500px;
}
.image img{
  width: 180px;
  height:180 ;
  object-fit: contain;
}
.content {
  display: flex;
  width: 90%;
  justify-content: space-around;
  align-items: center;
  position: absolute;
  left:10%;
  right:10%;
  transform: translate(-50
  5,-50%);
}
.main-text{
  width:500px;
  height:300px ;
  margin-right:20%;
}
.main-text h1{
  font-size: 3.5em;
  color:#1c3548;
  margin:0px 8px 10px 0px;
  line-height: 60px;
  left:10% ;
  right:10% ;
}
.main-text p{
  color:grey;
}
.resume-btn{
  width: 190px;
  height: 44px;
  display: flex;
  justify-content: center;
  align-items: center;
  color:white;
  background-color: #1db896;
  border-radius: 20px;
  font-size: 1.3em;
  box-shadow: 5px 10px 30px rgba(24,139,119,0.21);
}
.resume-btn:hover{
  background-color: #23cdaf;
  transition: all ease 0.2s;
}
.menu li a:hover{
  background-color:  #23cdaf;
  color:white;
  box-shadow:  5px 10px 30px rgba(24,139,119,0.21);
  transition: all ease 0.2s;
}
  </style>
  <body>
    <section id="main">
      <nav>
        <a href="#" class="logo">
          <img src="love.png" alt="the logo of project rock">
        </a>

        <span class="menu-space"></span>
        <ul class="menu">
          <li><a href="#">home</a></li>
          <li><a href="#">skills</a></li>
          <li><a href="#">recent</a></li>
          <li><a href="#">clients</a></li>
          <li><a href="#">contacts</a></li>
        </ul>

        <a href="#" class="hey"><strong>say hi!</strong></a>
      </nav>
    </section>

    <section class="content">
      <div class="image">
        <img src="dq.jpg" alt="rock">
      </div>
      <div class="main-text">
       <h1>Hello, I am The <br>  Rock</h1>
       <p>Hey, in this vedio i will be showing you guys how to buid a website using only html and css</p>
       <a href="#" class="resume-btn">See My Resume</a>
       </div>
    </section>
  </body>
</html>
