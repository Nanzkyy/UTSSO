<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <header>
        <nav>
            <div class="logo">UTS SO KELOMPOK 6</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Welcome to MyWebsite</h1>
        <p>Your success is our priority</p>
        <a href="#about" class="cta">UTS SISTEM OPERASI</a>
    </section>

    <section id="about" class="about">
             <h2>SELAMAT DATANG</h2>
        <p>Website ini di buat untuk UTS SO Ya Ges Yak</p>
    </section>

    <section id="services" class="services">
        <h2>Nama Kelompok</h2>
        <div class="service">
            <h3>Ananda Tyrta Pratama</h3>
            <p>NIM = 230401260.</p>
        </div>
        <div class="service">
            <h3>Azzahri Ahmelin</h3>
            <p>NIM = 230401231.</p>
        </div>
        <div class="service">
            <h3>Harya Jaya Kusuma</h3>
            <p>NIM = 230401226.</p>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Hubungi</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            
            <label for="message">Message:</label>
            <textarea id="message" name="message"></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; Anjay Mabar.</p>
    </footer>
</body>
</html>
