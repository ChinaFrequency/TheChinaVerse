<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Homepage</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
      background: url('linen-texture.jpg') repeat, linear-gradient(to bottom right, #e07a5f, #f4a261);
      background-blend-mode: overlay;
      color: #3b2f2f;
      line-height: 1.6;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      max-width: 1000px;
      margin: 3rem auto;
      padding: 2rem;
      background: #fffaf3;
      border: 2px solid #f4a261;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(224, 122, 95, 0.2);
    }

    .bio {
      flex: 1 1 500px;
      padding-right: 2rem;
    }

    .bio h1 {
      font-size: 2.5rem;
      color: #6a4c93; /* Deep plum */
      margin-bottom: 0.5rem;
      text-align: center;
    }

    .tagline {
      font-style: italic;
      color: #2a9d8f; /* Jade green */
      margin-bottom: 2rem;
      text-align: center;
    }

    .section {
      margin-bottom: 1.5rem;
      text-align: justify;
    }

    .section strong {
      color: #3b2f2f; /* Cocoa - no orange */
    }

    .footer {
      font-weight: 600;
      margin-top: 2rem;
      color: #5a3d3d;
      text-align: center;
    }

    .sparkle {
      font-size: 1.2rem;
      color: #2a9d8f; /* Jade green */
    }

    .photo {
      flex: 1 1 400px;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .photo img {
      max-width: 100%;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .banner {
      width: 100%;
      height: 270px;
      background-image: url('ancen.png');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
    }

    .rtl-text {
      direction: rtl;
      font-family: 'Inter', sans-serif;
      color: #3b2f2f;
      padding: 1rem;
      max-width: 700px;
      margin: 0 auto;
      text-align: center;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }

      .bio {
        padding-right: 0;
      }
    }
    .top-nav {
  background-color: #fffaf3;
  border-bottom: 2px solid #f4a261;
  padding: 1rem;
  font-family: 'Inter', sans-serif;
}

.nav-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1000px;
  margin: 0 auto;
  position: relative;
}

.nav-brand a {
  font-weight: 700;
  font-size: 1.5rem;
  color: #3b2f2f;
  text-decoration: none;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 2rem;
  margin: 0;
  padding: 0;
}

.nav-links li a {
  text-decoration: none;
  color: #3b2f2f;
  font-weight: 600;
}

.menu-toggle {
  display: none;
  font-size: 1.8rem;
  background: none;
  border: none;
  color: #3b2f2f;
  cursor: pointer;
}

@media (max-width: 768px) {
  .nav-links {
    display: none;
    flex-direction: column;
    position: absolute;
    top: 60px;
    right: 0;
    background-color: #fffaf3;
    border: 1px solid #f4a261;
    padding: 1rem;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    z-index: 1000;
  }

  .menu-toggle {
    display: block;
  }

  .nav-links.show {
    display: flex;
  }
}
  </style>
</head>
<body>
  
<!-- Navigation -->
<nav class="top-nav" role="navigation" aria-label="Main navigation">
  <div class="nav-container">
    <ul class="nav-links">
      
    <!-- Toggle Button for Mobile -->
    <button class="menu-toggle" onclick="toggleMenu()">☰</button>

    <!-- Dropdown Menu -->
    <ul class="dropdown" id="dropdownMenu">
      <li><a href="Home.html">Home</a></li>
      <li><a href="projects.html">Projects</a></li>
      <li><a href="writing.html">Creative Writing</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </div>
</nav>

  <div class="banner"></div>
  <div class="container">
    <div class="bio">
      <div class="rtl-text" dir="rtl">
        <h1>China</h1>
        <p class="tagline"> Spiritual Baddie • Techie Priestess • Learning Alchemist • Pen-slingin’ Storyteller </p>
      </div>

      <div class="section">
        I’ve been walking with spirit since before I could walk at all. Born and raised in Harlem, my gifts showed up early—visions, dreams, whispers from ancestors who never left my side. That sacred touch has guided me ever since.
      </div>

      <div class="section">
        I hold space for transformation through dream interpretation, tarot, and ancestral downloads. My work is intuitive, intentional, and deeply rooted in sacred systems—not trends.
      </div>

      <div class="section">
        I also build. Websites, learning modules, custom PCs—tools that empower. I design with clarity, care, and cultural pride, blending tech with spirit like it’s second nature.
      </div>

      <div class="section">
        I write, too. Poetry that heals. Stories that remember. Words that wrap around you like a warm shawl. My creative work is raw, rhythmic, and rooted in truth.
      </div>

      <div class="section">
        And yes, I still keep my hands in the beauty world—styling hair, painting nails, curating looks that feel like rituals of self-love. It’s not my main lane, but it’s part of my magic.
      </div>

      <div class="section">
        <strong>Degrees? Got 'em:</strong>
        <ul>
          <li>Master’s in Learning, Design & Technology</li>
          <li>Bachelor’s in Computer Science</li>
          <li>Associate’s in Computer Information</li>
        </ul>
      </div>

      <div class="section">
        I offer custom websites, hand-built PCs, learning modules for any subject, resume glow-ups, tax clarity, spiritual guidance, and writing that moves—poems, stories, and narrative work that speak to the soul.
      </div>

      <div class="footer sparkle">
        I’m here to help you glow from the inside out—spiritually, creatively, and practically.  
        <br><strong>Whatever you need to elevate, I got you.</strong>
      </div>
    </div>

    <div class="photo">
      <img src="shareFromBeautyPlus (3).jpg" alt="Portrait of China in armchair with African masks">
    </div>
  </div>
  <script>
  function toggleMenu() {
    const menu = document.getElementById('dropdownMenu');
    menu.style.display = menu.style.display === 'flex' ? 'none' : 'flex';
  }
</script>
<script>
  function toggleMenu() {
    const nav = document.getElementById('mainNav');
    nav.classList.toggle('show');
  }
</script>

</body>
</html>
