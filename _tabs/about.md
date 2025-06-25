---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
# credits to https://www.w3schools.com/howto/howto_js_slideshow.asp
# gave some basic understanding and referenced a stackpost a while back
# forgot the link :/ just sorta remembered how it worked
---

# Who I Am
<div class="slideshow-container">
  <div class="slides">
    <!-- Radio buttons to control the slides -->
    <input type="radio" id="slide1" name="slide" checked>
    <input type="radio" id="slide2" name="slide">
    <input type="radio" id="slide3" name="slide">

    <!-- The slides themselves -->
    <div class="slide">
      <img src="https://i.imgur.com/YEziibM.jpg" style="width:100%" alt="Slide 1">
    </div>
    <div class="slide">
      <img src="https://i.imgur.com/xIzTlgm.png" style="width:100%" alt="Slide 2">
    </div>
    <div class="slide">
      <img src="https://i.imgur.com/RWhiDwp.jpg" style="width:100%" alt="Slide 3">
    </div>

    <!-- Navigation buttons -->
    <div class="navigation">
      <label for="slide1" class="prev">&#10094;</label>
      <label for="slide2" class="next">&#10095;</label>
    </div>
  </div>
</div>

{% raw %}
<style>
  /* Basic styles for the slideshow container */
  .slideshow-container {
    position: relative;
    width: 100%;
    max-width: 600px;
    margin: auto;
    overflow: hidden;
  }

  /* Hide all slides by default */
  .slide {
    display: none;
    width: 100%;
    height: auto;
  }

  /* Style for the labels (which act as buttons for navigation) */
  .navigation {
    position: absolute;
    top: 50%;
    width: 100%;
    display: flex;
    justify-content: space-between;
    transform: translateY(-50%);
  }

  /* Style for the "next" and "prev" buttons */
  .prev, .next {
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
    padding: 10px;
    cursor: pointer;
  }

  /* Hide radio buttons */
  input[type="radio"] {
    display: none;
  }

  /* Display the current slide */
  input:nth-of-type(1):checked ~ .slides .slide:nth-of-type(1),
  input:nth-of-type(2):checked ~ .slides .slide:nth-of-type(2),
  input:nth-of-type(3):checked ~ .slides .slide:nth-of-type(3) {
    display: block;
  }

  /* Optional: Add a transition effect for the slides */
  .slides .slide {
    transition: opacity 1s ease-in-out;
  }
</style>
{% endraw %}

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
