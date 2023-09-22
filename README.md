<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Resume</title> 
 </head> 
 <body>  
   <style>
     * {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
:root {
  --primary-color: #ff7613;
  --text-color: #727171;
}
html {
  font-size: 10px;
}
body {
  font-family: Inter, sans-serif;
  background-color: black;
  color: white;
}

/* common styles */
img {
  width: 100%;
}
a {
  text-decoration: none;
  color: white;
}
.description {
  margin-top: 1rem;
  font-size: 1.5rem;
  font-weight: 400;
  color: var(--text-color);
}
.title {
  color: var(--primary-color);
  font-weight: 700;
  font-size: 2rem;
  text-transform: uppercase;
}
.item_preTitle {
  font-size: 1.4rem;
  color: var(--text-color);
  font-weight: 300;
}
.item_title {
  font-size: 1.6rem;
  color: white;
  font-weight: 500;
  margin: 0.8rem 0;
}
.item_subtitle {
  font-size: 1.4rem;
  color: var(--text-color);
  font-weight: 400;
}

/* layouts */
.container {
  max-width: 1000px;
  width: 90%;
  margin: 0 auto;
  display: grid;
  padding: 5rem;
  background: #070707;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
}
@media only screen and (max-width: 768px) {
  .container {
    width: 100%;
    grid-template-columns: 1fr;
    padding: 3rem;
    gap: 7rem;
  }
}
.profile {
  grid-column: 1 / -1;
  margin-bottom: 2rem;
}
.group-1,
.group-2 {
  display: flex;
  flex-direction: column;
  gap: 5rem;
}
.group-3 {
  max-width: 700px;
  width: 100%;
  margin: 0 auto;
  grid-column: 1/-1;
  display: flex;
  flex-direction: row;
  gap: 5rem;
}
.group-3 > div {
  flex: 1;
}
@media only screen and (max-width: 768px) {
  .profile {
    margin-bottom: 0;
  }
  .group-3 {
    flex-direction: column;
  }
}

/* profile */
.profile_container {
  display: flex;
  gap: 2rem;
}
.profile_profileImg {
  max-width: 250px;
}
.profile_name_firstName {
  color: white;
  font-weight: 200;
  font-size: clamp(2rem, 8vw, 4rem);
  text-transform: uppercase;
  display: block;
  margin-bottom: -0.8rem;
}
.profile_name_lastName {
  color: var(--primary-color);
  font-weight: 700;
  font-size: clamp(2.5rem, 15vw, 7rem);
  text-transform: uppercase;
  display: block;
}
.profile_title {
  font-size: 1.5rem;
  font-weight: 400;
  text-transform: uppercase;
}
.downloadBtn {
  display: block;
  text-decoration: underline;
  font-size: 1.6rem;
  margin-top: 1rem;
}
.downloadBtn:hover {
  color: var(--primary-color);
}
@media only screen and (max-width: 768px) {
  .profile_container {
    flex-direction: column;
  }
}

/* Expertise */
.skills_list {
  margin-top: 1rem;
  margin-left: 2rem;
  line-height: 2;
}

/* Ref  */
.ref_item {
  margin-top: 2rem;
}
.ref_name {
  font-size: 1.6rem;
  font-weight: 700;
}

/* eduction */
.edu_item {
  margin-top: 2rem;
}

/* certification */
.certification_item {
  margin-top: 2rem;
}
/* exp */
.exp_item {
  margin-top: 2rem;
}

/* awards */
.awards_item {
  margin-top: 2rem;
}
/* Interests */
.interest_items {
  margin-top: 2rem;
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 2rem;
}
.interest_item {
  font-size: 1.5rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  color: var(--text-color);
}
.interest_item svg {
  width: 2rem;
}

/* socials */
.social_items {
  margin-top: 2rem;
}
.social_item {
  margin-top: 1.5rem;
  font-size: 1.5rem;
  display: flex;
  gap: 0.5rem;
  align-items: center;
  justify-content: flex-start;
  color: var(--text-color);
}
.social_item:hover {
  color: var(--primary-color);
}
.social_item svg {
  width: 2rem;
}

hr {
  grid-column: 1/-1;
  width: 80%;
  margin: 0 auto;
  margin-top: 5rem;
  margin-bottom: 1rem;
  border: none;
  border-top: 2px solid rgba(128, 128, 128, 0.229);
}
@media only screen and (max-width: 768px) {
  hr {
    margin: 0 auto;
  }
}
   </style>
  <link rel="stylesheet" href="style.css"> 
  <div class="container"> 
   <div class="profile"> 
    <div class="profile_container"> 
     <div class="profile_profileImg"> 
      <img src="https://scontent.fmnl17-4.fna.fbcdn.net/v/t1.15752-9/379582436_634729388842740_5897574943133397465_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=ae9488&_nc_eui2=AeFgPIFa1xjcYACoJkuThkui6CwgMeJTV87oLCAx4lNXznGeb_tKou8pR2BNnD94enIJCVQKFucId2CN6ZIZ3_xn&_nc_ohc=3uE54lu4MroAX_5OVlp&_nc_ht=scontent.fmnl17-4.fna&oh=03_AdTEjSqA_H9dl0nDNsQEsqHU01A7_wo7rajsTGKviPgF1w&oe=6534BAB2&dl=1" alt="Delmonte Jansel"> 
     </div> 
     <div> 
      <h1 class="profile_name"> <span class="profile_name_firstName">Jansel</span> <span class="profile_name_lastName">Delmonte</span> </h1> 
      <p class="profile_title">FRONTEND </p> 
      <p class="description profile_description"> I am Jansel Valenzuela Delmonte as a Computer Science explore topic such as algorithms, data structures, programing langueage, sofrware development,artificial intelligence, computer architecture, computer networks, and much more. It provides a foundation for designing and building software, developing new technologies, and advancing our understanding of how computers can be utilized to improve our lives.</p>  
     </div> 
    </div> 
   </div> 
   <div class="group-1"> 
    <div class="skills"> 
     <h3 class="title">SKILLS</h3> 
     <ul class="skills_list description"> 
      <li>C#</li> 
      <li>HTML</li> 
      <li>CSS</li> 
      <li>FREE LANCER</li> 
     </ul> 
    </div> 
    <div class="edu"> 
     <h3 class="title">Education</h3> 
     <div class="edu_item"> 
      <p class="item_preTitle">2019-2020</p> 
      <h4 class="item_title">JUNIOR HIGH SCHOOL </h4> 
      <p class="item_subtitle"> BENIGNO AQUINO JR HIGH SCHOOL </p> 
     </div> 
     <div class="edu_item"> 
      <p class="item_preTitle">2021-2022</p> 
      <h4 class="item_title">SENIOR HIGH SCHOOL</h4> 
      <p class="item_subtitle"> ST CLARE COLLEGE</p> 
     </div> 
    </div> 
    <div class="group-2"> 
     <div class="exp"> 
      <h3 class="title">Work Experience</h3> 
      <div class="exp_item"> 
       <p>Im not work experience but im Traing to Individual at Teamwork and Communication Skill and Focus on your responsibilities, achievements, and the impact to made in those roles</p> 
      </div> 
     </div> 
     <div class="awards"> 
      <h3 class="title">Awards</h3> 
      <div class="awards_item"> 
       <p class="item_preTitle">(2015-2016)</p> 
       <h4 class="item_title">COMPLETERS.</h4> 
       <p></p>
       <li>Graduated in Junior High School in BENIGNO AQUINO JR HIGH SCHOOL.<p></p> </li>
      </div> 
      <div class="awards_item"> 
       <p class="item_preTitle">(2019-2020)</p> 
       <h4 class="item_title">HIGH SCHOOL GRADUATE.</h4> 
     
     <p> <li>Graduated in Senior High School in ST CLARE COLLEGE. </li> </p>
      </div> 
     </div> 
     <div class="HOBBIES"> 
      <h3 class="title">HOBBIES</h3> 
      <div class="interest_items"> 
       <div class="interest_item"> <i data-feather="music"></i> <span>Music</span> 
       </div> 
       <div class="interest_item"> <i data-feather="book"></i> <span>Books</span> 
       </div> 
       <div class="interest_item"> <i data-feather="map"></i> <span>Travel</span> 
       </div> 
      </div> 
     </div> 
    </div> 
    <hr> 
    <div class="group-3"> 
     <div class="contact"> 
      <h3 class="title">Contact</h3> 
      <div class="contact_info"> 
       <p class="description"> CALOOCAN CITY </p> 
       <p class="description">09127748000</p> 
       <p class="description"> janseldelmonte0@gmail.com </p> 
      </div> 
     </div> 
     <div class="social"> 
      <h3 class="title">Socials</h3> 
      <div class="social_items"> <a href="#" target="_b" class="social_item">https://www.facebook.com/Jayzeee05?mibextid=2JQ9oc <i data-feather="github">https://github.com/janseldelmonte/my_portfolio/upload/RESUME</i> <span>/</span> </a> <a href="#" target="_blank" class="social_item"> <i data-feather="twitter">@znaj_alpha</i> <span>/</span> </a> <a href="#" target="_blank" class="social_item"> <i data-feather="linkedin">http://www.linkedin.com/in/jansel-delmonte-8b17b228a?authuser=0</i> <span>/</span> </a> 
      </div> 
     </div> 
    </div> 
   </div> 
   <script>
    feather.replace()
  </script> 
  </div> 
 </body>
</html>
