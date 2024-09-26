
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    Научно-производственная фирма "Магнетик Ферролаб"
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="container">
            <a href="#"><img src="logo.png" alt="Logo"></a>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <!-- Main Content -->
    <main class="content">
        <section class="hero">
            <div class="container">
                <h1>Welcome to Our Site</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non quae accusantium nulla dicta minima repellendus cumque dolore vel! Dolores consequuntur incidunt itaque officia labore earum dignissimos culpa sequi magni distinctio.</p>
                <button type="button">Read More</button>
            </div>
        </section>

        <!-- Features Section -->
        <section class="features">
            <div class="container">
                <h2>Our Awesome Features</h2>
                <div class="feature-item">
                    <i class="fas fa-cogs"></i>
                    <h3>Feature Title</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem voluptatem debitis commodi excepturi optio temporibus enim facilis cupiditate eos obcaecati numquam? Ipsam autem aliquam necessitatibus quod vero pariatur harum illo.</p>
                </div>
                <div class="feature-item">
                    <i class="far fa-gem"></i>
                    <h3>Feature Title</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem voluptatem debitis commodi excepturi optio temporibus enim facilis cupiditate eos obcaecati numquam? Ipsam autem aliquam necessitatibus quod vero pariatur harum illo.</p>
                </div>
                <div class="feature-item">
                    <i class="fas fa-chart-line"></i>
                    <h3>Feature Title</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem voluptatem debitis commodi excepturi optio temporibus enim facilis cupiditate eos obcaecati numquam? Ipsam autem aliquam necessitatibus quod vero pariatur harum illo.</p>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>© Copyright 2023</p>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </footer>

    <!-- Import Font Awesome Icons -->
    <script src="https://kit.fontawesome.com/6b497635d2.js" crossorigin="anonymous"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
}

.header {
    background-color: #333;
    color: white;
    padding: 20px;
}

.header a {
    color: white;
    text-decoration: none;
}

.header nav ul {
    display: flex;
    list-style: none;
    justify-content: center;
    align-items: center;
    gap: 20px;
}

.header nav li a {
    display: block;
    padding: 10px;
}

.content {
    max-width: 1200px;
    margin: auto;
    padding: 20px;
}

.hero {
    text-align: center;
    padding: 20px;
}

.hero h1 {
    font-size: 3rem;
}

.hero p {
    margin-top: 10px;
}

.features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
}

.feature-item {
    display: flex;
    align-items: center;
    gap: 20px;
}

.feature-item i {
    font-size: 3rem;
}

.feature-item h3 {
    margin: 0;
}

.feature-item p {
    margin-top: 10px;
}

.footer {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

.footer p {
    margin: 0;
}

.footer nav ul {
    display: flex;
    list-style: none;
    justify-content: center;
    align-items: center;
    gap: 20px;
}

.footer nav li a {
    color: white;
    text-decoration: none;
}
