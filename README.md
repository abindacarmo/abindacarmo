<div align="center">

<!-- Wave top -->


<style>
  .banner {
  width: 100%;
  height: 200px;

  background: linear-gradient(
    135deg,
    #1E0A2E 0%,
    #220D1C 50%,
    #1A0E28 100%
  );

  background-size: 300% 300%;

  animation: gradientMove 8s ease infinite;

  border-radius: 14px;
  position: relative;
  overflow: hidden;
  font-family: 'Courier New', monospace;
}

/* floats icon */
    .float {
        position: absolute;
        color: #CE93D8;
        opacity: 0.4;
        animation: float 4s ease-in-out infinite;
    }

    .float1 {
    top: 30px;
    right: 80px;
    }

    .float2 {
    top: 80px;
    right: 180px;
    animation-delay: 1s;
    }

    .float3 {
    top: 150px;
    right: 100px;
    animation-delay: 2s;
    }

    .float4 {
    top: 60px;
    right: 300px;
    animation-delay: 1.5s;
    }

    .float5 {
    top: 140px;
    right: 250px;
    animation-delay: .5s;
    }

    .float6 {
    top: 15px;
    left: 250px;
    animation-delay: .5s;
    }

    .float7 {
    top: 180px;
    left: 300px;
    animation-delay: .5s;
    }

     .float8 {
    top: 80px;
    left: 350px;
    animation-delay: .7s;
    }

    .float9 {
    top: 100px;
    left: 500px;
    animation-delay: .9s;
    }

    .float10 {
    top: 90px;
    left: 700px;
    animation-delay: .5s;
    }

    .float11 {
    top: 130px;
    left: 600px;
    animation-delay: .6s;
    }

    .float12 {
    top: 40px;
    left: 900px;
    animation-delay: .10s;
    }

    .float13 {
    top: 20px;
    left: 800px;
    animation-delay: .6s;
    }

    .float14 {
    top: 50px;
    left: 600px;
    animation-delay: .9s;
    }

    .float15 {
    top: 60px;
    left: 400px;
    animation-delay: .8s;
    }
    .float16 {
    top: 70px;
    right: 400px;
    animation-delay: .10s;
    }
    .float17 {
    top: 200px;
    right: 350px;
    animation-delay: .9s;
    }
    .float18 {
    top: 150px;
    right: 500px;
    animation-delay: .5s;
    }
    .float19 {
    top: 170px;
    left: 850px;
    animation-delay: .6s;
    }
    .float20 {
    top: 120px;
    left: 810px;
    animation-delay: .8s;
    }


    @keyframes float {

    0% {
        transform: translateY(0px);
    }

    50% {
        transform: translateY(-12px);
    }

    100% {
        transform: translateY(0px);
    }

    }


  @keyframes floatIcon {
    0%   { transform: translateY(0px) rotate(var(--r)); opacity: var(--o); }
    50%  { transform: translateY(-10px) rotate(var(--r)); opacity: calc(var(--o) * 1.7); }
    100% { transform: translateY(0px) rotate(var(--r)); opacity: var(--o); }
  }
  .left-bar-top {
    position: absolute;
    left: 36px; top: 34px;
    width: 2.5px; height: 38px;
    background: #E91E8C;
    opacity: 0.85;
    border-radius: 1px;
  }
  .left-bar-bot {
    position: absolute;
    left: 36px; top: 76px;
    width: 2.5px; height: 42px;
    background: #9C27B0;
    opacity: 0.65;
    border-radius: 1px;
  }
  .bracket-tr {
    position: absolute;
    top: 10px; right: 12px;
    width: 22px; height: 22px;
    border-top: 1.2px solid #E91E8C;
    border-right: 1.2px solid #E91E8C;
    opacity: 0.6;
  }
  .bracket-bl {
    position: absolute;
    bottom: 10px; left: 12px;
    width: 22px; height: 22px;
    border-bottom: 1.2px solid #9C27B0;
    border-left: 1.2px solid #9C27B0;
    opacity: 0.6;
  }
  .content {
    position: absolute;
    left: 50px; top: 0; bottom: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 0;
  }
  .greeting {
    font-size: 11px;
    color: #CE93D8;
    letter-spacing: 3px;
    margin-bottom: 4px;
  }
  .name {
    font-family: Georgia, serif;
    font-size: 52px;
    font-weight: bold;
    color: #FAF0FF;
    line-height: 1;
    margin-bottom: 8px;
  }
  .name span { color: #E91E8C; }
  .name .dot { color: #9C27B0; font-size: 44px; }
  .tagline {
    font-size: 12px;
    color: #CE93D8;
    margin-bottom: 10px;
  }
  .tagline .arrow { color: #7B4F8E; }
  .tagline .highlight { color: #F48FB1; }
  .pills {
    display: flex;
    gap: 6px;
    flex-wrap: wrap;
  }
  .pill {
    font-family: 'Courier New', monospace;
    font-size: 10px;
    padding: 3px 11px;
    border-radius: 11px;
    border: 0.8px solid #9C27B0;
    background: #2e0e3e;
    color: #E1BEE7;
  }
  .pill.hot {
    border: 1.2px solid #E91E8C;
    background: #300618;
    color: #F48FB1;
  }
  .status {
    position: absolute;
    bottom: 14px;
    right: 20px;
    display: flex;
    align-items: center;
    gap: 6px;
    font-family: 'Courier New', monospace;
    font-size: 10px;
    color: #F48FB1;
  }
  .dot-pulse {
    width: 7px; height: 7px;
    background: #E91E8C;
    border-radius: 50%;
    animation: pulse 1.8s ease-in-out infinite;
  }
  @keyframes pulse {
    0%, 100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.4; transform: scale(0.7); }
  }

  @keyframes gradientMove {

  0% {
    background-position: 0% 50%;
  }

  50% {
    background-position: 100% 50%;
  }

  100% {
    background-position: 0% 50%;
  }

}
</style>

<div class="banner">
  <div class="top-line"></div>
  <div class="bot-line"></div>
  <div class="icons-layer" id="iconsLayer"></div>
  <div class="left-bar-top"></div>
  <div class="left-bar-bot"></div>
  <div class="bracket-tr"></div>
  <div class="bracket-bl"></div>

  <!-- floating icons -->

<div class="float float1"></div>
<div class="float float2">sql</div>
<div class="float float3">numpy</div>
<div class="float float4">{ }</div>
<div class="float float5">git</div>

<div class="float float6">hello</div>
<div class="float float7">world</></div>
<div class="float float8">&&</div>
<div class="float float9">php</div>
<div class="float float10">null</div>

<div class="float float11">int</div>
<div class="float float12">★</div>
<div class="float float13">for</div>
<div class="float float14">SELECT</div>
<div class="float float15">import</div>

<div class="float float16">for</div>
<div class="float float17">::</div>
<div class="float float18">df</div>
<div class="float float19">pandas</div>
<div class="float float20">[]</div>


  <div class="content">
    <div class="greeting">HI THERE ✦ I'M</div>
    <div class="name">Brig<span>ida</span><span class="dot">_</span></div>
    <div class="tagline">Web dev <span class="arrow">→</span> <span class="highlight">Data Engineer</span> <span class="arrow">in progress</span></div>
    <div class="pills">
      <span class="pill">PHP</span>
      <span class="pill">SQL</span>
      <span class="pill hot">Python ✦</span>
      <span class="pill">Kotlin</span>
      <span class="pill">Git</span>
      <span class="pill">Linux</span>
      <span class="pill hot">Data Eng. ↗</span>
    </div>
  </div>

  <div class="status">
    <div class="dot-pulse"></div>
    always learning
  </div>
</div>


<!-- Profile Photo 
<img src="https://github.com/abindacarmo.png" width="130" style="border-radius: 50%;" alt="Brigida's Profile Picture"/> -->

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=6E40C9&center=true&vCenter=true&width=600&lines=Backend+Developer+%F0%9F%9A%80;Data+Engineering+Enthusiast;Always+learning+new+things+%F0%9F%8C%B1)](https://git.io/typing-svg)

<!-- Colorful animated text badges 
![](https://img.shields.io/badge/-%F0%9F%92%9C%20Backend%20Developer-%23b44fde?style=flat-square)
![](https://img.shields.io/badge/-%F0%9F%90%8D%20Python-%233776AB?style=flat-square)
![](https://img.shields.io/badge/-%F0%9F%90%98%20PHP-%23777BB4?style=flat-square)
![](https://img.shields.io/badge/-%F0%9F%8C%B1%20Always%20Learning-%2300C49A?style=flat-square)-->

</div>

---

### 👩‍💻 About Me

- 🔭 I'm currently studying **Information Technology** at UNTL, Faculty of Science & Technology
- 🔭 I'm currently studying about Python and SQL for data engineering
- 🌱 I'm always learning and improving my skills
- 💬 Ask me about **Python** and **PHP**
<!--- - 📫 Reach me at: **github.com/abindacarmo** -->
- ⚡ Fun fact: I love building things behind the scenes and I love automotive!

---

### 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

---

### 📊 GitHub Stats
<div align="center">
<img src="https://github-readme-stats-mu-virid-92.vercel.app/api?username=abindacarmo&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&border_radius=12" height="180" alt="GitHub Stats" />
</div>
<div align="center">
<img src="https://streak-stats.demolab.com?user=abindacarmo&theme=tokyonight&hide_border=true&hide_logo=true" height="180" />
</div>

---

### 🐍 Contribution Graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=abindacarmo&theme=tokyo-night&hide_border=true" />

</div>
---

<div align="center">

*"live ur life"* ✨

<!-- Wave bottom -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6E40C9&height=100&section=footer&animation=fadeIn" />

</div>
