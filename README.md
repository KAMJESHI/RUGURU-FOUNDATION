# RUGURU-FOUNDATION
Foundation to help the Boy-Child 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RUGURU Foundation - Help a Boy Child</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="logo">🌟 RUGURU Foundation</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#donate">Donate</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <h1>RUGURU Foundation</h1>
                <p>Empowering Boy Children for a Brighter Future</p>
                <a href="#donate" class="cta-button">Make a Donation</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>The RUGURU Foundation is dedicated to providing educational support, mentorship, and resources to help boy children reach their full potential and achieve their dreams.</p>
            
            <div class="mission-vision">
                <div class="mission">
                    <h3>🎯 Our Mission</h3>
                    <p>To provide quality education and support systems that enable boy children to develop into responsible, confident, and successful individuals who contribute positively to society.</p>
                </div>
                <div class="vision">
                    <h3>✨ Our Vision</h3>
                    <p>A world where every boy child has access to opportunities that unlock their potential, regardless of their socioeconomic background.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Donation Section -->
    <section class="donate" id="donate">
        <div class="container">
            <h2>Support Our Cause</h2>
            <p>Your donation directly helps us support boy children through education, mentorship, and development programs.</p>
            
            <div class="donation-methods">
                <div class="donation-box">
                    <h3>📱 Donate via M-Pesa</h3>
                    <div class="donation-details">
                        <p><strong>Paybill Number:</strong> 400200</p>
                        <p><strong>Account Number:</strong> 0743305428</p>
                    </div>
                    <div class="donation-steps">
                        <h4>How to Donate:</h4>
                        <ol style="text-align: left; padding-left: 1.5rem;">
                            <li>Go to M-Pesa menu on your phone</li>
                            <li>Select "Lipa na M-Pesa Online"</li>
                            <li>Enter Paybill: <strong>400200</strong></li>
                            <li>Enter Account: <strong>0743305428</strong></li>
                            <li>Enter your donation amount</li>
                            <li>Enter your M-Pesa PIN</li>
                            <li>Complete the transaction</li>
                        </ol>
                    </div>
                </div>
            </div>

            <div class="impact">
                <h3>💪 Your Impact</h3>
                <ul>
                    <li><strong>500 KES</strong> - Provides school supplies for a child</li>
                    <li><strong>1,000 KES</strong> - Funds one month of tuition support</li>
                    <li><strong>5,000 KES</strong> - Provides mentorship program for 5 children</li>
                    <li><strong>10,000 KES</strong> - Supports a child's semester at school</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <h2>Get in Touch</h2>
            <p>Have questions? We'd love to hear from you!</p>
            
            <div class="contact-info">
                <div class="info-box">
                    <h3>📞 Phone</h3>
                    <p>+254 743 305 428</p>
                </div>
                <div class="info-box">
                    <h3>📧 Email</h3>
                    <p>info@rugurufoundation.org</p>
                </div>
                <div class="info-box">
                    <h3>📍 Location</h3>
                    <p>Kenya</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2026 RUGURU Foundation. All rights reserved. | Empowering Boy Children</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Navigation */
.navbar {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 1rem 0;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.navbar .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-links a {
    color: white;
    text-decoration: none;
    transition: opacity 0.3s;
}

.nav-links a:hover {
    opacity: 0.8;
}

/* Hero Section */
.hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 8rem 0;
    text-align: center;
}

.hero-content h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
}

.hero-content p {
    font-size: 1.5rem;
    margin-bottom: 2rem;
}

.cta-button {
    display: inline-block;
    background: #ff6b6b;
    color: white;
    padding: 1rem 2rem;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background 0.3s, transform 0.3s;
}

.cta-button:hover {
    background: #ee5a52;
    transform: scale(1.05);
}

/* About Section */
.about {
    padding: 4rem 0;
    background: #f8f9fa;
}

.about h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 2rem;
    color: #667eea;
}

.about > .container > p {
    text-align: center;
    font-size: 1.1rem;
    margin-bottom: 3rem;
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;
}

.mission-vision {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2rem;
}

.mission, .vision {
    background: white;
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.mission h3, .vision h3 {
    color: #667eea;
    margin-bottom: 1rem;
    font-size: 1.5rem;
}

/* Donation Section */
.donate {
    padding: 4rem 0;
    background: white;
}

.donate h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #667eea;
}

.donate > .container > p {
    text-align: center;
    font-size: 1.1rem;
    margin-bottom: 3rem;
}

.donation-methods {
    display: grid;
    grid-template-columns: 1fr;
    gap: 2rem;
    margin-bottom: 3rem;
}

.donation-box {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

.donation-box h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
}

.donation-details {
    background: rgba(255,255,255,0.1);
    padding: 1rem;
    border-radius: 5px;
    margin-bottom: 1rem;
    font-size: 1.1rem;
}

.donation-details p {
    margin: 0.5rem 0;
}

.donation-steps {
    background: rgba(255,255,255,0.1);
    padding: 1rem;
    border-radius: 5px;
    line-height: 1.8;
}

.impact {
    background: #f8f9fa;
    padding: 2rem;
    border-radius: 8px;
    text-align: center;
}

.impact h3 {
    color: #667eea;
    margin-bottom: 1.5rem;
    font-size: 1.5rem;
}

.impact ul {
    list-style: none;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
}

.impact li {
    background: white;
    padding: 1rem;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}

/* Contact Section */
.contact {
    padding: 4rem 0;
    background: #f8f9fa;
}

.contact h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #667eea;
}

.contact > .container > p {
    text-align: center;
    font-size: 1.1rem;
    margin-bottom: 3rem;
}

.contact-info {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
}

.info-box {
    background: white;
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    text-align: center;
}

.info-box h3 {
    color: #667eea;
    margin-bottom: 1rem;
    font-size: 1.3rem;
}

/* Footer */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 2rem 0;
}

/* Responsive Design */
@media (max-width: 768px) {
    .navbar .container {
        flex-direction: column;
        gap: 1rem;
    }

    .nav-links {
        flex-direction: column;
        gap: 1rem;
        text-align: center;
    }

    .hero-content h1 {
        font-size: 2rem;
    }

    .hero-content p {
        font-size: 1.1rem;
    }

    .hero {
        padding: 3rem 0;
    }

    .mission-vision {
        grid-template-columns: 1fr;
    }

    .about h2, .donate h2, .contact h2 {
        font-size: 1.8rem;
    }
}
// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            target.scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        }
    });
});

// Add scroll animation effect
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};

const observer = new IntersectionObserver(function(entries) {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.style.opacity = '1';
            entry.target.style.transform = 'translateY(0)';
        }
    });
}, observerOptions);

document.querySelectorAll('.mission, .vision, .donation-box, .info-box, .impact').forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(20px)';
    el.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
    observer.observe(el);
});

