<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>History of Hip Hop</title>
    <link rel="stylesheet" href="./css/style.css">
</head>

<body>

    <header>
        <h1>History of Hip Hop</h1>

        <nav aria-label="Main navigation">
            <a href="index.html">Home</a>
            <a href="page2.html">Hip Hop Through the Years</a>
        </nav>
    </header>

    <main>

        <section id="history" class="content-box">
            <h2>The Beginning of Hip Hop</h2>

            <p>
                Hip hop began in the Bronx in New York City during the 1970s.
                It gave people a way to express themselves through music,
                dancing, and art.
            </p>

            <p>
                Early hip hop included DJs, MCs, breakdancers, and graffiti
                artists. These different forms of expression helped create
                the culture we know as hip hop today.
            </p>

            <img
                class="hip-hop-image"
                src="images/hiphop.jpg"
                alt="Musician performing on stage in front of an audience"
                width="500"
            >
        </section>

        <section class="content-box">
            <h2>The Four Elements of Hip Hop</h2>

            <ul>
                <li>DJing</li>
                <li>MCing</li>
                <li>Breakdancing</li>
                <li>Graffiti Art</li>
            </ul>
        </section>

        <section class="content-box">
            <h2>The Growth of Hip Hop</h2>

            <ol>
                <li>Hip hop began in the Bronx during the 1970s.</li>
                <li>Hip hop became more popular during the 1980s.</li>
                <li>Rap became a major part of popular music during the 1990s.</li>
                <li>Hip hop continues to influence music and culture today.</li>
            </ol>
        </section>

    </main>
    <footer>
        <p>
            <a href="page2.html">Read about hip hop through the years</a>
        </p>
    </footer>

</body>
</html>
/* Main website styles */

body {
    background-color: #f2f2f2;
    color: #222222;
    font-family: Arial, sans-serif;
    font-size: 16px;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

h1 {
    text-align: center;
    font-size: 36px;
}

h2 {
    font-size: 26px;
}

p {
    text-align: left;
}

/* Header and navigation */
header {
    background-color: #222222;
    color: #ffffff;
    padding: 25px;
}

nav {
    text-align: center;
    margin-top: 15px;
}

nav a {
    color: #ffffff;
    margin: 0 10px;
    font-weight: bold;
}

/* Main content */
main {
    padding: 20px;
}

/* Content sections */
section {
    margin-bottom: 30px;
    padding: 20px;
}

.content-box {
    background-color: #ffffff;
    border: 1px solid #555555;
    padding: 20px;
    margin-bottom: 20px;
}

/* Images */
.hip-hop-image {
    display: block;
    margin: 20px auto;
    max-width: 100%;
    height: auto;
}

/* Flexbox layout */
.flex-container {
    display: flex;
    gap: 20px;
    justify-content: space-between;
}

.flex-item {
    flex: 1;
    background-color: #ffffff;
    padding: 20px;
    border: 1px solid #555555;
}

/* Unique sections */
#history {
    border-left: 5px solid #222222;
}

#modern {
    border-left: 5px solid #555555;
}

/* Footer */
footer {
    background-color: #222222;
    color: #ffffff;
    text-align: center;
    padding: 20px;
}

footer a {
    color: #ffffff;
    font-weight: bold;
}

/* Keyboard focus */
a:focus {
    outline: 3px solid #ffcc00;
    outline-offset: 3px;
}

/* Responsive design for smaller screens */
@media (max-width: 768px) {

    body {
        font-size: 15px;
    }

    h1 {
        font-size: 28px;
    }

    h2 {
        font-size: 22px;
    }

    main {
        padding: 10px;
    }

    section {
        padding: 15px;
    }

    /* Stack Flexbox sections on smaller screens */
    .flex-container {
        flex-direction: column;
        gap: 15px;
    }

    nav a {
        display: block;
        margin: 10px 0;
    }

    .hip-hop-image {
        width: 100%;
    }
}
git add .
git commit -m "Improve website accessibility"
git add .
git commit -m "Add responsive mobile layout"
git add .
git commit -m "Fix accessibility audit issues"
