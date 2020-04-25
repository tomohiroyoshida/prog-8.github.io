<!DOCTYPE html>
<html lang="ja">


    <head>
        <meta charset="UTF-8">
        <title>HITOMOHIRO</title>
        <meta name="description " content="This is Tomohiro's portfolio.">

        <!-----  CSS ----->
        <link rel="stylesheet" href="https://unpkg.com/ress/dist/ress.min.css">
        <link href="https://fonts.googleapis.com/css2?family=Rubik&display=swap" rel="stylesheet">
        <link href="css/style.css" rel="stylesheet">
        <link href="css/special.css" rel="stylesheet">
    </head>

    <body>
        <div id="wrapper">
            <div id="home" class="big-bg">
                <header class="page-header">
                    <div class="container">
                        <div class="title-block">TOMO'S Portfolio</div>
                        <div class="hamburger" id="open_nav">
                            <img src="hamburger.png" alt="">
                        </div>
                    </div>
                </header>

                <main>
                    <div class="container">
                        <div class="home-content wrapper" >
                            <h1 class="page-title">Hi!<br>
                                I'm Tomohiro Yoshida</h1>
                            <p>A Software engineer</p>
                        </div>
                        <div class="sub-content wrapper">
                            <h2><a href="index.html">Home</a></h2>
                            <h2><a href="https://www.wantedly.com/users/114407911">About Me</a></h2>
                            <h2><a href="contact.html">Contact</a></h2>
                        </div>
                    </div>      
                </main>
        
            </div>      
            <footer>
                <div class="container">
                    <p>@Tomohiro Yoshida</p>
                </div>  
            </footer>
        </div>
        <nav id="nav">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="https://www.wantedly.com/users/114407911">About Me</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>    

        <script src="scripts/jquery-3.4.1.min.js"></script>
        <script>
        'use strict';

        $(document).ready(function() {
            $('#open_nav').on('click', function() {
                $('#wrapper, #nav').toggleClass('show');
            });
        });
        </script>
    </body>

</html>
