# Codesoft-internship-task
// task 1 of internship.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LandScape page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Mahima Verma LandScape page</h1>
        <nav>
            <ul>
                <li> <a href="#">Home</a></li>
                <li><a href="#">features</a></li>
                <li><a href="#">contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="Hero">
        <h2>Welcome to my amazing LandScape product</h2>
        <p>
            Here you can discover an exciting and amazing features that 
            might be helpful for your coding journey.
        </p>
        <a href="#contact" class="button">Get Started</a>
    </section>

    <section id="features">
        <h2>Features</h2>
        <div class="featutes">
            <h3>Features one</h3>
            <p>Find details about feature one.</p>
        </div>
        <div class="features">
            <h3>Features two</h3>
            <p>Find Details about feaure two</p>
        </div>
    </section>

    <footer>
        <p> 
            $copy; 2024 Your company. All rights reserved.
           <br> Owner- mahima Verma<br>
           Web Development Internship (level-1 :- task 1)
        </p>
    </footer>
    
</body>
</html>

// CSS PART

*{
    margin: 0;
    padding: 0;
}
body{
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
header{
    background-color: #333;
    color: #fff;
    padding: 65px;
    display: flex;
    justify-content: space-between;
    text-align: center;
}
nav ul{
    list-style: none;
    display: flex;
    padding: 0;
}
nav ul li{
    display: inline;
    margin: 0 10px;
    margin-right: 25px;
}
nav ul li a{
    text-decoration: none;
    color: #fff;
}

.hero{
    text-align: center;
    padding: 120px 0;
    color: #fff;
}
.hero h2{
    font-size: 38px;
    margin-bottom: 25px;
}
.hero p{
    font-size: 18px;
    margin-bottom: 30px;
}
.btn{
    display: inline-block;
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}
.btn:hover{
    background-color: #0056b3;
}
section{
    padding: 20px;
    margin: 0 auto;
    max-width: 1200px;
}
.feature{
    margin-bottom: 20px;
}

footer{
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}
