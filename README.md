<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" 
          content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" 
          href=
"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
          integrity=
"sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
             crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="responsive.css">
</head>

<body>
    <!-- Navbar header section -->
    <header class="header">
        <nav class="navbar">
            <div class="logo">
                <h2 class="logo-heading">Jessa Gestopa</h2>
            </div>
            <div class="hamburger" id="hamburger">
                <i class="fas fa-bars hamburger-icon"></i>
                <i class="fas fa-times cross-icon"></i>
            </div>
            <div class="menu">
                <ul class="menu-list">
                    <li class="menu-list-items">
                        <a class="links" href="#home">
                              Home
                          </a>
                    </li>
                    <li class="menu-list-items">
                        <a class="links" href="#portfolio">
                              Portfolio
                          </a>
                    </li>
                    <li class="menu-list-items">
                        <a class="links" href="#about">
                              About
                          </a>
                    </li>
                    <li class="menu-list-items">
                        <a class="links" href="#services">
                              Services
                          </a>
                    </li>
                    <li class="menu-list-items">
                        <a class="links" href="#contact">
                              Contact Me
                          </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- Main hero banner -->
    <section id="home" class="hero">
        <div class="intro">
            <div class="headings">
                <h3 class="greet-heading">Hello, I'm</h3>
                <h1 class="my-heading">Jessa Gestopa</h1>
                <h4 class="sub-heading">
                    A web designer, A student from Northwestern Mindanao State College of Science and Technology.
                </h4>
            </div>
            <div class="intro-buttons">
                <button class="btn common-btn">Hire Me</button>
                <button class="btn ghost-btn">Download CV</button>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section class="portfolio" id="portfolio">
        <div class="portfolio-heading">
            <h1 class="my-heading text-center">Featured Portfolio</h1>
        </div>
        <div class="portfolio-content">
            <div class="my-row">
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="Image_-_How_to_design_a_website_.jpeg.webp" 
                                 alt="Web Design Image">
                        </div>
                        <h3 class="greet-heading blue-text">Web Design</h3>
                        <p class="small-para blue-text">Designing</p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="web_development_is_important_176fa0618e.jpg" 
                                 alt="Web Development Image">
                        </div>
                        <h3 class="greet-heading blue-text">
                              Web Development
                          </h3>
                        <p class="small-para blue-text">Development</p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="seo-idea-lightbulbs-ss-1920.jpg" alt="SEO Image">
                        </div>
                        <h3 class="greet-heading blue-text">SEO</h3>
                        <p class="small-para blue-text">Optimization</p>
                    </div>
                </div>
            </div>
            <div class="my-row">
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="hand-drawn-essay-illustration_23-2150268421.avif" 
                                 alt="Content Writting Image">
                        </div>
                        <h3 class="greet-heading blue-text">
                              Content Writing
                          </h3>
                        <p class="small-para blue-text">Writing</p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="wp.jpg" 
                                 alt="Wordpress Image">
                        </div>
                        <h3 class="greet-heading blue-text">
                              WordPress Dev
                          </h3>
                        <p class="small-para blue-text">
                              Content Management System
                          </p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="vde.jpg" 
                                 alt="Video Editing Image">
                        </div>
                        <h3 class="greet-heading blue-text">
                              Video Editing
                          </h3>
                        <p class="small-para blue-text">Editing</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="about-text">
            <h1 class="my-heading">About Me</h1>
            
            <p class="lead-para">
                I am Jessa Gestopa from the province of Zamboanga Del Sur, 
                I'm currently student at Northwertern Mindanao State College Science and Technology,
                I believe that  studying can be challenging, but it's also incredibly rewarding.
                Stay motivated, keep learning, and never give up on your dreams!
            </p>
            
        </div>
        <div class="about-image">
            <img src="ako.jpg" alt="About Image">
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="services-heading">
            <h1 class="my-heading text-center">My Services</h1>
        </div>
        <div class="services-content">
            <div class="my-row">
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fas fa-paint-brush"></i>
                        </div>
                        <h3 class="greet-heading blue-text">Web Design</h3>
                        <p class="small-para">
                            Web design focuses on the visual aspects of a website,
                             including its layout, color scheme, typography, and overall aesthetics.
                             It aims to create a user-friendly and visually appealing experience for website visitors.
                             Web design focuses on the visual aspects of a website, 
                             including its layout, color scheme, typography, and overall aesthetics.
                
                        </p>
                        
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fa-solid fa-code"></i>
                        </div>
                        <h3 class="greet-heading blue-text">
                              Web Development
                          </h3>
                        <p class="small-para">
                            Web development is the process of creating and maintaining websites.
                            It involves coding, designing, and deploying websites using various programming languages and tools.
                            Web development is the process of creating and maintaining websites.
                            It involves coding, designing, and deploying websites using various programming languages and tools.
                        </p>
                    
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fas fa-chart-line"></i>
                        </div>
                        <h3 class="greet-heading blue-text">SEO</h3>
                        <p class="small-para">
                            SEO (Search Engine Optimization) is the practice of improving a website's
                             ranking in search engine results pages (SERPs).
                             It involves optimizing website content, structure,
                             and technical aspects to make it more visible and relevant to search engines.
                             SEO (Search Engine Optimization) is the practice of improving a website's
                          </p>
                        
                    </div>
                </div>
            </div>
            <div class="my-row">
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fas fa-quote-left"></i>
                        </div>
                        <h3 class="greet-heading blue-text">
                              Content Writting
                          </h3>
                        <p class="small-para">
                            Content Writing: This involves creating engaging and informative text for various platforms,
                             including websites, blogs, social media, and marketing materials.
                              Content writers focus on crafting compelling narratives,
                               providing valuable information, and optimizing content for search engines.

                        </p>
                       
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fab fa-wordpress-simple"></i>
                        </div>
                        <h3 class="greet-heading blue-text">
                              WordPress Dev
                          </h3>
                        <p class="small-para">
                            
    
                        WordPress Development: This involves building
                         and customizing websites using the popular WordPress platform. 
                         WordPress developers work with themes, plugins,
                          and code to create functional and aesthetically pleasing websites.
                          and code to create functional and 
                    </p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fas fa-video"></i>
                        </div>
                        <h3 class="greet-heading blue-text">
                              Video Editing
                          </h3>
                        <p class="small-para">
                            Video Editing: This involves using software to manipulate 
                            and enhance video footage.
                             Video editors combine different video clips, 
                             add transitions, insert music and sound effects,
                              and adjust colors and lighting to create a polished 
                              and engaging final product. 
                          
                        </p>
                       
                    
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact me section -->
    <section class="contact" id="contact">
        <div class="contact-heading">
            <h1 class="my-heading text-center">Contact Me</h1>
        </div>
        <div class="contact-content">
            <div class="contact-form-container">
                <h1 class="greet-heading">Get In Touch</h1>
                <form class="contact-form">
                    <input class="form-controls" type="text" 
                           placeholder="Your Name">
                    <input class="form-controls" type="text" 
                           placeholder="Your Email">
                    <input class="form-controls" type="text" 
                           placeholder="Your Phone">
                    <textarea class="form-controls" 
                              placeholder="Write your message" 
                              name="message" id="" cols="30"
                              rows="10">
                      </textarea>
                    <input class="form-btn btn common-btn" 
                           type="submit" value="Send Message">
                </form>
            </div>
            <div class="contact-details">
                <h1 class="greet-heading">My Contact Details</h1>
                <div class="details">
                    <h5 class="contact-heading">EMAIL</h5>
                    <p class="contact-text">jessagestopa77@gmail.com</p>
                </div>
                <div class="details">
                    <h5 class="contact-heading">PHONE</h5>
                    <p class="contact-text">09098045211</p>
                </div>
             <div class="details">
                      <h5 class="contact-heading">ADDRESS</h5>
                    <p class="contact-text">Zamboanga Del Sur</p>
                   
                </div>
            </div>
        </div>
    </section>

    <!-- Footer section -->
    <footer class="footer">
        <div class="footer-content text-center">
            
    
            <div class="social-links">
                <div class="footer-menu">
                    <ul class="footer-menu-list">
                        <li class="footer-list-items">
                            <a class="footer-links" href="https://www.facebook.com/jessa.casiogestopa">
                                <i class="fab fa-facebook-f"></i>
                            </a>
                        </li>
                     
                        <li class="footer-list-items">
                            <a class="footer-links" href="#">
                                <i class="fab fa-instagram"></i>
                            </a>
                        </li>
                       
                    </ul>
                </div>
            </div>
        </div>
    </footer>


</body>

</html>
