<div align="center">
<<<<<<< HEAD

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

<br/>

<!-- TYPING SVG — pink/purple theme -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=E91E8C&center=true&vCenter=true&width=600&lines=Backend+Developer+%F0%9F%9A%80;Data+Engineering+Enthusiast+%F0%9F%90%8D)](https://git.io/typing-svg)
=======
<p align="center">
  <img src="assets/banner.svg" alt="Brigida's GitHub Banner" width="100%"/>
</p>
>>>>>>> ba5e09c425f8ea865d4967956c98a386a3ace13b

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=F2C4CE&center=true&vCenter=true&width=600&lines=Backend+Developer;Data+Engineering+Enthusiast)](https://git.io/typing-svg)
</div>

---

### About Me
```python

class Brigida:
    role     = "Informatics Engineering Student"
    school   = "UNTL — Faculty of Science & Technology"
    focus    = ["Data Engineering", "Full-Stack Dev"]
    learning = ["Python", "SQL", "Laravel", "Django"]
    skills   = ["PHP", "Kotlin", "Python", "SQL"]
    os       = "Linux Mint 🐧🌱"
    hobbies  = ["Building things⚙️", "Automotive🚗", "Music🎵"]
    motto    = "Build. Learn. Repeat."

    def __repr__(self) -> str:
        return f"<{self.__class__.__name__} | {self.role} | \"{self.motto}\">"

me = Brigida()
print(me)
# <Brigida | Informatics Engineering Student | "Build. Learn. Repeat.">
```

---

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats-mu-virid-92.vercel.app/api?username=abindacarmo&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&border_radius=12&title_color=F2C4CE&icon_color=D9A0B2&text_color=F2C4CE&bg_color=1A0D12" width="400" alt="GitHub Stats"/>
      <br/>
      <img src="https://streak-stats.demolab.com?user=abindacarmo&theme=tokyonight&hide_border=true&hide_logo=true&ring=F2C4CE&fire=F2C4CE&currStreakNum=F2C4CE&sideNums=F2C4CE&currStreakLabel=D9A0B2&sideLabels=D9A0B2&background=1A0D12&stroke=D9A0B2&dates=D9A0B2" width="400"/>
    </td>
    <td>
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=abindacarmo&theme=react&area=true&hide_border=true&color=F2C4CE&line=D9A0B2&point=F2C4CE&bg_color=1A0D12" alt="Activity Graph" width="600" />
    </td>
  </tr>
</table>

---

<div align="center">
  <img src="https://raw.githubusercontent.com/abindacarmo/abindacarmo/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

<div align="center">

*"Never Late to Begin Something, So just do it!!!"*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=background:1A0D12,D9A0B2,F2C4CE&height=100&section=footer"/></div>
