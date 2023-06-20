<!DOCTYPE html>
<html>
    <!--Head-->
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width" />
        <title>Caleb Gamble</title>
        <link rel="stylesheet" type="text/css" href="CSS/portfollio.css">
    </head>

    <!--Body-->
    <body class="Background">
        
        <!--Navbar-->
        <div class="Navbar">
            <a class="active" href="#Home">Home</a>
            <a href="#About">About</a>
            <a href="#GitHub">GitHub</a>
            <a href="#Contact">Contact</a>
        </div>

        <!--Breaks inserted to add space between navbar and the first heading-->
        <br>
        <br>

        <!--Background video-->
        <div id="Home">
            <video autoplay muted loop id="Typing_Video">
                <source src="Img/video/Typing.mp4" type="video/mp4">
                <!--Display message if video fails to run-->
                Your browser does not support HTML5 video.
            </video>
        </div>

        <!--Video text-->
        <div class="Video_Text">
            <h1 class="white-text">Caleb Gamble Portfolio</h1>
            <strong>
                <p class="center">
                    <q>The computer programmer is a creator of universes for which he alone is the lawgiver.
                        <br>No playwright, no stage director, no emperor, however powerful, has ever exercised such absolute authority to arrange a stage or
                        <br>field of battle and to command such unswervingly dutiful actors or troops.
                    </q>
                    <br> -Joseph Weizenbaum
                    <br>
                    <br> My name is Caleb Gamble. Welcome to my portfolio website. I will show you what ive done with coding and what i can do..
                    <br>
                    <br> Thank you for stopping by and enjoy! 
                </p>
            </strong>
        </div>

        <!--About section-->
        <div class="Row" id="About">
            <!--Left column-->
            <div class="Column_2">
                <img src="Img/laptop pic.jpg" alt="You will learn more about me">
            </div>
            <!--Right column-->
            <div class="Column_1">
                <h1>About</h1>
                <p>
                    I am a software developer who loves to code! I am so excited about code that it makes my heart race. 
                    <br>
                    <br>I am a graduate of <a href="https://www.learncodinganywhere.com" target="_blank">The Tech Academy</a>’s Software Developer Boot Camp, and trained and experienced in the following web and programming languages: HTML, CSS, JavaScript, SQL, C# and more. 
                    <br>
                    <br>I am a full-stack developer and would love to work with you on your project. <a href="#Contact">Contact</a> me below!
                </p>
            </div>
        </div>

        <!--GitHub section-->
        <div class="Row" id="GitHub">
            <!--Left column-->
            <div class="Column_1">
                <h1>GitHub</h1>
                <p>
                    You can view my coding projects on my GitHub profile here:
                    <br>
                    <p class="center"><a href="https://github.com/Gamblemaniac12" target="_blank">Caleb Gamble's Github</a></p>
                </p>
            </div>
            <!--Right column-->
            <div class="Column_2">
                <a href="https://github.com/the-tech-academy" target="_blank"><img src="Img/github.jpg" alt="GitHub Logo"></a>
            </div>
        </div>

        <!--Contact section-->
        <div class="Row" id="Contact">
            <!--Contact image, left column-->
            <div class="Column_2 Column_tall">
                <img src="Img/contact pic.jpg" alt="Contact_Image">
            </div>
            <!--Contact form, right column-->
            <div class="Column_1 Column_tall">
                <h1>Contact</h1>
                <!--This specifies where and how to send the form data; we are leaving it blank-->
                <form action="" method="POST"> <!-- Here we are utilizing a 3rd party service to submit the contact form data, insert your formspree endpoint in the action attribute -->
                    <label>Name:</label>
                        <input type="text" placeholder="Please enter your name here">
                    <label>Email:</label>
                        <input type="text" id="Email" name="Email" placeholder="Please enter your email here">
                    <label>Message:</label>
                        <input type="text" id="Message" name="Message" placeholder="Please write your message here">
                        <input type="submit" value="SUBMIT">
                </form>
            </div>
        </div>

        <!--Footer section-->
        <footer>
            <p>
                <p class="center">&copy Prosper Consulting Inc., <a href="https://www.learncodinganywhere.com/" target="_blank">The Tech Academy</a></p>
                <br>
            </p>
        </footer>
    </body>
</html>
