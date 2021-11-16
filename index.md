<!DOCTYPE html>
<html class="no-js" lang="en">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>My Portfolio</title>
    <link rel="shortcut icon" href="favicon.png" >
    <link rel="icon" href="favicon.png" >
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="libs/font-awesome/css/font-awesome.min.css">
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/styles.css" rel="stylesheet">
</head>

<body>
    <div id="mobile-menu-open" class="shadow-large">
        <i class="fa fa-bars" aria-hidden="true"></i>
    </div>
    <!-- End #mobile-menu-toggle -->
    <header>
        <div id="mobile-menu-close">
            <span>Close</span> <i class="fa fa-times" aria-hidden="true"></i>
        </div>
        <ul id="menu" class="shadow">
            <li>
                <a href="#about">About</a>
            </li>
            <li>
                <a href="#experience">Experience</a>
            </li>
            <li>
                <a href="#education">Education</a>
            </li>
            <li>
                <a href="#projects">Projects</a>
            </li>
            <li>
                <a href="#skills">Skills</a>
            </li>
            <li>
                <a href="#contact">Contact</a>
            </li>
        </ul>
    </header>
    <!-- End header -->

    <div id="lead">
        <div id="lead-content">
            <h1>Guy Dadon</h1>
            <h2>Software Developer</h2>
            <a href="https://docs.google.com/document/d/1MkFPGlzqOxlLwptOyTCBYwaVA5a59i2bjiMMu--GbG0/edit?usp=sharing"
                target="_blank" class="btn-rounded-white">
                My Resume</a>
        </div>
        <!-- End #lead-content -->

        <div id="lead-overlay"></div>

        <div id="lead-down">
            <span>
                <i class="fa fa-chevron-down" aria-hidden="true"></i>
            </span>
        </div>
        <!-- End #lead-down -->
    </div>
    <!-- End #lead -->

    <div id="about">
        <div class="container">
            <div class="row">
                <div>
                    <h2 class="heading">ABOUT ME</h2>

                    <p>
                        Jerusalem, Israel, Born in 1992 (28 years old). <br> Full Stack & Professional game developer
                        for 2
                        years,

                        <br><br>
                        I've always loved creating stuff, whether it's music, art or program. <br>
                        I'm a proficient self learner and a very fast one at that.

                        <br><br>
                        <span style="font-size: 16px;">
                            Guitarist & musician for 14 years (performe / compose /edit).
                        </span>
                    </p>
                </div>
            </div>
        </div>
    </div>
    <!-- End #about -->

    <div id="experience" class="background-alt">
        <h2 class="heading">EXPERIENCE</h2>
        <div id="experience-timeline">
            <div data-date="Aug 2019 – April 2020 <br>Jan 2021 – Now">
                <h3>Freelancer</h3>
                <h4>Game Developer</h4>
                <p>
                    Freelancer at
                    <a href="https://www.fiverr.com/guydadon542" target="_blank">Fiverr</a>
                    creating over <a href="#fiverr-projects">30 different video games </a>
                    for clients all over the world in many genres,
                    <br>While maintaing a 5 star rating throughout and creating all the
                    code, art and music myself.
                </p>
            </div>

            <div data-date="April 2020 – Jan 2021">
                <h3>Bonna inc.</h3>
                <h4>Software Developer</h4>
                <p>
                    Software developer at a new startup creating a personal finance app called "Paycheck" with
                    Text-From-Image
                    functionalities, And a city tycoon game with many minigames <a href="#minister">(Minister)</a>
                </p>
            </div>

            <div data-date="May 2014 – May 2019">
                <h3>Modiin ezrahi (מודיעין אזרחי)</h3>
                <h4>Security Guard</h4>
                <p>
                    Security guard in the main buildings of social security (ביטוח לאומי).
                </p>
            </div>

        </div>
    </div>
    <!-- End #experience -->

    <div id="projects">
        <h2 class="heading">PROJECTS</h2>
        <div class="container">
            <div class="row">

                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/jJcqJ_2C-BI">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>
                            Bullet Express
                        </h3>
                        <p>
                            A personal project i am working on for over a year fueled solely by passion.<br> A
                            full-fledged
                            rouge-lite video game where you have six uniqe guns which can be merged with each other
                            creating 30 hand-crafted guns to explore.
                            <br><br> All code, art and music by me.
                        </p>
                        View and play on:
                        <a href="https://gamejolt.com/games/BulletExpress/490457" target="_blank"
                            style="font-size: 20px;">GameJolt</a> or
                        <a href="https://lazygems.itch.io/bullet-express" target="_blank"
                            style="font-size: 20px;">itch.io</a>

                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/pc.png" width="32" height="32" style="margin-right: 40px;">
                </div>

                <div class="project shadow-large" id="fiverr-projects">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/mGv3uUBYKZo">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>30 Minutes Or Less</h3>
                        <p>
                            Deliver pizzas to different locations on the map before the
                            time runs out. Continue your delivery back and forth from the pizzeria to the customers.
                            Earn tip
                            money and extra time for each good delivery.
                            <br><br> All code and art by me.
                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/unity.png" width="32" height="32">
                    <img src="images/pc_mobile.png" width="32" height="32" style="margin-right: 40px;">

                </div>

                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/Xe8nnETSJ3s">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Moon Prosody</h3>
                        <p>
                            Bullet hell meets rythem game. <br>
                            Hit the notes guitar hero style while you shoot and dodge in this cyberpunk rythem shooter!
                            <br> including 2 original songs by me.
                            <br><br> All code, art and music by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/pc.png" width="32" height="32" style="margin-right: 40px;">

                </div>
                <!-- End .project -->



                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/f5bFrByYON0">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Project Empires</h3>
                        <p>
                            A remake of the classic Age Of Empires for mobile. <br>
                            Create units, build buildings, extract resources and engage politicaly with neighboring
                            states.
                            A very big collaborative project that has been in development for 6 months.
                            <br><br> All code by me.
                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/pc_mobile.png" width="32" height="32" style="margin-right: 40px;">
                </div>


                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/tm_XaGz0WQk">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>COSMONAV</h3>
                        <p>
                            Mine resources, befriend or befoe surrounding factions and visit planets and space stations
                            for goods in this top down space rpg.
                            <br><br> All code, art and music by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/pc_mobile.png" width="32" height="32" style="margin-right: 40px;">
                </div>

                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/SoiToEmZ-vM">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Jesus Saves The World</h3>
                        <p>
                            Play as jesus as he saves the world from zombies and demons in this holloween themed Action
                            RPG
                            <br><br> All code, art and music by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/pc.png" width="32" height="32" style="margin-right: 40px;">

                </div>


                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/lz5U_1GBqWg">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Knowledge Retention</h3>
                        <p>
                            Made for a college in the US for education purposes, the game is an interactive learning
                            experience leading you through a curriculum in a fun and engaging way.
                            <br><br> All code, art and music by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/pc.png" width="32" height="32" style="margin-right: 40px;">

                </div>


                <div class="project shadow-large" id="minister">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/qP_Rq8C2aj4">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Minister</h3>
                        <p>
                            Play as the minister of israel as you upgrade state offices and unlock new minigames in a
                            top down pixel art world.
                            <br><br> All code, art and music by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/pc_mobile.png" width="32" height="32" style="margin-right: 40px;">
                </div>

                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/A4Zqmhu6HAQ">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Purple Chase</h3>
                        <p>
                            Jetpack though 5 different cities with over 10 playable characters as you search for a cure
                            in this flappy bird like video game for mobile.
                            <br><br> All code and music by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/mobile.png" width="32" height="32" style="margin-right: 40px;">
                </div>

                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/XfvWPvJSpO0">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Super Nova</h3>
                        <p>
                            Help nova get to her exam on time in this educational mario like platformer, complete with
                            60 levels.
                            <br><br> All code, art and some music by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/pc.png" width="32" height="32" style="margin-right: 40px;">

                </div>

                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/bjLzivaxiaw">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Mister President I Found The Cure</h3>
                        <p>
                            Spray germs, fight store managers and go through mazes as you look for the cure.
                            <br><br> All code, art and music by me.
                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/mobile.png" width="32" height="32" style="margin-right: 40px;">

                </div>



                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/9elqFdkJzmg">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Immunity Guardian</h3>
                        <p>
                            An educational arcade-style top down shoot 'em up. Use top grade laser weapons to fight
                            pathogens and protect the immune system.
                            <br><br> All code and art by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/mobile.png" width="32" height="32" style="margin-right: 40px;">

                </div>



                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/0COBvsJKjDg">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Dont Stop Running</h3>
                        <p>
                            Keep running to grow the planet and avoid the lava until you have enough fuel to escape, and
                            even then you are not safe.
                            <br>Using custom drawing.
                            <br><br> All code, art and music by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/pc_mobile.png" width="32" height="32" style="margin-right: 40px;">
                </div>



                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/VY86wuEZf_A">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Cyber Cat</h3>
                        <p>
                            Jump and shoot on bugs in this endless runner for mobile.
                            <br><br> All code and most art by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/mobile.png" width="32" height="32" style="margin-right: 40px;">

                </div>


                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/ICTSe3XFwag">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Fast Math / Anatomy Mini Game</h3>
                        <p>
                            A fun set of educational mini games to challange your knowledge in anatomy and math.
                            <br><br> All code, art and sounds by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/pc_mobile.png" width="32" height="32" style="margin-right: 40px;">
                </div>



                <div class="project shadow-large">
                    <div class="project-image">
                        <iframe width="480" height="270" allowfullscreen="allowfullscreen"
                            src="https://www.youtube.com/embed/VDDfGge7sPg">
                        </iframe>
                    </div>
                    <!-- End .project-image -->
                    <div class="project-info">
                        <h3>Dual Basket Ball</h3>
                        <p>
                            A one button mini game, Dunk the basketball and never touch the ground.
                            <br><br> All code, art and music by me.

                        </p>
                    </div>
                    <!-- End .project-info -->
                    <img src="images/godot.png" width="32" height="32">
                    <img src="images/pc_mobile.png" width="32" height="32" style="margin-right: 40px;">
                </div>


                <!-- End .project -->
            </div>

        </div>
    </div>
    <!-- End #projects -->

    <div id="skills" class="background-alt">
        <h2 class="heading">SKILLS</h2>
        <ul>
            <li>Java <span class="green-dot"></span></li>
            <li>Python <span class="green-dot"></span></li>
            <li>C# <span class="green-dot"></span></li>
            <br>
            <li> <a href="https://godotengine.org/" target="_blank">
                    <img src="images/godot.png" width="24" height="24" style="margin-right: 8px;">
                    Godot Engine <span class="green-dot"></span>
                </a>
            </li>
            <li><img src="images/unity.png" width="24" height="24" style="margin-right: 8px;">
                Unity <span class="yellow-dot"></span></li>
            <li>Android Studio <span class="green-dot"></span></li>
            <br>
            <br>
            <li>Node.js <span class="red-dot"></span></li>
            <li>Angular <span class="green-dot"></span></li>
            <li>React <span class="red-dot"></span></li>
            <br>
            <li>JavaScript <span class="red-dot"></span></li>
            <li>TypeScript <span class="green-dot"></span></li>
            <li>HTML <span class="green-dot"></span></li>
            <li>CSS <span class="green-dot"></span></li>


        </ul>
        <br>
        <br>
        <br>

        <h1 class="heading" style="font-size: 26px;">LANGUAGES</h1>
        <ul>


            <li style="font-size: 18px;">Hebrew - Native</li>
            <li style="font-size: 18px;">English - Fluent</li>

        </ul>

    </div>
    <!-- End #skills -->

    <div id="education">
        <h2 class="heading">EDUCATION</h2>
        <div class="education-block">
            <h3>John Bryce</h3>
            <span class="education-date">November 2017 - January 2019</span>
            <h4>FullStack Java, One year (354 hours)</h4>
            <p>
            <ul>
                <li>
                    Android Studio
                </li>
                <li>
                    OOP, Design Patterns.
                </li>
                <li>
                    Back-end: Java, Spring, MSSQL, MySql, JPA.
                </li>
                <li>
                    Front-end: Angular, Bootstrap, Firebase
                </li>
                <li>
                    Security filters & Math utilities.
                </li>
            </ul>
            </br>
            <h4>Final project — Coupon management system</h4>
            <ul>
                <li>
                    With secure registration.
                </li>
                <li>
                    Grade - 97
                </li>
            </ul>
            </p>
        </div>
        <!-- End .education-block -->

        <div class="education-block">
            <h3>ORT Givat Ram</h3>
            <span class="education-date">Sept 2007 - Sept 2010</span>
            <h4>Electronics & Computer Science</h4>
            <ul>
                <li>
                    High school graduate with electives Electronics and computer science
                    expanding on english translation, C and Java.
                </li>
            </ul>
        </div>
        <!-- End .education-block -->
    </div>
    <!-- End #education -->

    <footer>
        <div class="container">
            <div class="row">
                <div class="col-sm-5 copyright">
                    <p>
                        Guy Dadon <br>


                        <span style="font-size: 18px;"> Phone: <a href="tel:+972-753-4377">+972-753-4377</a></span> <br>

                        <span style="font-size: 18px;">Email:
                            <a href="mailto: guydadon14@gmail.com">guydadon14@gmail.com</a>
                        </span>
                    </p>


                </div>
                <div class="col-sm-2 top">
                    <span id="to-top">
                        <i class="fa fa-chevron-up" aria-hidden="true"></i>
                    </span>
                    <img src="images/character_big.gif" alt="" style="margin-top: 32px;">

                </div>

                <div class="col-sm-5 social">
                    <ul>
                        <li>
                            <a href="https://github.com/PapaCheese" target="_blank"><i class="fa fa-github fa-2x"
                                    aria-hidden="true" style="margin-right: 16px;"></i></a>
                        </li>

                        <li>
                            <a href="https://www.linkedin.com/in/guy-dadon-024244167/" target="_blank"><i
                                    class="fa fa-linkedin fa-2x" aria-hidden="true"></i></a>
                        </li>

                    </ul>
                </div>
            </div>

        </div>
    </footer>
    <!-- End footer -->

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="js/scripts.min.js"></script>
</body>

</html>