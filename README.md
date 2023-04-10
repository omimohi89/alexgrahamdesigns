<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
<style>
html{
padding:1%;
}
.line{
display:flex;
margin-left:10%;
margin-top:5%;
margin-bottom:2%;
justify-content:center;
align-items:center;
border:1px solid black;
width:80%;

}
    .highlight{
        color:#FFEF08  ;
        display: inline;
    }
    .logo{
    	display:inline-flex;
    	/*justify-content:center;*/
    	/*align-items:center;*/
  	 
    	width:100px;
    	height:40px;
        margin-right: 2%;
	}
	.firstlogo{
    	width:100%;
	}
    .text {
  	 
   	 display: flex;
   	 width: 600px;
   	 height: 200px;
   	 justify-content: center;
   	 align-items: center;


    }

    .h1 {
   	 font-family: futura;
   	 font-size: 100px;

    }

   /* t {
   	 font-size: 20px;
   	 font: Garmond;
   	 text-align: center; 
        position: absolute;
   	 height: -40%;
    }*/

    .header {
   	 width: 1300px;
   	 height: 100px;
   	 position:sticky;
   	 

    }

    a {
   	 color: black;
   	 size: 15px;
   	 list-style: none;
        transition: 0.3s;
    }
    a:hover{
        color:yellow;
    }

    .nav {
   	 display: inline-flex;
   	 flex-direction: row;
   	 width: auto;
     justify-content: flex-end;
        /*margin-left: 20%;*/
   	 font-family: futura;
   	 font-weight: regular;
   	 font-size: 15px;
       	 
    }

    .nav li {
   	 font-weight: bold;
   	 
   	 width: 100px;
   	 height: 45px;
   	 margin: 15px;
   	 list-style-type: none;
        transition: 0.2s;
    }
    .nav li:hover{
        color: yellow;
    }

    .landingpage {
   	 display: flex;
   	 flex-direction:column;
   	 align-items: center;
   	 justify-content: center;
   	/* background-color: lightblue;*/
        margin-left:10%;
   	 width: 80%;
   	 height: 450px;
   	
   	 text-align: center;
    }

    .h1 {
   	 display:inline;
   	 justify-content:center;
   	 font-family: helvetica;
   	 font-weight: bold;
   	 font-size: 70px;

    }

    .h2 {
  	 
   	 font-family: arial;
   	 font-size: 20px;
   	 font-weight: light;
   	 margin-top: 10px;
   	 margin-left: 12px;

    }
.calltoaction{
    display:flex;
    color:black;
    font-family:helvetica;
    font-weight:bold;
    justify-content:center;
    align-items:center;
    margin-top:20px;
    width:150px;
    height:50px;
    border: 2px solid #FFEF08 ;
    border-radius:60px;
    transition:0.5s;
}
.calltoaction:hover{
    background-color:#FFEF08 ;
    
}
.description{
	display:flex;
	justify-content:center;
	align-items:center;
	width:80%;
	height:450px;
	/*background-color:lightblue;*/
	margin-top:5%;
    margin-left:10%;
	
}
.intro{
	font-family:helvetica;
	display:inline;
	justify-content:center;
	align-items:center;
	width:450px;
	height:350px;
	font-size:50px;
	font-weight:bold;
}
.pfp{
    display:flex;
    align-items:center;
	background-color:#FFEF08 ;
	width:400px;
	height:500px;
	margin-left:10%;
    background-image:url('https://www.dropbox.com/s/duxip25tw1xirn5/self.png?raw=1');
    background-repeat: no-repeat;
    background-size: cover;
    background-position:-40px,0px ;
    
}
    /*  .portfoliowindow{
margin:50px;
paddind :center;
height:300px;
width:300px;
border: 20px blue;
text-align:center;
text-color: black;
} */
    .work{
        display: flex;
        justify-content: center;
        font-family:helvetica;
        font-weight: bold;
        font-size: 25px;
        margin-top: 20px;
        margin-bottom: 50px;
    }
  /*  .portfoliowindow {
   	 text-align: center;
   	 display: grid;
   	 align-items: center;
   	 justify-content: center;
   	 grid-template-columns: repeat( 3, 2fr);
   	 grid-template-rows: (2, 1fr);
   	 /*gap: 10px;*/
   	 /*margin-left: 1%;*/
   	 height: 800px;
    }

   /* .portfolio {
   	 display: flex;
   	 background-color: lightblue;
   	 padding: center;
   	 width: 300px;
   	 height: 300px;
        margin-left:25%;
   	 justify-content: center;
   	 align-items: center;
    	transition:transform 0.3s ease-in-out;
   	 
    }
.portfolio:hover{
	transform:scale(1.1);
}
.portfolio-expanded {
	transform:scale(1.5);
}*/
    .flowcontainer{
        display: flex;
        margin: 10%;
        width: 80%;
        height: 700px;
        background-color: #FFEF08 ;
        }
    .flow1{
        margin-bottom: 3%;
        width: 200px;
        height:200px;
        background-color: #FFEF08 ;
        background-image: url('https://www.dropbox.com/s/a72viqaw57e0ctn/vend%20space-02.png?raw=1');
       
        
    }
    .flow2{
        margin-bottom: 3%;
        width: 200px;
        height:200px;
        background-color: #FFEF08 ;
        background-image: url('https://www.dropbox.com/s/a72viqaw57e0ctn/vend%20space-02.png?raw=1');
       
    }
    .img2{
        
    
    }
    footer {
   	 position: flex;
   	 bottom: 100%;
   	 background-color: lightblue;
   	 width: 100%;
   	 height: 200px;
    }

    .footer {
   	 display: flex;
   	 /*justify-content:space-between;*/
   	 align-items: center;
   	 background-color: #FFEF08 ;
   	 height: 200px;
   	 width: 90%;
   	 padding: 5%;
    }

    .info {
   	 height: 80px;
   	 color: white;
   	 font-weight: light;

    }

    .sns {
   	 color: white;
   	 text-decoration: none;
   	 position: absolute;
   	 left: 90%;

    }

    a {
   	 /*color: white;*/
   	 text-decoration: none;
    }

    t {
   	 width: 50px;
   	 padding: 5px;
    }

    .contact {
   	 font-size: 14px;

    }

    .tel {
   	 display: flex;
   	 width: 50px;
   	 height: 20px;

    }

    .email {
   	 font-size: 15px;
    }
.photo{
width:100%;
height:100%;
}
</style>


</head>

<body>
    <div class="header">
     	<div class="logo"> <img class="firstlogo" src="https://lh3.googleusercontent.com/pw/AMWts8CrNqMKUEziN43g0eya8R_KTN-fkSGGRleHnwWkZT-nQ8iSjkDNxLo73DAAPy5A2E-5dF4zpfbqMXTwPgqX7QkawB32i-upq3qgJzajgnLTlFfUukA=w600-h315-p-k" > </div>
   	 
   	 <ul class="nav">
   	    
   		 <li><a href="#home">home</a></li>
   		 <li><a href="#about">about</a></li>
   		 <li><a href="#contact">contact</a></li>
   	 </ul>
    </div>
<div class="line"></div>
    <div class="landingpage">
   	 <div class="text">
         <p class="h1">Meet Your <span class="highlight">Problem Solver </span></p>
  		 
   	 </div>
        <div class= "calltoaction"> <a href="http://www.google.com">contact</a></div>
    </div>
<div class="line"></div>
    <div class="description">
   	 
    	<p class="intro">
            Hi! I'm Alex and I will help you achieve <span class="highlight">your brand's goals.</span> 
    	</p>
    	<div class="pfp"></div>
    </div>
<div class="line"></div>
        <div class="work"><p>Works</p></div>
    <div class="flowcontainer">
    <div class="flow1">
        </div>
        <div class="flow2">
        </div>
        
    </div>
  
</body>
<footer>
    <div class="footer">
   	 <div class="info">
   		 <p class="contact">contact</p>
   		 <p class="tel">tel: <span>718</span></p>
         <p class="email">email: <span>alexgrahamdesign@gmail.com</span></p>
    </div>
    <div class="sns"> <a href="http://www.google.com">instagram</a></div>
    


</div>
</footer>

</html>
