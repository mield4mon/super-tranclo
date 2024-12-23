/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
}

/* Navbar */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    padding: 20px;
}

.navbar .logo h1 {
    color: #fff;
    font-family: 'Playfair Display', serif;
    font-size: 32px;
}

.navbar nav ul {
    list-style: none;
    display: flex;
}

.navbar nav ul li {
    margin-left: 30px;
}

.navbar nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

/* Hero Section */
.hero {
    background-image: url('https://via.placeholder.com/1600x800');
    background-size: cover;
    background-position: center;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #fff;
}

.hero h2 {
    font-size: 48px;
    font-family: 'Playfair Display', serif;
}

.hero p {
    font-size: 24px;
    margin: 20px 0;
}

.cta-button {
    background-color: #e74c3c;
    padding: 10px 30px;
    color: #fff;
    text-decoration: none;
    font-size: 20px;
    border-radius: 5px;
}

.cta-button:hover {
    background-color: #c0392b;
}

/* About Section */
.about {
    padding: 50px 0;
    background-color: #fff;
    text-align: center;
}

.about h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

.about p {
    font-size: 18px;
    max-width: 800px;
    margin: 0 auto;
}

/* Products Section */
.products {
    padding: 50px 0;
    background-color: #f4f4f4;
    text-align: center;
}

.products h2 {
    font-size: 36px;
    margin-bottom: 30px;
}

.product-gallery {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.product {
    width: 30%;
    margin: 10px 0;
}

.product img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

.product p {
    font-size: 18px;
    margin-top: 10px;
}

/* Contact Section */
.contact {
    padding: 50px 0;
    background-color: #fff;
    text-align: center;
}

.contact h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

.contact form {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 30px;
}

.contact label {
    font-size: 18px;
    margin-bottom: 10px;
    text-align: left;
    width: 80%;
}

.contact input, .contact textarea {
    width: 80%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 16px;
}

.contact .submit-button {
    background-color: #e74c3c;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.contact .submit-button:hover {
    background-color: #c0392b;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

footer p {
    font-size: 16px;
}
