[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TUGW0SrP)
# Welcome to the HTML5 Basics Assignment repository! 

This assignment is designed to help you build foundational knowledge of HTML5, understand its structure, and practice creating web page content using semantic elements.

## Learning Objectives

By completing this assignment, you will:

  Understand the structure and purpose of HTML5 in web development.
  Learn to create basic web page content using core HTML5 elements.
  Explore semantic HTML elements and their benefits for readability and SEO.
  Gain a basic understanding of accessibility and SEO best practices in HTML.
  
## Assignment Content
  1. HTML5 Basics
Learn the structure of an HTML document (e.g., <!DOCTYPE html>, <html>, <head>, <body>).
Explore core elements such as headings, paragraphs, lists, links, and images.
  2. Semantic HTML
Introduction to semantic tags like <header>, <footer>, <nav>, <section>, and <article>.
Learn how semantic elements improve content readability and support SEO.
  3. Accessibility and SEO Basics
Understand the importance of accessible HTML and SEO-friendly practices.
Use attributes like alt, title, and semantic structures to improve usability.

## Activities

Creating a Simple Webpage: Design a basic webpage that includes text, images, and links.
Use common HTML tags like h1, p, a, img, and ul or ol.
Structure a webpage with semantic tags such as header, footer, nav, section, and article.
Ensure the content is well-organized for readability and SEO.


assignment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A simple webpage with images, text, and links.">
    <title>Simple Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            text-align: center;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            margin: 0 10px;
        }
        nav a:hover {
            background-color: #575757;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .content-image {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Simple Webpage</h1>
        <p>Explore text, images, and links!</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <article>
            <h2>About This Page</h2>
            <p>This is a simple webpage created to showcase basic HTML tags and structure. It includes text, images, and links, making it a useful starting point for web development.</p>
        </article>
    </section>

    <section id="gallery">
        <article>
            <h2>Image Gallery</h2>
            <p>Here are some beautiful images that I’ve added to the gallery section:</p>
            <img src="https://via.placeholder.com/400" alt="Placeholder Image 1" class="content-image">
            <img src="https://via.placeholder.com/400" alt="Placeholder Image 2" class="content-image">
            <img src="https://via.placeholder.com/400" alt="Placeholder Image 3" class="content-image">
        </article>
    </section>

    <section id="contact">
        <article>
            <h2>Contact Me</h2>
            <p>If you have any questions, feel free to <a href="mailto:example@email.com">email me</a>!</p>
        </article>
    </section>

    <footer>
        <p>&copy; 2024 My Simple Webpage. All Rights Reserved.</p>
    </footer>
</body>
</html>


