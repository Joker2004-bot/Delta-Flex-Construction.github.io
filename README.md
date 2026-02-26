<!DOCTYPE html>
<html>
<head>
    <title>Delta Flex Construction</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0b0f1a;
            color: #ffffff;
        }

        /* NAVIGATION */
        nav {
            background: #05070d;
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav h3 {
            color: #00aaff;
            margin: 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-size: 14px;
        }

        nav a:hover {
            color: #00aaff;
        }

        /* HERO SECTION */
        header {
            background: linear-gradient(rgba(0,0,0,0.75), rgba(0,0,0,0.75)),
                        url("solar-install.jpg");
            background-size: cover;
            background-position: center;
            text-align: center;
            padding: 120px 20px;
        }

        header h1 {
            font-size: 48px;
            margin-bottom: 10px;
            color: #00aaff;
        }

        header p {
            font-size: 22px;
            margin-bottom: 30px;
        }

        .btn {
            background: #007bff;
            color: white;
            padding: 12px 30px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #0056b3;
        }

        section {
            padding: 70px 20px;
            max-width: 1100px;
            margin: auto;
        }

        h2 {
            text-align: center;
            margin-bottom: 40px;
            color: #00aaff;
        }

        /* ABOUT */
        .about p {
            text-align: center;
            max-width: 800px;
            margin: auto;
            line-height: 1.6;
        }

        /* SERVICES */
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .service-box {
            background: #121826;
            padding: 25px;
            border-radius: 8px;
            border-left: 4px solid #007bff;
            transition: 0.3s;
        }

        .service-box:hover {
            transform: translateY(-5px);
        }

        /* PROJECT IMAGE SECTION */
        .project {
            text-align: center;
        }

        .project img {
            width: 100%;
            max-width: 700px;
            border-radius: 10px;
            margin-top: 20px;
            box-shadow: 0 0 25px rgba(0,123,255,0.3);
        }

        /* CONTACT */
        .contact-box {
            background: #05070d;
            padding: 50px 20px;
            text-align: center;
            border-top: 3px solid #007bff;
        }

        .contact-box p {
            margin: 10px 0;
        }

        footer {
            text-align: center;
            padding: 15px;
            font-size: 13px;
            background: #000;
            color: #777;
        }

    </style>
</head>

<body>

<nav>
    <h3>Delta Flex Construction</h3>
    <div>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<header>
    <h1>Delta Flex Construction</h1>
    <p><strong>Reliable. Professional. We Get It Done.</strong></p>
    <a href="#contact" class="btn">Request a Quote</a>
</header>

<section id="about" class="about">
    <h2>About Us</h2>
    <p>
        Delta Flex Construction is a hardworking, self-driven construction company
        committed to delivering reliable and high-quality workmanship.
        Based in Gauteng and operating across South Africa,
        we take pride in getting the job done right — on time and on budget.
    </p>
    <p>
        Led by CEO Quintus Van Der Berg, we bring dedication,
        skill, and professional service to every project.
    </p>
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="services">
        <div class="service-box">
            <strong>Electrical Installations & Repairs</strong>
        </div>
        <div class="service-box">
            <strong>Solar Installations</strong>
        </div>
        <div class="service-box">
            <strong>COC (Certificate of Compliance)</strong>
        </div>
        <div class="service-box">
            <strong>General Construction & Building</strong>
        </div>
    </div>
</section>

<section class="project">
    <h2>Recent Solar Installation</h2>
    <p>Professional Sunsynk inverter and Hubble Lithium battery installation.</p>
    <img src="solar-install.jpg" alt="Solar Installation Project">
</section>

<section id="contact" class="contact-box">
    <h2>Contact Us</h2>
    <p><strong>CEO:</strong> Quintus Van Der Berg</p>
    <p><strong>Phone:</strong> 072 213 0137</p>
    <p>Call today for a professional quote.</p>
</section>

<footer>
    © 2026 Delta Flex Construction | All Rights Reserved
</footer>

</body>
</html>
