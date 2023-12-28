<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>vineeta-portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {

            font-family: 'Poppins', sans-serif;
            background-image: url("back.jpg");
            background-repeat: no-repeat;
            background-size: cover;

        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 100px;
            background-color: #0004;
            color: aliceblue;
            position: relative;

        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a {
            text-decoration: none;
            color: aliceblue;
        }

        nav ul li a:hover {
            color: brown;
            font-size: 1.03rem;
        }

        main hr {
            border: 0;
            background-color: black;
            height: 1.2px;
            margin: 30px 84px;
        }

        .left {
            font-size: 3rem;
        }

        .firstsection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 75px 0;
        }

        .firstsection>div {
            width: 40%;
        }

        .leftsection {
            font-size: 3rem;
        }

        .leftsection .btn {
            padding: 12px;
            background-color: transparent;
            border-radius: 6px;
            border: 2px solid rgb(125, 255, 212);
            border-radius: 6px;
            font-size: 20px;
            cursor: pointer;
            margin: 50px;
            text-decoration: none;


        }

        .rightsection img {

            margin: 10px 10px;
        }

        .purple {
            color: rgb(100, 15, 15);
        }

        #element {
            color: rgb(100, 15, 15);

        }

        .secondsection {
            max-width: 80vw;
            margin: auto;
            height: 28.5vh;
        }

        .secondsection h1 {
            font-size: 1.9rem;
        }


        .thirdsection h1 {
            font-size: 1.9rem;
        }

        .thirdsection {
            max-width: 80vw;
            margin: auto;
            height: 57vh;

        }

        .thirdsection .box {
            background-color: black;
            width: 47vw;
            height: 2px;
            margin: 40px 0;
            display: flex;
           
        }

        .thirdsection .vertical {
            height: 93px;
            width: 2px;
            background-color: black;
            margin: 0 100px;

        }

        .vertical-title {
            position: relative;
            top: 23px;
            width: 150px;
            left: -35px;
        }

        .vertical-desc {
            position: relative;
            top: 20px;
            width: 150px;
            font-size: 12px;
            left: -30px;
            color: darkslategrey
        }


        .image-top {
            width: 40px;
            margin: 20px 0;
            position: relative;
            top: -37px;
            left: -18px;
        }

        .image-middle {
            width: 35px;
            margin: 20px 0;
            position: relative;
            left: -15px;
            top: -37px;

        }

        .middle-title {
            position: relative;
            top: 23px;
            width: 150px;
            left: -35px;
        }

        .middle-desc {
            position: relative;
            top: 20px;
            width: 150px;
            font-size: 12px;
            left: -30px;
            color: darkslategrey
        }

        .image-last {
            width: 35px;
            margin: 20px 0;
            position: relative;
            left: -18px;
            top: -37px;
        }

        .last-title {
            position: relative;
            top: 23px;
            width: 150px;
            left: -35px;

        }

        .last-desc {
            position: relative;
            top: 20px;
            width: 150px;
            font-size: 12px;
            left: -30px;
            color: darkslategrey;

        }

        .fourthsection {
            max-width: 80vw;
            margin: auto;
            height: 50vh;
        }

        .fourthsection .bun {
            padding: 5px;
            background-color: transparent;
            color: aliceblue;
            border: 2px solid transparent;
            border-radius: 6px;
            font-size: 9px;
            cursor: pointer;
            margin: 7px;
            text-decoration: none;
        }

        .fourthsection .ben {
            padding: 5px;
            background-color: transparent;
            color: aliceblue;
            border: 2px solid transparent;
            border-radius: 6px;
            font-size: 9px;
            cursor: pointer;
            margin: 7px;
            text-decoration: none;

        }

        .wahajsection {
            max-width: 80vw;
            margin: 0 130px;
            height: 30vh;
            display: inline-flex;
        }


        .wahajsection img {

            width: 150px;
            margin: 3px 0;
            padding: 50px;
        }

        .techsection {

            max-width: 70vw;
            margin: 0 130px;
            height: 12vh;
            display: inline-flex;
        }

        .techsection .pun {
            padding: 10px;
            background-color: rgb(99, 99, 118);
            color: white;
            border: 2px solid rgb(125, 255, 212);
            border-radius: 6px;
            font-size: 17px;
            cursor: pointer;
            margin: 18px;

        }

        .techsection .python {
            padding: 10px;
            background-color: rgb(99, 99, 118);
            color: white;
            border: 2px solid rgb(125, 255, 212);
            border-radius: 6px;
            font-size: 17px;
            cursor: pointer;
            margin: 18px;
        }

        .techsection .html {
            padding: 10px;
            background-color: rgb(99, 99, 118);
            color: white;
            border: 2px solid rgb(125, 255, 212);
            border-radius: 6px;
            font-size: 17px;
            cursor: pointer;
            margin: 18px;
        }

        .techsection .CSS {
            padding: 10px;
            background-color: rgb(99, 99, 118);
            color: white;
            border: 2px solid rgb(125, 255, 212);
            border-radius: 6px;
            font-size: 17px;
            cursor: pointer;
            margin: 18px;
        }

        .techsection .SQL {
            padding: 10px;
            background-color: rgb(99, 99, 118);
            color: white;
            border: 2px solid rgb(125, 255, 212);
            border-radius: 6px;
            font-size: 17px;
            cursor: pointer;
            margin: 18px;
        }

        .techsection .java {
            padding: 10px;
            background-color: rgb(99, 99, 118);
            color: white;
            border: 2px solid rgb(125, 255, 212);
            border-radius: 6px;
            font-size: 17px;
            cursor: pointer;
            margin: 18px;
        }

        .fifthsection {
            max-width: 80vw;
            margin: 0 130px;
            height: 10vh;
            display: inline-flex;
        }

        .fifthsection img {
            width: 30px;
            margin: 3px 0;
            padding: 25px;
            transition: transform 0.3s;
        }

        .fifthsection img:hover {
            transform: rotate(30deg) scale(1.2);
        }

        .footer {
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
        }

        .footer ul {
            list-style: none;
        }

        .footer>div {
            width: 223px;
        }

        footer .footer-rights {
            text-align: center;
            color: grey;
            padding: 12px 0;

        }
    </style>

</head>

<body>

    <header>
        <nav>
            <div class="left">Vineeta's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="#About">About</a></li>
                    <li><a href="#Academics">Academics</a></li>
                    <li><a href="#Projects">Projects</a></li>
                    <li><a href="#Contact Me">Contact Me</a></li>
                </ul>
            </div>
            <div><br></div>
        </nav>

    </header>
    <main>
        <section class="firstsection">
            <div class="leftsection">
                Hi, My name is <span class="purple">Vineeta </span>
                <div>I'm a Fresher</div>
                <div>I can describe myself as</div>
                <span id="element"></span>
                <div class="buttons">
                    <button class="btn"><a
                            href="https://drive.google.com/file/d/1-Si6Prir6IlNO56DgRIGx7xbHng7KzVN/view?usp=drive_link">Download
                            Resume</a></button>
                </div>
            </div>
            <div class="rightsection">
                <img src="nee.jpg" alt="">
            </div>
        </section>
        <hr>
        <section class="secondsection">
            <h1 id="About">About</h1>
            <div class="ab" style="font-size: x-large;">I am good at effective communication with easy adaptability to
                the work environment and a sophisticated documentation with its feedback. I am a quick learner with lots
                of leaning capability.I am multitasker and punctual to the respected deadline. I am a smart worker which
                I achieved by constant hard work and trust within myself.
            </div>
        </section>
        <hr>
        <section class="thirdsection">
            <h1 id="Academics">Academics</h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="col.jpg" alt="">
                    <div class="vertical-title">
                        Gayatri Vidya Parishad College of engineering for women
                    </div>
                    <div class="vertical-desc">
                        2019-2023<br> Electronics and Communication<br>CGPA 6.85
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-middle" src="sch.jpg.png" alt="">
                    <div class="middle-title">
                        Tirmula Mahila Junior Kalasala
                    </div>
                    <div class="middle-desc">
                        2017-2019<br>MPC<br>CGPA 9.84
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-last" src="lil.jpg" alt="">
                    <div class="last-title">
                        Little Paradise High School
                    </div>
                    <div class="last-desc">
                        2017<br>10th Class<br>CGPA 9.5
                    </div>
                </div>
            </div>






        </section>
        <hr>
        <section class="fourthsection">
            <h1 id="Projects">Projects</h1>
            <h4>Implementation Of Low Power Ternary And Quaternary Adder Circuits</h4>
            <p1>-Implemented high speed low power adders.
                <br>- Improved data density, delay, and reduced dynamic power dissipation and chip area.
                <br> -Aimed to improve VLSI circuit designs through the utilization of multiple valued logic circuits.
            </p1>
            <div class="buttond">
                <button class="bun"><a
                        href="https://docs.google.com/document/d/1-ICsevxkRMHK33DFTaXAfDu2XnuEVZ_r/edit?usp=sharing&ouid=110093558316736896022&rtpof=true&sd=true">My
                        Work</a></button>
            </div>
            <h4>Alcohol Detection for Drunken Drivers and Engine Locking System</h4>
            <p1>This is a prototype<br>-Used Arudino to get the reading of alcohol and the alcohol is sensed by using
                MQ3.<br>
                -The buzzer is used to detect the high amount of alcohol in the surrounding atmosphere.<br>
                -We used normal motor as the replica of the real motor.<br>
                -To display the rating we used digital board and a message that “YOUR DRUNK”.</p1>
            <div class="buttonp">
                <button class="ben"><a
                        href="https://drive.google.com/file/d/1BbEEsstqtHDg2uS74eiE-ZjdAi92lf-Q/view?usp=drive_link">My
                        Work</a></button>
            </div>

        </section>
        <hr>
        <section class="wahajsection">
            <h1>Hobbies</h1>
            <div class="song">
                <img src="music.jpg" alt="" title="listening music">
            </div>
            <div class="food">
                <img src="cook.jpg" alt="" title="cooking">
            </div>
            <div class="code">
                <img src="vinnu.jpg" alt="" title="coding">
            </div>

        </section>
        <hr>
        <section class="techsection">
            <h1>Technical skills</h1>
            <div class="butto">
                <button class="pun">C language</button>
            </div>
            <div class="py">
                <button class="python">Python</button>
            </div>
            <div class="ml">
                <button class="html">HTML</button>
            </div>
            <div class="cs">
                <button class="CSS">CSS</button>
            </div>
            <div class="ql">
                <button class="SQL">SQL</button>
            </div>
            <div class="cr">
                <button class="java">Java Script</button>
            </div>

        </section>
        <hr>
        <section class="fifthsection">
            <h1 id="Contact Me">Contact Me</h1>
            <div class="link">
                <a href="https://www.linkedin.com/in/giduturi-vineeta/"> <img src="link.jpg" alt=""></a>

            </div>
            <div class="mail">
                <img src="mail.jpg" alt="" title="vineetagiduturi@gmail.com">
            </div>
            </div>
            <div class="face">
                <img src="fb.jpg" alt="" title="vineetagiduturi">

            </div>
        </section>
        <hr>
    </main>
    <footer>
        <div class="footer">
            <div class="footer-first">
                <h3>Vineeta's Portfolio</h3>
            </div>
            <div class="footer-second">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Academics</li>
                    <li>Projects</li>
                    <li>Contact Me</li>
                </ul>

            </div>
            <div class="footer-third">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Academics</li>
                    <li>Projects</li>
                    <li>Contact Me</li>
                </ul>
            </div>
            <div class="footer-fourth">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Academics</li>
                    <li>Projects</li>
                    <li>Contact Me</li>
                </ul>
            </div>
        </div>
        <div class="footer-rights">
            Copyright &#xa9; www.vineetasportfolio.com| All rights reserved
        </div>
    </footer>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['Team Player', 'Quick learner', 'Smart worker', 'Vocal'],
            typeSpeed: 50,
        });
    </script>
</body>

</html>
