![about-pic](https://github.com/user-attachments/assets/47cfcd67-6d45-4f2f-87ea-6a9ac428fc3b)<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel = "stylesheet" href="style.css" />
    <link rel = "stylesheet" href="mediaqueries.css" />


</head>
<body>
    <nav id="desktop-nav"> 
        <div class="logo"> John Laurence Mendoza </div>
        <div> 
            <ul class="nav-links"> 
                <li><a href="#about"> About </a></li>
                <li><a href="#field"> Field of Interest </a></li>
                <li><a href="#sdg"> SDG </a></li>
                <li><a href="#affiliations"> Affiliations </a></li>
                <li><a href="#contacts"> Contacts </a></li>
            </ul>
        </div>
    </nav>

    <nav id="hamburger-nav">
        <div class="logo"> John Laurence </div>
        <div class="hamburger-menu"> 
        <div class="hamburger-icon" onclick= "toggleMenu()"> 
            <span></span>
            <span></span>
            <span></span>
        </div>
        <div class="menu-links"> 
                <li><a href="#about" onclick= "toggleMenu()"> About </a></li>
                <li><a href="experience" onclick= "toggleMenu()"> Experiences </a></li>
                <li><a href="#sdg" onclick= "toggleMenu()"> SDG </a></li>
                <li><a href="#sdg" onclick= "toggleMenu()" > Projects </a></li>
                <li><a href="#contacts" onclick= "toggleMenu()" > Contacts </a></li>


        
            </div>
        </div>
    </nav>
    <section id="profile">
        <div class = "section__pic-container"> 
            <img src="./assets/ID .png" alt="John Laurence Profile Picture
            ">
        </div>
        <div class="section__text">
            <p class="section__text__p1"> Hello, I'm  </p>
            <h1 class="title"> John Laurence </h1>
            <p class="section__text__p2"> Software Engineer </p>
            <div class="btn-container">
                <button class="btn btn-color-2" onclick="window.open('./assets/Resume-CV.pdf')"> 
                    Download CV </button>

                <button class="btn btn-color-1" onclick="location.href='#contacts'">
                        Contact Info </button>
            </div>
            <div id="social-container">
                <img src="./assets/linkedin.png" alt="My LinkedIn profile" class="icon2"
                onclick="location.href='https://www.linkedin.com/in/john-laurence-mendoza-3b08bb273/edit/forms/intro/new/?profileFormEntryPoint=PROFILE_SECTION'">

                <img src="./assets/github.png" alt="My Github profile" class="icon2"
                onclick="location.href='https://github.com/laur0819codes'">
            </div>
        </div>
    </section>

    <section id="about"> 
        <p class="section__text__p1"> Get to Know More </p>
        <h1 class="title"> About Me </h1>
        <div class="section-container">
            <div class="section__pic-container"> 
                <img src="./assets/profile2.jpeg" alt="Profile Picture" class="about-pic"/>
            </div>
            <div class="about-details-containers"> 
                <div class="about-containers"> 
                    <div class="details-container">
                        <img src="./assets/experience.png" alt="experience icon" class="icon"/>
                        <h3> Experiences </h3>
                        <p> 1 year <br> Front End Development</p>

                    </div>
                    <div class="details-container">
                        <img src="./assets/education.png" alt="education icon" class="icon"/>
                        <h3> Education </h3>
                        <p> Science, Technology Engineering and Mathematics <br> Bachelors of Science in Computer Science</p>

                    </div>
                </div>
                    <div class="text-container">
                        <p> <b> Hi! I'm Laurence</b>, an aspiring software engineer and enthusiastic leader with a vision for a brighter future. I’m fueled by a passion for innovation, teamwork, and making meaningful contributions to the world around me. My dream is to achieve success while empowering others to reach their full potential and serving our country with integrity and dedication. I believe in the power of giving back to the community, creating opportunities for growth, and inspiring positive change. With a heart full of ambition and a drive to lead with purpose, I’m excited to embrace every challenge and turn dreams into reality! </p>
                    </div>
            </div>
        </div> 
        <img src="./assets/arrow.png" alt="arow icon" class="icon arrow" onclick="location.href='#field'"/>
    </section>

    <section id="field">
        <p class="section__text__p1"> Explore My </p>
        <h1 class="title"> Field of Interest </h1>
        <div class="details-container">
        <div class="about-containers">
            <div class="about-details-containers">
                <h2 class="field-sub-title"> Interests </h2>
                <div class="article-container"> 
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Computer Science</h3>
                            <p> Solving problems with technology.</p>
                        </div>


                    </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Photography</h3>
                            <p> Capturing moments creatively</p>
                        </div>


                    </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Public Speaking</h3>
                            <p> Engaging audiences confidently</p>
                        </div>


                    </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Fashion Arts</h3>
                            <p> Expressing creativity through style</p>
                        </div>


                    </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Cosmology</h3>
                            <p> Exploring the universe's mysteries</p>
                        </div>


                    </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Music</h3>
                            <p> Listening to Kpop, POP, and OPM</p>
                        </div>


                    </article>
                </div>

            </div>
            <div class="about-details-containers">
                <h2 class="field-sub-title"> Talents and Hobbies </h2>
                <div class="article-container"> 
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Dancing</h3>
                            <p> Expressing through movement</p>
                        </div>


                    </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Singing</h3>
                            <p> Not a great singer but Kareoke is Life!</p>
                        </div>


                    </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Hosting</h3>
                            <p>Leading events with charm </p>
                        </div>


                    </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Travelling</h3>
                            <p> Exploring new places and cultures</p>
                        </div>


                    </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Leadership</h3>
                            <p> Inspiring and guiding teams </p>
                        </div>


                    </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Technology</h3>
                            <p> Exploring innovative solutions</p>
                        </div>


                    </article>
                </div>

            </div>
        </div>
        </div>

        <img src="./assets/arrow.png" alt="Arrow icon" class="icon arrow" onclick="location.href='#sdg'"/>

       

        
    </section>

<section id="sdg">
        <p class="sdg-section__text__p1">Advocating for Sustainable Development Goals</p>
        <h1 class="title-sdg">My Advocacies</h1>
        <div class="experience-details-container">
          <div class="about-containers">
      
            <!-- No Poverty Advocacy -->
            <div class="details-container color-container">
              <div class="article-container">
                <img
                  src="./assets/Sustainable_Development_Goal_01NoPoverty.svg.png"
                  alt="No Poverty Advocacy"
                  class="project-img"
                />
              </div>
              <h2 class="experience-sub-title project-title">No Poverty</h2>
              <p class="project-description">
                Committed to eradicating poverty and ensuring economic opportunities for all.
              </p>
              <div class="btn-container">
                <button
                  class="btn btn-color-2 project-btn"
                  onclick="location.href='https://sdgs.un.org/goals/goal1'"
                >
                  Learn More
                </button>
              </div>
            </div>
      
            <!-- Equality Education -->
            <div class="details-container color-container">
              <div class="article-container">
                <img
                  src="./assets/E_SDG-goals_icons-individual-rgb-04-1024x1024.png"
                  alt="Quality Education"
                  class="project-img"
                />
              </div>
              <h2 class="experience-sub-title project-title">Quality Education</h2>
              <p class="project-description">
                Ensure inclusive and equitable quality education and promote lifelong learning opportunities for all
              </p>
              <div class="btn-container">
                <button
                  class="btn btn-color-2 project-btn"
                  onclick="location.href='https://sdgs.un.org/goals/goal4'"
                >
                  Learn More
                </button>
              </div>
            </div>

            <!-- Gender Equality Advocacy -->
            <div class="details-container color-container">
                <div class="article-container">
                  <img
                    src="./assets/E_SDG-goals_icons-individual-rgb-05-1024x1024.png"
                    alt="Gender Equality Advocacy"
                    class="project-img"
                  />
                </div>
                <h2 class="experience-sub-title project-title">Gender Equality</h2>
                <p class="project-description">
                  Promoting equal rights and opportunities regardless of gender.
                </p>
                <div class="btn-container">
                  <button
                    class="btn btn-color-2 project-btn"
                    onclick="location.href='https://sdgs.un.org/goals/goal5'"
                  >
                    Learn More
                  </button>
                </div>
              </div>
      
          </div>
        </div>
        <img
          src="./assets/arrow.png"
          alt="Arrow icon"
          class="icon arrow"
          onclick="location.href='#community-service'"
        />
    
    <section> <section id="community-service">
        <p class="cs-section__text__p1">Giving Back to the Community</p>
        <h1 class="cs-title">Community Service Projects</h1>
      
        <div class="service-container">
          <!-- School Donation Program -->
          <div class="service-program">
            <h2 class="service-title">School Donation Program</h2>
            <p class="service-description">
                During my senior high school years, I was a member of the Supreme Student Government (SSG). As part of our school’s annual Love Community Action Program, we organized a school donation drive, contributing to meaningful community outreach and fostering a spirit of generosity and compassion among students.
            </p>
            <div class="service-images">
              <img src="./assets/school1.jpeg" alt="School Donation 1" class="service-img" />
              <img src="./assets/school2.jpeg" alt="School Donation 2" class="service-img" />
              <img src="./assets/school3.jpeg" alt="School Donation 3" class="service-img" />
              <img src="./assets/school4.jpeg" alt="School Donation 4" class="service-img" />
            </div>
          </div>
      
          <!-- Coastal Clean Up Program -->
          <div class="service-program">
            <h2 class="service-title2">Coastal Clean Up Program</h2>
            <p class="service-description">
              An initiative focused on cleaning our coasts to promote environmental sustainability and marine life preservation.
            </p>
            <div class="service-images">
              <img src="./assets/eco-isko1.jpeg" alt="Coastal Cleanup 1" class="service-img" />
              <img src="./assets/eco-isko2.jpeg" alt="Coastal Cleanup 2" class="service-img" />
              <img src="./assets/eco-isko3.jpeg" alt="Coastal Cleanup 3" class="service-img" />
              <img src="./assets/eco-isko4.jpeg" alt="Coastal Cleanup 4" class="service-img" />
            </div>
          </div>
        </div>

        <img
          src="./assets/arrow.png"
          alt="Arrow icon"
          class="icon arrow"
          onclick="location.href='#affiliations'"
        />
        
      </section> 
      
      </section>

               
            
        
    </section>

      <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Affiliations</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <section id="affiliations">
    <div class="container">
      <h1 class="section-title">My Affiliations</h1>
      <p class="section-description">Here are the organizations I’m proud to be a part of:</p>
      <div class="affiliations-grid">
        <div class="affiliation-card">
          <h3 class="affiliation-name">Department of Science and Technology</h3>
          <p class="position">SEI - Scholar</p>
        </div>
        <div class="affiliation-card">
          <h3 class="affiliation-name">ACCESSS - Association of Computer Science Students</h3>
          <p class="position">First Year Representative</p>
        </div>
        <div class="affiliation-card">
          <h3 class="affiliation-name">College of Informatics and Computing Sciences Student Council</h3>
          <p class="position">First Year Representative</p>
        </div>
        <div class="affiliation-card">
          <h3 class="affiliation-name">Association of DOST-SEI Scholars - Alangilan Campus</h3>
          <p class="position">Marketing and Sponsorship Assistant Head</p>
        </div>
        <div class="affiliation-card">
          <h3 class="affiliation-name">Junior Philippine Computer Society BatStateU Alangilan Chapter</h3>
          <p class="position">Member</p>
        </div>
        <div class="affiliation-card">
          <h3 class="affiliation-name">CICS Dance Crew</h3>
          <p class="position">Member</p>
        </div>
      </div>
    </div>

    <img
          src="./assets/arrow.png"
          alt="Arrow icon"
          class="icon arrow"
          onclick="location.href='#contacts'"
        />


  </section>
</body>
</html>


<section id="contacts">
  <p class="csection__text__p1">Get in Touch</p>
  <h1 class="ctitle">Contact Me</h1>
  <div class="contact-info-upper-container">
    <div class="contact-info-container">
      <img
        src="./assets/email.png"
        alt="Email icon"
        class="icon contact-icon email-icon"
      />
      <p><a href="mailto:24-05554@g.batstate-u.edu.ph"> 24-05554@g.batstate-u.edu.ph </a></p>
    </div>
    <div class="contact-info-container">
      <img
        src="./assets/linkedin.png"
        alt="LinkedIn icon"
        class="icon contact-icon"
      />
      <p><a href="https://www.linkedin.com">LinkedIn</a></p>
    </div>
  </div>
</section>
      <footer>
        <nav>
          <div class="nav-links-container">
            <ul class="nav-links"> 
              <li><a href="#about"> About </a></li>
              <li><a href="#field"> Field of Interest </a></li>
              <li><a href="#sdg"> SDG </a></li>
              <li><a href="#affiliations"> Affiliations </a></li>
              <li><a href="#contacts"> Contacts </a></li>
          </ul>
          </div>
        </nav>
        <p> Copyright &#169; 2024 John Laurence. All Rights Reserved </p>
      </footer>
    <script src="script.js"></script>
  </body>
</html>


/* GENERAL */ 


@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap');


* { 
    margin: 0;
    padding: 0;

}

body {
    font-family: "Poppins", sans-serif;

}

html {
    scroll-behavior: smooth;
}

p {
    color:rgb(85,85,85);   
}

/*transition */

a, .btn {
   transition: all 300ms ease;
}

/* Desktop Nav */

nav, .nav-links {
    display: flex;
}

nav {
    justify-content: space-around;
    align-items: center;
    height: 17vh;
}

.nav-links {
    gap: 2rem;
    list-style: none;
    font-style: 1.5rem;
}

a{
    color: black;
    text-decoration: none;
    text-decoration-color: white;
}

a:hover {
    color: gray;
    text-decoration: underline;
    text-underline-offset: 1rem;
    text-decoration-color: rgb (181, 181, 181);

}

.logo {
    font-size: 2rem;
    
}

.logo:hover {
    cursor: default;
}

/* HAMBUGER MENU */

#hamburger-nav {
    display: none;
}

.hamburger-menu {
    position: relative;
    display: inline-block;
}

.hamburger-icon {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 24px;
    width: 30px;
    cursor: pointer;

}

.hamburger-icon span {
    width: 100%;
    height: 2px;
    background-color: black;
    transition: all 0.3 ease-in-out;
}

.menu-links {
    position: absolute;
    top: 100%;
    right: 0%;
    background-color: white;
    width: fit-content;
    max-height: 0;
    overflow: hidden;
    transition: all;

}

.menu-links a {
    display: block;
    padding: 10px;
    text-align: center;
    font-size: 1.5rem;
    color: black;
    text-decoration: none;
    transition: all 0.3 ease-in-out;
}

.menu-links li {
    list-style: none;
}

.menu-links.open {
    max-height: 300px;
}

.hamburger-icon.open span:first-child {
    transform: rotate(45deg) translate(10px, 5px);
}
.hamburger-icon.open span:nth-child(2) {
    opacity: 0;
}
.hamburger-icon.open span:last-child {
    transform: rotate(-45deg) translate(10px, -5px);
}

.hamburger-icon span:first-child {
    transform: none;
}
.hamburger-icon span:first-child {
    opacity: 1;
}
.hamburger-icon span:first-child {
    transform: none;
}

section {
    padding-top: 4vh;
    height: 96vh;
    margin: 0 10rem;
    box-sizing: border-box;
    min-height: fit-content;
  }
  
  .section-container {
    display: flex;
  }
  
  /* PROFILE SECTION */
  
  #profile {
    display: flex;
    justify-content: center;
    gap: 5rem;
    height: 80vh;
  }
  
  .section__pic-container {
    display: flex;
    height: 400px;
    width: 400px;
    margin: auto 0;
  }
  
  .section__text {
    align-self: center;
    text-align: center;
  }
  
  .section__text p {
    font-weight: 600;
  }
  
  .section__text__p1 {
    text-align: center;
  }
  
  .section__text__p2 {
    font-size: 1.75rem;
    margin-bottom: 1rem;
  }
  
  .title {
    font-size: 3rem;
    text-align: center;
  }
  
  #socials-container {
    display: flex;
    justify-content: center;
    margin-top: 1rem;
    gap: 1rem;
  }

/* ICONS */

.icon {
    cursor: pointer;
    height: 2rem;
    
}

.icon2 {
  cursor: pointer;
  height: 2rem;
  margin-top: 1rem;
}

/*buttons*/

.btn-container {
    display: flex;
    justify-content: center;
    gap: 1rem;
}

.btn {
    font-weight: 600;
    transition: all 300ms ease;
    padding: 1rem;
    width: 8rem;
    border-radius: 2rem;
}

.btn-color-1, 
.btn-color-2 {
    border: rgb(53, 53, 53) 0.1rem solid;
    
}

.btn-color-1:hover, 
.btn-color-2:hover {
    cursor: pointer;
}

.btn-color-1:hover, 
.btn-color-2:hover {
    background: rgb(53
    , 53, 53);
    color: white;

}

.btn-color-1:hover {
    background: rgb(0, 0, 0);

}

.btn-color-2 {
    background: none;
}

.btn-color-2:hover {
    border: rgb(255, 255, 255) 0.1rem solid;
}

.btn-container {
    gap: 1rem;
}


/*about section*/

#about {
    position: relative;
}

.about-containers {
    gap: 2rem;
    margin-bottom: 2rem;
    margin-top: 2rem;

}

.about-details-container {
    justify-content: center;
    flex-direction: column;
}

.about-containers, .about-details-container {
    display: flex;

}

.about-pic {
    border-radius: 2rem;
}

.icon arrow {
    position: absolute;
    right: -5rem;
    bottom: 2.5rem;
}

.details-container {
    padding: 1.5rem;
    flex: 1;
    background-color: white;
    border-radius: 2rem;
    border: rgb(53, 53, 53) 0.1rem solid;
    border-color: rgb(163, 163,163);
    text-align: center;
}

.section-container {
    gap: 4rem;
    height: 80%;
}

.section__pic-container {
    height: 400px;
    width: 400px;
    margin: auto 0;
}

/* Field of Interest*/

#field {
    position: relative;
}

.field-sub-title {
    color: rgb(85,85, 85);
    font-weight: 800;
    font-size: 1.75rem;
    margin-bottom: 2rem;
}

.field-details-container {
    display: flex;
    justify-content: center;
    flex-direction: column;

}

.article-container {
    display: flex;
    text-align: initial;
    flex-wrap: wrap;
    flex-direction: row;
    gap: 2.5rem;
    justify-content: space-around;
}

article {
    display: flex;
    width: 10rem;
    justify-content: space-around;
    gap: 0.5rem;
}

article.icon {
    cursor: default;
}

/*SGD*/

#sdg {
    position: relative;
    padding: 2rem;
    background-color: #f9f9f9;
  }
  
  .sdg-section__text__p1 {
    font-size: 1.5rem;
    color: #555;
    margin-bottom: 0.5rem;
    text-align: center;
  }
  
  .title-sdg {
    text-align: center;
    font-size: 2rem;
    color: #222;
    margin-bottom: 1rem;
  }
  
  .experience-details-container {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    justify-content: center;
  }
  
  .color-container {
    border: 1px solid rgb(163, 163, 163);
    background: rgb(250, 250, 250);
    border-radius: 1rem;
    padding: 1.5rem;
    width: 300px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
  }
  
  .color-container:hover {
    transform: translateY(-10px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
  }
  
  .project-img {
    border-radius: 1rem;
    width: 100%;
    height: auto;
    margin-bottom: 1rem;
  }
  
  .project-title {
    font-size: 1.8rem;
    margin: 1rem 0;
    color: #222;
  }
  
  .project-description {
    font-size: 1rem;
    color: #555;
    margin-bottom: 1.5rem;
  }
  
  .project-btn {
    color: #fff;
    background-color: rgb(53, 53, 53);
    border: none;
    border-radius: 0.5rem;
    padding: 0.5rem 1rem;
    cursor: pointer;
    font-size: 1rem;
    transition: background-color 0.3s;
  }
  
  .project-btn:hover {
    background-color: gray;
  }
  
  .icon.arrow {
    display: block;
    margin: 2rem auto 0;
    width: 50px;
    height: auto;
    cursor: pointer;
    transition: transform 0.3s;
  }
  
  .icon.arrow:hover {
    transform: translateY(-5px);
  }


  #community-service {
    padding: 3rem 0;
    background-color: #f9f9f9;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  
  .cs-title {
    font-size: 2.5rem;
    color: #222;
    margin-bottom: 2rem;
  }
  
  .cs-section__text__p1 {
    font-size: 1.2rem;
    color: #555;
    margin-bottom: 1rem;
    max-width: 800px;
  }

  .service-title {
    margin-top: 1rem;
  }

  .service-description {
    margin-bottom: 2rem;
  }

  .service-title2 {
    margin-top: 2rem;
  }
  
  
  .service-gallery {
    display: grid;
    grid-template-columns: repeat(4, 1fr); 
    gap: 1rem;
    width: 100%; 
    padding: 0 3rem; 
    margin-top: 2rem;
  }
  
  .service-img {
    width: 100%;
    height: auto;
    border-radius: 0.8rem;
    object-fit: cover;
    box-shadow: 0 6px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  
  .service-img:hover {
    transform: scale(1.05); 
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
  }
  
  @media screen and (max-width: 1024px) {
    .service-gallery {
      grid-template-columns: repeat(2, 1fr); 
    }
  }
  
  @media screen and (max-width: 768px) {
    .service-gallery {
      grid-template-columns: 1fr; 
    }
  }


/* Affiliations Section */
#affiliations {
  padding: 40px 20px;
  background-color: #ffffff;
  border: 2px solid #ddd; 
  border-radius: 10px;    
  max-width: 900px;       
  margin: 40px auto;      
}

.container {
  text-align: center;
}

.section-title {
  font-size: 2rem;
  margin-bottom: 10px;
  color: #333333;
}

.section-description {
  font-size: 1rem;
  color: #555555;
  margin-bottom: 30px;
}

.affiliations-grid {
  display: grid;
  grid-template-columns: 1fr; 
  gap: 20px;
  justify-items: center; 
}

.affiliation-card {
  background-color: #f9f9f9;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
  width: 80%; 
  max-width: 600px; 
  transition: transform 0.2s ease-in-out;
}

.affiliation-card:hover {
  transform: translateY(-5px);
}

.affiliation-name {
  font-size: 1.2rem;
  color: #222222;
  margin-bottom: 10px;
}

.position {
  font-size: 1rem;
  color: #666666;
}

/* Responsive Design */
@media (max-width: 768px) {
  .section-title {
    font-size: 1.5rem;
  }
  .section-description {
    font-size: 0.9rem;
  }
  .affiliation-card {
    width: 90%; 
  }
}

/* Contacts */

#contact {
  display: flex;
  justify-content: center;
  flex-direction: column;
  height: 70vh;
}

.csection__text {
  align-self: center;
  text-align: center;
  margin-top: 5rem;
  margin-bottom: 1rem;

}

.csection__text p {
  font-weight: 600;
  margin-bottom: 2rem;
}

.csection__text__p1 {
  text-align: center;
  margin-top: 5rem;
}

.csection__text__p2 {
  font-size: 1.75rem;
}

.ctitle {
  font-size: 3rem;
  text-align: center;
}

.contact-info-upper-container {
  display: flex;
  justify-content: center;
  border-radius: 2rem;
  border: rgb(53, 53, 53) 0.1rem solid;
  border-color: rgb(163, 163, 163);
  background: (250, 250, 250);
  margin-top: 2rem;
  padding: 0.5rem;
}

.contact-info-container {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  margin: 1rem;
}

.contact-info-container p {
  font-size: larger;
}

.contact-icon {
  cursor: default;
}

.email-icon {
  height: 2.5rem;
}
![Sustainable_Development_Goal_01NoPoverty svg](https://github.com/user-attachments/assets/2c836128-a291-4954-a9f0-4c08472d0e3f)
![school4](https://github.com/user-attachments/assets/3f52d3d1-5304-428e-9653-ecb3d277f30d)
![school3](https://github.com/user-attachments/assets/05979b99-b70f-4921-ad0a-b6d85979ddd8)
![school2](https://github.com/user-attachments/assets/e2265cce-cb2c-402e-adcc-dc2f7628bf92)
![school1](https://github.com/user-attachments/assets/652f0a16-3f27-4f91-a60c-242495101272)
![project-3](https://github.com/user-attachments/assets/b19adccf-444a-4962-80e4-bd6876efbfe2)
![project-2](https://github.com/user-attachments/assets/65d2a051-2d2b-47a6-9c2c-1bf783094688)
![project-1](https://github.com/user-attachments/assets/b56f7921-3988-4604-824a-ba74ad5c61b1)
![profile-pic-2](https://github.com/user-attachments/assets/74e979cc-bda8-461f-b1b6-7f6aac0fc1f0)
![profile-pic](https://github.com/user-attachments/assets/89c6166e-df87-4f6f-a2ee-8f4e8ba34e3a)
![profile2](https://github.com/user-attachments/assets/c6f6716a-d1e6-453d-b1a9-6130d180d1bb)
![linkedin](https://github.com/user-attachments/assets/f3d9f9f6-6076-47f3-b6d0-fbf64c9047c5)
![ID ](https://github.com/user-attachments/assets/d66b0468-4111-44e3-9c17-c0c4b79dd9f5)
![goal4](https://github.com/user-attachments/assets/16b4e3bf-02c0-48cd-b703-cf55c67fb105)
![github](https://github.com/user-attachments/assets/c1cdc1cf-844b-4cd1-b62a-e44bd66a54c3)
![experience](https://github.com/user-attachments/assets/d31e214f-736e-44a7-a6b6-37328de34603)
![email](https://github.com/user-attachments/assets/43757e87-c1bd-4b69-b08f-a81e0e5e036c)
![education](https://github.com/user-attachments/assets/0c7fb0e1-07c6-45c1-9927-b041399c83fe)
![eco-isko4](https://github.com/user-attachments/assets/5c91eb3a-eb6b-48e2-8f84-128b5141f7cc)
![eco-isko3](https://github.com/user-attachments/assets/e726ecd7-e9de-4d3e-a5e2-59b9517d557d)
![eco-isko2](https://github.com/user-attachments/assets/78af9aee-e95e-415e-9cad-b310b8e7a1ba)
![eco-isko1](https://github.com/user-attachments/assets/21a7e10e-980c-41f9-9e7d-20b855dee4da)
![E_SDG-goals_icons-individual-rgb-12-1024x1024](https://github.com/user-attachments/assets/39a65116-2f2c-4393-b534-c2ddbda375cb)
![E_SDG-goals_icons-individual-rgb-05-1024x1024](https://github.com/user-attachments/assets/0e607788-ee7e-4590-a8c0-0e98a9d7c90d)
![E_SDG-goals_icons-individual-rgb-04-1024x1024](https://github.com/user-attachments/assets/f07deab3-12ca-4602-b7fc-7beb43111f12)
![checkmark](https://github.com/user-attachments/assets/d932d589-5fe8-48aa-83ec-5277a8405936)
![arrow](https://github.com/user-attachments/assets/ef7db9c5-9609-4ae0-9391-104c42ab04c4)

/* Footer */

footer {
  height: 26vh;
  margin: 0 1rem;
}

footer p{
  text-align: center;
}

