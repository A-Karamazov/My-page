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
            grid-template-rows: 300px 1fr 150px;
            grid-template-areas: 
            "header header"
            "section main"
            "footer footer";
            min-height: 100svh;
            gap: 0.5rem;
            padding: .5rem;
        }

        header {
            grid-area: header;
        }
        
        section {
            grid-area: section;
            width: 100%;
            height: 100%;
        }

        main {
             grid-area: main;
             position: relative;
             isolation: isolate;
        }

        footer {
            grid-area: footer;
        }
    </style>
</head>

<body>
    <header>
        header
    </header>

    <section>
        section
    </section>

    <main>
        <article>
            <h1>Oh Fernando Alonso </h1>

        </article>
        <div class="gallery">

        </div>
    </main>
    <footer>
        footer
    </footer>
</body>

</html>
