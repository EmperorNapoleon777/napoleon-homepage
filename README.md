<!DOCTYPE html>

<html lang="en">
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css"
            rel="stylesheet"
            integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65"
            crossorigin="anonymous">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
            integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
            crossorigin="anonymous">
        </script>
        <link href="styles.css" rel="stylesheet">
        <title>Napoleon's Homepage</title>
        <link rel="icon" href="napfrance_favicon.ico" type="image/x-icon">
    </head>
    <h1 class='header'>Napoleon Bonaparte's Homepage</h1>
    <hr>
    <h3 style='text-align: center'>Titles: Emperor, General</h3>
    <body>
        <hr>
        <div class='section' style='text-align: center'>
            Welcome to my homepage!
            If you aren't already part of my ever expanding empire, you will be soon!
        </div>

        <div class='footnote' style='text-align: center'>
            Click the menu icon on the top right to explore more!
        </div>

        <div id="menu-placeholder"></div>

        <!--
        <script>
            document.getElementById('menu-logo').onclick = function() {
                var menuBar = document.getElementById('menu-bar');
                if (menuBar.classList.contains('hidden')) {
                    menuBar.classList.remove('hidden');
                } else {
                    menuBar.classList.add('hidden');
                }
            }
        </script>
        -->

        <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
        <script>
            $(document).ready(function() {
                $("#menu-placeholder").load("menu.html");
            });
        </script>
    </body>
</html>
