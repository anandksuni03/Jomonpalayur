<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8"><!-- for editing in browser -->
    <meta http-equiv="X-UA-compatible" content="IE-edge"> <!-- to improve the performance to the website -->
    <meta name="viewport" content="width=device-width, intial-scale=1.0"> <!-- to fit into differnt devices -->
    <title>personal portfolio</title>
    <script defer src="script.js"></script> 
    <link rel="stylesheet" href="sytle.css">
    <script src="https://kit.fontawesome.com/867b952505.js" crossorigin="anonymous"></script>
</head>   
<body>
<div id="header">
     <div class="container">
        <nav>
            <img src="images/aks logo.png" class="logo">
            <ul>
                <li><a href="#header">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
                
            
            </ul>
        
        </nav>
        <div class="header-text">
            <p>Tech Enthusistant</p>
            <h1> HI I am <span><b>Anand</b></span> <br>K Suni</h1>
        </div>
     </div>
</div>
<!----------about------------>
<div id="about">
    <div class="container"></div>
       <div class="row">
           <div class="about-col-1">
            <img src="images/user.png">
           </div>
           <div class="about-col-2">
               <h1 class="sub-tiltle">About Me</h1>
               <p>Today, we commit to this next great leap into the cosmos because we're human, and our nature is to fly. 
                ~Stephen Hawking 
 
  Prepare to be captivated! Unveil the remarkable advancements in lighting technology and unlock the secrets behind the enchanting impact of BLUE light on our lives. 💎🛡️
 
 The IEEE Education Society Kerala Chapter in Collaboration with the IEEE Photonics Society Kerala chapter is excited to announce our Webinar on  The Evolution of Lights and the Engineering Brilliance of Blue Light🔌💡. 
 
 Speaker: Mr Abhinav R. 
 Junior Research Fellow, IIT Palakkad
 STEM & HAC Lead, IEEE Education Society Kerala Chapter 
 Secretary, IEEE SIGHT Group  Kerala 
 Lead, IEEE Humanitarian  Working Group IEEE YP Kerala.
               </p>
               <div class="tab-titles">
                <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                <p class="tab-links" onclick="opentab('experience')">experience</p>
                <p class="tab-links" onclick="opentab('education')">education</p>

               </div>
               <div class="tab-contents active-tab " id="skills">
                <ul>
                    <li><span>UI/UX</span><br>Designing App intrefaces</li>
                    <li><span>web development</span><br>Designing web intrefaces</li>
                    <li><span>app development</span><br>Designing App for android</li>
                </ul>
               </div>
               <div class="tab-contents" id="experience">
                <ul>
                    <li><span>me</span><br>aks</li>
                    <li><span>hello</span><br>Designing web intrefacesgood</li>
                    <li><span>hi</span><br>Designing App for android wdn</li>
                </ul>
               </div>
               <div class="tab-contents" id="education">
                <ul>
                    <li><span>his</span><br>Designieafng App intrefaces</li>
                    <li><span>hert</span><br>Designinefag web intrefaces</li>
                    <li><span>bye</span><br>Designinesfg App for android</li>
                </ul>
               </div>

           </div>


       </div>
</div>

<!-----services-------->

<div class="services">

    <div class="container">
        <h1 class="sub-tiltle">my services</h1>
        <div class="services-list">
            <div>
                <i class="fa-solid fa-code"></i>
                <h2>Web design</h2>
                <p>adyauyfwf3ig
                    3uqgcuru
                </p>
                <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-sharp fa-solid fa-crop-simple"></i>
                <h2>app design</h2>
                <p>adyauyfwf3ig
                    3uqgcuru
                </p>
                <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-brands fa-android"></i>
                <h2>ps design</h2>
                <p>adyauyfwf3ig
                    3uqgcuru
                </p>
                <a href="#">learn more</a>
            </div>
        </div>

    </div>
</div>
<!-----portfolio------->
<div id="portfolio">
    <div class="container">
        <h1 class="sub-tiltle">my work</h1>
        <div class="work-list">
            <div class="work">
                <img src="images/work-1.png">
                <div class="layer">
                    <h3>social media apps</h3>
                    <p>uaufhoaeifhoaieh
                        aefhofeiahfjalf
                    </p>
                    <a href="#"><i class="fa-solid fa-link"></i></a> <!--icon-->
                </div>
            </div>
            <div class="work">
                <img src="images/work-2.png">
                <div class="layer">
                    <h3>social </h3>
                    <p>uaufhoaeifhoaieh
                        aefhofeiahfjadeaaflf
                    </p>
                    <a href="#"><i class="fa-solid fa-link"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-3.png">
                <div class="layer">
                    <h3>social media </h3>
                    <p>uaufhoaeifhoaieh
                        aefhofeiahfcssdcf
                    </p>
                    <a href="#"><i class="fa-solid fa-link"></i></a>
                </div>
            </div>

        </div>
        <a href="#" class="btn">See more</a>

    </div>
</div>
<!----------contact-------------->

<div id="contact">
    <div class="container"> <!---for width adjust according to the screen-->
       <div class="row">
        <div class="contact-left">
            <h1 class="subtitle">contact me</h1> <!-- to change the font size, color, and other properties of the subtitle heading.-->
            <p><i class="fa-solid fa-paper-plane"></i>contact@example.com</p>
            <p><i class="fa-solid fa-phone"></i>ph 0123456789</p>
            <div class="social-media-icons">
                <a href=""><i class="fa-brands fa-instagram"></i></a>
                <a href=""><i class="fa-brands fa-instagram"></i></a>
                <a href=""><i class="fa-brands fa-instagram"></i></a>
                <a href=""><i class="fa-brands fa-instagram"></i></a>
            </div>
            <a href="images/my-cv.pdf" download class="btn btn2">download cv</a>
        </div>
        <div class="contact-right">
            <form>
                <input type="text" name="name" placeholder="your name" required>
                <input type="email" email="email" placeholder="your email" required>
                <textarea name="message" rows="6" placeholder="your message"></textarea>
                <button type="submit " class="btn btn2">submit</button>
            </form> 
            

        </div>

       </div>
        
    </div>
    <div class="copyright">
        <p>copyright @  Anand.</p>
    </div>
</div>


<script> 

     var tablinks = document.getElementsByClassName("tab-links");
     var tabcontents = document.getElementsByClassName("tab-contents");

function opentab(tabname){
    for(tablink of tablinks){
        tablink.classList.remove("active-link");/*it will active class*/
    }
    for(tabcontent of tabcontents){
        tabcontent.classList.remove("active-tab");/*it will active class*/
    }
    event.currentTarget.classList.add("active-link")
    document.getElementById(tabname).classList.add("active-tab") /* to get data of specific tab*/

}


</script>
</body>

    
</html>
