# CSS-Basic-Project
###style.css###
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
}

header {
    background-color: #000;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.container {
    text-align: center;
    padding: 100px 20px;
}

button {
    padding: 10px 20px;
    margin: 10px;
    border: none;
    color: #fff;
    cursor: pointer;
}

button#login {
    background-color: #f00;
}

button#signup {
    background-color: #0f0;
}

.products, .people {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 50px 20px;
}

.product, .person {
    background-color: #333;
    padding: 20px;
    width: 200px;
    text-align: center;
    border-radius: 10px;
}

.contact-form, .contact-info {
    display: inline-block;
    vertical-align: top;
    width: 45%;
    margin: 2.5%;
    text-align: left;
}

input[type="text"], input[type="email"] {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    background-color: #333;
    border: none;
    color: #fff;
}

input[type="submit"] {
    width: 100%;
    padding: 10px;
    background-color: #f00;
    border: none;
    color: #fff;
    cursor: pointer;
}
###home.html###
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SN Technologies</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>SN Technologies</h1>
        <nav>
            <ul>
                <li><a href="home.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact_us.html">CONTACT</a></li>
            </ul>
        </nav>
    </header>
    <div class="container">
        <h2>Driving progress through precision engineering and boundless creativity.</h2>
        <button id="login">Log In</button>
        <button id="signup">Sign Up</button>
    </div>
</body>
</html>

###product.html###
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SN Technologies - Products</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>SN Technologies</h1>
        <nav>
            <ul>
                <li><a href="home.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact_us.html">CONTACT</a></li>
            </ul>
        </nav>
    </header>
    <div class="products">
        <div class="product">Web Development<img src="https://miro.medium.com/v2/resize:fit:12000/0*tQQ7SLPOJfxaG4ZY" width="200"><p>
            At SN Technologies, we excel in creating dynamic, user-friendly websites using the latest technologies. Our secure cloud servers enable clients to host their websites efficiently, ensuring seamless data management and enhanced security. Partner with us for innovative web solutions and reliable cloud hosting to stay competitive in the digital age.
        </p></div>
        <div class="product">Cloud Server Services<img src="images/cloud.jpg" width="200"><p>
            At SN Technologies, we provide secure cloud servers to help clients host their websites efficiently. Our state-of-the-art infrastructure ensures seamless data management, enhanced security, and cost-effective solutions. Partner with us to achieve greater operational efficiency and stay competitive in the digital age.
        </p></div>
        <div class="product">Cyber Security<img src="https://roche.scene7.com/is/image/RocheDiaProd/Cyber_Security_hero_Image_2880x1404?scl=1" width="200"><p>
            At SN Technologies, we create dynamic, user-friendly websites using the latest technologies. Our secure cloud servers enable clients to host their websites efficiently, ensuring seamless data management and enhanced security. Additionally, our robust cyber security solutions protect your digital assets from threats. Partner with us for innovative web solutions, reliable cloud hosting, and top-notch cyber security to stay competitive in the digital age.
        </p></div>
        
    </div>
</body>
</html>

###council.html###

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SN Technologies - People</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>SN Technologies</h1>
        <nav>
            <ul>
                <li><a href="home.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact_us.html">CONTACT</a></li>
            </ul>
        </nav>
    </header>
    <div class="people">
        <div class="person">
            <img src="https://m.media-amazon.com/images/M/MV5BYTNlOGZhYzgtMmE3OC00Y2NiLWFhNWQtNzg5MjRhNTJhZGVmXkEyXkFqcGdeQXVyNzg5MzIyOA@@._V1_.jpg"height="250" width="100%">
            <h3>Jeff Bezos</h3>
            <p>Founder & CEO</p>
            <p>Opetarions & Management</p>
        </div>
        <div class="person">
            <img src="https://cdn.tgdd.vn/Files/2022/02/20/1416452/steve-jobs-apple-iphone_1280x720-800-resize.jpg"height="250" width="100%">
            <h3>Steve Jobs</h3>
            <p>CEO, Co-Founder</p>
            <p>Lead Analyst</p>

        </div>
        <div class="person">
            <img src="https://media.cnn.com/api/v1/images/stellar/prod/190613182312-01-google-oklahoma.jpg?q=w_1110,c_fill"height="250" width="100%">
            <h3>Sundar Pichai</h3>
            <p>Director</p>
            <p>Technical Operations</p>
        </div>
        <div class="person">
            <img src="https://assets.editorial.aetnd.com/uploads/2015/02/list-disney-158937223-2.jpg""height="250" width="100%">
            <h3>Walt Disney</h3>
            <p>Asst. Director</p>
            <p>Technical Operations</p>
        </div>
        <div class="person">
            <img src="https://media.wired.com/photos/650399af65d83ff288720473/1:1/w_1285,h_1285,c_limit/If-Elon-Musk-Had-Been-a-Happy-Child,-Would-He-Still-Be-Launching-Rockets--Business-Redux-h_16082330.jpg" height="250" width="100%">
            <h3>Elon Musk</h3>
            <p>Director</p>
            <p>Sales & Customer Relations</p>
        </div>
    </div>
</body>
</html>
###contact_us.html###

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SN Technologies - Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>SN Technologies</h1>
        <nav>
            <ul>
                <li><a href="home.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact_us.html">CONTACT</a></li>
            </ul>
        </nav>
    </header>
    <div class="contact">
        <div class="contact-form">
            <h3>Contact Us</h3>
            <form>
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Your Email</label>
                <input type="email" id="email" name="email" required>
                <input type="submit" value="Submit">
            </form>
        </div>
        <div class="contact-info">
            <h3>Contact Information</h3>
            <p><strong>Address:</strong> 1234 Tech Lane, Innovation City, CodeState 56789</p>
            <p><strong>Phone:</strong> +1 234 567 890</p>
            <p><strong>Email:</strong> info@sntechnologies.com</p>
            <p><strong>Email:</strong> customercare@sntechnologies.com</p>
            
        </div>
    </div>
</body>
</html>


