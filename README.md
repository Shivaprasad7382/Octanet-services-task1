<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <h1>Welcome to My Landing Page</h1>
        <p>A simple landing page example</p>
    </header>

    <section class="main-content">
        <h2>About Us</h2>
        <p>This is a brief description of our company or product.</p>
        <a href="#contact" class="cta-button">Contact Us</a>
    </section>

    <section id="contact" class="contact-form">
        <h2>Contact Us</h2>
        <form action="submit.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 My Company</p>
    </footer>
</body>

</html>

//css
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

/* Reset default styles */
body,
html {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

/* Header styles */
header {
    background-color: #f8f8f8;
    text-align: center;
    padding: 40px 0;
}

header h1 {
    color: #333;
    font-size: 36px;
}

/* Main content styles */
.main-content {
    padding: 40px;
    text-align: center;
}

.main-content h2 {
    color: #333;
}

.cta-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

.cta-button:hover {
    background-color: #0056b3;
}

/* Contact form styles */
.contact-form {
    background-color: #f0f0f0;
    padding: 40px;
}

.contact-form h2 {
    color: #333;
    text-align: center;
}

.contact-form form {
    max-width: 400px;
    margin: 0 auto;
}

.contact-form label {
    display: block;
    margin-bottom: 8px;
}

.contact-form input[type="text"],
.contact-form input[type="email"],
.contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border-radius: 5px;
    border: 1px solid #ddd;
}

.contact-form button {
    display: block;
    width: 100%;
    padding: 10px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.contact-form button:hover {
    background-color: #0056b3;
}
