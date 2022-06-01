<!doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
        <title>julianne's website</title>
        
        <!-- CSS -->
        <link rel="stylesheet" href="css/reset.css">
        <link rel="stylesheet" href="css/simplegrid.css">
        <link rel="stylesheet" href="css/icomoon.css">
        <link rel="stylesheet" href="css/lightcase.css">
        <link rel="stylesheet" href="js/owl-carousel/owl.carousel.css" />
        <link rel="stylesheet" href="js/owl-carousel/owl.theme.css" />
        <link rel="stylesheet" href="js/owl-carousel/owl.transitions.css" />
        <link rel="stylesheet" href="style.css">

        <!-- Google Fonts -->
        <link href='http://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,700,900' rel='stylesheet' type='text/css'>
        <link href='http://fonts.googleapis.com/css?family=Montserrat:400,700' rel='stylesheet' type='text/css'>


        <!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
           <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
           <!--[if lt IE 9]>
             <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
             <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
           <![endif]-->
        </head>
        <body id="home">
            <!-- Header -->
            <header id="top-header" class="header-home">
                <div class="grid">
                    <div class="col-1-1">
                        <div class="content">
                            <div class="logo-wrap">
                                <a href="#0" class="logo">julianne</a>
                            </div>
                            <nav class="navigation">
                                <input type="checkbox" id="nav-button">
                                <label for="nav-button" onclick></label>
                                <ul class="nav-container">
                                    <li><a href="#home" class="current">Home</a></li>
                                    <li><a href="#services">Skills</a></li>
                                    <li><a href="#work">Portfolio</a></li>
                                    <li><a href="#blog">Blog</a></li>
                                    <li><a href="#pricing">About</a></li>
                                    <li><a href="#team">Resume</a></li>
                                    <li><a href="#contact">Contact</a></li>
                                </ul>
                            </nav>
                        </div>
                    </div>
                </div>
            </header>
            <!-- End Header -->

            <!-- Parallax Section -->
            <div class="parallax-section parallax1">
                <div class="grid grid-pad">
                    <div class="col-1-1">
                         <div class="content content-header" >
                            <h2>Kumusta!</h2>
                            <p>Welcome to my website! I am Julianne Teodosio, a Bachelor of Science in Entertainment and Multimedia Computing student from City College of San Jose Del Monte.</p> 
                        </div>
                    </div>
                </div>
            </div>
            <!-- End Parallax Section -->

            <!-- CurveUp -->
            <svg class="curveUpColor" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                <path d="M0 100 C 20 0 50 0 100 100 Z"></path>
            </svg>

            <!-- Skills Section -->
            <div class="wrap services-wrap" id="services">
                <section class="grid grid-pad services">
                    <h2>Skills</h2>
                    <div class="col-1-4 service-box service-1" >
                        <div class="content">
                            <div class="service-icon">
                                <i class="circle-icon icon-heart4"></i>
                            </div>
                            <div class="service-entry">
                                <h3>Artistry</h3>
                                <p>The skill to see, identify, and create art that is pleasing to the eyes. And the ability to enjoy designing and creating.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-1-4 service-box service-2" >
                        <div class="content">
                            <div class="service-icon">
                                <i class="circle-icon icon-star4"></i>
                            </div>
                            <div class="service-entry">
                                <h3>Imagination</h3>
                                <p>The ability to turn imaginations into illustrations. Enjoys drawing, painting, and sculpting. Can prepare sketches and rough illustrations. </p>
                            </div>
                        </div>
                    </div>
                    <div class="col-1-4 service-box service-3">
                        <div class="content">
                            <div class="service-icon">
                                <i class="circle-icon icon-display"></i>
                            </div>
                            <div class="service-entry">
                                <h3>Design Softwares</h3>
                                <p>Proficiency with Adobe Creative Cloud. Has knowledge in both 2D and 3D design softwares.  </p>
                            </div>
                        </div>
                    </div>
                    <div class="col-1-4 service-box service-4" >
                        <div class="content">
                            <div class="service-icon">
                                <i class="circle-icon icon-user6"></i>
                            </div>
                            <div class="service-entry">
                                <h3>Communication</h3>
                                <p>An active listener, open for suggestions and ideas, and very intuitive.</p>
                            </div>
                        </div>
                    </div>
                </section>
            </div>
            <!-- End Skills Section -->
            
            <!-- CurveDown -->
            <svg class="curveDownColor" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                <path d="M0 0 C 50 100 80 100 100 0 Z"></path>
            </svg>

            <!-- Portfolio Section -->
            <div class="wrap grey recent-wrap" id="work">
                <section class="grid grid-pad">
                    <h2>Portfolio</h2>
                    <!-- Start of Filter section -->
                    <div class="col-1-1 mix">
                        <ul class="filters" >
                            <li class="filter active" data-filter="all">All</li>
                            <li class="filter" data-filter=".illustration">Digital Illustrations</li>
                            <li class="filter" data-filter=".web-design">Traditional Illustrations</li>
                            <li class="filter" data-filter=".photography">Photography</li>
                        </ul>
                    </div>
                    <!-- End of Filter section -->
                    <div class="portfolio-items" >
                        <div class="col-1-3 mix illustration">
                            <div class="content">
                                <div class="recent-work">
                                    <img src="images/work/1-small.jpg" alt="">                                    
                                    <div class="overlay">
                                        <span>Digital Illustrations</span>
                                        <h2><a class="img-wrap" data-rel="lightcase:illustration" title="Asian tourist - Illustration" href="images/work/1-big.jpg">lost</a></h2>
                                    </div>
                                    
                                </div>
                            </div>
                        </div>
                        <div class="col-1-3 mix photography">
                            <div class="content">
                                <div class="recent-work">
                                    <img src="images/work/5-small.jpg" alt="">
                                    <div class="overlay">
                                        <span>Photography</span>
                                        <h2><a class="img-wrap" data-rel="lightcase:photography" title="Blue flowers - Photography" href="images/work/5-big.jpg">rays</a></h2>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-1-3 mix illustration">
                            <div class="content">
                                <div class="recent-work">
                                    <img src="images/work/2-small.jpg" alt="">
                                    <div class="overlay">
                                        <span>Digital Illustrations</span>
                                        <h2><a class="img-wrap" data-rel="lightcase:illustration" title="Batman Wannabe - Illustration" href="images/work/2-big.jpg">stars</a></h2>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-1-3 mix photography">
                            <div class="content">
                                <div class="recent-work">
                                    <img src="images/work/8-small.jpg" alt="">
                                    <div class="overlay">
                                        <span>Photography</span>
                                        <h2><a class="img-wrap" data-rel="lightcase:photography" title="Big city and dreams - Photography" href="images/work/8-big.jpg">shore</a></h2>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-1-3 mix web-design">
                            <div class="content">
                                <div class="recent-work">
                                    <img src="images/work/6-small.jpg" alt="">
                                    <div class="overlay">
                                        <span>Traditional Illustrations</span>
                                        <h2><a class="img-wrap" data-rel="lightcase:webdesign" title="Minimal nature - Web Design" href="images/work/6-big.jpg">i</a></h2>
                                    </div>
                                </div>
                                </div>
                            </div>
                            <div class="col-1-3 mix web-design">
                            <div class="content">
                                <div class="recent-work">
                                    <img src="images/work/3-small.jpg" alt="">
                                    <div class="overlay">
                                        <span>Traditional Illustrations</span>
                                        <h2><a class="img-wrap" data-rel="lightcase:illustration" title="Jack the sailor - Illustration" href="images/work/3-big.jpg">hole</a></h2>
                                    </div>
                                </div>
                                </div>
                            </div>
                            <div class="col-1-3 mix web-design">
                            <div class="content">
                                <div class="recent-work">
                                    <img src="images/work/10-small.jpg" alt="">
                                    <div class="overlay">
                                        <span>Traditional Illustrations</span>
                                        <h2><a class="img-wrap" data-rel="lightcase:illustration" title="Jack the sailor - Illustration" href="images/work/10-big.jpg">coffee</a></h2>
                                    </div>
                                </div>
                                </div>
                            </div>
                            <div class="col-1-3 mix photography">
                            <div class="content">
                                <div class="recent-work">
                                    <img src="images/work/7-small.jpg" alt="">
                                    <div class="overlay">
                                        <span>Photography</span>
                                        <h2><a class="img-wrap" data-rel="lightcase:photography" title="Enjoy live - Photography" href="images/work/7-big.jpg">interior</a></h2>
                                    </div>
                                </div>
                                </div>
                            </div>
                            <div class="col-1-3 mix illustration">
                            <div class="content">
                                <div class="recent-work">
                                    <img src="images/work/4-small.jpg" alt="">
                                    <div class="overlay">
                                        <span>Digital Illustrations</span>
                                        <h2><a class="img-wrap" data-rel="lightcase:illustration" title="Run kitty run - Photography" href="images/work/4-big.jpg">standing</a></h2>
                                    </div>
                                </div>
                                </div>
                            </div>
                            <div class="col-1-3 mix illustration">
                            <div class="content">
                                <div class="recent-work">
                                    <img src="images/work/9-small.jpg" alt="">
                                    <div class="overlay">
                                        <span>Digital Illustrations</span>
                                        <h2><a class="img-wrap" data-rel="lightcase:webdesign" title="Would you? - Web Design" href="images/work/9-big.jpg">portrait</a></h2>
                                    </div>
                                </div>
                                </div>
                            </div>
                        </div>
                      
                        <div class="col-1-1"><a class="btn" href=https://www.instagram.com/hiraethiee/#0>View More at "https://www.instagram.com/hiraethiee/"</a></div>

                </section>  
            </div>
            <!-- End Portfolio Section -->

            <!-- CurveUp -->
            <svg class="curveUpColor" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                <path d="M0 100 C 20 0 50 0 100 100 Z"></path>
            </svg>

              <!-- Quotes Section -->
            <div class="wrap services-wrap" >
                <section class="grid grid-pad">
                    <div class="col-1-1 service-box cl-client-carousel-container">
                        <div class="content">
                            <div class="cl-client-carousel">
                                
                                <div class="item client-carousel-item"><!-- Start of item -->
                                <div class="quotes-icon">
                                    <i class="icon-quotes-left"></i>
                                </div>
                                <p>“To be an artist is to believe in life.”</p>
                                <h4>– Henry Moore.</h4>
                                </div><!-- End of item -->
                                
                                <div class="item client-carousel-item"><!-- Start of item -->
                                <div class="quotes-icon">
                                    <i class="icon-quotes-left"></i>
                                </div>
                                <p>"Art enables us to find ourselves and lose ourselves at the same time."</p>
                                <h4>-Thomas Merton</h4>
                                </div><!-- End of item -->
                                <div class="item client-carousel-item"><!-- Start of item -->
                                <div class="quotes-icon">
                                    <i class="icon-quotes-left"></i>
                                </div>
                                <p>"One eye sees, the other feels."</p>
                                <h4>-Paul Klee</h4>
                                </div><!-- End of item -->
                                
                            </div>
                        </div>
                    </div>
                </section>
            </div>
            <!-- End Quotes Section -->

             <!-- CurveDown -->
            <svg class="curveDownColor" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                <path d="M0 0 C 50 100 80 100 100 0 Z"></path>
            </svg>

            <!-- Blog Section -->
            <div class="wrap blog-grid grey" id="blog">
                <div class="grid grid-pad">
                    <div class="content" >
                        <h2>Blog</h2>
                        <div class="col-1-2" >
                            <article class="post-wrap">
                                <div class="post-img">
                                    <a href="#0"><img src="images/post/post-n1.jpg" alt=""></a>
                                </div>
                                <div class="post">
                                    <h2 class="entry-title"><a href="#0">Arts and Crafts</a></h2>
                                    <div class="post-meta">
                                        <a href="#0">to think less and to do more</a> 
                                    </div>
                                    <p>One of the things that makes me calm is making something with my hands. Choosing colors and painting the picture in my mind. More than painting, I also enjoy sculpting. Creating the shapes one by one and seeing the results as it is. Making something that keeps me focused helps me think less and do more.
                                    </p>
                                </div>
                            </article>
                        </div>
                        <div class="col-1-2" >
                            <article class="post-wrap">
                                <div class="post-img">
                                    <a href="#0"><img src="images/post/post-n2.jpg" alt=""></a>
                                </div>
                                <div class="post">
                                    <h2 class="entry-title"><a href="#0">Food</a></h2>
                                    <div class="post-meta">
                                        <a href="#0">to eat something that i like </a>
                                    </div>
                                    <p>To be able to eat something that I crave instantly makes me in a good mood. It is not everyday that I can choose what I want to eat but when I suddenly crave for something, it is also not everyday that I can eat something that I want. So eating the food that I had in mind, or the food in my favourite list really makes me happy.
                                    </p>
                                </div>
                            </article>
                        </div>
                        <div class="col-1-2" >
                            <article class="post-wrap">
                                <div class="post-img">
                                    <a href="#0"><img src="images/post/post-n3.jpg" alt=""></a>
                                </div>
                                <div class="post">
                                    <h2 class="entry-title"><a href="#0">music</a></h2>
                                    <div class="post-meta">
                                        <a href="#0">to spend good time listening</a> 
                                    </div>
                                    <p>Listening to music gives comfort to a lot of people no matter how different the genre each person is likes. Listening to songs I used to not like, those I loved ever since I first heard, and mostly the songs I used to listen to as a kid gives me different kind of comfort. It lets me reminisce the good old days as well as appreciate today.
                                    </p>
                                </div>
                            </article>
                        </div>
                        <div class="col-1-2" >
                            <article class="post-wrap">
                                <div class="post-img">
                                    <a href="#0"><img src="images/post/post-n4.jpg" alt=""></a>
                                </div>
                                <div class="post">
                                    <h2 class="entry-title"><a href="#0">outdoors</a></h2>
                                    <div class="post-meta">
                                        <a href="#0">to go outside, enjoy the wind, and sunlight</a>
                                    </div>
                                    <p>I used to not like going out, I would prefer to stay home even after staying at home for a week. But this pandemic made me realize that peopple need to go outside just the same as how they breathe. To be near the trees, to be hit by the sun rays, to feel the wind, and to be near other people. I realized that the these things are what makes me more human.
                                    </p>
                                </div>
                            </article>
                        </div>
                        
                    </div>
                </div>
            </div>
            <!-- End Blog Section -->

            <!-- CurveUp -->
            <svg class="curveUpColor" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                <path d="M0 100 C 20 0 50 0 100 100 Z"></path>
            </svg>
            
            <!-- About Me Section -->
            <div class="wrap" id="pricing">
                <div class="grid grid-pad">
                    <div class="content" >
                        <div class="col-1-1">
                            <section id="price-tables">
                                <h2>About Me</h2>
                                <ul id="plans">
                                    <li class="plan" >
                                        <ul class="plan-wrap">
                                            <li class="title"><h2>Hi! This is Julianne!</h2></li>
                                            
                                                <ul class="options">
                                                    <li> <span>
                                                        <p> Hello :) </p>
                                                        <p>I am Julianne Bianca B. Teodosio</p>
                                                        <p>Born in February 17, 2001 at Makati City</p>
                                                        <p>Currently a third-year college student at City College of San Jose Del Monte</p>
                                                        <p>Studying Bachelor of Science in Entertainment and Multimedia Computing</p>

                                                        </span></li>
                                                    <li> <span></span></li>
                                                    <li> <span></span></li>
                                                    <li><span></span></li>
                                                    <li> <span></span></li>
                                                </ul>
                                            
                                        </ul>
                                    </li>
                                    <li class="plan best-plan" >
                                        <ul class="plan-wrap">
                                            <li class="title"><h2 class="best-plan-title">my story</h2></li>
                                            
                                            <li>
                                                <ul class="options">
                                                    <li> <span>

                                                        <p>I am an introverted person who likes to keep my own private space. Although I can look like a quiet person, I can totally be loud when I am in a comfortable situation with the people I am used to be with. I feel that I feel more than I think but still overthink situations. I used to dream a lot of dreams but now I just try to live and realize that happiness comes and goes. </p>
                                                        </p>

                                                    </span></li>
                                                    <li> <span></span></li>
                                                    <li> <span> </span></li>
                                                    <li><span> </span></li>
                                                    <li> <span> </span></li>
                                                </ul>
                                            </li>
                                            
                                        </ul>
                                    </li>
                                    <li class="plan" >
                                        <ul class="plan-wrap">
                                            <li class="title"><h2>Art Journey</h2></li>
                                            
                                            <li>
                                                <ul class="options">
                                                    <li><span>When I was about 3 years old when I can already hold a pen, I was told that I am talented in drawing since I can illustrate basic elements such as a person, house, or a tree without being taught. Growing up I was told that I should pursue that career. Although some may see it as a compliment, I have found it burdensome since I don't enjoy drawing that much. I just thought that I was being told that I am good at it because my dad is a very talented and great artist and that I got it from him. But since I am used to this nature, I pursued art and hoping to explore more of it. </span></li>
                                                    
                                                </ul>
                                            </li>
                                            
                                        </ul>
                                    </li>
                                    <li class="plan" >
                                        <ul class="plan-wrap">
                                            <li class="title"><h2>goals</h2></li>
                                            
                                            <li>
                                                <ul class="options">
                                                    <li> <span>Today my goals are more about finding my lost self. I had a hard time adjusting with the pandemic situation and couldn't find a way out. Instead of finding happiness I hope to be a person who strives to do better. I want to be a better me, so that I can be of help with the people I love that stayed with me, as well as those who surrounds me. </span></li>
                                                    
                                                </ul>
                                            </li>
                                           
                                        </ul>
                                    </li>
                                    </ul>
                                </section>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- End Pricing Section -->

                <!-- CurveDown -->
                <svg class="curveDownColor" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <path d="M0 0 C 50 100 80 100 100 0 Z"></path>
                </svg>

                <!-- Parallax Section - Counter -->
                <div class="parallax-section parallax2">                    
                    <div class="wrap">
                        <section class="grid grid-pad callout">
                            <div class="col-1-3">
                                <div class="content" >
                                <div class="info-counter">
                                        <div class="info-counter-row">
                                            
                                        </div>
                                        <div class="info-counter-content">
                                            <h5 class="info-counter-number">
                                           
                                           
                                            </h5>
                                        
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-1-3">
                                <div class="content" >
                                <div class="info-counter">
                                        <div class="info-counter-row">
                                           
                                        </div>
                                        <div class="info-counter-content">
                                            <h5 class="info-counter-number">
                                            
                                            </h5>
                                        
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <div class="col-1-3">
                                <div class="content" >
                                <div class="info-counter">
                                        <div class="info-counter-row">
                                        </div>
                                        <div class="info-counter-content">
                                            <h5 class="info-counter-number">
                                            </h5>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </section>
                    </div>
                </div>
                <!-- End Parallax Section -->

                <!-- CurveUp -->
                <svg class="curveUpColor curveGrey" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <path d="M0 100 C 20 0 50 0 100 100 Z"></path>
                </svg>

                <!-- Team Section -->
                <div class="wrap team-wrap grey" id="team">
                    <div class="grid grid-pad">
                        <div class="content" >
                            <h2>Resume</h2>
                            <div class="col-1-4" >
                                <div class="content staff-content">
                                    <div class="recent-work staff-img">
                                        <div class="img-wrap staff-img">
                                            <img src="images/team/user2.png" alt="">
                                           
                                                
                                            </div>
                                        </div>
                                        <div class="work-info staff-info">
                                            <h5>Teodosio, Julianne Bianca</h5>
                                            <span>Graphic Artist</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-1-4" >
                                <div class="content staff-content">
                                    <div class="recent-work staff-img">
                                        <div class="img-wrap staff-img">
                                            <div class="teamsocial">
                                                
                                            </div>
                                        </div>
                                        <div class="work-info staff-info">
                                            <h5>Personal Information</h5>
                                            <span>Birthday: February 17, 2001</span>
                                            <span>Email Address: bsemc.teodosiojbb@gmail.com</span>
                                            <span>Address: B24 L5 Melody Plains Subd., Muzon, CSJDM Bulacan</span>

                                            <h5>Objectives</h5>
                                            <span>To broaden my knowledge and enhance my skills while pursuing a career of my choice. As well as to gain more experience in the field of art so that I can grow and expand my wisdom.</span>
                                            
                                        </div>
                                    </div>
                                </div>
                                
                            </div>
                            <div class="col-1-4" >
                                <div class="content staff-content">
                                    <div class="recent-work staff-img">
                                        <div class="img-wrap staff-img">
                                            
                                            <div class="teamsocial">
                                                
                                            </div>
                                        </div>
                                        <div class="work-info staff-info">
                                            <h5>Education</h5>
                                            <span>City College of San Jose Del Monte (2019-Present)</span>
                                            <span>AMA Computer College - Fairview (2017-2019)</span>                       <span>School of Our Lady of La Salette (2013-2017)</span>
                                            <span>Melody Plains Academy (2005-2013)</span>
                                        </div>
                                    </div>
                                </div>
                                
                            </div>
                            <div class="col-1-4" >
                                <div class="content staff-content">
                                    <div class="recent-work staff-img">
                                        <div class="img-wrap staff-img">
                                            
                                            <div class="teamsocial">
                                                
                                            </div>
                                        </div>
                                        <div class="work-info staff-info">
                                            <h5>Experience</h5>
                                            <span>Crips Digital Studios (2017-2020)</span>
                                            <span>ZKL Arts and Designs (2019)</span>
                                            <h5>Seminars</h5>
                                             <span>Knowing more about Entertainment and Multimedia Computing (2019)</span>
                                            <span>Fundamentals of Graphic Design (2018)</span>
                                        </div>
                                    </div>
                                </div>
                                
                            </div>
                        </div>
                    </div>
                </div>
                <!-- End Team Section -->

                <!-- CurveUp -->
                <svg class="curveUpColor" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <path d="M0 100 C 20 0 50 0 100 100 Z"></path>
                </svg>

               

                <!-- CurveDown -->
                <svg class="curveDownColor curveMapUp" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <path d="M0 0 C 50 100 80 100 100 0 Z"></path>
                </svg>
                
                <!-- Parallax Section -->
                <div class="map">                    
                    <div class="wrap">
                        
                        </section>
                    </div>
                </div>
                <!-- End Parallax Section -->

                <!-- CurveUp -->
                <svg class="curveUpColor curveMapDown" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <path d="M0 100 C 20 0 50 0 100 100 Z"></path>
                </svg>

                <!-- Contact Section -->
                <div class="wrap contact" id="contact">
                    <div class="grid grid-pad" >
                        <h2>Contact</h2>
                        <div class="col-1-2" >
                            <div class="content address">
                                <h3>Be friends with me!</h3>
                                
                                <address>
                                    <div>
                                        <div class="box-icon">
                                            <i class="icon-mail"></i>
                                        </div>
                                        <span>E-mail Address:</span>
                                        <p>bsemc.teodosiojbb@gmail.com</p>
                                    </div>
                                    
                                    <div>
                                        <div class="box-icon">
                                            <i class="icon-instagram"></i>
                                        </div>
                                        <span>Instagram</span>
                                        <p>@hiraethiee</p>
                                    </div>
                                    <div>
                                        <div class="box-icon">
                                            <i class="icon-twitter"></i>
                                        </div>
                                        <span>Twitter</span>
                                        <p>@hiraethiee</p>
                                    </div>
                                    <div>
                                        <div class="box-icon">
                                            <i class="icon-phone"></i>
                                        </div>
                                        <span>Phone:</span>
                                        <p>0945 665 0786</p>
                                    </div>                                  
                                </address>
                            </div>
                        </div>
                         <div class="col-1-2 pleft-25" >
                            <div class="content contact-form">
                                <form class="form">
                                    
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- End Contact Section -->

                <!-- CurveDown -->
                <svg class="curveDownColor" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <path d="M0 0 C 50 100 80 100 100 0 Z"></path>
                </svg>

                

                <div class="loader-overlay">
                    <div class="loader">
                        <div class="bar"></div>
                        <div class="bar"></div>
                        <div class="bar"></div>
                        <div class="bar"></div>
                        <div class="bar"></div>
                    </div>
                </div>

                <!-- JS -->
                <script src="js/jquery.js"></script>
                <script src="js/main.js"></script>
                <script src="js/mixitup.js"></script>
                <script src="js/smoothscroll.js"></script>
                <script src="js/jquery.nav.js"></script>
                <script src="js/owl-carousel/owl.carousel.min.js"></script>
                <script src="https://maps.googleapis.com/maps/api/js"></script>
                <script src="http://cdnjs.cloudflare.com/ajax/libs/waypoints/2.0.3/waypoints.min.js"></script>
                <script src="js/jquery.counterup.min.js"></script>
                <script src="js/lightcase.min.js"></script>
            </body>
        </html>
