---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---
# Who I Am
<!-- Slideshow styling -->
<style>
  .slideshow-container { max-width: 100%; position: relative; }
  .mySlides { display: none; }
  .mySlides img { width: 100%; border-radius: 10px; }
  .dot { height: 10px; width: 10px; margin: 5px; background-color: #bbb; border-radius: 50%; display: inline-block; }
</style>

<!-- Slideshow HTML -->
<div class="slideshow-container">
  <div class="mySlides fade"><img src="https://i.imgur.com/YEziibM.jpeg"></div>
  <div class="mySlides fade"><img src="https://i.imgur.com/xIzTlgm.png"></div>
  <div class="mySlides fade"><img src="https://i.imgur.com/RWhiDwp.jpeg"></div>
</div>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<!-- Slideshow JS -->
<script>
let slideIndex = 0;
showSlides();
function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) slides[i].style.display = "none";
  slideIndex++;
  if (slideIndex > slides.length) slideIndex = 1;
  for (i = 0; i < dots.length; i++) dots[i].style.backgroundColor = "#bbb";
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].style.backgroundColor = "#717171";
  setTimeout(showSlides, 4000);
}
</script>


**Here is some info about my nerdy-self, since personality matters.**
- I'm a 21 year old engineering student with a passion for anything technology related!
- Because I'm a nerd, I operate my own home-lab where I develop or play around with computers, servers, or open-source softwares.
- My personal interests include...
    - Working on my gaming desktop I custom built myself
    - Assisting friends online with computer or hardware related issues
    - Becoming a technical wizard whom can control magical rocks (silicon) to 'think'

# Education
<img src="https://i.imgur.com/zQPDAnd.png" alt="sparty" width="200" style="border-radius: 50%;">

**Junior student at Michigan State University for Computer Science Engineering**
- Specializing in Networking and Cybersecurity
- Studying for a CompTIA Network+ certification

# Experiences
**IT Assistant Volunteer Intern : Packard Proving Grounds Historic Site**
<iframe
  width="100%"
  height="450"
  style="border:0;"
  loading="lazy"
  referrerpolicy="no-referrer-when-downgrade"
  src="https://www.google.com/maps?q=42.662116079998576,-83.03518698731247&z=15&output=embed">
</iframe>
- *Began assisting June 2025*
- Completed Projects:
    - Installing a few IoT cameras on a local network
    - Developing an open-source kiosk solution via linux