<!DOCTYPE html>
<html lang="en">
<head>
    <title>My Website</title>
</head>
<style>
    /* Navigation Menu */
nav {
    background-color: #333;
    color: #fff;
    padding: 10px;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

nav li {
    display: inline-block;
    margin-right: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

/* About Us Section */
#about {
    background-color:lightgray
}
</style>
<body>
    <!-- Navigation Menu -->
    <nav>
        <ul>
            <li><a href="#about">About us</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- About Us Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>We are a team of professionals in creating and planning events that are guaranteed to be amazing and memorable!</p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <div class="skill">
            <h3>Organization skill</h3>
            <p>We are experts in keeping track of all the deatils in the event from scheduling and budgeting to managing vendors and staff.</p>
        </div>
        <div class="skill">
            <h3>Problem-solving skill</h3>
            <p> Events can be unpredictable, and event planners need to be able to handle unexpected challenges that arise by being able to think creatively and quickly to resolve issues.</p>
        </div>
        <div class="skill">
            <h3>Communication skill</h3>
            <p>We have excellent communication skills to interact with clients, vendors, and staff. Which enable us to clearly articulate our vision for the event and listen to the needs and concerns of others.</p>
        </div>
        <div class="skill">
            <h3>Attention to detail</h3>
            <p>We pay close attention to even the smallest details to ensure that the event runs smoothly and thus are able to catch errors and fix them before they become significant problems.</p>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio-item">
            <img src="https://images.squarespace-cdn.com/content/v1/585ac0bb414fb5eed215d4e3/1578421536500-8T3HYSPYRWJ7L2WYXG2P/Modern+Catholic+Ceremony+Ideas?format=750w" alt="Project 1">
        </div>
        <div class="portfolio-item">
            <img src="https://images.squarespace-cdn.com/content/v1/585ac0bb414fb5eed215d4e3/1551391495485-KYVY8OY141P0MWEX5AM6/Luxury+Boasthouse+wedding+by+best+wedding+planners+Boston+and+NYC?format=750w" alt="Project 2">
        </div>
        <div class="portfolio-item">
            <img src="https://images.squarespace-cdn.com/content/v1/585ac0bb414fb5eed215d4e3/ab7bdb9d-1011-4e7f-875f-6aed05fb7139/51902105678_6d49908d70_c.jpg?format=750w" alt="Project 3">
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <h3>Jackson Tenga</h3>
        <address>
             Lublin, Poland
        </address>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="subject">Subject:</label>
            <input type="text" id="subject" name="subject" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send</button>
        </form>
    </section>
</body>
</html>
