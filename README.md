<div align="center">

<!--
████████████████████████████████████████████
  HERO SVG — UNIQUE DARK TERMINAL DESIGN
  Inline so no separate file needed
████████████████████████████████████████████
-->

<svg viewBox="0 0 860 480" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <!-- backgrounds -->
    <linearGradient id="mainBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#020408"/>
      <stop offset="100%" stop-color="#0a0f1a"/>
    </linearGradient>
    <linearGradient id="cardBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#080c12"/>
    </linearGradient>
    <linearGradient id="cyanLine" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="transparent"/>
      <stop offset="30%" stop-color="#00f5ff"/>
      <stop offset="70%" stop-color="#00c8d7"/>
      <stop offset="100%" stop-color="transparent"/>
    </linearGradient>
    <linearGradient id="nameG" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#e2e8f0"/>
      <stop offset="50%" stop-color="#00f5ff"/>
      <stop offset="100%" stop-color="#67e8f9"/>
    </linearGradient>
    <linearGradient id="barC" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#003d4d"/>
      <stop offset="100%" stop-color="#00f5ff"/>
    </linearGradient>
    <linearGradient id="barG" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#14532d"/>
      <stop offset="100%" stop-color="#4ade80"/>
    </linearGradient>
    <linearGradient id="barA" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#451a03"/>
      <stop offset="100%" stop-color="#fbbf24"/>
    </linearGradient>
    <linearGradient id="barP" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#2e1065"/>
      <stop offset="100%" stop-color="#a78bfa"/>
    </linearGradient>
    <linearGradient id="topAccent" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#00f5ff" stop-opacity="0"/>
      <stop offset="20%" stop-color="#00f5ff"/>
      <stop offset="80%" stop-color="#00f5ff"/>
      <stop offset="100%" stop-color="#00f5ff" stop-opacity="0"/>
    </linearGradient>
    <!-- dot grid -->
    <pattern id="grid" x="0" y="0" width="32" height="32" patternUnits="userSpaceOnUse">
      <circle cx="16" cy="16" r="0.6" fill="#00f5ff" fill-opacity="0.05"/>
    </pattern>
    <!-- glow filter -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur in="SourceGraphic" stdDeviation="3" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glowStrong" x="-40%" y="-40%" width="180%" height="180%">
      <feGaussianBlur in="SourceGraphic" stdDeviation="6" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- scan line texture -->
    <pattern id="scan" x="0" y="0" width="1" height="4" patternUnits="userSpaceOnUse">
      <rect width="1" height="1" fill="black" fill-opacity="0.08"/>
    </pattern>
  </defs>

  <!-- ── FULL BG ── -->
  <rect width="860" height="480" fill="url(#mainBg)"/>
  <rect width="860" height="480" fill="url(#grid)"/>
  <rect width="860" height="480" fill="url(#scan)"/>

  <!-- ambient light orbs -->
  <ellipse cx="120" cy="240" rx="260" ry="200" fill="#00f5ff" fill-opacity="0.025"/>
  <ellipse cx="740" cy="240" rx="220" ry="180" fill="#0ea5e9" fill-opacity="0.02"/>
  <ellipse cx="430" cy="60"  rx="300" ry="100" fill="#00f5ff" fill-opacity="0.015"/>

  <!-- ── TOP ACCENT LINE ── -->
  <rect x="0" y="0" width="860" height="1" fill="url(#topAccent)"/>

  <!-- ── CORNER BRACKETS ── -->
  <g stroke="#00f5ff" stroke-width="1.5" fill="none" stroke-opacity="0.4">
    <path d="M18,14 L8,14 L8,28"/>
    <path d="M842,14 L852,14 L852,28"/>
    <path d="M18,466 L8,466 L8,452"/>
    <path d="M842,466 L852,466 L852,452"/>
  </g>

  <!-- ════════════════════════════════════════
       LEFT PANEL — TERMINAL WINDOW
  ════════════════════════════════════════ -->

  <!-- terminal card shadow/glow -->
  <rect x="26" y="36" width="380" height="320" rx="12" fill="#00f5ff" fill-opacity="0.04"/>
  <!-- terminal card -->
  <rect x="24" y="34" width="380" height="320" rx="11" fill="url(#cardBg)" stroke="#1e2938" stroke-width="1"/>
  <!-- top glint line -->
  <line x1="36" y1="34" x2="392" y2="34" stroke="#00f5ff" stroke-width="0.5" stroke-opacity="0.3"/>

  <!-- title bar -->
  <rect x="24" y="34" width="380" height="36" rx="11" fill="#0d1520"/>
  <rect x="24" y="58" width="380" height="12" fill="#0d1520"/>

  <!-- traffic lights -->
  <circle cx="46" cy="52" r="5.5" fill="#ff5f57"/>
  <circle cx="64" cy="52" r="5.5" fill="#febc2e"/>
  <circle cx="82" cy="52" r="5.5" fill="#28c840"/>

  <!-- title bar text -->
  <text x="212" y="56" text-anchor="middle" font-family="'Fira Code','Courier New',monospace" font-size="10.5" fill="#4a5568">● kuldeep@dev: ~/projects</text>

  <!-- terminal prompt line -->
  <text x="40" y="90" font-family="'Fira Code','Courier New',monospace" font-size="11" fill="#4ade80">kuldeep</text>
  <text x="96" y="90" font-family="'Fira Code','Courier New',monospace" font-size="11" fill="#64748b">@</text>
  <text x="105" y="90" font-family="'Fira Code','Courier New',monospace" font-size="11" fill="#00f5ff">dev</text>
  <text x="131" y="90" font-family="'Fira Code','Courier New',monospace" font-size="11" fill="#64748b"> ~/profile </text>
  <text x="207" y="90" font-family="'Fira Code','Courier New',monospace" font-size="11" fill="#a78bfa">$</text>
  <text x="218" y="90" font-family="'Fira Code','Courier New',monospace" font-size="11" fill="#e2e8f0"> cat me.json</text>

  <!-- separator -->
  <line x1="36" y1="100" x2="392" y2="100" stroke="#1e2938" stroke-width="0.5"/>

  <!-- JSON content -->
  <g font-family="'Fira Code','Courier New',monospace" font-size="11">
    <text x="40" y="120" fill="#8892a4">{</text>

    <text x="52" y="139" fill="#64748b">"</text>
    <text x="57" y="139" fill="#79c0ff">name</text>
    <text x="91" y="139" fill="#64748b">":</text>
    <text x="103" y="139" fill="#a5d6ff">"Kuldeep Chudasama"</text>
    <text x="264" y="139" fill="#8892a4">,</text>

    <text x="52" y="157" fill="#64748b">"</text>
    <text x="57" y="157" fill="#79c0ff">role</text>
    <text x="85" y="157" fill="#64748b">":</text>
    <text x="97" y="157" fill="#a5d6ff">"Full Stack Developer"</text>
    <text x="272" y="157" fill="#8892a4">,</text>

    <text x="52" y="175" fill="#64748b">"</text>
    <text x="57" y="175" fill="#79c0ff">stack</text>
    <text x="91" y="175" fill="#64748b">":</text>
    <text x="103" y="175" fill="#8892a4">[</text>
    <text x="111" y="175" fill="#a5d6ff">"MERN"</text>
    <text x="161" y="175" fill="#8892a4">,</text>
    <text x="169" y="175" fill="#a5d6ff">"PHP"</text>
    <text x="203" y="175" fill="#8892a4">,</text>
    <text x="211" y="175" fill="#a5d6ff">"CMS"</text>
    <text x="247" y="175" fill="#8892a4">],</text>

    <text x="52" y="193" fill="#64748b">"</text>
    <text x="57" y="193" fill="#79c0ff">location</text>
    <text x="109" y="193" fill="#64748b">":</text>
    <text x="121" y="193" fill="#a5d6ff">"India 🇮🇳"</text>
    <text x="205" y="193" fill="#8892a4">,</text>

    <text x="52" y="211" fill="#64748b">"</text>
    <text x="57" y="211" fill="#79c0ff">status</text>
    <text x="97" y="211" fill="#64748b">":</text>
    <text x="109" y="211" fill="#4ade80">"🟢 Available"</text>
    <text x="216" y="211" fill="#8892a4">,</text>

    <text x="52" y="229" fill="#64748b">"</text>
    <text x="57" y="229" fill="#79c0ff">perfect</text>
    <text x="103" y="229" fill="#64748b">":</text>
    <text x="115" y="229" fill="#ff7b72">false</text>
    <text x="144" y="229" fill="#8892a4">,</text>
    <text x="160" y="229" fill="#3d4a5c">// honest</text>

    <text x="52" y="247" fill="#64748b">"</text>
    <text x="57" y="247" fill="#79c0ff">improving</text>
    <text x="115" y="247" fill="#64748b">":</text>
    <text x="127" y="247" fill="#4ade80">true</text>
    <text x="153" y="247" fill="#8892a4">,</text>
    <text x="168" y="247" fill="#3d4a5c">// always ∞</text>

    <text x="52" y="265" fill="#64748b">"</text>
    <text x="57" y="265" fill="#79c0ff">coffee</text>
    <text x="97" y="265" fill="#64748b">":</text>
    <text x="109" y="265" fill="#fbbf24">"yes please ☕"</text>
    <text x="231" y="265" fill="#8892a4">,</text>

    <text x="52" y="283" fill="#64748b">"</text>
    <text x="57" y="283" fill="#79c0ff">giveUp</text>
    <text x="103" y="283" fill="#64748b">":</text>
    <text x="115" y="283" fill="#a78bfa">() =&gt; never</text>
    <text x="205" y="283" fill="#3d4a5c">// undefined</text>

    <text x="40" y="301" fill="#8892a4">}</text>

    <!-- blinking cursor line -->
    <text x="40" y="318" fill="#4ade80">$</text>
    <text x="52" y="318" fill="#e2e8f0"> _</text>
  </g>

  <!-- ════════════════════════════════════════
       RIGHT PANEL — NAME + STATS
  ════════════════════════════════════════ -->

  <!-- big name with glow -->
  <text x="456" y="110" font-family="'Segoe UI',Arial,sans-serif" font-size="22" font-weight="700" fill="#00f5ff" fill-opacity="0.18" filter="url(#glowStrong)">Kuldeep Chudasama</text>
  <text x="456" y="110" font-family="'Segoe UI',Arial,sans-serif" font-size="22" font-weight="700" fill="url(#nameG)">Kuldeep Chudasama</text>

  <!-- role line -->
  <text x="456" y="136" font-family="'Fira Code','Courier New',monospace" font-size="12" fill="#64748b" letter-spacing="2">FULL STACK · MERN · CMS · THEME</text>

  <!-- cyan accent bar -->
  <rect x="456" y="148" width="370" height="1.5" rx="1" fill="url(#cyanLine)" opacity="0.8"/>

  <!-- ── SKILL BARS (right panel) ── -->
  <!-- Languages heading -->
  <text x="456" y="172" font-family="'Fira Code','Courier New',monospace" font-size="9" fill="#00f5ff" letter-spacing="2.5">// LANGUAGES</text>
  <line x1="570" y1="168" x2="826" y2="168" stroke="#1e2938" stroke-width="0.5"/>

  <!-- JS bar -->
  <text x="456" y="188" font-family="'Fira Code','Courier New',monospace" font-size="10.5" fill="#c9d1d9">JS</text>
  <rect x="490" y="180" width="280" height="5" rx="2.5" fill="#0d1520"/>
  <rect x="490" y="180" width="224" height="5" rx="2.5" fill="url(#barC)"/>
  <text x="778" y="188" font-family="'Fira Code','Courier New',monospace" font-size="10" fill="#00f5ff" text-anchor="end">80%</text>
  <text x="784" y="188" font-family="'Fira Code','Courier New',monospace" font-size="9" fill="#3d4a5c">Advanced</text>

  <!-- PHP bar -->
  <text x="456" y="204" font-family="'Fira Code','Courier New',monospace" font-size="10.5" fill="#c9d1d9">PHP</text>
  <rect x="490" y="196" width="280" height="5" rx="2.5" fill="#0d1520"/>
  <rect x="490" y="196" width="182" height="5" rx="2.5" fill="url(#barP)"/>
  <text x="778" y="204" font-family="'Fira Code','Courier New',monospace" font-size="10" fill="#a78bfa" text-anchor="end">65%</text>
  <text x="784" y="204" font-family="'Fira Code','Courier New',monospace" font-size="9" fill="#3d4a5c">Intermediate+</text>

  <!-- TS bar -->
  <text x="456" y="220" font-family="'Fira Code','Courier New',monospace" font-size="10.5" fill="#c9d1d9">TS</text>
  <rect x="490" y="212" width="280" height="5" rx="2.5" fill="#0d1520"/>
  <rect x="490" y="212" width="168" height="5" rx="2.5" fill="url(#barC)"/>
  <text x="778" y="220" font-family="'Fira Code','Courier New',monospace" font-size="10" fill="#00f5ff" text-anchor="end">60%</text>
  <text x="784" y="220" font-family="'Fira Code','Courier New',monospace" font-size="9" fill="#3d4a5c">Intermediate</text>

  <!-- CMS heading -->
  <text x="456" y="244" font-family="'Fira Code','Courier New',monospace" font-size="9" fill="#00f5ff" letter-spacing="2.5">// CMS &amp; THEME</text>
  <line x1="570" y1="240" x2="826" y2="240" stroke="#1e2938" stroke-width="0.5"/>

  <!-- WordPress -->
  <text x="456" y="260" font-family="'Fira Code','Courier New',monospace" font-size="10.5" fill="#c9d1d9">WP</text>
  <rect x="490" y="252" width="280" height="5" rx="2.5" fill="#0d1520"/>
  <rect x="490" y="252" width="252" height="5" rx="2.5" fill="url(#barC)"/>
  <text x="778" y="260" font-family="'Fira Code','Courier New',monospace" font-size="10" fill="#00f5ff" text-anchor="end">90%</text>
  <text x="784" y="260" font-family="'Fira Code','Courier New',monospace" font-size="9" fill="#3d4a5c">Expert</text>

  <!-- Shopify -->
  <text x="456" y="276" font-family="'Fira Code','Courier New',monospace" font-size="10.5" fill="#c9d1d9">SHO</text>
  <rect x="490" y="268" width="280" height="5" rx="2.5" fill="#0d1520"/>
  <rect x="490" y="268" width="224" height="5" rx="2.5" fill="url(#barG)"/>
  <text x="778" y="276" font-family="'Fira Code','Courier New',monospace" font-size="10" fill="#4ade80" text-anchor="end">80%</text>
  <text x="784" y="276" font-family="'Fira Code','Courier New',monospace" font-size="9" fill="#3d4a5c">Advanced</text>

  <!-- Joomla -->
  <text x="456" y="292" font-family="'Fira Code','Courier New',monospace" font-size="10.5" fill="#c9d1d9">JML</text>
  <rect x="490" y="284" width="280" height="5" rx="2.5" fill="#0d1520"/>
  <rect x="490" y="284" width="182" height="5" rx="2.5" fill="url(#barA)"/>
  <text x="778" y="292" font-family="'Fira Code','Courier New',monospace" font-size="10" fill="#fbbf24" text-anchor="end">65%</text>
  <text x="784" y="292" font-family="'Fira Code','Courier New',monospace" font-size="9" fill="#3d4a5c">Intermediate+</text>

  <!-- Moodle -->
  <text x="456" y="308" font-family="'Fira Code','Courier New',monospace" font-size="10.5" fill="#c9d1d9">MDL</text>
  <rect x="490" y="300" width="280" height="5" rx="2.5" fill="#0d1520"/>
  <rect x="490" y="300" width="168" height="5" rx="2.5" fill="url(#barA)"/>
  <text x="778" y="308" font-family="'Fira Code','Courier New',monospace" font-size="10" fill="#fbbf24" text-anchor="end">60%</text>
  <text x="784" y="308" font-family="'Fira Code','Courier New',monospace" font-size="9" fill="#3d4a5c">Intermediate</text>

  <!-- ── BOTTOM STATS ROW ── -->
  <line x1="456" y1="328" x2="836" y2="328" stroke="#1e2938" stroke-width="0.5"/>

  <!-- stat boxes -->
  <!-- 3+ yrs -->
  <rect x="456" y="336" width="84" height="52" rx="7" fill="#0d1520" stroke="#1e2938" stroke-width="1"/>
  <text x="498" y="358" text-anchor="middle" font-family="'Segoe UI',Arial,sans-serif" font-size="22" font-weight="800" fill="#00f5ff" filter="url(#glow)">3+</text>
  <text x="498" y="374" text-anchor="middle" font-family="'Fira Code','Courier New',monospace" font-size="8" fill="#4a5568" letter-spacing="1">YRS EXP</text>

  <!-- 50+ projects -->
  <rect x="548" y="336" width="84" height="52" rx="7" fill="#0d1520" stroke="#1e2938" stroke-width="1"/>
  <text x="590" y="358" text-anchor="middle" font-family="'Segoe UI',Arial,sans-serif" font-size="22" font-weight="800" fill="#4ade80" filter="url(#glow)">50+</text>
  <text x="590" y="374" text-anchor="middle" font-family="'Fira Code','Courier New',monospace" font-size="8" fill="#4a5568" letter-spacing="1">PROJECTS</text>

  <!-- 10+ cms -->
  <rect x="640" y="336" width="84" height="52" rx="7" fill="#0d1520" stroke="#1e2938" stroke-width="1"/>
  <text x="682" y="358" text-anchor="middle" font-family="'Segoe UI',Arial,sans-serif" font-size="22" font-weight="800" fill="#fbbf24" filter="url(#glow)">10+</text>
  <text x="682" y="374" text-anchor="middle" font-family="'Fira Code','Courier New',monospace" font-size="8" fill="#4a5568" letter-spacing="1">CMS BUILDS</text>

  <!-- coffees -->
  <rect x="732" y="336" width="84" height="52" rx="7" fill="#0d1520" stroke="#1e2938" stroke-width="1"/>
  <text x="774" y="358" text-anchor="middle" font-family="'Segoe UI',Arial,sans-serif" font-size="22" font-weight="800" fill="#f87171" filter="url(#glow)">∞</text>
  <text x="774" y="374" text-anchor="middle" font-family="'Fira Code','Courier New',monospace" font-size="8" fill="#4a5568" letter-spacing="1">COFFEES ☕</text>

  <!-- ── TECH TAG PILLS ── -->
  <g font-family="'Fira Code','Courier New',monospace" font-size="9.5">
    <!-- React -->
    <rect x="456" y="400" width="52" height="20" rx="4" fill="#061220" stroke="#1e3a5f" stroke-width="1"/>
    <text x="482" y="414" text-anchor="middle" fill="#61dafb">React</text>
    <!-- Node -->
    <rect x="514" y="400" width="56" height="20" rx="4" fill="#061a0a" stroke="#14532d" stroke-width="1"/>
    <text x="542" y="414" text-anchor="middle" fill="#4ade80">Node.js</text>
    <!-- MongoDB -->
    <rect x="576" y="400" width="68" height="20" rx="4" fill="#051a05" stroke="#15803d" stroke-width="1"/>
    <text x="610" y="414" text-anchor="middle" fill="#4ade80">MongoDB</text>
    <!-- Express -->
    <rect x="650" y="400" width="64" height="20" rx="4" fill="#0d0d0d" stroke="#333" stroke-width="1"/>
    <text x="682" y="414" text-anchor="middle" fill="#94a3b8">Express</text>
    <!-- Bootstrap -->
    <rect x="720" y="400" width="76" height="20" rx="4" fill="#12062c" stroke="#4c1d95" stroke-width="1"/>
    <text x="758" y="414" text-anchor="middle" fill="#a78bfa">Bootstrap</text>

    <!-- row 2 -->
    <rect x="456" y="426" width="76" height="20" rx="4" fill="#1a0a00" stroke="#92400e" stroke-width="1"/>
    <text x="494" y="440" text-anchor="middle" fill="#fbbf24">WordPress</text>
    <rect x="538" y="426" width="60" height="20" rx="4" fill="#0a1a06" stroke="#166534" stroke-width="1"/>
    <text x="568" y="440" text-anchor="middle" fill="#4ade80">Shopify</text>
    <rect x="604" y="426" width="54" height="20" rx="4" fill="#1a0a00" stroke="#78350f" stroke-width="1"/>
    <text x="631" y="440" text-anchor="middle" fill="#fbbf24">Joomla</text>
    <rect x="664" y="426" width="58" height="20" rx="4" fill="#1a0a00" stroke="#7c2d12" stroke-width="1"/>
    <text x="693" y="440" text-anchor="middle" fill="#fb923c">Moodle</text>
    <rect x="728" y="426" width="42" height="20" rx="4" fill="#120626" stroke="#4c1d95" stroke-width="1"/>
    <text x="749" y="440" text-anchor="middle" fill="#a78bfa">PHP</text>
  </g>

  <!-- ── DIVIDER LINE ── -->
  <line x1="440" y1="34" x2="440" y2="468" stroke="#1e2938" stroke-width="0.5" stroke-dasharray="4,4"/>

  <!-- ── BOTTOM BAR ── -->
  <rect x="0" y="460" width="860" height="20" fill="#020408"/>
  <rect x="0" y="460" width="860" height="0.5" fill="url(#cyanLine)" opacity="0.3"/>
  <text x="430" y="473" text-anchor="middle" font-family="'Fira Code','Courier New',monospace" font-size="8.5" fill="#2d3748">github.com/Kuldip1211  ·  kuldeepchudasama6999@gmail.com  ·  India 🇮🇳</text>
</svg>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=17&pause=1000&color=00F5FF&center=true&vCenter=true&width=700&lines=Hey+%F0%9F%91%8B+Welcome+to+my+GitHub!;MERN+Stack+%7C+CMS+%7C+Theme+Developer;WordPress+%7C+Shopify+%7C+Joomla+%7C+Moodle;Always+building.+Always+learning.+%F0%9F%94%A5" alt="Typing SVG"/>

<br/><br/>

<img src="https://img.shields.io/badge/Status-Available%20for%20hire-00f5ff?style=for-the-badge&labelColor=0d1117&logo=checkmarx&logoColor=00f5ff"/>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=Kuldip1211&style=for-the-badge&color=00f5ff&labelColor=0d1117&label=PROFILE+VIEWS"/>
&nbsp;
<img src="https://img.shields.io/github/followers/Kuldip1211?style=for-the-badge&color=00f5ff&labelColor=0d1117&logo=github"/>

</div>

---

## 💬 My Daily Standup

| # | Question | Answer |
|:-:|:---------|:-------|
| ✅ | What did you do yesterday? | Googled how to center a div... again |
| ✅ | What will you do today? | Push to `main` and pray 🙏 |
| ❌ | Any blockers? | Yes. Stack Overflow is down |
| 🤔 | ETA on the fix? | "It's almost done" *(since 3 days)* |

---

## 👨‍💻 About Me

- 🔭 &nbsp; Full Stack Developer — **MERN + PHP + CMS**
- 🎨 &nbsp; Expert in **WordPress · Shopify · Joomla · Moodle** theme development
- ⚡ &nbsp; Building **scalable web apps** and **custom CMS solutions**
- 🌱 &nbsp; Currently learning **Docker · CI/CD · AWS · System Design**
- 💼 &nbsp; Open to **Freelance** and **Full-time** opportunities
- 📍 &nbsp; Based in **India 🇮🇳**
- ☕ &nbsp; `while(alive) { code(); drinkCoffee(); }`
- 😅 &nbsp; `perfect = false` but `improving = true` — always

---

## ⚡ Tech Arsenal

<div align="center">

### 🟨 Languages

<img src="https://skillicons.dev/icons?i=js,ts,php,java&theme=dark&perline=8"/>

| Skill | Bar | Level |
|:------|:---:|------:|
| JavaScript | `████████████████░░░░` | **Advanced** 80% |
| PHP | `█████████████░░░░░░░` | **Intermediate+** 65% |
| TypeScript | `████████████░░░░░░░░` | **Intermediate** 60% |
| Java | `████████░░░░░░░░░░░░` | **Familiar** 40% |

### ⚛️ Frontend

<img src="https://skillicons.dev/icons?i=html,css,react,redux,bootstrap,tailwind&theme=dark&perline=8"/>

| Skill | Bar | Level |
|:------|:---:|------:|
| HTML5 / CSS3 | `██████████████████░░` | **Expert** 90% |
| React.js | `████████████████░░░░` | **Advanced** 80% |
| Bootstrap | `████████████████░░░░` | **Advanced** 80% |
| Redux / Recoil | `█████████████░░░░░░░` | **Intermediate+** 65% |

### 🖥️ Backend & Database

<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb&theme=dark&perline=8"/>

| Skill | Bar | Level |
|:------|:---:|------:|
| Node.js | `████████████████░░░░` | **Advanced** 80% |
| Express.js | `████████████████░░░░` | **Advanced** 80% |
| MongoDB | `██████████████░░░░░░` | **Intermediate+** 70% |

### 🧩 CMS & Theme Development

<img src="https://skillicons.dev/icons?i=wordpress,shopify&theme=dark&perline=8"/>

| Skill | Bar | Level |
|:------|:---:|------:|
| Custom Theme Dev | `███████████████████░` | **Expert** 95% |
| WordPress | `██████████████████░░` | **Expert** 90% |
| Shopify (Liquid) | `████████████████░░░░` | **Advanced** 80% |
| Joomla | `█████████████░░░░░░░` | **Intermediate+** 65% |
| Moodle | `████████████░░░░░░░░` | **Intermediate** 60% |

</div>

---

## 🤣 Dev Life in Memes

<div align="center">

<table>
<tr>
<td align="center" width="33%">

**When code works on first try**

![works](https://media.giphy.com/media/5z0cCCGooBQUtejM4v/giphy.gif)

*Happened once. In 2019.*

</td>
<td align="center" width="33%">

**Me at 2AM debugging**

![debug](https://media.giphy.com/media/iIqmM5tTjmpOB9mpbn/giphy.gif)

*"It was just a semicolon" 😭*

</td>
<td align="center" width="33%">

**Pushing to production Friday**

![production](https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif)

*Praying to the server gods 🙏*

</td>
</tr>
</table>

</div>

---

## 📊 GitHub Dashboard

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Kuldip1211&show_icons=true&theme=chartreuse-dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=00f5ff&icon_color=00f5ff&text_color=c9d1d9&border_radius=10"/>
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kuldip1211&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00f5ff&text_color=c9d1d9&border_radius=10&langs_count=8"/>

<br/><br/>

<img width="70%" src="https://github-readme-streak-stats.herokuapp.com/?user=Kuldip1211&theme=black-ice&hide_border=true&stroke=0000&background=0d1117&ring=00f5ff&fire=ff6b6b&currStreakLabel=00f5ff&sideLabels=8b949e&dates=8b949e"/>

</div>

---

## 📈 Contribution Graph

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Kuldip1211&bg_color=0d1117&color=00f5ff&line=00f5ff&point=ff6b6b&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=Kuldip1211&theme=matrix&no-frame=true&no-bg=true&margin-w=6&column=6)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Kuldip1211/Kuldip1211/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Kuldip1211/Kuldip1211/output/github-contribution-grid-snake.svg"/>
  <img alt="snake" src="https://raw.githubusercontent.com/Kuldip1211/Kuldip1211/output/github-contribution-grid-snake-dark.svg"/>
</picture>

</div>

---

## 😂 Honest Dev Stats

<div align="center">

<img src="https://readme-jokes.vercel.app/api?theme=dark&bgColor=%230d1117&borderColor=%2321262d&textColor=%23c9d1d9&qColor=%2300f5ff&aColor=%238b949e" alt="Dev Joke"/>

</div>

<br/>

| What I Say | What I Actually Mean |
|:-----------|:---------------------|
| 🧑‍💻 "Writing clean code" | Copy-pasting from Stack Overflow |
| 🐛 "Quick bug fix" | 4 hours and 12 coffees later |
| 📝 "Adding comments" | `// TODO: fix this later` *(from 2 years ago)* |
| 🚀 "Deploying to prod" | *types nervously and closes laptop* |
| ⏰ "5 minute task" | It's been 3 days |
| 📖 "Reading the docs" | Ctrl+F → copy → paste → hope |

---

## 🌱 Currently Leveling Up

<div align="center">

| Technology | Status | Progress |
|:-----------|:------:|:---------|
| 🐳 Docker | 📖 Learning | `████░░░░░░░░░░░░░░░░` 20% |
| ⚙️ CI/CD | 📖 Exploring | `████░░░░░░░░░░░░░░░░` 20% |
| ☁️ AWS | 📖 Starting | `███░░░░░░░░░░░░░░░░░` 15% |
| 🏗️ System Design | 📖 Reading | `██████░░░░░░░░░░░░░░` 30% |

</div>

---

## 🛠️ Dev Tools

<div align="center">

<img src="https://skillicons.dev/icons?i=vscode,git,github,postman,figma,linux,docker&theme=dark&perline=8"/>

</div>

---

## 🧠 Life Philosophy

```javascript
// The honest developer manifesto
const kuldeep = {
  name:      "Kuldeep Chudasama",
  role:      "Full Stack Developer",
  coffee:    () => "yes please ☕",
  code:      () => "always — even at 2AM",
  learn:     () => "every single day",
  perfect:   false,          // honest — nobody is
  improving: true,           // always — no exceptions
  giveUp:    () => never,    // this function is undefined
  mood: (bugs) => bugs > 0 ? "debugging mode 🐛" : "who are you kidding",
};

// The real developer loop
while (kuldeep.alive) {
  drinkCoffee();
  writeCode();
  encounterBug();          // always returns true
  searchStackOverflow();   // 50% of the day
  pushToGit();
  if (itWorked) celebrate();   // lasts 3 seconds
  else          repeat();      // lasts 3 days
}
// spoiler: itWorked is almost always false on the first try
```

---

## 📡 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kuldeep-chudasama-1759b1256/)
&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-Drop_a_Mail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kuldeepchudasama6999@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-@Kuldip1211-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kuldip1211)

<br/>

<img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="60"/>

**Drop a message — let's build something awesome together!**

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020408,50:00f5ff,100:020408&height=100&section=footer"/>

*"Not perfect — just persistent. Every bug is a lesson. Every PR is progress."*

</div>
