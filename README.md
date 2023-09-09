<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="stylesheet" href="mediaqueries.css" />
  </head>
  <body>
    <nav id="desktop-nav">
      <div class="logo">Sweta</div>
      <div>
        <ul class="nav-links">
          <li><a href="#about">About</a></li>
          <li><a href="#experience">Skills</a></li>
          <li><a href="./images/SWETA_CV.docx" target="_blank">Resume</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </div>
    </nav>
    <nav id="hamburger-nav">
      <div class="logo">Sweta</div>
      <div class="hamburger-menu">
        <div class="hamburger-icon" onclick="toggleMenu()">
          <span></span>
          <span></span>
          <span></span>
        </div>
        <div class="menu-links">
          <li><a href="#about" onclick="toggleMenu()">About</a></li>
          <li><a href="#resume" onclick="toggleMenu()">Resume</a></li>
          <li><a href="#projects" onclick="toggleMenu()">Projects</a></li>
          <li><a href="#contact" onclick="toggleMenu()">Contact</a></li>
        </div>
      </div>
    </nav>
    <section id="profile">
      <div class="section__pic-container">
        <img src="images/logo.png.png" class ="logo">/>
      </div>
      <div class="section__text">
        <p class="section__text__p1">Hello, I'm</p>
        <h1 class="title">Sweta</h1>
        <p class="section__text__p2">Web Developer</p>
        <div class="btn-container">
          <button
            class="btn btn-color-2"
            onclick="window.open('./images/sweta_resume.pdf')"
          >
            Download CV
          </button>
          <button class="btn btn-color-1" onclick="location.href='./#contact'">
            Contact Info
          </button>
        </div>
        <div id="socials-container">
          <img
            src="./images/download.htm"
            alt="My LinkedIn profile"
            class="icon"
            onclick="location.href='https://www.linkedin.com/in/sweta-sikarwar-578307287/'"
          />
          <img
            src="./images/github.png"
            alt="My Github profile"
            class="icon"
            onclick="location.href='https://github.com/Sser-06/Sser-06'"
          />
        </div>
      </div>
    </section>
    <section id="about">
      <p class="section__text__p1">Get To Know More</p>
      <h1 class="title">About Me</h1>
      <div class="section-container">
        <div class="section__pic-container">
          <img
            src="images\photo.png.jpg"
            alt="Profile picture"
            class="about-pic"
          />
        </div>
        <div class="about-details-container">
          <div class="about-containers">
            <div class="details-container">
              <img
                src="./images/experience.png"
                alt="Experience icon"
                class="icon"
              />
              <h3>Experience</h3>
              <p>Web Developer</p>
            </div>
            <div class="details-container">
              <img
                src="./images/education.png"
                alt="Education icon"
                class="icon"
              />
              <h3>Education</h3>
              <p>B.Tech CSE</p>
            </div>
          </div>
          <div class="text-container">
            <p>
              Hello! I'm Sweta, a passionate and driven individual currently pursuing a Bachelor's degree in Computer Science and Engineering from Amity University Madhya Pradesh. I am currently in my third year of studies, focusing on expanding my skills and knowledge in the world of technology. With a keen interest in web development and a knack for creating visually appealing and user-friendly interfaces, I label myself as a Web developer.
            </p>
          </div>
        </div>
      </div>
      <img
        src="./images/Arrow.jpg.png"
        alt="Arrow icon"
        class="icon arrow"
        onclick="location.href='./#experience'"
      />
    </section>
    <section id="experience">
      <p class="section__text__p1">Explore My</p>
      <h1 class="title">Skills</h1>
      <div class="experience-details-container">
        <div class="about-containers">
          <div class="details-container">
            <h2 class="experience-sub-title"> Development</h2>
            <div class="article-container">
              <article>
                <img
                  src="./images/experience.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>HTML</h3>
                  <p>Experienced</p>
                </div>
              </article>
              <article>
                <img
                  src="./images/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>CSS</h3>
                  <p>Experienced</p>
                </div>
              </article>

              <article>
                <img
                  src="./images/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>JavaScript</h3>
                  <p>Basic</p>
                </div>
              </article>

            </div>
          </div>
          <div class="details-container">
            <h2 class="experience-sub-title">Web Development</h2>
            <div class="article-container">
              <article>
                <img
                  src="./images/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>MongoDB</h3>
                  <p>Basic</p>
                </div>
              </article>
              <article>
                <img
                  src="./images/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Node JS</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="./images/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Express JS</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="./images/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Git</h3>
                  <p>Intermediate</p>
                </div>
              </article>
            </div>
          </div>
        </div>
      </div>
      <img
        src="./images/Arrow.jpg.png"
        alt="Arrow icon"
        class="icon arrow"
        onclick="location.href='./#projects'"
      />
    </section>
    <section id="projects">
      <p class="section__text__p1">Browse My Recent</p>
      <h1 class="title">Projects</h1>
      <div class="experience-details-container">
        <div class="about-containers">
          <div class="details-container color-container">
            <h2 class="experience-sub-title project-title">Project One</h2>

            <h3>Fork</h3>
            <p>A basic login page</p>
            <p>Language used :- HTML & CSS </p> <br>
            <div class="article-container">
              <img
                src="./images/project-1.png"
                alt="Project 1"
                class="project-img"
              />
            </div>
           

          </div>
          
            
              
              <div class="article-container">
                <div class="details-container color-container"></div>
                <h2 class="experience-sub-title project-title">Project Two</h2>
          <h3>To Do List</h3>
          <p>A to do list adding or deleting list content</p>
          <p>Language used :- HTML, CSS & JAVASCRIPT</p> <br>

              <img
                src="./images/project-2t.png"
                alt="Project 2"
                class="project-img"
              />
            </div>
            
          </div>
          <div class="details-container color-container">
            <div class="article-container">
              <h2 class="experience-sub-title project-title">Project Three</h2>

          <h3>Countdown Clock</h3>
          <p>A Countdown Clock page</p>
          <p>Language used :- HTML, CSS & JAVASCRIPT</p> <br>

              <img
                src="./images/project-3.png"
                alt="Project 3"
                class="project-img"
              />
            </div>
            
          </div>
        </div>
      </div>
      <img
        src="./images/Arrow.jpg.png"
        alt="Arrow icon"
        class="icon arrow"
        onclick="location.href='./#projects'"
      />
    </section>
    <section id="contact">
      <p class="section__text__p1">Get in Touch</p>
      <h1 class="title">Contact Me</h1>
      <div class="contact-info-upper-container">
        <div class="contact-info-container">
          <img
            src="./images/email.jpg"
            alt="Email icon"
            class="icon contact-icon email-icon"
          />
          <p><a href="mailto:swetasikarwar035@gmail.com">swetasikarwar035@gmail.com</a></p>
        </div>
        <div class="contact-info-container">
          <img
            src="./images/linkedin.jpg"
            alt="LinkedIn icon"
            class="icon contact-icon"
          />
          <p><a href="https://www.linkedin.com/in/sweta-sikarwar-578307287/">LinkedIn</a></p>
        </div>
      </div>
    </section>
    <footer>
      <nav>
        <div class="nav-links-container">
          <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </div>
      </nav>
      <p>Copyright &#169; 2023 Sweta. All Rights Reserved.</p>
    </footer>
    <script src="script.js"></script>
  </body>
</html># task1-personal-portfolio-page
