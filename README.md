# To create a web Portfolio/CV using HTML & CSS

### AIM :
      To create a web Portfolio/CV using HTML & CSS
    
### ALGORITHM :
      Step 1: Start by creating a new folder. 
	Step 2: Create and Open the “index.html”, write the code.
	Step 3: Create a new CSS file “style.css” 
	Step 4: Design the basic structure of your website using HTML tags like <header>,      
                        <nav>, <main>, and <footer>.
      Step 5: Implement navigation menus using HTML lists (<ul> or <ol>) and CSS                                                   
             styling.
	Step 6: Test your website by opening the HTML file in a web browser. Make any  
                        necessary adjustments to the HTML and CSS code to achieve the desired   
                        layout and design.
                       
### PROGRAM :
      
          index.html
          
          <!DOCTYPE html>
            <html lang="en">
              <head>
                <meta charset="UTF-8" />
                <meta http-equiv="X-UA-Compatible" content="IE=edge" />
                <meta name="viewport" content="width=device-width, initial-scale=1.0" />
                <title>Personal Portfolio</title>
                <link rel="stylesheet" href="style.css" />
                <!-------Using-FontAwesome----->
                <script src="https://kit.fontawesome.com/c8e4d183c2.js"
                crossorigin="anonymous"></script>
              </head>
              <body>
                <section>
                  <!------Navigation------>
                  <nav>
                    <!---Logo-->
                    <a href="#" class="logo">Profile</a>
                    <!-----menu-->
                    <ul>
                      <li><a href="#" class="active">HOME</a></li>
                      <li><a href="#">ABOUT</a></li>
                      <li><a href="#">PROJECTS</a></li>
                      <li><a href="#">CONTACT</a></li>
                    </ul>
                  </nav>
                  <!--------Text------->
                  <div class="text-container">
                    <p>Hello!</p>
                    <p>I'm JANANI</p>
                    <p>Student</p>
                    <button class="cv-button">Download CV</button>
                  </div>
                  <!-----------Photo-------->
                  <img src="img2.png" class="photo" alt="photo" />
                </section>
                <!-------About Section------>
                <div class="about-container">
                  <!--------image------------>
                  <img src="img2.png" />
                  <!------About Text--------->
                  <div class="about-text">
                    <p>About ME</p>
                    <p>Student</p>
                    <p>
                      Hello, I'm a student currently in 3rd year, pursuing Computer Science
                      Engineering. I wish to secure a responsible career opportunity to
                      fully utilize my training and skills, while making a significant
                      contribution to the success of the organisation. I'm a dedicated
                      individual looking ahead for a challenging role at a progressive
                      organisation that offers immense growth opportunities and to implement
                      my advanced knowledge and skills
                    </p>
                    <button href="#index1.html">Download CV</button>
                  </div>
                </div>
                <!--------------------Education Section----------->
                <div class="education">
                  <!-------text------->
                  <div class="education-text">
                    <p>Education</p>
                    <p>
                      Timeline of my educatiion is mentioned for further details click More
                    </p>
                  </div>
                  <!--------Box-------->
                  <div class="box-container">
                    <!------1----------->
                    <div class="box-1">
                      <span>1</span>
                      <p class="heading1">Undergraduate</p>
                      <p class="course1">B.E CSE- 2020-2024</p>
                      <p class="percentage">8.89 CGPA until 5th Semester</p>
                      <button>More</button>
                    </div>
                    <!-------2------------>
                    <div class="box-2">
                      <span>2</span>
                      <p class="heading">Secondary School</p>
                      <p class="course1">Grade XII - 2018-2020</p>
                      <p class="percentage">75%</p>
                      <button>More</button>
                    </div>
                    <!-------3------------->
                    <div class="box-3">
                      <span>3</span>
                      <p class="heading1">High School</p>
                      <p class="course1">Grade X - 2017-2018</p>
                      <p class="percentage">85%</p>
                      <button>More</button>
                    </div>
                  </div>
                </div>

                <!----------------Projects ---------->
                <div class="projects">
                  <p>Projects</p>
                 <!--------Box-------->
                 <div class="pbox-container">
                  <!------1----------->
                  <div class="pbox-1">
                    <span>1</span>
                    <p class="heading1">Mini-project</p>
                    <p class="course1">Non contact Heart Rtae Monitor</p>
                    <p class="percentage">
                      This project has been implemented using python to measure the heart
                      hate of a human live.
                    </p>
                    <button>More</button>
                  </div>
                </div>
                <!-----------Footer------->
                <footer>
                  <!----------Social-------->
                  <div class="social-icons">

                    <a href="#"><i class = "fab fa-facebook"></i></a>
                    <a href="#"><i class = "fab fa-twitter"></i></a>
                    <a href="#"><i class = "fab fa-instagram"></i></a>
                    <a href="#"><i class = "fab fa-youtube"></i></a>


                  </div>
                  <!------copyright------>
                  <p class="------copyright------">Copyrights Reserved</p>
                </footer>
              </body>
            </html>
            
      

      style.css
      
      @charset "utf-8";
      /* this is a css file */
      /* home sectionit */
      body {
        margin: 0px;
        padding: 0px;
      }
      ul {
        list-style: none;
      }
      a {
        text-decoration: none;
      }
      section {
        width: 100%;
        height: 95vh;
        background-image: url("img1.png");
        background-repeat: no-repeat;
        background-size: cover;
        position: relative;
      }
      nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 60px;
        background-color: #ffffff;
        box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.2);
        padding: 0px 5%;
      }
      nav ul {
        display: flex;
      }
      nav ul li a {
        margin: 30px;
        font-family: Segoe Script;
        color: #103e45;
        font-size: 15px;
        font-weight: 700;
      }
      .logo {
        font-family: myriad pro regular;
        color: black;
        font-size: 22px;
      }
      .active {
        font-weight: bold;
        color: aqua;
      }
      .text-container p:nth-child(1) {
        font-family: Gill Sans;
        font-weight: bold;
        color: rgb(23, 34, 44);
        font-size: 22px;
      }
      .text-container p:nth-child(2) {
        font-family: calibri;
        font-weight: bold;
        letter-spacing: 1px;
        color: rgb(3, 14, 24);
        font-size: 65px;
      }
      .text-container p:nth-child(3) {
        font-family: Segoe Scripta;
        letter-spacing: 1px;
        color: rgb(3, 14, 24);
        font-size: 30px;
        line-height: 30px;
      }
      .text-container p {
        line-height: 0px;
        margin: 45px 0px 25px;
      }
      .text-container {
        position: absolute;
        left: 15%;
        top: 45%;
        transform: translate(-15%, -45%);
      }
      .text-container button {
        width: 130px;
        height: 45px;
        border-radius: 10px;
        font-family: calibri;
        font-weight: bold;
        font-size: 14px;
        outline: none;
        margin: 0px 10px;
      }
      .cv-button {
        background-color: black;
        color: #05e1d6;
        border: none;
      }
      button:active {
        transform: scale(1.1);
      }
      .photo {
        height: 560px;
        position: absolute;
        bottom: 40px;
        left: 70%;
        transform: translateX(-70);
      }
      /* about section */
      .about-container {
        width: 80%;
        height: 330px;
        background-color: rgb(165, 239, 246);
        border-radius: 20px;
        box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.2);
        display: flex;
        margin: -7% auto 20px auto;
        position: relative;
        justify-content: space-evenly;
        align-items: center;
      }
      .about-container img {
        height: 300px;
      }
      .about-text {
        width: 750px;
      }
      .about-text p:nth-child(1) {
        color: #103e45;
        font-family: Gill Sans;
        font-weight: bold;
        font-size: 23px;
        line-height: 0px;
      }
      .about-text p:nth-child(2) {
        color: #147180;
        font-family: Segoe Scripta;
        font-weight: bold;
        font-size: 13px;
        line-height: 5px;
      }
      .about-text p:nth-child(3),
      .aboout-text p:nth-child(4) {
        color: #013138;
        font-family: calibri;
        font-size: 16px;
      }
      .about-text button {
        width: 120px;
        height: 40px;
        color: #05e1d6;
        outline: none;
        border: none;
        font-family: calibri;
        background-color: #103e45;
        font-weight: bold;
        margin: 0px 10px;
      }
      /* education section */
      .education {
        height: 600px;
        background-color: rgb(165, 239, 246);
        padding: 2% 10% 0px 10%;
      }
      .education-text p:nth-child(1) {
        font-family: calibri;
        color: rgb(16, 22, 22);
        font-weight: bold;
        font-size: 30px;
        line-height: 0px;
      }
      .education-text p:nth-child(2) {
        font-family: calibri;
        color: rgb(16, 22, 22);
        font-weight: bold;
        font-size: 15px;
        line-height: 5px;
      }
      .education-text p:nth-child(3) {
        font-family: calibri;
        color: rgb(16, 22, 22);
      }
      .education-text {
        width: 500px;
        margin: 50px 0px;
      }
      .box-1,
      .box-2,
      .box-3 {
        width: 300px;
        height: 320px;
        background-repeat: no-repeat;
        background-size: cover;
        box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.3);
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
      }
      .box-container {
        display: flex;
        justify-content: space-between;
      }
      .box-1 span,
      .box-2 span,
      .box-3 span {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        background-color: #147180;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: calibri;
        font-weight: bold;
      }
      .box-1 p:nth-child(2),
      .box-1 p:nth-child(2),
      .box-1 p:nth-child(2) {
        color: #121515;
        font-family: calibri;
        font-size: 23px;
        line-height: 0px;
      }
   
      
 ### OUTPUT :
 
 ![Screenshot (412)](https://github.com/JANANI0210/html-resume/assets/86832944/113bbcb2-f90c-4127-a6ef-8388f4c01e97)
 
### RESULT :
         Thus,  to create a web Portfolio/CV using HTML & CSS has been executed successfully.

            
            




