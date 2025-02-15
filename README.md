<!DOCTYPE html>
<html lang="en">
<head> 
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>

    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    
    <style>
        h1 {
            margin-top: 50px;
            margin-bottom: 50px;
            margin-left: 50px;
            margin-right: 20px;
        }

        nav {
            background-color: #BDB2FF;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none; 
            margin-right: 10px;
            font-size: 16px;
        }
    </style>
</head>
<body style="background-color: lightblue;">
    <header>
        <h3 class="pacifico-regular">erikajazly</h3>
        <nav>
            <a href="/">Home</a>
            <a href="/about.html">About Me</a>
            <a href="/grades.html">Grades</a>
            <a href="/contact.html">Contact</a>
            <a href="/facebook.html">Facebook</a>
            <a href="/Instagram.html">Instagram</a>
        </nav>
    </header>
    <hr>

    <center><h1 class="pacifico-regular">My Portfolio</h1></center>

    <div class="container">
        <img src="photoPortfolio.jpg" alt="My Portfolio Image">
        <article>
            <p>I'm passionate about learning and making the process fun and memorable.
            My free time is spent with loved ones, creating meaningful moments.
            I enjoy eating, organizing, cleaning, roller skating, and taking strolls.
            Currently, my main focus is graduating college to build a stable future and
            provide for my family, especially my youngest brother.
            I'm driven to support him financially and emotionally throughout his studies.</p>
        </article>
    </div>

    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Prelims</th>
                <th>Midterms</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Erika</td>
                <td>100</td>
                <td>200</td>
            </tr>
            <tr>
                <td>Jazly</td>
                <td>100</td>
                <td>95</td>
            </tr>
            <tr>
                <td>Ikang</td>
                <td>50</td>
                <td>70</td>
            </tr>
        </tbody>
    </table>

    <ul>
        <li>Address: Magsaysay, Tagudin, Illocos Sur</li>
            <a target="_blank" href="https://www.google.com/maps/place/WCMV%2BXC9%2C+Tagudin%2C+Ilocos+Sur%2C+Philippines/@17.1061992,120.3323271,17z/data=!3m1!4b1!4m5!3m4!1s0x33904447e9260843:0x24533006f59a411!8m2!3d17.1061992!4d120.3345158"> Google Maps</a>
        
    </ul>

    <form>
        <div>
            <label for="fname">First Name</label>
            <input type="text" id="fname" />
        </div>
        <div>
            <label for="age">Age</label>
            <input type="number" id="age" />
        </div>
        <button>Submit</button>
    </form>

    <footer>
        <hr />
        © 2025 erikajazly.Co. All rights reserved.
        <nav>
            <a href="/terms">Terms &amp; Conditions</a>
        </nav>
    </footer>
</body>
</html> 
