# my_website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me and My Interests</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e6f2e6;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        header {
            background-color: #228B22;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin-top: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            color: #228B22;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            margin: 20px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid #228B22;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        footer {
            background-color: #228B22;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        img {
            width: 100%;
            max-width: 300px;
            height: auto;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Personl Page</h1>
    <p>Explore my world!</p>
</header>

<nav>
    <a href="#about">About Me</a>
    <a href="#gallery">Gallery</a>
    <a href="#video">Video</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>Hi,my name is Sara,  I'm an 18-year-old student studying Computer Science at ESI-SBA. I have a passion for technology and exploring new things.
        <br> here are some of the moments caprured by cameara that i would  like to sheare with you!  
    </p>
</section>

<section id="gallery">
    <h2>Gallery</h2>
    <p>Here are some of my favorite moments captured:</p>
    <table>
        <tr>
            <th>Image</th>
            <th>Description</th>
        </tr>
        <tr>
            <td><img src="c:\Users\sara2\Downloads\WhatsApp Image 2025-01-10 at 8.38.01 AM(1).jpeg" alt="Strawberry Drink"></td>
            <td bgcolor="pink" >A refreshing strawberry drink I enjoyed at a cozy cafe.</td>
        </tr>
        <tr>
            <td><img src="c:\Users\sara2\Downloads\WhatsApp Image 2025-01-10 at 8.37.56 AM.jpeg" alt="Evening Cityscape"></td>
            <td bgcolor="pink"> <italic>sky and clouds that look really fluffy .</italic></td>
        </tr>
    </table>
</section>

<section id="video">
    <h2>Video</h2>
    <p>Check out this cool video I found on YouTube:</p>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/i63STOtAL2g?si=UK-Y15TipG407Yg6" frameborder="0" allowfullscreen></iframe>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>If you'd like to get in touch, feel free to <a href="mailto:example@example.com">email me</a>.</p>
</section>



</body>
</html>
