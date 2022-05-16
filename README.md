html {
	box-sizing: border-box;
}

*,
*:before,
*:after {
	box-sizing: inherit;
}


@media screen and (min-width: 560px) and (max-width: 1200px)  {
    html {
        font-size: 60%;
    }
}

.nav-list {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 8%;
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

.nav-list1 {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 8%;
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
}

@media screen and (max-width: 560px) {
    .horizontal-navbar {
        justify-content: center;
    }
    .nav-list {
        margin: 18px;
    }
}

ul {
   list-style: circle;
}
   
li { 
   float: left;
   color: white;
   text-align: justify;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 24px;
  text-decoration: none;
}

li a:hover:not(.active) {
  background-color: #115;
}

body {
	display: block;
    background-attachment: fixed;
    background-color: #000;
    line-height: 2;
}

h1 { 
  display: block;
  font-size: 48px;
  margin-top: 60px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  font-weight: 900;
  color: white;
  text-align: center;
  font-family: sans;
  text-decoration: none; 
}

h2 {
	font-family: sans-serif;
    font-weight: 700;
    text-align: left;
    font-size: 30px;
	margin-left: 20px;
}

.nadpis-vedlajsi {
    color: #00FF00;
}

.nadpis-hlavny {
    text-align: center;
    font-size: 50px;
    color: #be3144;
    text-shadow: 1.5px 1.5px #f0f0f0;
}

.main {
    margin-left: 170px;
    font-size: 25px;
    padding: 0px 30px;
}

footer {
   position: fixed;
   left: 0;
   bottom: 0;
   width: 100%;
   background-color: red;
   color: white;
   text-align: center;
   font-family: sans;
}

@media screen and (max-width: 560px) {
    footer {
        text-align: center;
    }
}

.grid-container {
    display: grid;   
    grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));	
    grid-gap: 115px;
    width: 100%;
    max-width: 1300px;
    margin: 0 auto;
	position: fixed;
	top: 220px;
	left: 110px;
}

@media screen and (max-width: 470px) {
	
    .grid-container {
        grid-template-columns: 1fr;
    }
}

.foto {
    height: 100%;
    width: 100%;
    border-style: solid;
    border-width: 7px;
    border-color: #FFFF00;
}

.project {
    background-color: darkblue; 	
    text-align: center;
	font-size: 25px;
	margin: 0px;
	height: 45px;
	width: 360px;
	border-radius: 8px; 
}

.code {
    color: white;	
}


a {
    color: white;
	text-decoration: none;
} 

odkaz {
    color: white;
}

.vertical-navbar {
    height: 100%;
    width: 178px;
    position: fixed;
    top: 0;
    left: 0;
    background-color: #20B2AA;
    padding-top: 20px;
}

.vertical-navbar a {
    padding: 6px 16px;
    text-decoration: none;
    font-size: 25px;
    color: #f0f0f0;
    display: block;
}

.vertical-navbar a:hover {
    font-size: 30px;
    color: #000099;	
}

.dl {
	display: block;
    width: 300px;
    height: 350px;
    margin-left: 40%;
    cursor: pointer;
	position: absolute;
	top: 215px;
	left: 10px;
	
}

#logo {
	position: absolute;
    top: 45%;
    margin-left: 10%;
	margin-bottom: 40%;
} 

.fotka {
    width: 600px;
    height: 500px;
	border-style: solid;
    border-width: 12px;
    border-color: #8B4513;
}

strong {
    color: red;
}

@media screen and (max-height: 450px) {
    .vertical-navbar {
        padding-top: 15px;
    }
    .vertical-navbar a {
        font-size: 18px;
    }
}

.sun {
    opacity: 1;
	box-shadow: 0px 0px 0px 0px yellow;
	width: 100px;
	height: 100px;
	position: absolute;
	top: 300px;
	left: 1200px;
	animation: sunpulse 2s alternate infinite;
	border-radius: 50%;
	background-image: radial-gradient(circle, #ffd200 95%, #f7971e);
}

@keyframes sunpulse {
	from {
		box-shadow: 0 0 100px #ff0, 0 0 100px #ff0;
	}
	to {
		box-shadow: 0 0 25px #ff0, 0 0 75px #ff0;
	}
}
  

     
      
      
      
      
      
    
