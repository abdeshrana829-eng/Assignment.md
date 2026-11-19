Complete code — index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Landing Page</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f5f7ff;
            color: #222;
        }

        /* Header */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 8%;
            background: white;
        }

        .logo {
            font-size: 26px;
            font-weight: bold;
            color: #5b4bdb;
        }

        nav {
            display: flex;
            gap: 30px;
        }

        nav a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
        }

        nav a:hover {
            color: #5b4bdb;
        }

        .header-btn {
            background: #5b4bdb;
            color: white;
            padding: 12px 22px;
            border-radius: 6px;
            text-decoration: none;
        }

        /* Hero Section */
        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 80px 8%;
            gap: 40px;
            min-height: 550px;
        }

        .hero-content {
            flex: 1;
        }

        .hero-content h1 {
            font-size: 48px;
            line-height: 1.2;
            margin-bottom: 20px;
            color: #222;
        }

        .hero-content h1 span {
            color: #5b4bdb;
        }

        .hero-content p {
            font-size: 17px;
            line-height: 1.7;
            color: #666;
            margin-bottom: 30px;
        }

        .hero-btn {
            display: inline-block;
            background: #5b4bdb;
            color: white;
            padding: 14px 28px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
        }

        .hero-btn:hover,
        .header-btn:hover {
            background: #4032b5;
        }

        /* Hero Image */
        .hero-image {
            flex: 1;
            display: flex;
            justify-content: center;
        }

        .hero-image img {
            width: 100%;
            max-width: 500px;
            border-radius: 15px;
        }

        /* Footer */
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 22px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header {
                flex-wrap: wrap;
                gap: 20px;
            }

            nav {
                order: 3;
                width: 100%;
                justify-content: center;
                flex-wrap: wrap;
                gap: 18px;
            }

            .hero {
                flex-direction: column;
                text-align: center;
                padding: 50px 6%;
            }

            .hero-content h1 {
                font-size: 36px;
            }

            .hero-image img {
                max-width: 100%;
            }
        }

        @media (max-width: 480px) {
            header {
                padding: 18px 5%;
            }

            .logo {
                font-size: 22px;
            }

            .header-btn {
                padding: 10px 14px;
                font-size: 13px;
            }

            .hero-content h1 {
                font-size: 30px;
            }

            nav {
                gap: 14px;
                font-size: 14px;
            }
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header>
        <div class="logo">WebFlow.</div>

        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Services</a>
            <a href="#">Contact</a>
        </nav>

        <a href="#" class="header-btn">Get Started</a>
    </header>

    <!-- Hero Section -->
    <section class="hero">

        <div class="hero-content">
            <h1>
                Build Your Future
                <span>With Us</span>
            </h1>

            <p>
                Discover innovative digital solutions to grow your
                business. We help you create amazing experiences
                with modern technology and creative design.
            </p>

            <a href="#" class="hero-btn">Explore More</a>
        </div>

        <div class="hero-image">
            <img
                src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?w=800"
                alt="Modern workspace with computer"
            >
        </div>

    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 WebFlow. All Rights Reserved.</p>
    </footer>

</body>
</html>
Expected output
pourtion: web design, product page, hero header, illustration by Konolee for FRAGMENTS on Dribbble
 
Assignment requirements covered
Requirement

Status

Logo and navigation links

Done

Header CTA button

Done

Hero heading and paragraph

Done

Hero button

Done

Image / illustration

Done

Flexbox side-by-side layout

Done

Proper alignment

Done

Footer styling

Done

Responsive media queries

Done

How to run the assignment
Create a folder named Assignment-7.4.

Create a file named index.html.

Paste the complete code into the file.

Save the file.

Open index.html in your browser.

Resize the browser to check desktop, tablet, and mobile layouts.

Note: This assignment uses HTML, CSS Flexbox, hover effects, and media queries. No JavaScript is required.


