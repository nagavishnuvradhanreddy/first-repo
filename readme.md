<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Capstone Project</title>
    <link
    href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet" />
    <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous" />
    <link 
    rel="stylesheet"href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="../Capstone Project/css/index.css"/>
</head>
<body>
<!--Header/Navbar-->
<header>
    <div class="container">
       <nav class="main-nav">
           <div class="logo">
               <img src="../Capstone Project/assets/images/logo.jpg" alt="logo" />
           </div>
           <ul class="navlist">
              <li><a href="#">Home</a></li>
              <li><a href="#Services">Services</a></li>
              <li><a href="#About">About</a></li>
              <li><a href="#Testimonials">Testimonials</a></li>
              <li><a href="#Contact Us">Contact Us</a></li>
           </ul>

           <div class="hamburger-menu">
            <button
                class="navbar-toggler"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#navlist"
                aria-controls="navlist"
                aria-expanded="false"
                aria-label="Expand navigation"
            >
            <i class="fa-solid fa-bars fs-5"></i>
            </button>
            </div>
        </nav>
    </div>
    <!--Collapsible Navigation-->
    <div class="collapse navbar-collapse bg-dark" id="navlist">
        <ul class="navbar-nav mx-auto">
            <li class="nav-item">
                <a class="nav-link text-white text-center" href="#">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-white text-center" href="#services">Services</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-white text-center" href="#testimonials">Testimonials</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-white text-center" href="#contact">Contact Us</a>
            </li>
        </ul>
    </div>
</header>
<!--Hero section-->
<section class="hero">
    <div class="hero-text">
        <h2>
            Best <em>EdTech</em> Company<br />&amp;Programming
            <em>Services</em>
        </h2>
        <div class="divider"></div>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque molestiae, alias dignissimos consequuntur voluptatibus aspernatur necessitatibus incidunt eos atque! Lorem ipsum dolor sit amet consectetur adipisicing elit. Et, tempore!
        </p>
    </div>
</section>

<!--Services-->

<div class="container">
    <section class="row services" id="services">
        <div class="col-12">
            <div class="section-heading">
                <h6>Services</h6>
                <h4>Learn Skills</h4>
            </div>
        </div>
        <div class="col-md-6">
            <div class="service-item">
              <i class="fa-solid fa-book"></i> 
              <h4>Interactive Platform</h4> 
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi,impedit.
              </p>
            </div>
        </div>
        <div class="col-md-6">
            <div class="service-item">
                <i class="fa-solid fa-code"></i>
                <h4>Doubt Support</h4>
                <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptates.    
                </p>
            </div>
        </div>
        <div class="col-md-6">
            <div class="service-item">
                <i class="fa-solid fa-computer-mouse"></i>
                <h4>Interactive Coding Challenges</h4>
                <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. commodi,quod.    
                </p>
            </div>
        </div>
        <div class="col-md-6">
            <div class="service-item">
                <i class="fa-solid fa-tablet"></i>
                <h4>Mobile and Tablet Coding!</h4>
                <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Itaqua soluta .   
                </p>
            </div>
        </div>
        <div class="col-md-6">
            <div class="service-item">
                <i class="fas fa-archway"></i>
                <h4>Support For Coding Enthusiasts</h4>
                <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Maxime,Velit.   
                </p>
            </div>
        </div>
        <div class="col-md-6">
            <div class="service-item">
                <i class="fas fa-puzzle-piece"></i>
                <h4>Customizable Coding Experience</h4>
                <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repellat, laborum?   
                </p>
            </div>
        </div>
    </section>
</div>
<!--Banner-->

<div class ="container-fluid">
    <section class="row banner">
    <div class="col-lg-5 col-md-12">
        <h4>
            Coding <em>Solutions</em> and <strong>Programming</strong> Mastery
        </h4>
    </div>
    <div class="col-lg-7 col-md-12">
        <div class="buttons">
           <div class="btn btn1">
              <a href="#about">Discover More</a>
           </div>
           <div class="btn btn2">
                <a href="#contact">Contact Us</a>
           </div>
        </div>
    </div>
    </section>

    <!--About Us-->
    <section class="row about-us" id="about">
        <div class="col-12">
            <div class="section-heading">
                <h6>About Us</h6>
                <h4>Know Us Better</h4>
            </div>
            <div class="details">
                <div class="btn btn-warning">
                    <span>Coding Courses</span>
                </div>
                <ul class="course-list">
                    <li class="list-head bg-dark-subtle d-none d-md-flex">
                          <span>Course Title</span>
                          <span>Duration</span>
                          <span>Level</span>
                          <span>Instructor</span>
                    </li>
                    <li>
                           <span class="item-title">Web Development Basics</span>
                           <span>3 Months</span>
                           <span>Beginner</span>
                           <span>John Doe</span>
                    </li>
                    <li class="bg-dark-subtle">
                            <span class="item-title">Advanced JavaScript</span>
                            <span>4 Months</span>
                            <span>Intermediate</span>
                            <span>Jane Smith</span>
                    </li>
                    <li>
                        <span class="item-title">Data Structures</span>
                        <span>6 Months</span>
                        <span>Advanced</span>
                        <span>Chris Williams</span>
                    </li>
                    <li class="bg-dark-subtle">
                        <span class="item-title">Full Stack Development</span>
                        <span>8 Months</span>
                        <span>Expert</span>
                        <span>Emily Johnson</span>
                    </li>
                </ul>
            </div>
        </div>
    </section>
</div>
<!--Learning Plan Form-->
<section class="learning-plan container-fluid">
        <div class="row align-items-center justify-content-center py-5">
            <!-- Left Section - Image and Description -->
            <div class="col-lg-6 col-md-6 col-sm-12 text-center">
                <img src="../Capstone Project/assets/images/pic.png" alt="Student with books" class="img-fluid mb-3">
            </div>
            <!-- Right Section - Form -->
            <div class="col-lg-6 col-md-6 col-sm-12">
                <div class="form-container p-4 shadow-lg">
                    <h6>Your Coding Journey</h6>
                    <h4>Create A Learning Plan</h4>
                    <form>
                        <div class="d-flex flex-wrap gap-3">
                            <div class="flex-grow-1">
                                <label for="name" class="form-label">Your Name</label>
                                <input type="text" class="form-control" id="name" placeholder="Enter your name">
                            </div>
                            <div class="flex-grow-1">
                                <label for="email" class="form-label">Your Email</label>
                                <input type="email" class="form-control" id="email" placeholder="Enter your email">
                            </div>
                        </div>
                        <div class="mb-3">
                            <label for="learningArea" class="form-label">Learning Area</label>
                            <input type="text" class="form-control" id="learningArea" placeholder="Enter learning area">
                        </div>
                        <div class="mb-3">
                            <label for="goal" class="form-label">Your Goal</label>
                            <select class="form-select" id="goal">
                                <option selected>Choose an Option</option>
                                <option value="1">Become a Full-Stack Developer</option>
                                <option value="2">Learn Data Science</option>
                                <option value="3">Improve Coding Skills</option>
                            </select>
                        </div>
                        <button type="submit" class="btn btn-primary w-100">Submit Now</button>
                    </form>
                </div>
            </div>
        </div>
    </section>
         <!--Testimonials-->
    <div class="container">
        <section class="row testimonials" id="testimonials">
            <div class="col-12">
                <div class="section-heading text-center">
                    <h6>TESTIMONIALS</h6>
                    <h4>What our Students Say</h4>
                </div>
            </div>
            
         <!--corousel-->
        <div 
            id="testimonialCarousel" 
            class="carousel slide"
            data-bs-ride="carousel"
        >
            <div class="carousel-inner">
              <div class="carousel-item active">
        <!--testimonial card-->
        <div class="testimonial-card">
            <div class="content">
                <i class="fa fa-quote-left"></i>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, enim animi, temporibus id fugiat consectetur debitis sequi aut beatae, ratione ea laboriosam maiores culpa voluptas.</p>
                <h4>Noah Williams</h4>
                <span class="subtitle">Full Stack Developer</span>
            </div>
            <div class="image-container">
                <img src="../Capstone Project/assets/images/testimonials-01.jpg" alt="Noah Williams"/>
            </div>
          </div>
        </div>
        
        <div class="carousel-item">
            <div class="testimonial-card">
                <div class="content">
                    <i class="fa fa-quote-left"></i>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, enim animi, temporibus id fugiat consectetur debitis sequi aut beatae, ratione ea laboriosam maiores culpa voluptas.</p>
                    <h4>Isabella Hernandez</h4>
                    <span class="subtitle">Web Development Student</span>
                </div>
                <div class="image-container">
                    <img src="../Capstone Project/assets/images/testimonials-02.png" alt="Isabella Hernandez"/>
                </div>
            </div>
        </div>

        <div class="carousel-item">
            <!--testimonial card-->
            <div class="testimonial-card">
                <div class="content">
                    <i class="fa fa-quote-left"></i>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, enim animi, temporibus id fugiat consectetur debitis sequi aut beatae, ratione ea laboriosam maiores culpa voluptas.</p>
                    <h4>Sophia Anderson</h4>
                    <span class="subtitle">Data Science Enthusiast</span>
                </div>
                <div class="image-container">
                    <img src="../Capstone Project/assets/images/testimonials-03.jpg" alt="Sophia Anderson"/>
                </div>
            </div>
        </div>
    </div>
    <button 
        class="carousel-control-prev" 
        type="button" 
        data-bs-target="#testimonialCarousel" 
        data-bs-slide="prev"
       >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
    </button>
    <button 
        class="carousel-control-next" 
        type="button" 
        data-bs-target="#testimonialCarousel" 
        data-bs-slide="next"
    >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
        </button>
    </div>
   </section>
</div>
<!--Contact Us-->
<section class="contact-section">
    <h6>Contact Us</h6>
    <h4>Let's Connect</h4>
    
    <div class="map">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d224567.72022471685!2d76.82493141041805!3d28.42316029598877!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390d03d1c62ba76b%3A0xec4dbad7537d963b!2sCN%20-%20Sunrise%20Mentors!5e0!3m2!1sen!2sin!4v1728977232703!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>

    <div class="contact-info">
        <div class="info-item email-item">
            <i class="fas fa-envelope"></i>
            <span>Email: john.doe@codingninjas.com</span>
        </div>
        <div class="info-item phone-item">
            <i class="fas fa-phone"></i>
            <span>Phone: 010-020-0340</span>
        </div>
        <div class="info-item Address-item">
            <i class="fas fa-map-marker-alt"></i>
            <span>Address: Haryana, India</span>
        </div>
    </div>
</section>
<!--Inquiry Form-->
<section class="contact-form">
    <h2>Feel Free To Inquire About Our Coding Courses</h2>
    <form action="#" method="post">
        <div class="form-row">
            <input type="text" placeholder="Your Name" class="input-field">
            <input type="text" placeholder="Your Phone" class="input-field">
        </div>
        <div class="form-row">
            <input type="email" placeholder="Your E-mail" class="input-field">
            <input type="text" placeholder="Subject" class="input-field">
        </div>
        <textarea placeholder="Your Message" class="message-field"></textarea>
        <button class="btn btn-orange mb-3">Send Message</button>
    </form>
</section>
<!--Footer-->
<footer class="footer bg-dark text-center text-white py-3">
    <div class="container">
        <p class="mb-0">Copyright &copy; 2024 Coding Ninjas Co, Ltd. All Rights Reserved.</p>
        <p class="mb-0">Designed by <span class="text-orange">CodingNinjas</span></p>
    </div>
</footer>
<!--script-->
    <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bund
    le.min.js"
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDz
    Oxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
