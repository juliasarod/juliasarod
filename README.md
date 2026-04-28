<style>
  body {
    margin: 0;
    padding: 0;
    background-color: #0d001a;
  }

  .space {
    position: relative;
    width: 100%;
    height: 400px;
    background: radial-gradient(circle at bottom, #1a0033, #0d001a);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border-radius: 15px;
    font-family: 'Verdana', sans-serif;
  }


  .title-main {
    color: white;
    font-size: 40px;
    font-weight: bold;
    letter-spacing: 2px;
    margin: 0;
    z-index: 10;
    text-shadow: 0 0 15px rgba(199, 125, 255, 0.5);
  }

  .subtitle-main {
    color: #c77dff;
    font-size: 12px;
    letter-spacing: 1px;
    margin-top: 5px;
    z-index: 10;
    text-transform: uppercase;
  }

  /* Estrelinhas pequenas */
  .star {
    position: absolute;
    width: 2px;
    height: 2px;
    background: #e9d5ff;
    border-radius: 50%;
    animation: blink var(--duration, 2s) infinite ease-in-out;
  }

  @keyframes blink {
    0%, 100% { opacity: 0.2; transform: scale(1); }
    50% { opacity: 1; transform: scale(1.2); }
  }

  .big-star {
    position: absolute;
    color: #c084fc;
    font-size: 18px;
    opacity: 0.5;
  }

  .planet {
    position: absolute;
    width: 20px;
    height: 20px;
    background: linear-gradient(45deg, #9333ea, #4c1d95);
    border-radius: 50%;
    animation: float 6s infinite ease-in-out;
  }

  @keyframes float {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
  }

  .shooting-star {
    position: absolute;
    width: 80px;
    height: 2px;
    background: linear-gradient(90deg, white, transparent);
    animation: shoot 8s infinite linear;
  }

  @keyframes shoot {
    0% { transform: translate(-100px, -100px) rotate(45deg); opacity: 0; }
    5% { opacity: 1; }
    20% { transform: translate(600px, 600px) rotate(45deg); opacity: 0; }
    100% { opacity: 0; }
  }
</style>

<div class="space">
  <h1 class="title-main">JÚLIA SANTOS</h1>
  <p class="subtitle-main">WELCOME TO MY UNIVERSE</p>

  <div class="star" style="top:5%; left:15%; --duration: 1.5s;"></div>
  <div class="star" style="top:12%; left:40%; --duration: 2.1s;"></div>
  <div class="star" style="top:25%; left:65%; --duration: 1.8s;"></div>
  <div class="star" style="top:8%; left:85%; --duration: 2.5s;"></div>
  <div class="star" style="top:45%; left:10%; --duration: 1.2s;"></div>
  <div class="star" style="top:55%; left:90%; --duration: 3s;"></div>
  <div class="star" style="top:75%; left:50%; --duration: 1.7s;"></div>
  <div class="star" style="top:85%; left:20%; --duration: 2.2s;"></div>
  <div class="star" style="top:92%; left:75%; --duration: 1.9s;"></div>
  <div class="star" style="top:35%; left:25%; --duration: 2.4s;"></div>
  <div class="star" style="top:60%; left:40%; --duration: 1.6s;"></div>
  <div class="star" style="top:20%; left:5%; --duration: 2.8s;"></div>
  <div class="star" style="top:80%; left:95%; --duration: 1.3s;"></div>
  <div class="star" style="top:50%; left:70%; --duration: 2.6s;"></div>
  <div class="star" style="top:15%; left:55%; --duration: 1.4s;"></div>
  <div class="star" style="top:40%; left:80%; --duration: 2.1s;"></div>
  <div class="star" style="top:70%; left:12%; --duration: 1.8s;"></div>
  <div class="star" style="top:30%; left:92%; --duration: 2.3s;"></div>
  <div class="star" style="top:65%; left:60%; --duration: 1.5s;"></div>
  <div class="star" style="top:10%; left:30%; --duration: 2.7s;"></div>

  <div class="big-star" style="top:15%; left:22%;">★</div>
  <div class="big-star" style="top:70%; left:82%;">★</div>
  <div class="big-star" style="top:40%; left:5%;">★</div>
  <div class="big-star" style="top:85%; left:45%;">★</div>
  <div class="big-star" style="top:10%; left:90%;">★</div>

  <div class="planet" style="top:15%; left:75%;"></div>
  <div class="planet" style="top:80%; left:10%;"></div>

  <div class="shooting-star" style="top:0%; left:15%;"></div>
</div>

---

### 🛠️ Technologies & Tools

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

### 🌟 GitHub Stats

![Julia's GitHub stats](https://github-readme-stats.vercel.app/api?username=juliasarod&show_icons=true&theme=tokyonight&title_color=9b59b6&icon_color=9b59b6&border_color=9b59b6)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=juliasarod&layout=compact&theme=tokyonight&title_color=9b59b6&border_color=9b59b6)

---
