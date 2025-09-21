<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Homepage</title>
  <style>
   html {
  scroll-behavior: smooth;
  font-size: 1.2rem; 
}
body {
  background: linear-gradient(90deg, #FF6F61, #FFEC8B, #F9A602); 
  color: #333;
} 
body {
  padding-top: 80px;
  font-size: 1.50rem; 
  font-family: 'Segoe UI', 'Helvetica Neue', Arial, sans-serif;
  line-height: 1.7;
  color: #333;
}
  .sparkle-container {
  position: relative;
  overflow: hidden;
}

.sparkle {
  position: absolute;
  width: 8px;
  height: 8px;
  background: radial-gradient(circle, #fff 0%, #f4a6b0 100%);
  border-radius: 50%;
  animation: floatSparkle 3s infinite ease-in-out;
  opacity: 0.8;
}

@keyframes floatSparkle {
  0% {
    transform: translateY(0) rotate(0deg);
    opacity: 1;
  }
  100% {
    transform: translateY(-100px) rotate(360deg);
    opacity: 0;
  }
}  
  .banner {
    width: 100%;
    height: 300px;
    background-image: url('ancen.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
  }

  .top-nav {
    width: 100%;
    background-color: #1a1a1a;
    padding: 1rem 2rem;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 1000;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
  }

  .nav-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
  }

  .brand {
    color: #f5f5f5;
    font-size: 1.5rem; /* 24px */
    font-weight: 700;
    letter-spacing: 0.5px;
  }

  .nav-links {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
    align-items: center;
  }

  .nav-links li {
    margin-left: 2rem;
    position: relative;
  }

  .nav-links a {
    color: #ffffff;
    text-decoration: none;
    font-size: 1.125rem; /* 18px */
    font-weight: 600;
    transition: color 0.3s ease;
  }

  .nav-links a:hover,
  .nav-links a:focus {
    color: #00aaff;
    text-decoration: underline;
    outline: none;
  }

  .menu-icon {
    list-style: none;
  }

  .menu-icon button {
    background: none;
    border: none;
    font-size: 1.5rem;
    cursor: pointer;
    color: #ffffff;
  }

  .dropdown {
    display: none;
    position: absolute;
    top: 2rem;
    right: 0;
    background-color: white;
    border: 1px solid #ccc;
    list-style: none;
    padding: 0.5rem;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    z-index: 1001;
  }
  .dropdown.open {
  display: block;
 }
  .dropdown li {
    margin: 0.5rem 0;
  }

  .dropdown li a {
    color: #333;
    text-decoration: none;
  }
   
  @media (max-width: 600px) {
  iframe {
    height: 300px;
  }
} 
    @media (max-width: 600px) {
  .nav-links a {
    font-size: 0.85rem; /* ≈13.6px */
  }

  .dropdown li a {
    font-size: 0.85rem;
  }

  .nav-links li {
    margin-left: 0.4rem; /* reduce spacing between tabs */
  }
}
   
  </style>
</head>
<body>
  
<!-- Navigation -->
<nav class="top-nav" role="navigation" aria-label="Main navigation">
  <div class="nav-container">
   <ul class="nav-links">
      <li><a href="Home.html">Home</a></li>
      <li><a href="projects.html">Projects</a></li>
      <li><a href="writing.html">Creative Writing</a></li>
      <li><a href="contact.html">Contact</a></li>
     <li class="menu-icon">
        <button onclick="toggleMenu()" aria-label="Toggle menu">☰</button>
        <ul class="dropdown" id="dropdownMenu">
         <li><a href="Home.html">Home</a></li>
         <li><a href="projects.html">Projects</a></li>
         <li><a href="writing.html">Creative Writing</a></li>
         <li><a href="contact.html">Contact</a></li>
          
       </ul>
      </li>
    </ul>
  </div>
</nav>

  <div class="banner"></div>
 <div class="container">
   <!-- Flex Layout for Bio + Photo -->
   <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start; padding: 3rem 2rem; max-width: 1200px; margin: auto; gap: 2rem;">
 
     <!-- Text Section -->
     <div style="flex: 1; min-width: 300px;">
     <h1 style="font-size: 2.5rem; color: #880E4F; margin-bottom: 1rem;">It's China </h1>
      <div style="font-size: 1.25rem; line-height: 1.8; color: #1a1a1a;">

        <p class="tagline"> • Spiritual Baddie • Techie Priestess • Learning Alchemist • Pen-slingin’ Storyteller </p>
      </div>

    <p> I’ve been walking with spirit since before I could walk at all. Born and raised in Harlem, my gifts showed up early—visions, dreams, whispers from ancestors who never left my side. That sacred touch has guided me ever since. </p>
    <p> I hold space for transformation through dream interpretation, tarot, and ancestral downloads. My work is intuitive, intentional, and deeply rooted in sacred systems—not trends. </p>
    <p> I also build. Websites, learning modules, custom PCs—tools that empower. I design with clarity, care, and cultural pride, blending tech with spirit like it’s second nature. </p>
    <p> I write, too. Poetry that heals. Stories that remember. Words that wrap around you like a warm shawl. My creative work is raw, rhythmic, and rooted in truth. </p>
    <p> And yes, I still keep my hands in the beauty world—styling hair, painting nails, curating looks that feel like rituals of self-love. It’s not my main lane, but it’s part of my magic.</p>
    
        <strong>Degrees? Got 'em:</strong>
        <ul>
          <li>Master’s in Learning, Design & Technology</li>
          <li>Bachelor’s in Computer Science</li>
          <li>Associate’s in Computer Information</li>
        </ul>
      </div>

      <p> I offer custom websites, hand-built PCs, learning modules for any subject, resume glow-ups, tax clarity, spiritual guidance, and writing that moves—poems, stories, and narrative work that speak to the soul.</p>
   
      <p> I’m here to help you glow from the inside out—spiritually, creatively, and practically.<br><strong>Whatever you need to elevate, I got you.</strong> </p>
   
<!-- Image Section -->
     <div style="flex: 0 0 280px; text-align: center;">
      <img src="shareFromBeautyPlus (3).jpg" alt="Portrait of China in armchair with African masks" style="width: 100%; max-width: 280px; border-radius: 50%; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
    </div>
  </div>

  <hr style="border: none; border-top: 2px solid #D35400; margin: 3rem 0;">

<footer style="text-align: center; padding: 2rem;">
<img src="chinalogo.png" alt="China' logo" style="height: 70px;">
<p style="font-size: 0.9rem; color: #777;">Made with sparkle and semantic HTML by China</p>
  © 2025 China. All rights reserved.  
  Content on this site may not be reproduced, distributed, or used without written permission.
</footer>
<script>
  function toggleMenu() {
    const menu = document.getElementById("dropdownMenu");
    menu.style.display = menu.style.display === "block" ? "none" : "block";
  }

  window.onclick = function(event) {
    if (!event.target.matches('.menu-icon button')) {
      const dropdown = document.getElementById("dropdownMenu");
      if (dropdown && dropdown.style.display === "block") {
        dropdown.style.display = "none";
      }
    }
  };
</script>
</body>
</html>
