<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>D-Gen Digital Marketing Agency</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            color: #e0e0e0;
            background: linear-gradient(135deg, #000000, #434343);
            overflow-x: hidden; /* Ensure horizontal overflow is hidden, but allow vertical scrolling */
            position: relative;
        }

        header {
            background: url('https://source.unsplash.com/1600x900/?business,technology') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding: 100px 20px;
        }

        header h1 {
            font-size: 3em;
            font-family: 'Courier New', Courier, monospace;
            text-shadow: 2px 2px 4px #000000;
        }

        header p {
            font-size: 1.5em;
            margin-top: 10px;
        }

        section {
            padding: 40px 20px;
            text-align: center;
        }

        #hero {
            background: url('https://source.unsplash.com/1600x900/?technology,team') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding: 100px 20px;
            margin-bottom: 20px;
        }

        #hero h2 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        #hero p {
            font-size: 1.5em;
            margin-top: 10px;
        }

        #cta-button {
            background-color: #1e90ff;
            color: #fff;
            padding: 15px 30px;
            font-size: 1.2em;
            border: none;
            border-radius: 5px;
            text-transform: uppercase;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            margin-top: 20px;
        }

        #cta-button:hover {
            background-color: #4682b4;
        }

        #services, #testimonials, #contact {
            background: url('https://source.unsplash.com/1600x900/?digital,marketing') no-repeat center center/cover;
            margin: 20px 0;
            border-radius: 8px;
            padding: 20px;
            color: #fff;
        }

        #services h2, #testimonials h2, #contact h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        #services ul {
            list-style-type: none;
            padding: 0;
            font-size: 1.2em;
        }

        #services li {
            margin: 10px 0;
        }

        #testimonials {
            background: rgba(0, 0, 0, 0.5);
        }

        #testimonials blockquote {
            font-size: 1.2em;
            margin: 20px auto;
            padding: 20px;
            border-left: 4px solid #1e90ff;
            max-width: 800px;
        }

        a {
            color: #1e90ff;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
        }

        footer p {
            font-size: 1em;
        }

        /* 3D effect */
        @keyframes move {
            from {
                transform: rotateX(0deg) rotateY(0deg);
            }
            to {
                transform: rotateX(360deg) rotateY(360deg);
            }
        }

        .moving-object {
            position: absolute;
            width: 100px;
            height: 100px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            animation: move 10s infinite linear;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }

            header p {
                font-size: 1.2em;
            }

            #services h2, #testimonials h2, #contact h2 {
                font-size: 2em;
            }

            #services ul {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>D-Gen Digital Marketing Agency</h1>
        <p>Welcome to D-Gen, where we deliver cutting-edge digital solutions tailored to your needs.</p>
    </header>

    <section id="hero">
        <h2>Your Digital Success Starts Here</h2>
        <p>Explore our services and see how we can help your business grow.</p>
        <a href="#services" id="cta-button">Explore Services</a>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Social Media Marketing</li>
            <li>Content Creation</li>
            <li>SEO</li>
            <li>Production</li>
            <li>Business Consulting</li>
            <li>Software Development</li>
            <li>Website Development</li>
            <li>And More...</li>
        </ul>
    </section>

    <section id="testimonials">
        <h2>What Our Clients Say</h2>
        <blockquote>
            <p>"D-Gen's services transformed our online presence. The team is incredibly professional and results-driven!"</p>
            <cite>- Alex Smith, CEO of TechCorp</cite>
        </blockquote>
        <blockquote>
            <p>"We saw a significant increase in engagement and leads after working with D-Gen. Highly recommend!"</p>
            <cite>- Sarah Lee, Marketing Manager at Web Solutions</cite>
        </blockquote>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:itsdgen@gmail.com">itsdgen@gmail.com</a></p>
        <p>Mobile (Sri Lanka): +94740234993</p>
        <p>Mobile (UK): +44793015997
