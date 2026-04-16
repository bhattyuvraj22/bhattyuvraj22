<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=30&duration=3000&pause=99999&color=6C63FF&center=true&vCenter=true&width=700&height=65&lines=Hey+there%2C+I%27m+Yuvraj+Bhatt+%F0%9F%91%8B" alt="Yuvraj Bhatt" />

<br/>

```
developer  ·  ml explorer  ·  cyber nerd  ·  gen ai builder
```

[![LinkedIn](https://img.shields.io/badge/-bhattyuvraj22-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/bhattyuvraj22)
[![GitHub](https://img.shields.io/badge/-bhattyuvraj22-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/bhattyuvraj22)
[![Mail](https://img.shields.io/badge/-your@email.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:your@email.com)

</div>

---

<table width="100%">
<tr>
<td width="55%" valign="top">

### 🐍 `yuvraj.py`

```python
class Yuvraj:
    location   = "Guwahati, Assam 🇮🇳"
    passions   = [
        "Web Dev 🌐",
        "Machine Learning 🤖",
        "Cyber Security 🔐",
        "Generative AI ✨",
    ]
    sports     = ["Basketball 🏀", "Cricket 🏏"]
    currently  = "Learning ML & advanced algorithms"
    mindset    = "Build things that scale."
```

</td>
<td width="45%" valign="top" align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bhattyuvraj22&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6C63FF&icon_color=FF6B9D&text_color=c9d1d9&rank_icon=github" width="100%"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=bhattyuvraj22&theme=tokyonight&hide_border=true&background=0d1117&ring=6C63FF&fire=FF6B9D&currStreakLabel=6C63FF" width="100%"/>

</td>
</tr>
</table>

---

<div align="center">

## 🏀🏏🕺 Off the Screen

<svg width="100%" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg" role="img">
  <title>Off the screen — basketball, cricket, and dance</title>
  <desc>Animated panels showing a bouncing basketball, a cricket bowl, and a dancing stick figure</desc>

  <defs>
    <style>
      /* ── shared fonts ── */
      .lbl { font-family: 'Fira Code', monospace; font-size: 13px; fill: #c9d1d9; text-anchor: middle; }
      .sub { font-family: 'Fira Code', monospace; font-size: 10px; fill: #555552; text-anchor: middle; }

      /* ── Basketball bounce ── */
      .bb {
        animation: bb 1.3s cubic-bezier(.33,0,.66,1) infinite;
      }
      @keyframes bb {
        0%,100% { transform: translateY(0); }
        45%      { transform: translateY(70px); }
        50%      { transform: translateY(73px); }
        55%      { transform: translateY(70px); }
      }
      .bb-shadow {
        animation: bs 1.3s cubic-bezier(.33,0,.66,1) infinite;
        transform-origin: 150px 218px;
      }
      @keyframes bs {
        0%,100% { transform: scaleX(1);   opacity: .12; }
        50%      { transform: scaleX(1.7); opacity: .28; }
      }

      /* ── Cricket ball arc ── */
      .cb {
        animation: cb 2s ease-in-out infinite;
        offset-path: path("M 460,75 Q 550,195 650,115");
        offset-rotate: 0deg;
      }
      @keyframes cb {
        0%        { offset-distance: 0%;   opacity: 1; }
        78%       { offset-distance: 100%; opacity: 1; }
        84%       { offset-distance: 100%; opacity: 0; }
        85%       { offset-distance: 0%;   opacity: 0; }
        100%      { offset-distance: 0%;   opacity: 1; }
      }
      .cb-spin {
        animation: sp .45s linear infinite;
        transform-origin: 14px 14px;
      }
      @keyframes sp { to { transform: rotate(360deg); } }

      /* ── Dancer ── */
      /* body sway */
      .dancer { animation: sway 0.6s ease-in-out infinite alternate; transform-origin: 790px 155px; }
      @keyframes sway { from { transform: rotate(-6deg); } to { transform: rotate(6deg); } }

      /* left arm swings up/down */
      .arm-l { animation: arml 0.6s ease-in-out infinite alternate; transform-origin: 784px 155px; }
      @keyframes arml { from { transform: rotate(-70deg); } to { transform: rotate(20deg); } }

      /* right arm counter-swings */
      .arm-r { animation: armr 0.6s ease-in-out infinite alternate; transform-origin: 796px 155px; }
      @keyframes armr { from { transform: rotate(20deg); } to { transform: rotate(-70deg); } }

      /* left leg kicks */
      .leg-l { animation: legl 0.6s ease-in-out infinite alternate; transform-origin: 785px 178px; }
      @keyframes legl { from { transform: rotate(-20deg); } to { transform: rotate(30deg); } }

      /* right leg counter-kicks */
      .leg-r { animation: legr 0.6s ease-in-out infinite alternate; transform-origin: 795px 178px; }
      @keyframes legr { from { transform: rotate(30deg); } to { transform: rotate(-20deg); } }

      /* music notes float up */
      .note { animation: note 1.8s ease-in infinite; }
      .note:nth-child(2) { animation-delay: .6s; }
      .note:nth-child(3) { animation-delay: 1.2s; }
      @keyframes note {
        0%   { transform: translateY(0);  opacity: 0; }
        10%  { opacity: .9; }
        80%  { opacity: .7; }
        100% { transform: translateY(-55px); opacity: 0; }
      }
    </style>

    <!-- subtle court pattern -->
    <pattern id="court" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
      <rect width="20" height="20" fill="none"/>
      <line x1="0" y1="20" x2="20" y2="0" stroke="#1a1f2e" stroke-width=".4"/>
    </pattern>
  </defs>

  <!-- ═══════════════ PANEL 1 – BASKETBALL ═══════════════ -->
  <rect x="10" y="10" width="280" height="260" rx="12" fill="#0d1117" stroke="#378ADD" stroke-width=".6" opacity=".8"/>
  <rect x="10" y="10" width="280" height="260" rx="12" fill="url(#court)" opacity=".4"/>

  <!-- backboard + rim -->
  <rect x="17" y="88" width="4" height="30" fill="#378ADD" opacity=".5" rx="1"/>
  <line x1="21" y1="98" x2="48" y2="98" stroke="#378ADD" stroke-width="2" opacity=".7"/>
  <ellipse cx="58" cy="98" rx="12" ry="5.5" fill="none" stroke="#FF6B9D" stroke-width="2.5" opacity=".9"/>

  <!-- court arc -->
  <path d="M 10,60 Q 100,230 10,195" fill="none" stroke="#378ADD" stroke-width=".8" opacity=".25"/>
  <!-- half-court line -->
  <line x1="10" y1="140" x2="290" y2="140" stroke="#378ADD" stroke-width=".6" opacity=".2"/>
  <ellipse cx="150" cy="140" rx="42" ry="20" fill="none" stroke="#378ADD" stroke-width=".6" opacity=".2"/>

  <!-- shadow -->
  <ellipse cx="150" cy="218" rx="18" ry="5" fill="#6C63FF" class="bb-shadow"/>

  <!-- basketball -->
  <g class="bb">
    <circle cx="150" cy="138" r="20" fill="#E55A00" stroke="#b84400" stroke-width="1.2"/>
    <path d="M130,138 Q150,122 170,138" fill="none" stroke="#7a2d00" stroke-width="1.4"/>
    <path d="M130,138 Q150,154 170,138" fill="none" stroke="#7a2d00" stroke-width="1.4"/>
    <line x1="150" y1="118" x2="150" y2="158" stroke="#7a2d00" stroke-width="1.4"/>
  </g>

  <text x="150" y="244" class="lbl">basketball</text>
  <text x="150" y="259" class="sub">half-court · full intensity</text>


  <!-- ═══════════════ PANEL 2 – CRICKET ═══════════════ -->
  <rect x="310" y="10" width="280" height="260" rx="12" fill="#0d1117" stroke="#5DCAA5" stroke-width=".6" opacity=".8"/>

  <!-- pitch strip -->
  <rect x="510" y="28" width="28" height="178" rx="3" fill="#1D9E75" opacity=".12" stroke="#5DCAA5" stroke-width=".5"/>

  <!-- crease lines -->
  <line x1="494" y1="48"  x2="550" y2="48"  stroke="#5DCAA5" stroke-width="1.4" opacity=".55"/>
  <line x1="494" y1="184" x2="550" y2="184" stroke="#5DCAA5" stroke-width="1.4" opacity=".55"/>

  <!-- stumps -->
  <line x1="518" y1="184" x2="518" y2="158" stroke="#c9d1d9" stroke-width="2.2"/>
  <line x1="524" y1="184" x2="524" y2="156" stroke="#c9d1d9" stroke-width="2.2"/>
  <line x1="530" y1="184" x2="530" y2="158" stroke="#c9d1d9" stroke-width="2.2"/>
  <!-- bails -->
  <line x1="516" y1="156" x2="532" y2="156" stroke="#FAC775" stroke-width="1.8"/>

  <!-- trajectory ghost dots -->
  <circle cx="480" cy="102" r="2.5" fill="#c0392b" opacity=".18"/>
  <circle cx="510" cy="136" r="2.5" fill="#c0392b" opacity=".18"/>
  <circle cx="545" cy="158" r="2.5" fill="#c0392b" opacity=".18"/>
  <circle cx="585" cy="148" r="2.5" fill="#c0392b" opacity=".18"/>
  <circle cx="625" cy="132" r="2.5" fill="#c0392b" opacity=".18"/>

  <!-- bowling crease (bowler end) -->
  <line x1="340" y1="184" x2="410" y2="184" stroke="#5DCAA5" stroke-width="1" opacity=".3"/>

  <!-- cricket ball on arc -->
  <g class="cb">
    <circle cx="14" cy="14" r="13" fill="#c0392b" stroke="#922b21" stroke-width=".8"/>
    <g class="cb-spin">
      <path d="M5,11 Q14,7 23,11" fill="none" stroke="#f0e0d8" stroke-width="1.1" opacity=".85"/>
      <path d="M5,17 Q14,21 23,17" fill="none" stroke="#f0e0d8" stroke-width="1.1" opacity=".85"/>
    </g>
  </g>

  <text x="450" y="244" class="lbl">cricket</text>
  <text x="450" y="259" class="sub">grew up watching it</text>


  <!-- ═══════════════ PANEL 3 – DANCE ═══════════════ -->
  <rect x="610" y="10" width="280" height="260" rx="12" fill="#0d1117" stroke="#a855f7" stroke-width=".6" opacity=".8"/>

  <!-- subtle floor line -->
  <line x1="625" y1="210" x2="875" y2="210" stroke="#a855f7" stroke-width=".5" opacity=".25"/>

  <!-- music notes (float upward) -->
  <g transform="translate(820, 90)">
    <g class="note">
      <text font-family="'Fira Code', monospace" font-size="16" fill="#a855f7" opacity=".8">♪</text>
    </g>
    <g class="note">
      <text font-family="'Fira Code', monospace" font-size="12" fill="#FF6B9D" opacity=".7" x="18">♫</text>
    </g>
    <g class="note">
      <text font-family="'Fira Code', monospace" font-size="14" fill="#6C63FF" opacity=".75" x="6" y="-10">♩</text>
    </g>
  </g>

  <!-- ── stick figure dancer ── -->
  <!-- head (doesn't sway — attached to neck top) -->
  <circle cx="790" cy="118" r="12" fill="none" stroke="#c9d1d9" stroke-width="2.2"/>

  <!-- body group (torso + limbs) swaying from hip -->
  <g class="dancer">
    <!-- torso -->
    <line x1="790" y1="130" x2="790" y2="178" stroke="#c9d1d9" stroke-width="2.2" stroke-linecap="round"/>

    <!-- left arm -->
    <g class="arm-l">
      <line x1="784" y1="150" x2="760" y2="170" stroke="#FF6B9D" stroke-width="2" stroke-linecap="round"/>
    </g>
    <!-- right arm -->
    <g class="arm-r">
      <line x1="796" y1="150" x2="820" y2="170" stroke="#FF6B9D" stroke-width="2" stroke-linecap="round"/>
    </g>

    <!-- left leg -->
    <g class="leg-l">
      <line x1="785" y1="178" x2="768" y2="210" stroke="#6C63FF" stroke-width="2.2" stroke-linecap="round"/>
    </g>
    <!-- right leg -->
    <g class="leg-r">
      <line x1="795" y1="178" x2="812" y2="210" stroke="#6C63FF" stroke-width="2.2" stroke-linecap="round"/>
    </g>
  </g>

  <text x="750" y="244" class="lbl">dance</text>
  <text x="750" y="259" class="sub">yes, actually.</text>
</svg>

*Same mindset across everything — read the game, make your move.*

</div>

---

<div align="center">

## 📈 Activity

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=bhattyuvraj22&bg_color=0d1117&color=6C63FF&line=FF6B9D&point=ffffff&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

---

## 🐍 Snake eating my contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/bhattyuvraj22/bhattyuvraj22/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/bhattyuvraj22/bhattyuvraj22/output/github-contribution-grid-snake.svg"/>
  <img alt="snake animation" src="https://raw.githubusercontent.com/bhattyuvraj22/bhattyuvraj22/output/github-contribution-grid-snake.svg"/>
</picture>

</div>
