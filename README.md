<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>README Preview — saadahmed333</title>
<style>
  :root {
    --bg: #FFFFFF;
    --surface: #F8FAFC;
    --border: #E2E8F0;
    --text: #1E293B;
    --muted: #64748B;
    --accent: #2563EB;
  }
  * { box-sizing: border-box; }
  body {
    background: #EEF1F5;
    margin: 0;
    padding: 56px 16px;
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
  }
  .card {
    max-width: 820px;
    margin: 0 auto;
    background: var(--bg);
    border: 1px solid var(--border);
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 12px 40px rgba(15,23,42,0.08);
    opacity: 0;
    animation: reveal 0.6s ease-out forwards;
  }
  @keyframes reveal {
    from { opacity: 0; transform: translateY(10px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .content { padding: 0 40px 40px 40px; color: var(--text); }
  img.wave { width: calc(100% + 80px); margin: 0 -40px 6px -40px; display: block; }
  .typing-wrap { display: flex; justify-content: center; margin: 4px 0 28px 0; }
  h3.section {
    font-size: 15px;
    font-weight: 600;
    color: var(--text);
    border-bottom: 1px solid var(--border);
    padding-bottom: 8px;
    margin: 32px 0 14px 0;
    letter-spacing: 0.2px;
  }
  p.body { font-size: 14.5px; line-height: 1.7; color: var(--muted); margin: 0 0 16px 0; }
  p.body b { color: var(--text); }
  ul.meta { list-style: none; padding: 0; margin: 0; }
  ul.meta li { font-size: 14px; margin-bottom: 9px; color: var(--muted); }
  ul.meta b { color: var(--text); }
  a { color: var(--accent); text-decoration: none; }
  a:hover { text-decoration: underline; }
  .group-label { font-size: 13px; font-weight: 600; color: var(--muted); margin: 18px 0 10px 0; }
  .icon-row { display: flex; flex-wrap: wrap; gap: 16px; align-items: center; margin-bottom: 4px; }
  .icon-row img { width: 32px; height: 32px; }
  .stats-row { display: flex; justify-content: center; gap: 12px; flex-wrap: wrap; margin: 6px 0; }
  .stats-row img { max-width: 48%; border-radius: 6px; }
  .streak { display: flex; justify-content: center; margin: 4px 0 6px 0; }
  .footer-wave { margin: 30px -40px -40px -40px; width: calc(100% + 80px); }
  .note {
    max-width: 820px; margin: 18px auto 0 auto; color: #94A3B8;
    font-size: 12.5px; text-align: center;
  }
</style>
</head>
<body>

<div class="card">
  <div class="content">
    <img class="wave" src="https://capsule-render.vercel.app/api?type=waving&height=150&section=header&text=Saad%20Ahmed&fontSize=42&fontColor=FFFFFF&fontAlignY=42&animation=fadeIn&color=2563EB" alt="header wave" />

    <div class="typing-wrap">
      <img src="https://readme-typing-svg.demolab.com/?font=Inter&weight=500&size=18&pause=1400&color=2563EB&center=true&vCenter=true&width=560&height=30&lines=Software+Developer;React+%C2%B7+Next.js+%C2%B7+React+Native;Python+%C2%B7+Node.js+%C2%B7+Flutter" alt="typing" />
    </div>

    <h3 class="section">About</h3>
    <p class="body">I'm a software developer building products across web, mobile, and backend — <b>React, Next.js, React Native, Python, Node.js, and Flutter</b>. I'm currently expanding into <b>AI and Data Engineering</b>.</p>
    <ul class="meta">
      <li>📫 <b>Email:</b> saadahmed1742@gmail.com</li>
      <li>📄 <b>Resume:</b> <a href="#">View here</a></li>
      <li>🔗 <b>LinkedIn:</b> <a href="#">saad-ahmed-0700b4249</a></li>
      <li>🏆 <b>HackerRank:</b> <a href="#">@saadahmed1742</a></li>
    </ul>

    <h3 class="section">Skills</h3>

    <div class="group-label">Languages</div>
    <div class="icon-row">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" title="JavaScript"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" title="TypeScript"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" title="Python"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-plain.svg" title="Dart"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" title="C++"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg" title="HTML5"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" title="CSS3"/>
    </div>

    <div class="group-label">Frontend &amp; Mobile</div>
    <div class="icon-row">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original-wordmark.svg" title="React"/>
      <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" title="Next.js"/>
      <img src="https://reactnative.dev/img/header_logo.svg" title="React Native"/>
      <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" title="Flutter"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redux/redux-original.svg" title="Redux"/>
      <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" title="Tailwind CSS"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" title="Sass"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-plain-wordmark.svg" title="Bootstrap"/>
    </div>

    <div class="group-label">Backend</div>
    <div class="icon-row">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original-wordmark.svg" title="Node.js"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original-wordmark.svg" title="Express"/>
      <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" title="Firebase"/>
    </div>

    <div class="group-label">Databases, SQL &amp; Data Engineering</div>
    <div class="icon-row">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" title="MySQL"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original-wordmark.svg" title="PostgreSQL"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original-wordmark.svg" title="MongoDB"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apache/apache-original-wordmark.svg" title="Apache"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original-wordmark.svg" style="background:#fff;border-radius:4px;padding:2px;" title="Kafka"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apacheairflow/apacheairflow-original.svg" title="Airflow"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachespark/apachespark-original.svg" title="Spark"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" style="background:#fff;border-radius:4px;padding:2px;" title="Pandas"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" title="NumPy"/>
    </div>

    <div class="group-label">Tools &amp; Platforms</div>
    <div class="icon-row">
      <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" title="Git"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original-wordmark.svg" title="Docker"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" style="background:#fff;border-radius:4px;padding:2px;" title="AWS"/>
      <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" title="Figma"/>
      <img src="https://cdn.simpleicons.org/adobexd" title="Adobe XD"/>
    </div>

    <h3 class="section">GitHub Stats</h3>
    <div class="stats-row">
      <img src="https://github-stats-extended.vercel.app/api?username=saadahmed333&show_icons=true&hide_border=false&cache_bust=1788722386&bg_color=ffffff&title_color=2563EB&text_color=1E293B&icon_color=2563EB&border_color=e2e8f0" alt="stats"/>
      <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=saadahmed333&layout=compact&hide_border=false&cache_bust=1788722386&bg_color=ffffff&title_color=2563EB&text_color=1E293B&border_color=e2e8f0" alt="top langs"/>
    </div>
    <div class="streak">
      <img src="https://streak-stats.demolab.com?user=saadahmed333&hide_border=false&background=ffffff&border=e2e8f0&ring=2563EB&fire=2563EB&currStreakLabel=1E293B&sideLabels=1E293B&dates=64748B" alt="streak"/>
    </div>

    <img class="footer-wave" src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&animation=fadeIn&color=2563EB" alt="footer wave" />
  </div>
</div>

<div class="note">
  Single accent color (teal), real section headers, no terminal chrome — matches how GitHub renders markdown headers and HTML natively.
</div>

</body>
</html>
