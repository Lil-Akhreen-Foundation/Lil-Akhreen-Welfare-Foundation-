# Lil-Akhreen-Welfare-Foundation-
Perfect! I can make a fully functional website for the Lil Akhreen Welfare Foundation. I’ll create all the files and structure so you can run it locally or host it online. Here’s a ready-to-use version with HTML, CSS, and basic contact form functionality:


---

1. Create index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lil Akhreen Welfare Foundation</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Lil Akhreen Welfare Foundation</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#team">Team</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>The Lil Akhreen Welfare Foundation is dedicated to improving the lives of those in need. We focus on community development, education, and welfare projects. Our mission is to bring positive change and support to every corner of society.</p>
    </section>

    <section id="team">
        <h2>Our Team</h2>
        <div class="team-container">
            <div class="team-member">
                <h3>Sabahudin Khan</h3>
                <p>Chairman</p>
            </div>
            <div class="team-member">
                <h3>Mubashir Aziz</h3>
                <p>President</p>
            </div>
            <div class="team-member">
                <h3>Faizan Wani</h3>
                <p>Senior Vice President</p>
            </div>
            <div class="team-member">
                <h3>Syeda Konain Zehra</h3>
                <p>General Secretary</p>
            </div>
            <div class="team-member">
                <h3>Aiman Younis</h3>
                <p>Finance Secretary</p>
            </div>
            <div class="team-member">
                <h3>Kashmala Rajpoot</h3>
                <p>Record Head</p>
            </div>
            <div class="team-member">
                <h3>Sajid Iqbal</h3>
                <p>Verification Head</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <div class="contact-form">
            <form action="mailto:akhreenwelfare@example.com" method="post" enctype="text/plain">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
            <p style="text-align:center; margin-top:10px;">Or call us at: <strong>0316-9480488</strong></p>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Lil Akhreen Welfare Foundation. All Rights Reserved.</p>
    </footer>
</body>
</html>


---

2. Create style.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    color: #333;
}

header {
    background-color: #00539C;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

nav {
    margin: 10px 0;
}

nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

section {
    padding: 40px 20px;
    max-width: 1000px;
    margin: auto;
}

h2 {
    color: #00539C;
    text-align: center;
}

.team-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    margin-top: 20px;
}

.team-member {
    background-color: white;
    border-radius: 10px;
    padding: 20px;
    width: 250px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    text-align: center;
}

.team-member h3 {
    margin: 10px 0 5px 0;
}

.team-member p {
    margin: 0;
    color: #555;
}

.contact-form {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    max-width: 500px;
    margin: auto;
}

.contact-form input, .contact-form textarea {
    width: 100%;
    padding: 10px;
    margin: 8px 0;
    border-radius: 5px;
    border: 1px solid #ccc;
    font-size: 1em;
}

.contact-form button {
    background-color: #00539C;
    color: white;
    border: none;
    padding: 12px 20px;
    font-size: 1em;
    border-radius: 5px;
    cursor: pointer;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #e1e1e1;
}


---

How to Use This Website

1. Save the first code as index.html.


2. Save the second code as style.css in the same folder.


3. Open index.html in any browser.


4. The Contact form uses mailto: so it will open your email client to send messages. You can later upgrade it to a real backend form.




---

I can also make it fully functional online with a real working contact form and a donation section if you want it to be production-ready.

Do you want me to do that next?
