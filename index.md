---
layout: blocks
title: Home
date: 
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2020/01/09/logo.png"
  navigation:
  - link: "/courses"
    link_text: Courses
  - link: "/masterclass"
    link_text: Masterclass
  - link: "/trading101"
    link_text: Trading 101
  cta:
    url: "#FAQ"
    button_text: FAQ
- template: hero-banner-w-image
  block: hero-2
  headline: "<em>Affordable Education </em><br><strong>For Every Need</strong>"
  content: Be it Trading, Investing or a grassroots course into Trading, you are at the right place!<strong> We won't say we're the best, but... yeah, we are! </strong>
  cta:
    enabled: true
    url: "/masterclass"
    button_text: Enrol Now!
  image:
    image: "/uploads/2020/01/09/Home.png"
    alt_text: School of Markets
  background_image: ''
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: <strong> Learn 24/7 anytime, all-time!</strong><br><spanclass="light">We bring a unique mobile based knowledge solution.</span>
  content: You don't have to sign in to any website or app, it's delivered to either your Google or One Drive. That simple!<br> <br> <strong>Psst... you get additional knowledge resources every month. No strings attached!</strong>
  media:
    image: "/uploads/2020/01/09/phone mockup.png"
    alt_text: Learn on the go
- template: hero-banner-w-image
  block: hero-3
  headline: We have just one aim.<br><strong>More Knowledge at less prices.</strong>
  content: We don't aim to drain your pockets, as we believe that knowledge must be accessible to everyone always. We're simple people with simple yet strong ideals.<br>Are you <strong>Still waiting</strong>?
  cta:
    enabled: true
    url: "/masterclass"
    button_text: Enrol Now!
  background_image: ''
  image:
    image: "/uploads/2020/01/09/hope.png"
    alt_text: Knowledge

- template: 1-column-text
  block: one-column-1
  headline: <a name="FAQ"><h3>FAQs</h3></a>
  content:
    <br>
    <strong> Do video lectures actually work?</strong><br><em>There is this big misconception that a live face to face session is better, but, with a cloud based series, people have consistently reported better understanding to us, and you can replay it any number of times. With the modern day needs and skewed work-life balance, you can Binge like Netflix. Just that, you learn here, than just laughing along to a recorded laugh track on a retarded sitcom.</em><br><br>
    <strong> How to do the enrolment process?</strong><br><em>Go to the respective Courses from the top, and register for the course. You'd get the course sent to you, within 24 hours.</em><br><br><strong> How much profit can I make?</strong><br><em>This is the wrong question. The right question would be how much you are willing to risk. If you are willing to take minimal risk, you can make 10% per trade very easily.(Which our Masterclass specialises in) If you're willing to risk more of your capital, sky is the limit. We've had people making 30 times!(Though we strictly never recommend it)</em><br><br><strong> Can I get a Discount?</strong><br><em>Really? Take a look at our prices. We'd gladly price our courses for ₹5, if we were selling samosas<br>(On second thought, quality matters, so, even that would be at least ₹15). The courses have far more value than courses that are sold for over ₹50 thousand.</em><br><br><strong> How much capital will I need?</strong><br><em>There is no requirement of any minimum capital, only a mind to learn is required. But, we would suggest at least ₹5 thousand to start with.</em>    

<div>
h2 {
	color: #000;
	font-size: 26px;
	font-weight: 300;
	text-align: center;
	position: relative;
	margin: 30px 0 60px;
}
h2::after {
	content: "";
	width: 100px;
	position: absolute;
	margin: 0 auto;
	height: 4px;
	border-radius: 1px;
	background: #1abc9c;
	left: 0;
	right: 0;
	bottom: -20px;
}
.carousel {
	margin: 0 auto;
	padding: 0 70px;
}
.carousel .item {
	color: #999;
	overflow: hidden;
    min-height: 120px;
	font-size: 13px;
}
.carousel .media {
	position: relative;
	padding: 0 0 0 20px;
}
.carousel .media img {
	width: 75px;
	height: 75px;
	display: block;
	border-radius: 50%;
}
.carousel .testimonial-wrapper {
	padding: 0 10px;
}
.carousel .testimonial {
    color: #808080;
    position: relative;
    padding: 15px;
    background: #f1f1f1;
    border: 1px solid #efefef;
    border-radius: 3px;
	margin-bottom: 15px;
}
.carousel .testimonial::after {
	content: "";
	width: 15px;
	height: 15px;
	display: block;
	background: #f1f1f1;
	border: 1px solid #efefef;
	border-width: 0 0 1px 1px;
	position: absolute;
	bottom: -8px;
	left: 46px;
	transform: rotateZ(-46deg);
}
.carousel .star-rating li {
	padding: 0 2px;
}
.carousel .star-rating i {
	font-size: 16px;
	color: #ffdc12;
}
.carousel .overview {
	padding: 3px 0 0 15px;
}
.carousel .overview .details {
	padding: 5px 0 8px;
}
.carousel .overview b {
	text-transform: uppercase;
	color: #1abc9c;
}
.carousel .carousel-indicators {
	bottom: -70px;
}
.carousel-indicators li, .carousel-indicators li.active {
	width: 18px;
    height: 18px;
	border-radius: 50%;
	margin: 1px 2px;
}
.carousel-indicators li {	
    background: #e2e2e2;
    border: 4px solid #fff;
}
.carousel-indicators li.active {
	color: #fff;
    background: #1abc9c;
    border: 5px double;    
}
</style>

<div class="container">
	<div class="row">
		<div class="col-sm-12">
			<h2>See What <b>Our Customers</b> Say About Us</h2>
			<div id="myCarousel" class="carousel slide" data-ride="carousel">
				<!-- Carousel indicators -->
				<ol class="carousel-indicators">
					<li data-target="#myCarousel" data-slide-to="0" class="active"></li>
					<li data-target="#myCarousel" data-slide-to="1"></li>
					<li data-target="#myCarousel" data-slide-to="2"></li>
				</ol>   
				<!-- Wrapper for carousel items -->
				<div class="carousel-inner">
					<div class="item carousel-item active">
						<div class="row">
							<div class="col-sm-6">
								<div class="testimonial-wrapper">
									<div class="testimonial">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eu sem tempor, varius quam at, luctus dui. Mauris magna metus, dapibus nec turpis vel, semper malesuada ante, commodo iacul viverra.</div>
									<div class="media">
										<div class="media-left d-flex mr-3">
											<img src="/examples/images/clients/1.jpg" alt="">										
										</div>
										<div class="media-body">
											<div class="overview">
												<div class="name"><b>Paula Wilson</b></div>
												<div class="details">Media Analyst / SkyNet</div>
												<div class="star-rating">
													<ul class="list-inline">
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star-half-o"></i></li>
													</ul>
												</div>
											</div>										
										</div>
									</div>
								</div>								
							</div>
							<div class="col-sm-6">
								<div class="testimonial-wrapper">
									<div class="testimonial">Vestibulum quis quam ut magna consequat faucibus. Pellentesque eget mi suscipit tincidunt. Utmtc tempus dictum. Pellentesque virra. Quis quam ut magna consequat faucibus, metus id mi gravida.</div>
									<div class="media">
										<div class="media-left d-flex mr-3">
											<img src="/examples/images/clients/2.jpg" alt="">										
										</div>
										<div class="media-body">
											<div class="overview">
												<div class="name"><b>Antonio Moreno</b></div>
												<div class="details">Web Developer / SoftBee</div>
												<div class="star-rating">
													<ul class="list-inline">
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star-o"></i></li>
													</ul>
												</div>
											</div>
										</div>
									</div>
								</div>								
							</div>
						</div>			
					</div>
					<div class="item carousel-item">
						<div class="row">
							<div class="col-sm-6">
								<div class="testimonial-wrapper">
									<div class="testimonial">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eu sem tempor, varius quam at, luctus dui. Mauris magna metus, dapibus nec turpis vel, semper malesuada ante, commodo iacul viverra.</div>
									<div class="media">
										<div class="media-left d-flex mr-3">
											<img src="/examples/images/clients/3.jpg" alt="">										
										</div>
										<div class="media-body">
											<div class="overview">
												<div class="name"><b>Michael Holz</b></div>
												<div class="details">Web Developer / DevCorp</div>											
												<div class="star-rating">
													<ul class="list-inline">
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star-o"></i></li>
													</ul>
												</div>
											</div>
										</div>
									</div>
								</div>								
							</div>
							<div class="col-sm-6">
								<div class="testimonial-wrapper">
									<div class="testimonial">Vestibulum quis quam ut magna consequat faucibus. Pellentesque eget mi suscipit tincidunt. Utmtc tempus dictum. Pellentesque virra. Quis quam ut magna consequat faucibus, metus id mi gravida.</div>
									<div class="media">
										<div class="media-left d-flex mr-3">
											<img src="/examples/images/clients/4.jpg" alt="">										
										</div>
										<div class="media-body">
											<div class="overview">
												<div class="name"><b>Mary Saveley</b></div>
												<div class="details">Graphic Designer / MarsMedia</div>
												<div class="star-rating">
													<ul class="list-inline">
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star-o"></i></li>
													</ul>
												</div>
											</div>										
										</div>
									</div>
								</div>								
							</div>
						</div>			
					</div>
					<div class="item carousel-item">
						<div class="row">
							<div class="col-sm-6">
								<div class="testimonial-wrapper">
									<div class="testimonial">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eu sem tempor, varius quam at, luctus dui. Mauris magna metus, dapibus nec turpis vel, semper malesuada ante, commodo iacul viverra.</div>
									<div class="media">
										<div class="media-left d-flex mr-3">
											<img src="/examples/images/clients/5.jpg" alt="">										
										</div>
										<div class="media-body">
											<div class="overview">
												<div class="name"><b>Martin Sommer</b></div>
												<div class="details">SEO Analyst / RealSearch</div>
												<div class="star-rating">
													<ul class="list-inline">
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star-o"></i></li>
													</ul>
												</div>
											</div>										
										</div>
									</div>
								</div>								
							</div>
							<div class="col-sm-6">
								<div class="testimonial-wrapper">
									<div class="testimonial">Vestibulum quis quam ut magna consequat faucibus. Pellentesque eget mi suscipit tincidunt. Utmtc tempus dictum. Pellentesque virra. Quis quam ut magna consequat faucibus, metus id mi gravida.</div>
									<div class="media">
										<div class="media-left d-flex mr-3">
											<img src="/examples/images/clients/6.jpg" alt="">										
										</div>
										<div class="media-body">
											<div class="overview">
												<div class="name"><b>John Williams</b></div>
												<div class="details">Web Designer / UniqueDesign</div>
												<div class="star-rating">
													<ul class="list-inline">
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star"></i></li>
														<li class="list-inline-item"><i class="fa fa-star-o"></i></li>
													</ul>
												</div>
											</div>										
										</div>
									</div>
								</div>								
							</div>
						</div>			
					</div>
				</div>
			</div>
		</div>
	</div>
</div>  
</div>                         		                            

- template: 1-column-text
  block: one-column-1
  headline: Further Queries?
  content: <a href="https://wa.me/919080673240" title="WhatsApp">Click here to reach
    to us on WhatsApp</a>
- template: simple-footer
  block: footer-1
  content: <em>Made with<span class="Apple-converted-space"> </span><span class="love">Love</span><span
    class="Apple-converted-space"> </span>for Students</em>❤︎

---
foo bar
