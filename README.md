<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tr4de.in</title>
    
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <style>                  
        /* Reset margins, paddings, and set box-sizing */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Navbar Base Styles */
        .navbar {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            background: linear-gradient(to right, #141e30, #243b55);
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 15px 0;
            z-index: 1000;
            box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.5);
        }

        .navbar ul {
            list-style: none;
            display: flex;
            gap: 30px;
        }

        .navbar ul li {
            display: inline-block;
        }

        .navbar ul li a {
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            transition: 0.3s ease-in-out;
        }

        /* Active Link Styling */
        .navbar ul li a.active {
            background: #00c6ff;
            color: white;
        }

        .nav-link.active {
            color: #00c6ff;
            font-weight: bold;
            border-bottom: 2px solid #00c6ff;
        }

        /* Body Styles */
  
            body {
    background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    background-size: cover;
    background-color: #203a43; /* Fallback for smooth scrolling */
            color: white;
            user-select: none;
        }
        
      .section {
    min-height: 100vh;
    display: flex;    
    justify-content: center;
    align-items: center;
}
section {
    scroll-margin-top: 100px;
}
    
        /* Smooth Scrolling */
    html {
          scroll-behavior: smooth;
       }
       
        /* Center the Hero Content */
        .hero-content {
            text-align: center;
            margin: 80px auto;
        }

        /* Heading Styles */
        .hero-content h1 {
            font-size: 2.5rem;
            font-weight: bold;
            margin-bottom: 15px;
            letter-spacing: 1.5px;
            text-transform: uppercase;
        }

        /* Paragraph */
        .hero-content p {
            font-size: 1.2rem;
            margin-bottom: 25px;
            opacity: 0.9;
        }

        /* Button Styles */
        .btn {
            display: inline-block;
            padding: 12px 30px;
            font-size: 1.2rem;
            font-weight: bold;
            text-transform: uppercase;
            text-decoration: none;
            color: white;
            background: linear-gradient(45deg, #ff8c00, #ff5e62);
            border-radius: 50px;
            transition: all 0.3s ease-in-out;
            box-shadow: 0px 4px 10px rgba(255, 94, 98, 0.5);
        }

        /* Hover Effect */
        .btn:hover {
            background: linear-gradient(45deg, #ff5e62, #ff8c00);
            transform: scale(1.05);
            box-shadow: 0px 5px 20px rgba(255, 94, 98, 0.7);
        }
 
        /* About Section */
        .about-section {
            text-align: center;
            padding: 60px 20px;
        }

        /* Container */
        .container {
            max-width: 800px;
            margin: 0 auto;
        }

        /* Headings */
        .about-section h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            text-transform: uppercase;
        }

        .subtitle {
            font-size: 1.5rem;
            margin-bottom: 20px;
            font-style: italic;
            opacity: 0.8;
        }

        /* Paragraphs */
        .about-section p {
            font-size: 1.2rem;
            line-height: 1.6;
            margin-bottom: 20px;
        }

        /* Features List */
        .features-list {
            list-style: none;
            padding: 0;
            margin: 20px 0;
            text-align: left;
        }

        .features-list li {
            font-size: 1.2rem;
            padding: 10px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            margin: 10px 0;
        }

        .about-section p {
            font-size: 1rem;
        }
        
        /* Container for 3D Flip Effect */
.card-container {
  perspective: 450px;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 30vh;  
  background: #0;
}

.card-container img {
width: 100%;
  height: 100%;
    
}
/* Business Card Styles */
.business-card {
  width: 300px;
  height: 200px;
  transform-style: preserve-3d;
  transition: transform 0.6s;
  position: relative;
}


.business-card.flipped {
  transform: rotateY(180deg);
}

/* Front and Back Side */
.front, .back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 15px;
}

/* Card Background Colors */
.front {
  background-color: black;
  color: white;
}

.back {
  background-color: black;
  color: white;
  transform: rotateY(180deg);
}

/* Profile Image */
.profile-image {
  width: 100%;
  height: 100%;
}

/* Text Styles */
.full-name {
  font-size: 1.5em;
  margin: 10px 0;
}

.designation {
  font-size: 1em;
  color: #aaa;
  text-align: center;
}

.back a {
  text-decoration: none;
  color: inherit;
  font-weight: bold;
}

/* Social Media Links */
.social-media a {
  display: inline-block;
  margin: 5px 0;
  text-decoration: none;
  color: #ffffff;
  font-weight: bold;
}

.social-media a:hover {
  text-decoration: none;
}

/* Icon Colors */
.fa-phone {
  color: #007bff; /* Blue */
}

.fa-envelope {
  color: #ff9800; /* Orange */
}

.fa-whatsapp {
  color: #1EBE5D; /* WhatsApp Green */
}

.fa-instagram {
  color: #E4405F; /* Instagram Pink */
}

.fa-facebook{
    color:#165DB6;
}

.fa-telegram{
color:#0077B5;
}

.C-btn {
    background: #00c6ff;
    color: white;
    font-size: 18px;
    font-weight: bold;
    padding: 12px 24px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: all 0.3s ease-in-out;
    box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.5);
    outline: none;
    position: relative;
    overflow: hidden;
    display: inline-block;
    text-align: center;
}

/* Hover Effect */
.C-btn:hover {
    filter: brightness(0.9); /* Slight darkening on hover */
    transform: scale(1.05);
}

/* Click Effect */
.C-btn:active {
    transform: scale(0.95);
}

/* Ripple Effect */
.C-btn::after {
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    background: rgba(255, 255, 255, 0.2);
    top: 0;
    left: 0;
    opacity: 0;
    transition: opacity 0.3s ease-in-out;
}

.C-btn:hover::after {
    opacity: 1;
}

.footer {
    display: flex;
    flex-wrap: wrap; /* Allows wrapping if needed */
    justify-content: space-around; /* Space out the items */
    align-items: center;
    flex-direction: row; /* Ensure it stays horizontal */
    }

footer {
    background: black !important;
    color: #fff;
    padding: 40px 0;
    text-align: center;
    position: relative;
    z-index: 10;
}

.footer-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;
    width: 100%;
}

.footer-links, .footer-social, .footer-logo {
    flex: 1; /* Make each section take equal space */
    min-width: 150px; /* Prevent items from getting too small */
    text-align: center; /* Center content */
}

@media (max-width: 768px) {
    .footer {
        flex-wrap: nowrap; /* Prevent stacking */
        overflow-x: auto; /* Allow horizontal scrolling if needed */
        white-space: nowrap; /* Keep items in a single row */
    }
    
    .footer-container {
        flex-direction: row; /* Maintain row structure */
    }
}

.footer-logo h2 {
    font-size: 26px;
    color: #00aced;
    margin-bottom: 5px;
}

.footer-logo p {
    font-size: 14px;
    opacity: 0.8;
}

.footer-links, .footer-social {
    margin: 15px 0;
}

.footer-links h3, .footer-social h3 {
    font-size: 18px;
    margin-bottom: 10px;
    color: #00aced;
}

.footer-links a {
    display: block;
    color: #fff;
    text-decoration: none;
    margin: 5px 0;
    transition: 0.3s;
}



.footer-social a {
    color: #fff;
    font-size: 20px;
    margin: 0 10px;
    display: inline-block;
    transition: 0.3s;
}

.footer-social a:hover {
    color: #00aced;
}

.footer-bottom {
    margin-top: 20px;
    padding-top: 10px;
    border-top: 1px solid #333;
    font-size: 14px;
    opacity: 0.7;
}

.footer-bottom a {
    color: #00aced;
    text-decoration: none;
}

.footer-bottom a:hover {
    text-decoration: underline;
}

@media (max-width: 768px) {
    .footer-container {
        flex-direction: column;
        text-align: center;
    }
}  
       .explore-courses-btn {
    display: inline-block;
    background: linear-gradient(45deg, #ff6a00, #ee0979); /* Gradient background */
    color: #fff; /* White text */
    padding: 12px 16px; /* Default padding */
    margin-top: 15px; /* Space above the button */
    border: none;
    border-radius: 30px; /* Fully rounded corners for a modern look */
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 1px;
    text-decoration: none; /* Remove underline from text */
    transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out; /* Smooth animation effects */
}

.explore-courses-btn:hover {
    transform: translateY(-3px); /* Slight lift effect on hover */
    box-shadow: 0 10px 20px rgba(238, 9, 121, 0.2); /* Subtle shadow for depth */
}

/* Laptop-specific styles for the button inside the footer */
@media (min-width: 1024px) and (max-width: 1440px) {
    footer .explore-courses-btn {
        padding: 16px 24px !important;  /* Increase horizontal padding */
        font-size: 1.2rem !important;   /* Increase font size */
    }
}
    </style>

</head>
<body>

    <!-- Navigation Bar -->
<main>
    <nav class="navbar">
        <ul>
            <li>
                <a href="#home" class="nav-link">Home</a></li>
            <li><a href="#About" class="nav-link">About</a></li>
            <li><a href="#Connect" class="nav-link">Connect</a></li>
        </ul>
    </nav>
</main>
    <!-- Home -->
    <section id="home" class="home"><br>
        <div class="hero-content">
            <h1>Welcome to Tr4de.in</h1>
            <p>Learn, trade, and grow with expert guidance in the forex market.</p>
            <a href="Courses.html" class="btn">Explore Courses</a>
        </div><br>
    </section>

    <!-- About Section -->
    <section id="About" class="about-section">
        <div class="container">
            <h1>About Us</h1>
            <p class="subtitle">Empowering Traders with Knowledge & Expertise</p>
            <p>
                At <strong>Tr4de.in</strong>, we are committed to helping traders of all levels <strong>learn, trade, and grow</strong> in the fast-paced world of <strong>forex trading</strong>. 
                Whether you’re a beginner looking to understand the basics or an experienced trader aiming to refine your strategy, we provide the resources, insights, and tools to help you succeed.
            </p>
            
            <h2>Why Choose Tr4de.in?</h2>
            <ul class="features-list">
                <li>✅ <strong>Expert-Led Education</strong> – Learn from seasoned traders with years of market experience.</li>
                <li>✅ <strong>Comprehensive Courses</strong> – Covering technical analysis, risk management, trading psychology, and more.</li>
                <li>✅ <strong>Market Insights & Strategies</strong> – Stay ahead with real-time updates, forecasts, and proven strategies.</li>
                <li>✅ <strong>Community & Support</strong> – Join a network of like-minded traders and grow together.</li>
            </ul>

         "we help trader's <strong>build confidence & consistency</strong> in the Forex market"       
        </div>
    </section>
    
 <!-- contact -->
        <section id="Connect" class ="about-section">
            
                <div class="container">
         <h1> Contact us</h1>
            <p class="subtitle">We’re here to help! Reach out to us anytime.</p> </div> <br> <br>  <br>                    
     <!-- card -->
     <div class="card-container">
      
    <div class="business-card" id="businesscard">
      <!-- Front Side -->
      <div class="front"><img src="https://i.ibb.co/wF8LKhC5/profile.jpg"alt="Profile Image">
      </div>
      
      <!-- Back Side -->
      <div class="back">
      <br> <h3>Contact Information</h3><br>
        <p>
          <i class="fas fa-envelope"></i>
          <a href="mailto:tr4de.in@gmail.com">tr4de.in@gmail.com</a>
        <br>
          <i class="fas fa-phone"></i>
          <a href="tel:+916238299788">+91 6238299788</a>
              <!-- Social Media Links -->
        <div class="social-media">
            <i class="fab fa-whatsapp"></i>
            <a href="https://wa.me/+916238299788" target="_blank">WhatsApp</a><br>
            <i class="fab fa-instagram"></i>
            <a href="https://www.instagram.com/tr4de.in?igsh=ajlhcnd0OW1zY2c2" target="_blank">Instagram</a>
          </p>
        </div>    
      </div>
</div>
</div> <br><br><p class="subtitle">
Stay in touch with us</p><button id="C-btn" class="C-btn">connect</button>
                
      
           
  </section>

<footer>
    <div class="footer-container">
        <div class="footer-logo">
            <h2>Trade.in</h2>
            <p>Your Trusted Trading Partner</p>
        </div>

        <div class="footer-links">
            <h3>Quick Links</h3>
            <a href="#home">Home</a>
            <a href="#About">About</a>
            <a href="#Connect">Contact</a>
            
        </div>

        <div class="footer-social">
            <h3>Follow Us</h3>
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-telegram"></i></a>
            <a href="https://chat.whatsapp.com/Ehw9ppiB7Hv7o2DQzUn4tF"><i class="fab fa-whatsapp"></i></a>
            <a href="https://www.instagram.com/tr4de.in?igsh=ajlhcnd0OW1zY2c2"><i class="fab fa-instagram"></i></a>
        </div>
        <a href="Courses.html" class="explore-courses-btn">Explore Courses</a>
    </div>

    <div class="footer-bottom">
        <p>&copy; 2025 Trade.in | All Rights Reserved | <a href="#">Privacy Policy</a></p>
    </div>
</footer>
      
      
      <script type="text/javascript" defer>
                  document.querySelectorAll('a[href^="#"]').forEach(link => {
  link.addEventListener("click", function(e) {
    e.preventDefault();
    const targetId = this.getAttribute("href").substring(1);
    const targetSection = document.getElementById(targetId);
    if (targetSection) {
      window.scrollTo({
        top: targetSection.offsetTop - document.querySelector(".navbar").offsetHeight,
        behavior: "smooth"
      });
    }
  });
});
          
document.addEventListener("DOMContentLoaded", function () {
    const sections = document.querySelectorAll("section");
    const navLinks = document.querySelectorAll(".nav-link");
    const navbarHeight = document.querySelector(".navbar").offsetHeight;

    // Ensure sections have a minimum height
    sections.forEach(section => {
        if (section.offsetHeight < window.innerHeight / 2) {
            section.style.minHeight = "50vh";
        }
    });

    // Function to highlight the active section in the navbar
    function updateActiveLink() {
        let currentSection = "";
        sections.forEach(section => {
            const sectionTop = section.offsetTop - navbarHeight;
            const sectionHeight = section.clientHeight;
            if (window.scrollY >= sectionTop && window.scrollY < sectionTop + sectionHeight) {
                currentSection = section.getAttribute("id");
            }
        });

        navLinks.forEach(link => {
            link.classList.remove("active");
            if (link.getAttribute("href").substring(1) === currentSection) {
                link.classList.add("active");
            }
        });
    }

    // Scroll event to update active link
    window.addEventListener("scroll", updateActiveLink);

    // Smooth scrolling when clicking nav links
    document.querySelector(".navbar").addEventListener("click", function (e) {
        if (e.target.classList.contains("nav-link")) {
            e.preventDefault();
            const targetId = e.target.getAttribute("href").substring(1);
            const targetSection = document.getElementById(targetId);
            if (targetSection) {
                window.scrollTo({
                    top: targetSection.offsetTop - navbarHeight,
                    behavior: "smooth",
                });
                // Update active class immediately
                navLinks.forEach(link => link.classList.remove("active"));
                e.target.classList.add("active");
            }
        }
    });

    // Highlight first section on page load
    updateActiveLink();
});

document.addEventListener("DOMContentLoaded", function () {
    const businessCard = document.querySelector(".business-card");
    const flipButton = document.querySelector("#C-btn");

    if (businessCard && flipButton) {
        flipButton.addEventListener("click", function () {
            businessCard.classList.toggle("flipped");
        });
    } else {
        console.error("Element not found");
    }
});
</script>
      
</body>
</html> 
