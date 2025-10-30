# html-project
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>THEOPHILE</title>
<style>

		*{ 
			margin: 0;
			padding: 0;
			box-sizing: border-box;
		}
		body{
			font-family: segoe UI',sans-serif;
			line height:1.6;
			color: #333;
			background: #f9f9f9;

		}
		.container{
			width: 90%;
			max-width: 1100px;
			margin: auto;
			padding: 20px 0;


		}
	
		header{
			background: #0d47a1;
			color: white;
			padding: 20px;
		}
		header h1{
			float: left;
		}

		nav ul{
			list-style: none;
			display: flex;
			justify-content: flex-end;
			gap: 20px;
		
		}
		nav a{
			color: white;
			text-decoration: none;
			font-weight: bold;

		}
		.hero{
			background: #1976d2;
			color: white;
			padding: 60px 0;
			text-align: center;

		}
		.hero .btn {
			background: white;
			color: #1976d2;
			padding: 3px 0;
			border:none;
			margin-top: 20px;
			font-weight: bold;
			text-decoration: none;
			border-radius:5px ;


		}
		.hero .btn:hover{
			background: blue;
			color: white;
		}

		.section{
			padding: 50px;

		}
		.section.alt{
			background: #eeeeee;

		}
		grid{
			display: flex;
			gap: 20px;
			flex-wrap: wrap;
		}
		.grid li,.card{
			background: white;
			padding: 20px;
			flex: 1 1 30%;
			border: 1px solid #ddd;
			border-radius: 5px;
			text-align: center;


		}
		form{
			display: flex;
			flex-direction: column;
			gap: 15px;
			max-width: 400px;
			

		}
		form input,form textarea{
			padding: 10px;
			border: 1px solid #aaa;
			font-size: 16px;
			border-radius: 10px;

		}
		form button{
			background: #0d47a1;
			color: white;
			padding: 12px;
			border: none;
			cursor: pointer;
			font-weight: bold;
			border-radius: 10px;
		
			max-width: 160PX;


		}
		footer{
			background: #0d47a1;
			color: white;
			text-align: center;
			padding: 20px 0;
			margin-top: 40px;
		}
		.container,h2{
			text-align: center;
			padding: 12px;


		

		}

	</style>
</head>
<body>
	<header>
		<div class="container">
			<h1>THEOPHILEMAKER</h1>
			<nav>
				<ul>
					<li><a href="#home">home</a></li> 				
					<li>
						<a href="#services">service</a>
					</li>
					<li>
						<a href="#products">product</a>
					</li>
					<li>
						<a href="#contact">contact</a>
					</li></ul>
				
			</nav>
			
		</div>
	</header>

	<section id="home" class="hero">
		<div class="container">
			<h2> Your trusted Tech Patner</h2>
			<p> Explore,connect,and upgrade with THEOPHILEMAKER-We bring technology closer to you.</p>

			<a href="#products"class="btn">Shop now</a>
			
		</div>
		
	</section>

	<section id="services" class="section">
		<div class="container">
			<h2>OUR SERVICES</h2>
			<ul class="grid">
				<li>moble & laptop Repairs</li>
				<li>Tech support &Diagnostcs</li>
				<li>Software intallation</li>
				<li>Hardware upgrades</li>
				
			</ul>
		</div>
		
	</section>


	<section id="products" class="section alt">
		<div class="container">
			<h2>Featured Product</h2>
			<div class="grid">
				<div class="card">
					<h3>Wireless Earbuds</h3>
					<p>
						High-quality sound and long-lasting battery.
					</p>

				</div>
				<div class="card">
					<h3>Smartwatch</h3>
					<p>
						stay connected and track your health.
					</p>
					
				</div>
				<div class="card">
					<h3>Phone Accessories</h3>
					<p>
						Chargers, cases, screen protectors & more.
					</p>
					
				</div>
			</div>
		</div>
		</section>
	

	<section id="contact" class="section">
		<div class="container">
			<h2>contact us</h2>
			<p>
				Have a question or need help? Reach out|
			</p>
			<form>
				<input type="text" placeholder ="Enter your name" required/>
				<input type="Email" placeholder ="Enter your Email" required/>
				<input type="password"placeholder="enter your password"required/>
				<input type="mobile number"placeholder="enter mobile number"required/>

				<textarea placeholder=" your message" rows="4" required></textarea>

				<button type="submit">send message</button>

			</form>

			
		</div>
		
	</section>
	<footer>
		<div class="container">
			<p>&copy; 2026 THEOPHILEMAKER. Allrights reserved.</p>

			
		</div>
	</footer>



	

</body>
</html>
