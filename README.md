<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            box-sizing: border-box;
        }

        body>* {
            border: 2px solid green;
        }

        body, html {
            margin: 0;
            padding: 0;
            border: 2px solid green;
        }

        body {
            display: grid;
            grid-template-columns: 200px 1fr;
            grid-template-rows: 1fr 120px;
        }

        header {
            grid-area: header;
        }
        
        section {
            grid-area: section;
        }

        main {
             grid-area: main;
        }

        footer {
            grid-area: footer;
        }
    </style>
</head>

<body>
    <header>

    </header>

    <section>

    </section>

    <main>
        <article>
            <h1>Oh Fernando Alonso </h1>

        </article>
        <div class="gallery">

        </div>
    </main>
    <footer>

    </footer>
</body>

</html>
