<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baker's Staple - Premium Glazes for Bakers</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        :root {
            --primary-color: #f8e9e2;
            --secondary-color: #e6c9df;
            --accent-color: #b8d8e3;
            --text-color: #4a4a4a;
        }
        
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            color: var(--text-color);
            background-color: #fefefe;
        }
        
        .navbar {
            background-color: white;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        
        .navbar-brand {
            font-weight: 700;
            color: var(--text-color);
        }
        
        .nav-link {
            color: var(--text-color);
            font-weight: 500;
        }
        
        .hero {
            background-color: var(--primary-color);
            padding: 6rem 0;
        }
        
        .hero h1 {
            font-weight: 700;
            margin-bottom: 1.5rem;
        }
        
        .hero p {
            font-size: 1.2rem;
        }
        
        .btn-primary {
            background-color: var(--accent-color);
            border: none;
            color: var(--text-color);
            font-weight: 600;
            padding: 0.6rem 1.5rem;
            border-radius: 30px;
        }
        
        .btn-primary:hover {
            background-color: #9ec9d8;
        }
        
        .product-card {
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s ease;
            margin-bottom: 2rem;
            border: none;
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        }
        
        .product-card:hover {
            transform: translateY(-5px);
        }
        
        .section-title {
            position: relative;
            margin-bottom: 2rem;
            padding-bottom: 1rem;
        }
        
        .section-title:after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 80px;
            height: 3px;
            background-color: var(--secondary-color);
        }
        
        .about-section {
            background-color: #f9f9f9;
        }
        
        .contact-form label {
            font-weight: 500;
        }
        
        .form-control:focus {
            border-color: var(--accent-color);
            box-shadow: 0 0 0 0.25rem rgba(184, 216, 227, 0.25);
        }
        
        footer {
            background-color: var(--text-color);
            color: white;
            padding: 3rem 0;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg sticky-top">
        <div class="container">
            <a class="navbar-brand" href="#">Baker's Staple</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#products">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#faq">FAQ</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <h1>Premium Glazes for Bakery Perfection</h1>
                    <p class="lead">Elevate your baked goods with our handcrafted, flavorful glazes. Made with quality ingredients for professional and home bakers alike.</p>
                    <a href="#products" class="btn btn-primary mt-3">Explore Flavors</a>
                </div>
                <div class="col-lg-6">
                    <img src="/api/placeholder/600/400" alt="Assorted pastries with glazes" class="img-fluid rounded">
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section class="py-5" id="products">
        <div class="container">
            <h2 class="section-title">Our Glaze Collection</h2>
            <div class="row">
                <!-- Product 1 -->
                <div class="col-md-4">
                    <div class="card product-card">
                        <img src="/api/placeholder/400/300" class="card-img-top" alt="Classic Vanilla Glaze">
                        <div class="card-body">
                            <h5 class="card-title">Classic Vanilla Glaze</h5>
                            <p class="card-text">Our bestselling smooth, sweet vanilla glaze perfect for donuts and pastries.</p>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="col-md-4">
                    <div class="card product-card">
                        <img src="/api/placeholder/400/300" class="card-img-top" alt="Chocolate Ganache Glaze">
                        <div class="card-body">
                            <h5 class="card-title">Chocolate Ganache Glaze</h5>
                            <p class="card-text">Rich, silky chocolate glaze that sets beautifully on cakes and pastries.</p>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="col-md-4">
                    <div class="card product-card">
                        <img src="/api/placeholder/400/300" class="card-img-top" alt="Lemon Zest Glaze">
                        <div class="card-body">
                            <h5 class="card-title">Lemon Zest Glaze</h5>
                            <p class="card-text">Tangy and bright glaze with real lemon zest, perfect for summer treats.</p>
                        </div>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="col-md-4">
                    <div class="card product-card">
                        <img src="/api/placeholder/400/300" class="card-img-top" alt="Maple Pecan Glaze">
                        <div class="card-body">
                            <h5 class="card-title">Maple Pecan Glaze</h5>
                            <p class="card-text">Sweet maple flavor with crushed pecans for added texture and nutty taste.</p>
                        </div>
                    </div>
                </div>
                
                <!-- Product 5 -->
                <div class="col-md-4">
                    <div class="card product-card">
                        <img src="/api/placeholder/400/300" class="card-img-top" alt="Raspberry Glaze">
                        <div class="card-body">
                            <h5 class="card-title">Raspberry Glaze</h5>
                            <p class="card-text">Made with real raspberries for a fruity, vibrant topping to any pastry.</p>
                        </div>
                    </div>
                </div>
                
                <!-- Product 6 -->
                <div class="col-md-4">
                    <div class="card product-card">
                        <img src="/api/placeholder/400/300" class="card-img-top" alt="Caramel Glaze">
                        <div class="card-body">
                            <h5 class="card-title">Caramel Glaze</h5>
                            <p class="card-text">Rich, buttery caramel glaze that adds depth and sweetness to any dessert.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about-section py-5" id="about">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6 order-lg-2">
                    <img src="/api/placeholder/600/400" alt="Our workshop" class="img-fluid rounded">
                </div>
                <div class="col-lg-6 order-lg-1">
                    <h2 class="section-title">About Baker's Staple</h2>
                    <p>Founded in 2018, Baker's Staple began with a passion for creating perfect glazes that would elevate any baked good. What started as experiments in a home kitchen has grown into a beloved supplier for local bakeries and home bakers alike.</p>
                    <p>We pride ourselves on using only high-quality ingredients, creating glazes that are ready to use and consistently delicious. Our small team handcrafts each batch with care, ensuring the perfect consistency and flavor every time.</p>
                    <p>Whether you're a professional baker looking for reliable, delicious glazes for your creations or a home baker wanting to add a professional touch to your treats, Baker's Staple has the perfect glaze for you.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="py-5" id="faq">
        <div class="container">
            <h2 class="section-title">Frequently Asked Questions</h2>
            <div class="accordion" id="faqAccordion">
                <!-- FAQ Item 1 -->
                <div class="accordion-item">
                    <h2 class="accordion-header">
                        <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#faq1">
                            How should I store my glazes?
                        </button>
                    </h2>
                    <div id="faq1" class="accordion-collapse collapse show" data-bs-parent="#faqAccordion">
                        <div class="accordion-body">
                            Our glazes should be stored in a cool, dry place. Once opened, keep refrigerated and use within 3 weeks for best quality. Bring to room temperature before use.
                        </div>
                    </div>
                </div>
                
                <!-- FAQ Item 2 -->
                <div class="accordion-item">
                    <h2 class="accordion-header">
                        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq2">
                            Do you offer wholesale pricing?
                        </button>
                    </h2>
                    <div id="faq2" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
                        <div class="accordion-body">
                            Yes! We offer wholesale pricing for bakeries, cafés, and other food businesses. Please contact us through our form below for wholesale inquiries and pricing.
                        </div>
                    </div>
                </div>
                
                <!-- FAQ Item 3 -->
                <div class="accordion-item">
                    <h2 class="accordion-header">
                        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq3">
                            Are your glazes suitable for vegan baking?
                        </button>
                    </h2>
                    <div id="faq3" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
                        <div class="accordion-body">
                            We offer a select range of vegan glazes including our fruit-based varieties. Please check the product descriptions or contact us to confirm which glazes are vegan-friendly.
                        </div>
                    </div>
                </div>
                
                <!-- FAQ Item 4 -->
                <div class="accordion-item">
                    <h2 class="accordion-header">
                        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq4">
                            What is the shelf life of your products?
                        </button>
                    </h2>
                    <div id="faq4" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
                        <div class="accordion-body">
                            Unopened, our glazes have a shelf life of 4 months from production date. Each jar is labeled with a "best by" date for your convenience.
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-5" id="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="row">
                <div class="col-lg-6">
                    <form class="contact-form">
                        <div class="mb-3">
                            <label for="name" class="form-label">Name</label>
                            <input type="text" class="form-control" id="name" required>
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Email</label>
                            <input type="email" class="form-control" id="email" required>
                        </div>
                        <div class="mb-3">
                            <label for="subject" class="form-label">Subject</label>
                            <select class="form-select" id="subject">
                                <option selected>General Inquiry</option>
                                <option>Wholesale Information</option>
                                <option>Product Questions</option>
                                <option>Feedback</option>
                            </select>
                        </div>
                        <div class="mb-3">
                            <label for="message" class="form-label">Message</label>
                            <textarea class="form-control" id="message" rows="4" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>
                <div class="col-lg-6">
                    <div class="ms-lg-4 mt-4 mt-lg-0">
                        <h4>Contact Information</h4>
                        <p><strong>Email:</strong> info@bakersstaple.com</p>
                        <p><strong>Phone:</strong> (555) 123-4567</p>
                        <p><strong>Address:</strong> 123 Bakery Lane, Flourtown, CA 90210</p>
                        <p><strong>Hours:</strong> Monday-Friday, 9am-5pm</p>
                        
                        <h4 class="mt-4">Follow Us</h4>
                        <div class="d-flex gap-3 mt-2">
                            <a href="#" class="text-decoration-none">
                                <img src="/api/placeholder/32/32" alt="Facebook">
                            </a>
                            <a href="#" class="text-decoration-none">
                                <img src="/api/placeholder/32/32" alt="Instagram">
                            </a>
                            <a href="#" class="text-decoration-none">
                                <img src="/api/placeholder/32/32" alt="Pinterest">
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h5>Baker's Staple</h5>
                    <p>Crafting premium glazes for professional and home bakers since 2018.</p>
                </div>
                <div class="col-md-3">
                    <h5>Quick Links</h5>
                    <ul class="list-unstyled">
                        <li><a href="#home" class="text-white">Home</a></li>
                        <li><a href="#products" class="text-white">Products</a></li>
                        <li><a href="#about" class="text-white">About Us</a></li>
                        <li><a href="#contact" class="text-white">Contact</a></li>
                    </ul>
                </div>
                <div class="col-md-3">
                    <h5>Newsletter</h5>
                    <p>Subscribe for updates and baking tips</p>
                    <div class="input-group mb-3">
                        <input type="email" class="form-control" placeholder="Email">
                        <button class="btn btn-light" type="button">Subscribe</button>
                    </div>
                </div>
            </div>
            <div class="border-top border-secondary pt-4 mt-4">
                <p class="text-center mb-0">&copy; 2025 Baker's Staple. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        // Simple form handling with alert
        document.querySelector('.contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message! We will get back to you soon.');
            this.reset();
        });

        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
