<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">
<link rel="stylesheet" href="./css/style.css">
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>History of Hip Hop</title>

    <!-- Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- My custom CSS -->
    <link rel="stylesheet" href="./css/style.css">
</head>

<body>

    <header class="site-header">
        <div class="container py-4">
            <h1 class="text-center">History of Hip Hop</h1>

            <nav class="text-center mt-3" aria-label="Main navigation">
                <a class="btn btn-outline-light mx-1" href="index.html">Home</a>
                <a class="btn btn-outline-light mx-1" href="page2.html">
                    Hip Hop Through the Years
                </a>
            </nav>
        </div>
    </header>

    <main class="container py-5">

        <!-- Beginning of Hip Hop -->
        <section id="history" class="card shadow-sm mb-4">
            <div class="card-body p-4">

                <h2 class="card-title">The Beginning of Hip Hop</h2>

                <p class="card-text">
                    Hip hop began in the Bronx in New York City during the 1970s.
                    It gave people a way to express themselves through music,
                    dancing, and art.
                </p>

                <p class="card-text">
                    Early hip hop included DJs, MCs, breakdancers, and graffiti
                    artists. These different forms of expression helped create
                    the culture we know as hip hop today.
                </p>

                <img
                    class="img-fluid rounded hip-hop-image"
                    src="images/hiphop.jpg"
                    alt="Musician performing on stage in front of an audience"
                    width="500"
                >

            </div>
        </section>

        <!-- Four Elements -->
        <section class="card shadow-sm mb-4">
            <div class="card-body p-4">

                <h2 class="card-title">The Four Elements of Hip Hop</h2>

                <ul class="list-group list-group-flush mt-3">
                    <li class="list-group-item">DJing</li>
                    <li class="list-group-item">MCing</li>
                    <li class="list-group-item">Breakdancing</li>
                    <li class="list-group-item">Graffiti Art</li>
                </ul>

            </div>
        </section>

        <!-- Growth of Hip Hop -->
        <section class="card shadow-sm mb-4">
            <div class="card-body p-4">

                <h2 class="card-title">The Growth of Hip Hop</h2>

                <ol class="mt-3">
                    <li>Hip hop began in the Bronx during the 1970s.</li>
                    <li>Hip hop became more popular during the 1980s.</li>
                    <li>Rap became a major part of popular music during the 1990s.</li>
                    <li>Hip hop continues to influence music and culture today.</li>
                </ol>

            </div>
        </section>

    </main>

    <footer class="site-footer">
        <div class="container text-center py-4">

            <p class="mb-3">
                Learn more about how hip hop developed over time.
            </p>

            <a class="btn btn-light" href="page2.html">
                Read About Hip Hop Through the Years
            </a>

        </div>
    </footer>
    </body>
</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Hip Hop Through the Years</title>

    <!-- Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- My custom CSS -->
    <link rel="stylesheet" href="./css/style.css">
</head>

<body>

    <header class="site-header">
        <div class="container py-4">

            <h1 class="text-center">Hip Hop Through the Years</h1>

            <nav class="text-center mt-3" aria-label="Main navigation">
                <a class="btn btn-outline-light mx-1" href="index.html">
                    Home
                </a>

                <a class="btn btn-outline-light mx-1" href="page2.html">
                    Hip Hop Through the Years
                </a>
            </nav>

        </div>
    </header>

    <main class="container py-5">

        <!-- Bootstrap grid -->
        <div class="row g-4">

            <!-- Hip Hop Through the Years -->
            <section id="history" class="col-12 col-md-6">

                <div class="card shadow-sm h-100">
                    <div class="card-body p-4">

                        <h2 class="card-title">
                            Hip Hop Through the Years
                        </h2>

                        <p class="card-text">
                            Hip hop continued to change as new artists and
                            styles became popular. Different regions of the
                            United States developed their own sounds and
                            influenced hip hop.
                        </p>

                        <p class="card-text">
                            During the 1990s and 2000s, hip hop became an
                            important part of mainstream music. Artists used
                            rap to tell stories, discuss their experiences,
                            and represent their communities.
                        </p>

                    </div>
                </div>

            </section>

            <!-- Hip Hop Today -->
            <section id="modern" class="col-12 col-md-6">

                <div class="card shadow-sm h-100">
                    <div class="card-body p-4">

                        <h2 class="card-title">
                            Hip Hop Today
                        </h2>

                        <p class="card-text">
                            Today, hip hop is one of the most popular forms
                            of music around the world. Modern artists continue
                            to combine rap with different sounds and styles.
                        </p>

                        <p class="card-text">
                            Hip hop has also influenced fashion, language,
                            dance, and other areas of popular culture.
                        </p>

                        <img
                            class="img-fluid rounded hip-hop-image mt-3"
                            src="images/hiphop.jpg"
                            alt="Musician performing on stage in front of an audience"
                            width="500"
                        >

                    </div>
                </div>

            </section>

        </div>

    </main>

    <footer class="site-footer">
        <div class="container text-center py-4">

            <p class="mb-3">
                Explore the history and cultural influence of hip hop.
            </p>

            <a class="btn btn-light" href="index.html">
                Return to the Hip Hop History Homepage
            </a>
/* Custom styles that work alongside Bootstrap */

body {
    background-color: #f2f2f2;
    color: #222222;
    font-family: Arial, sans-serif;
}

/* Custom header design */
.site-header {
    background-color: #222222;
    color: #ffffff;
}

/* Custom heading */
.site-header h1 {
    font-size: 36px;
    font-weight: bold;
}

/* Custom section borders */
#history {
    border-left: 5px solid #222222;
}

#modern {
    border-left: 5px solid #555555;
}

/* Custom image styling */
.hip-hop-image {
    display: block;
    margin-left: auto;
    margin-right: auto;
}

/* Custom footer */
.site-footer {
    background-color: #222222;
    color: #ffffff;
}

/* Keyboard accessibility */
a:focus {
    outline: 3px solid #ffcc00;
    outline-offset: 3px;
}

/* Small-screen adjustments */
@media (max-width: 768px) {

    .site-header h1 {
        font-size: 28px;
    }

    main {
        padding-top: 30px;
        padding-bottom: 30px;
    }

    .hip-hop-image {
        width: 100%;
        height: auto;
    }
}.flex-container {
    display: flex;
    gap: 20px;
}
<div class="row g-4">
<section class="col-12 col-md-6">
git add .
git commit -m "Add Bootstrap to HTML pages"
git add .
git commit -m "Add Bootstrap grid and components"
git add .
git commit -m "Refactor custom CSS"
