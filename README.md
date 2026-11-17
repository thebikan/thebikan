<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 340" width="100%" role="img" aria-label="Thebikan animated terminal banner">
<defs>
<pattern id="d1" width="7" height="7" patternUnits="userSpaceOnUse"><circle cx="3.5" cy="3.5" r="1.5" fill="#c9ee52"/></pattern>
<pattern id="d2" width="5" height="5" patternUnits="userSpaceOnUse"><circle cx="2.5" cy="2.5" r="0.9" fill="#39ff14"/></pattern>
<radialGradient id="fade"><stop offset="0" stop-color="#fff"/><stop offset="0.55" stop-color="#fff" stop-opacity="0.6"/><stop offset="1" stop-color="#000"/></radialGradient>
<mask id="mL" maskUnits="userSpaceOnUse" x="-50" y="0" width="450" height="340"><ellipse cx="150" cy="170" rx="210" ry="150" fill="url(#fade)"/></mask>
<mask id="mR" maskUnits="userSpaceOnUse" x="600" y="0" width="450" height="340"><ellipse cx="850" cy="170" rx="210" ry="150" fill="url(#fade)"/></mask>
<linearGradient id="bg" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#0b1410"/><stop offset="1" stop-color="#0d1117"/></linearGradient>
<linearGradient id="beam" x1="0" y1="0" x2="1" y2="0"><stop offset="0" stop-color="#c9ee52" stop-opacity="0"/><stop offset="0.5" stop-color="#c9ee52"/><stop offset="1" stop-color="#c9ee52" stop-opacity="0"/></linearGradient>
<clipPath id="c0"><rect x="326" y="98" width="0" height="28"><animate attributeName="width" values="0;0;356;356;0" keyTimes="0;0.04;0.14;0.93;1" dur="11s" repeatCount="indefinite"/></rect></clipPath>
<clipPath id="c1"><rect x="326" y="128" width="0" height="28"><animate attributeName="width" values="0;0;356;356;0" keyTimes="0;0.18;0.28;0.93;1" dur="11s" repeatCount="indefinite"/></rect></clipPath>
<clipPath id="c2"><rect x="326" y="158" width="0" height="28"><animate attributeName="width" values="0;0;356;356;0" keyTimes="0;0.34;0.44000000000000006;0.93;1" dur="11s" repeatCount="indefinite"/></rect></clipPath>
<clipPath id="c3"><rect x="326" y="188" width="0" height="28"><animate attributeName="width" values="0;0;356;356;0" keyTimes="0;0.48;0.58;0.93;1" dur="11s" repeatCount="indefinite"/></rect></clipPath>
<clipPath id="c4"><rect x="326" y="218" width="0" height="28"><animate attributeName="width" values="0;0;356;356;0" keyTimes="0;0.62;0.72;0.93;1" dur="11s" repeatCount="indefinite"/></rect></clipPath>
</defs>
<rect width="1000" height="340" rx="14" fill="url(#bg)"/>
<rect x="0.5" y="0.5" width="999" height="339" rx="14" fill="none" stroke="#c9ee52" stroke-opacity="0.25"/>

<!-- left dithered cloud drifting in -->
<g mask="url(#mL)">
 <g><rect x="-60" y="0" width="460" height="340" fill="url(#d1)"/>
 <animateTransform attributeName="transform" type="translate" values="-14 0;22 0;-14 0" dur="6s" repeatCount="indefinite"/></g>
</g>
<!-- right dithered cloud drifting in -->
<g mask="url(#mR)">
 <g><rect x="600" y="0" width="460" height="340" fill="url(#d2)"/>
 <animateTransform attributeName="transform" type="translate" values="14 0;-22 0;14 0" dur="6s" repeatCount="indefinite"/></g>
</g>

<!-- reaching beams + spark -->
<rect x="230" y="168" width="90" height="3" fill="url(#beam)" opacity="0.8"><animate attributeName="opacity" values="0.2;0.9;0.2" dur="2.4s" repeatCount="indefinite"/></rect>
<rect x="690" y="168" width="90" height="3" fill="url(#beam)" opacity="0.8"><animate attributeName="opacity" values="0.9;0.2;0.9" dur="2.4s" repeatCount="indefinite"/></rect>
<circle cx="500" cy="14" r="3" fill="#c9ee52"><animate attributeName="opacity" values="1;0.2;1" dur="1.6s" repeatCount="indefinite"/></circle>

<!-- terminal window -->
<rect x="300" y="52" width="400" height="236" rx="12" fill="#0d1117" stroke="#c9ee52" stroke-width="1.5"/>
<rect x="300" y="52" width="400" height="34" rx="12" fill="#161b22"/>
<rect x="300" y="72" width="400" height="14" fill="#161b22"/>
<circle cx="322" cy="69" r="5" fill="#ff5f56"/><circle cx="340" cy="69" r="5" fill="#ffbd2e"/><circle cx="358" cy="69" r="5" fill="#39ff14"/>
<text x="500" y="73" font-size="12" fill="#8b949e" text-anchor="middle" font-family="monospace">thebikan@portfolio ~</text>
<g font-family="SFMono-Regular,Consolas,'Liberation Mono',Menlo,monospace">
<text x="330" y="118" font-size="16" font-weight="400" fill="#8b949e" clip-path="url(#c0)">$ whoami</text>
<text x="330" y="148" font-size="22" font-weight="700" fill="#ffffff" clip-path="url(#c1)">Thebikan Sriranganathan</text>
<text x="330" y="178" font-size="16" font-weight="700" fill="#c9ee52" clip-path="url(#c2)">Full-Stack Developer</text>
<text x="330" y="208" font-size="16" font-weight="400" fill="#c9d1d9" clip-path="url(#c3)">TypeScript · React · Node.js · C#</text>
<text x="330" y="238" font-size="16" font-weight="400" fill="#8b949e" clip-path="url(#c4)">open to junior &amp; remote roles</text>
<text x="330" y="268" font-size="16" fill="#c9ee52">$</text>
<rect x="346" y="254" width="10" height="18" fill="#c9ee52"><animate attributeName="opacity" values="1;1;0;0" keyTimes="0;0.5;0.5;1" dur="1s" repeatCount="indefinite"/></rect>
</g>

<!-- twinkling pixels -->
<g fill="#c9ee52">
<rect x="120" y="60" width="4" height="4"><animate attributeName="opacity" values="0;1;0" dur="3s" repeatCount="indefinite"/></rect>
<rect x="210" y="270" width="4" height="4"><animate attributeName="opacity" values="0;1;0" dur="2.6s" begin="0.8s" repeatCount="indefinite"/></rect>
<rect x="860" y="70" width="4" height="4"><animate attributeName="opacity" values="0;1;0" dur="3.4s" begin="0.4s" repeatCount="indefinite"/></rect>
<rect x="790" y="280" width="4" height="4"><animate attributeName="opacity" values="0;1;0" dur="2.8s" begin="1.2s" repeatCount="indefinite"/></rect>
</g>
</svg>

<!--
  SETUP
  1. Put this file at the ROOT of your repo  thebikan/thebikan  (README.md)
  2. Create a folder  assets/  in that repo and upload  hero.svg  into it
  3. Replace YOUR_EMAIL below. Username is already "thebikan".
  Accent colour: lime #c9ee52 (matches your profile photo)  |  Card bg: #0d1117
-->

<div align="center">

<img src="assets/hero.svg" alt="Thebikan – Full-Stack Developer" width="100%" />

<br/>

<img src="https://img.shields.io/badge/Jaffna%2C%20Sri%20Lanka-0d1117?style=for-the-badge&logo=googlemaps&logoColor=c9ee52" alt="location" />
<img src="https://img.shields.io/badge/Open%20to%20Work-c9ee52?style=for-the-badge&logoColor=0d1117&labelColor=0d1117" alt="open to work" />
<img src="https://komarev.com/ghpvc/?username=thebikan&label=Profile%20views&color=c9ee52&style=for-the-badge&labelColor=0d1117" alt="views" />

</div>

<br/>

## 🚀 About Me

Final-year **BSc (Hons) Computer Science** student at ESOFT Metro Campus (London Metropolitan University), based in **Jaffna, Sri Lanka**.

I build full-stack web platforms with **TypeScript, React / Next.js, Node.js, C# and SQL Server**, and I use AI-assisted tools like **Cursor** to ship faster without dropping code quality.

> 🎯 **Goal:** write clean code, build reliable software, and grow into an engineer who creates systems that last.

<br/>

## 🛠️ Featured Projects

<table>
  <tr>
    <td width="26%"><b>⚡ CreatorOS</b></td>
    <td>AI-powered social media management SaaS for marketing agencies.<br/>
      <img src="https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=c9ee52" />
      <img src="https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=c9ee52" />
      <img src="https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=c9ee52" />
    </td>
  </tr>
  <tr>
    <td><b>🤝 Connectify</b></td>
    <td>Two-sided influencer ↔ business marketplace — final year project.<br/>
      <img src="https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=c9ee52" />
      <img src="https://img.shields.io/badge/Full--Stack-0d1117?style=flat-square&logoColor=c9ee52" />
    </td>
  </tr>
  <tr>
    <td><b>💳 NovaCredit</b></td>
    <td>Solo full-stack build — currently in progress.<br/>
      <img src="https://img.shields.io/badge/In%20Progress-c9ee52?style=flat-square&labelColor=0d1117" />
    </td>
  </tr>
  <tr>
    <td><b>💊 SmartMed</b></td>
    <td>Pharmacy management system — layered C# .NET WinForms app (UI / BLL / DAL) with SQL Server, unit tests and a test plan.<br/>
      <img src="https://img.shields.io/badge/C%23-0d1117?style=flat-square&logo=csharp&logoColor=c9ee52" />
      <img src="https://img.shields.io/badge/SQL%20Server-0d1117?style=flat-square&logo=microsoftsqlserver&logoColor=c9ee52" />
    </td>
  </tr>
</table>

<br/>

## 💻 Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,cs,dotnet,java,go,postgres,mysql,docker,git,github,vscode,html,css,tailwind,figma&theme=dark&perline=10" alt="tech stack" />
</p>

<br/>

## 📊 GitHub Stats

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=thebikan&show_icons=true&hide_border=true&bg_color=0d1117&title_color=c9ee52&icon_color=c9ee52&text_color=c9d1d9&ring_color=c9ee52" alt="stats" />
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thebikan&layout=compact&hide_border=true&bg_color=0d1117&title_color=c9ee52&text_color=c9d1d9" alt="top languages" />
</p>

<p align="center">
  <img width="100%" src="https://streak-stats.demolab.com?user=thebikan&hide_border=true&background=0d1117&ring=c9ee52&fire=c9ee52&currStreakLabel=c9ee52&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=8b949e" alt="streak" />
</p>

<br/>

## 📈 Activity Graph

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=thebikan&bg_color=0d1117&color=c9ee52&line=c9ee52&point=ffffff&area=true&area_color=c9ee52&hide_border=true" alt="activity graph" />
</p>

<br/>

## 🤝 Let's Connect

<p align="center">
  <a href="https://thebikan.dev"><img src="https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=googlechrome&logoColor=c9ee52" alt="portfolio" /></a>
  <a href="https://linkedin.com/in/thebikan"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=c9ee52" alt="linkedin" /></a>
  <a href="https://x.com/Thebikan_"><img src="https://img.shields.io/badge/X-0d1117?style=for-the-badge&logo=x&logoColor=c9ee52" alt="x" /></a>
  <a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=c9ee52" alt="email" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&height=90&color=0:0d1117,100:c9ee52&section=footer" width="100%" alt="footer" />
