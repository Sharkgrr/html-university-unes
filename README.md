# html-university-unes

HTML Principles Learning Project

Project Overview

This project serves as an introduction to the fundamental principles of HTML, focusing on the creation of a basic web page for UNES (Universidad Nacional Experimental de la Seguridad). The structure of the project follows best practices in HTML, helping learners understand core concepts such as document structure, elements, and the use of tables, images, and links.

Key Features
DOCTYPE Declaration: The <!doctype html> at the beginning of the document ensures the browser interprets the page as an HTML5 document.
Head Section: Includes the <meta charset="utf-8"> tag to set the character encoding, ensuring the web page displays characters correctly.
Body Structure: Organizes content using tables, links, and headings.

HTML Concepts Covered

1. Basic Structure of an HTML Document
The HTML document starts with a <!doctype html> declaration, followed by the <html>, <head>, and <body> tags, which define the structure of the webpage:

<!doctype html>
<html>
<head>
   <title>UNES</title>
   <meta charset="utf-8">
</head>
<body>
   <!-- Content goes here -->
</body>
</html>


2. Incorporating Images
Images are added using the <img> tag with the src attribute pointing to the image location, such as the university logo:

<img src="image/logo.png">

3. Tables for Layout
This project uses an HTML <table> to organize content. Although modern websites favor CSS for layout, tables are useful for understanding basic structural organization:

<table border="0" width="900" align="center">
   <tr>
      <td height="89"><img src="image/logo.png"></td>
      <td align="center">
         <a href="">Menu</a> | 
         <a href="about-us.html">About Us</a> | 
         <a href="contact.html">Contact</a>
      </td>
   </tr>
   <!-- More rows and cells here -->
</table>

4. Navigation Links
Links are created using the <a> tag with the href attribute pointing to the destination URL. This is important for navigation between pages:

<a href="about-us.html">About Us</a>

5. Text Formatting and Headings
Text is organized into paragraphs (<p>) and headings (<h2>), with inline formatting using <strong> for bold and <i> for italic text:

<h2>About university</h2>
<p>UNES is a public university specializing in security sciences...</p>

Learning Goals

This project aims to help you:

Understand the structure of an HTML document.
Learn how to include images and create basic navigation using links.
Organize content using tables (for learning purposes) and headings.
Format text with semantic HTML tags like <strong> and <p>.
Begin incorporating external resources like images and links to build a simple, structured webpage.

How to Run This Project

Download the HTML file and images.
Open the index.html file in any web browser to see the rendered webpage.
Modify the HTML code to experiment with different layouts, elements, and content.
Contact

For further information or assistance with this project, feel free to reach out via:
Email: raphaelaoliveira79@gmail.com

This README provides guidance for understanding and learning HTML principles based on the UNES webpage project.
