<html>
	<head>
    	<title>
            Home
         </title>
    </head>
	<body>
		<p>
        	Alan's Website
        </p>
      	<!-- Navigation Bar starts here -->
        <ul>
            <li ><a class= "active" href= "index.html">Home</a></li>
            <li><a href= "portfolio.html">Portfolio</a></li>
            <li><a href= "index.html">Contact Me</a></li>
        </ul>
      	<!-- End navigation bar -->
        
        <h2 class="headers" align= "center" >
        	Welcome To My Website!
        </h2>
	<h3 class="headers2">
	<img src="Alan.jpg" alt="Alan" height="200" class=" left" style=" padding: 0px 30px 0px 100px"> About me
        </h3>
        <p >  
		My name is Alan Lopez and I attend Lynwood High School. I am 15 years old and currently a 10th grader. I am 
		interested in mechanical engineering and computer science. _________stuff i have to put in______________. Feel free to go through my portfolio to see the 
		works I have created or remixed.  
		</p>
        
	</body>

<style>
	h1{
	padding: 0px 10px;
	line-height: 0px;
	}
	ul{
		list-style-type:none;
		margin:0;
		padding: 13px 16px;
		overflow:hidden;
		background-color:white;
	}
	li{
		display: inline;
	}
	li a{

		text-decoration: none;
		padding: 14px 16px;
		color: #000000;
	}
	li a:hover{
		background-color: #aaa;
		color: #fff
	}
	li a.active {
    background-color: #811d5e;
    color: white;
	}

	.left{
		float: left;
		margins: 10px 10px 10px 10px;
	}
	p{
		color: #ff6f01;
		font-family: "Courier New", Courier, monospace;
		font-size: 18px;
		margin-right: 100px;
		margin-left: 100px;
		text-indent: 30px;
		line-height: 2.0;
		}
	.lists { 
		text-align: center; 
		list-style-position:inside;
		color: #1E90FF;
		font-family: "Variane Script";
		font-size: 24px;
	}
	.headers{
		color: #1E90FF;
		font-family: "Variane Script";
		font-size: 50px;
	}
	.headers2{
		color: #f3b05a;
		font-family: "Variane Script";
		font-size: 50px;
	}
	.home{
	display:block;
	padding: 20px, 30px;
	background-color: #e7e7e7
	}
	body{
	background-image: url('sunset.jpg'); 
	background-position: middle;
	background-repeat: no-repeat;
	background-size: 1920px 1080px;
	}
	@font-face{
		font-family: 'Variane Script';
		src: url('Variane Script.ttf') format('truetype');
	}
</style>
</html>
