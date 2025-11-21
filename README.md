[portfolio.html](https://github.com/user-attachments/files/23671872/portfolio.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>portfolio1</title>
    <style>


    * {
        box-sizing: border-box;
        margin: 10px;
        padding: 2px;
        font-family: Georgia, 'Times New Roman', Times, serif;
        color: #ffffff;
        background-color: rgba(255, 255, 255, 0.428);
        
    }

    h1 {
        color:#02c3fe;
        font-weight: bold;
        font-style: italic;
        font-size: 50px;
        text-shadow: 2px 3px 4px #000000;
        
    }

    h2 {
        text-align: center;
        color: rgb(225, 222, 222);
        font-size: 40px;
        font-style: italic;
        text-shadow: 2px 3px 4px #000000;
        float:initial;
    }

    img.me{
        border-radius: 50%;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        transition: transform 0.3s ease;
        margin-right: 20px;
        align-items: center;
        vertical-align: middle;
        display: inline-block;
        margin-top: 10px;

    }

    img:hover {
        transform: scale(1.1);
        box-shadow: 1px 6px 20px rgb(0, 157, 255);
        transition: 0.5s ease;
    }

    fieldset {
        border: #a6ff00 2px solid;
        padding: 20px;
        transition: box-shadow 0.3s ease;
        margin-bottom: 20px;
        border-radius: 8px;
        box-shadow: #aaff01 0 4px 8px;
        pointer-events: fill;
        background: linear-gradient(100deg, rgb(0, 0, 0), rgb(255, 0, 0));
        backdrop-filter: blur(10px);
        border: 1px solid rgba(255, 255, 255, 0.2);
        box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
    }

    fieldset:hover {
        box-shadow: 0 4px 12px rgb(0, 0, 0);
        transition: box-shadow 0.3s ease;
        transform: scale(1.02) 0.3s ease;
        cursor: pointer;
        background: linear-gradient(100deg, rgb(0, 0, 0), rgb(255, 0, 0));
        backdrop-filter: blur(10px);
        border: 1px solid rgb(0, 0, 255);
    }

    legend {
        font-weight: bold;
        color: #ffeb3b;
        font-size: 1.5em;
        margin-bottom: 10px;
        text-shadow: 2px 1px 2px #000000;
        background-color: transparent;
    }

    legend:hover {
        color: #aaff01;
        transition: scale(1.1) 7color 0.3s ease;
    }

    ul,li {
        list-style-type: square;
        padding-left: 20px;
        color: #ffffff;
        font-size: 18px;
        pointer-events: fill;
        background-color: transparent;
    }
    
    a {
        color: #02ff56;
        text-decoration:double;
        background-color: transparent;
    }
    a:hover {
        color: #02c3fe;
        text-decoration: underline;
        transition: color 0.3s ease;
    }

    footer {
        padding: 10px;
        color: rgb(0, 0, 0);
        bottom: 0;
        width: 100%;
        box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.3);
        font-size: 14px;
        float:inline-end;
    }

    p,h3 {
        display: inline;
        background-color: transparent;
        }

    h3:hover {
        color: #aaff01;
        transition: color 0.3s ease;
    }

    h1 {
        display: flex;
        }


    p.end {
        text-align: center;
        font-size: 16px;
        color: #000000;
    }

    ul.contact-info li {
        margin-bottom: 10px;
        display:ruby;
        background-color: transparent;
        position:relative;
        left:20px;

    }

     </style>

    </head>

    <body>
    <img class="me" src="/images/IMG_20250525_095414.jpg" alt="My Photo" width=150px; height=150px; style="border-radius: 100%; display: block; zoom: 150%;">
    <h1>My Portfolio</h1>




    <fieldset>
        <legend>Contact Me</legend>
        <p>Feel free to connect with me on social media or check out my projects!</p>
        <ul class="contact-info">
         <li>Email:<a href="gunasekhargandham6@gmail.com" target="_top">gunasekhargandham6@gmail.com</a></li>
         <li>Phone:<a href="8328398230" target="_top">contact</a></li>
         <li>LinkedIn: <a href="https://www.linkedin.com/in/gandham-guna-sekhar-42031529a/" target="_top">Gandham Gunasekhar</a></li>
         <li>GitHub: <a href="https://github.com/gunasekhar095" target="_top">Gunasekhar095</a></li>
        </ul>
    </fieldset>




    <fieldset>
        <legend>About Me</legend>
        <p>Hello! I'm</p><h3>GUNASEKHAR GANDHAM</h3><p>, a passionate web developer with a love for creating beautiful and functional websites. I specialize in HTML, CSS, and JavaScript.</p>
    </fieldset>

    <fieldset>
        <legend>Education</legend>
        <ul>
            <li>Bachelor's Degree in Electronics and Communication Engineering from N.B.K.R.I.S.T. with CGPA: 6.0/10.</li>
            <li>Intermediate at T.M.R. Jr College with 67%.</li>
            <li>SSC at Vema High School with 87%.</li>
            <li>Certified Web Developer from kodnest Institute.</li>
        </ul>
    </fieldset>



    <fieldset>
        <legend>Skills</legend>
        <ul>
            <li>FRONTEND:- HTML, CSS, JavaScript</li>
            <li>TOOLS:- VISUAL STUDIO CODE, GIT, GITHUB, FIGMA, Chrome DevTools </li>
            <li>Responsive Web Design</li>
            <li>Version Control with Git</li>
        </ul>
    </fieldset>



    <fieldset>
        <legend>Projects</legend>
        <ul>
            <li>Micro Project:- Object Distance Measuring using Arduino uno and Ultrasonic Sensor</li>
            <li>Major Project:- Medicine Remainder and Automatic Alert for Low Medicine Stock</li>
            <li>Portfolio Website: <a href="https://gunasekhar095.github.io/Portfolio/" target="_blank">View Project</a></li>
            <li>Responsive Website: <a href="https://gunasekhar095.github.io/Responsive-Website/" target="_blank">View Project</a></li>
        </ul>
    </fieldset>




    <fieldset>
        <legend>Internships</legend>
        <ul>
            <li>Completed a 6-month internship on Web Development at kodnest Institute.</li>
            <li>Completed a 3-month internship on Embedded Systems at CODTECH IT SOLUTIONS</li>
        </ul>
    </fieldset>




    <fieldset>
        <legend>Certifications</legend>
        <ul>
        <li><a href="/pdfs/NPTEL-Programming In Java.pdf" download>NPTEL-Programming in Java</a></li>
        </ul>
    </fieldset>
    



    <footer>
        <p class="end">&copy; 2025 GUNASEKHAR. All rights reserved.</p>
    </footer>



</body>
</html>
