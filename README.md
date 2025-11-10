<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=WDXL+Lubrifont+SC&display=swap" rel="stylesheet">
    <title>Experimental site</title>
    <style>
        body {
            background-color: #0f0800;
            font-family: 'WDXL Lubrifont SC', sans-serif;
            margin: 0;
        }

        .container {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100dvh;
            margin: 0;
            font-size: 2rem;
            text-align: center;
            text-shadow: 0 0 7px currentColor;
        }

        .h1{
            color: darkgoldenrod;
            border-bottom: 3px solid darkgoldenrod;
            padding-bottom: 5px;
        }

        p {
            color: gold;
        }

        .test {
            border: 3px solid gold;
            border-radius: 15px / 15px;
            padding-left: 3px;
            padding-right: 3px;
        }

        .strong {
            color: goldenrod;
        }

        a {
            color: palegoldenrod;
            margin: 3px;
        }

        .site-img {
            max-width: 8rem;
            margin: 0;
            color: palegoldenrod;
            border: 3px solid palegoldenrod;
            border-radius: 50% 10% 50% 10% / 10% 50% 10% 50%;
        }
    </style>
</head>
<body>
    <main class="container">
        <h1 class="h1">Test site</h1>
        <p class="p1">This is just my <span class="test">test site</span> for experimentation and demonstrating my capabilities. The site serves no purpose and will most likely never be launched.</p>
        <img src="https://avatarzo.ru/wp-content/uploads/seryj-gus.jpg" alt="A goose lived here 🫣" class="site-img">
        <p class="p2">This doesn't stop the site from being improved, but it still <strong class="strong">won't</strong> be launched. Perhaps on GitHub, for testing.</p>
        <div class="links1">
            <a class="contact" href="https://t.me/xxxiter">Contact me</a>
            <a class="git" href="https://github.com/vatikano1241-star">My GitHub</a>
        </div>
    </main>
    <script>
        console.log("Successfully loaded");
        console.log("Test");
        console.log("2 + 2 = ", 2+2)
    </script>
</body>
</html>
