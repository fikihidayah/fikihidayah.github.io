<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Personal Portfolio | Responsive Website Design</title>
	<link rel="stylesheet" href="style.css">
	<script src="js/all.js"></script>
</head>
<body>

    <!-- navbar -->
    <header>
    	<a href="#" class="logo">Portfolio</a>
    	<div class="toggle" onclick="toggleActive();"></div>
    	<ul class="menu">
    		<li><a href="#home" onclick="toggleActive();">Home</a></li>
    		<li><a href="#about" onclick="toggleActive();">About</a></li>
    		<li><a href="#services" onclick="toggleActive();">Services</a></li>
    		<li><a href="#work" onclick="toggleActive();">Work</a></li>
    		<li><a href="#testimonial" onclick="toggleActive();">Testimonial</a></li>
    		<li><a href="#contact" onclick="toggleActive();">Contact</a></li>
    	</ul>
    </header>

    <!-- akhir navbar -->

    <!-- banner -->
    <section class="banner" id="home">
    	<div class="textBx">
    		<h2>Hello, My Name is <br><span>Syafiki Hidayah</span></h2>
    		<h3>Hi,I'm a Student</h3>
    		<a href="#about" class="btn">About Me</a>
    	</div>
    </section>
    <!-- akhir banner -->

    <!-- about -->
    <section class="about" id="about">
    	<div class="heading">
    		<h2>About Me</h2>
    	</div>
    	<div class="content">
    		<div class="contentBx w50">
    			<h3>Hi,I'm a Student</h3>
    			<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio, aspernatur illum assumenda, dolorum iusto reiciendis aliquam nesciunt iure expedita commodi asperiores fugit quasi obcaecati odio voluptatum itaque maiores est nihil. <br><br>
    				Lorem ipsum dolor sit, amet consectetur adipisicing elit. Qui illum, fugiat nobis, laboriosam reprehenderit, quidem maxime suscipit numquam vel vero, eveniet omnis sequi? Libero reprehenderit quis, officia. Officia, recusandae, rerum!
    			</p>
    		</div>
    		<div class="w50 foto">
    			<img src="img1.jpg" class="img">
    		</div>
    	</div>
    </section>

    <!-- akhir about -->

    <!-- services -->
    <section class="services" id="services">
    	<div class="heading white">
    		<h2>Our Services</h2>
    		<p>Lorem ipsum, dolor sit, amet consectetur adipisicing elit. Reiciendis ad iure iste quaerat perferendis sunt.</p>
    	</div>
    	<div class="content">
    		<div class="servicesBx">
    			<img src="icon1.png">
    			<h2>Web Design</h2>
    			<p>Lorem ipsum dolor sit amet, consectetur, adipisicing elit. Facere delectus expedita ad enim nostrum sequi provident soluta eaque molestias perferendis culpa consectetur sit ea praesentium, esse dolor.</p>
    		</div>
    		<div class="servicesBx">
    			<img src="icon2.png">
    			<h2>Web Development</h2>
    			<p>Lorem ipsum dolor sit amet, consectetur, adipisicing elit. Facere delectus expedita ad enim nostrum sequi provident soluta eaque molestias perferendis culpa consectetur sit ea praesentium, esse dolor.</p>
    		</div>
    		<div class="servicesBx">
    			<img src="icon3.png">
    			<h2>Android App</h2>
    			<p>Lorem ipsum dolor sit amet, consectetur, adipisicing elit. Facere delectus expedita ad enim nostrum sequi provident soluta eaque molestias perferendis culpa consectetur sit ea praesentium, esse dolor.</p>
    		</div>
    		<div class="servicesBx">
    			<img src="icon4.png">
    			<h2>Pothograpy</h2>
    			<p>Lorem ipsum dolor sit amet, consectetur, adipisicing elit. Facere delectus expedita ad enim nostrum sequi provident soluta eaque molestias perferendis culpa consectetur sit ea praesentium, esse dolor.</p>
    		</div>
    		<div class="servicesBx">
    			<img src="icon5.png">
    			<h2>Content Writing</h2>
    			<p>Lorem ipsum dolor sit amet, consectetur, adipisicing elit. Facere delectus expedita ad enim nostrum sequi provident soluta eaque molestias perferendis culpa consectetur sit ea praesentium, esse dolor.</p>
    		</div>
    		<div class="servicesBx">
    			<img src="icon6.png">
    			<h2>Video Editing</h2>
    			<p>Lorem ipsum dolor sit amet, consectetur, adipisicing elit. Facere delectus expedita ad enim nostrum sequi provident soluta eaque molestias perferendis culpa consectetur sit ea praesentium, esse dolor.</p>
    		</div>
    	</div>
    </section>

    <!-- akhir services -->

    <!-- work -->
    <section class="work" id="work">
    	<div class="heading">
    		<h2>Latest Work</h2>
    		<p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    	</div>
    	<div class="content">
    		<div class="workBx">
    			<img src="product1.jpg">
    		</div>
    		<div class="workBx">
    			<img src="product2.jpg">
    		</div>
    		<div class="workBx">
    			<img src="product3.jpg">
    		</div>
    		<div class="workBx">
    			<img src="product4.jpg">
    		</div>
    		<div class="heading">
    			<a href="#" class="btn">View More</a>
    		</div>
    	</div>
    </section>

    <!-- akhir work -->

    <!-- testimonial -->
    <section class="testimonial" id="testimonial">
    	<div class="heading">
    		<h2>Testimonial</h2>
    	</div>
    	<div class="content">
    		<div class="testimonialBx">
    			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic earum, fugiat fuga? Fuga eaque nostrum repellendus odit cupiditate, vero sit. Natus, odit! Impedit voluptatibus sequi optio saepe id ea repellat.</p>
    			<h3>Someone Famous <br><span>Creative Designer</span></h3>
    		</div>
    		<div class="testimonialBx">
    			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic earum, fugiat fuga? Fuga eaque nostrum repellendus odit cupiditate, vero sit. Natus, odit! Impedit voluptatibus sequi optio saepe id ea repellat.</p>
    			<h3>Someone Famous <br><span>Creative Designer</span></h3>
    		</div>
    	</div>
    </section>

    <!-- akhir testimonial -->

    <!-- contact -->
    <section class="contact" id="contact">
    	<div class="heading white">
    		<h2>Contact Us</h2>
    		<p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    	</div>
    	<div class="content">
    		<div class="contactInfo">
    			<h3>Contact Info</h3>
    			<div class="contactInfoBx">
    				<div class="box">
    					<div class="icon">
    						<i class="fa fa-map-marker"></i>
    					</div>
    					<div class="text">
    						<h3>Address</h3>
    						<p>Buana Vista Indah <br>Batam, Kepri <br>29464</p>
    					</div>
    				</div>
    				<div class="box">
    					<div class="icon">
    						<i class="fa fa-phone"></i>
    					</div>
    					<div class="text">
    						<h3>Phone</h3>
    						<p>085766224633</p>
    					</div>
    				</div>
    				<div class="box">
    					<div class="icon">
    						<i class="fa fa-envelope"></i>
    					</div>
    					<div class="text">
    						<h3>Email</h3>
    						<p>fikimantap@gmail.com</p>
    					</div>
    				</div>
    			</div>
    		</div>
    		<div class="formBx">
    			<form>
    				<h3>Message Me</h3>
    				<input type="text" name="" placeholder="Full Name">
    				<input type="email" name="" placeholder="Email">
    				<textarea placeholder="Your Message"></textarea>
    				<input type="submit" value="send">
    			</form>
    		</div>
    	</div>
    </section>
    <!-- akhir contact -->

    <div class="copyright">
    	<p>&copy Copyright 2020 SYAFIKIHIDAYAH All rights Reserved</p>
    </div>

    <script type="text/javascript">
    	// window.addEventListener('load', function () {
    	// 	if(window.scrollY > 150){
    	// 		var header = document.querySelector('header'); // ambil element header
    	// 		header.classList.toggle('sticky', window.scrollY > 150);
    	// 	}
    	// })

    	window.addEventListener('scroll', function(){
    		var header = document.querySelector('header'); // ambil element header
    		header.classList.toggle('sticky', window.scrollY > 150); // menambahkan class ketika di scroll ke bawah sebanyak 150
    	});

    	function toggleActive(){
    		var toggle = document.querySelector('.toggle');
    		var menu = document.querySelector('.menu');
    		toggle.classList.toggle('active');
    		menu.classList.toggle('active');
    	}
    </script>

</body>
</html>
