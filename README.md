<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Abdullah — Portfolio</title>
  <meta name="description" content="Portfolio of Abdullah — Graphic Designer " />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#06b6d4;--muted:#94a3b8;--glass: rgba(255,255,255,0.03)}
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,-apple-system,'Segoe UI',Roboto,'Helvetica Neue',Arial;color:#e6eef6;background:linear-gradient(180deg,#071028 0%,#07172b 100%);}
    .container{max-width:1100px;margin:0 auto;padding:32px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:48px;height:48px;border-radius:10px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;color:#021226;font-weight:800}
    nav a{color:var(--muted);text-decoration:none;margin-left:18px;font-weight:600}
    .hero{display:grid;grid-template-columns:1fr 360px;gap:28px;align-items:center;margin-top:40px}
    .hero-card{background:var(--glass);padding:28px;border-radius:16px;box-shadow:0 8px 30px rgba(2,6,23,0.6)}
    h1{font-size:34px;margin:0 0 8px}
    p.lead{color:var(--muted);margin:0 0 16px}
    .btn{display:inline-block;padding:10px 14px;border-radius:10px;background:var(--accent);color:#021226;font-weight:700;text-decoration:none}
    .skills{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .skill{background:rgba(255,255,255,0.04);padding:6px 10px;border-radius:8px;font-weight:600;color:var(--muted)}
    .projects{margin-top:36px;display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
    .card{background:var(--card);padding:16px;border-radius:12px;min-height:160px}
    .card img{width:100%;height:120px;object-fit:cover;border-radius:8px}
    footer{margin-top:48px;padding:20px 0;color:var(--muted);text-align:center}
    @media (max-width:900px){.hero{grid-template-columns:1fr;padding-bottom:12px}.projects{grid-template-columns:repeat(2,1fr)}nav a{display:none}}
    @media (max-width:520px){.projects{grid-template-columns:1fr}h1{font-size:28px}}
    .muted{color:var(--muted)}
    .tag{font-size:12px;padding:6px 8px;border-radius:999px;background:rgba(255,255,255,0.02);display:inline-block}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">AB</div>
        <div>
          <div style="font-weight:800">Abdullah</div>
          <div class="muted" style="font-size:13px">Graphic Designer </div>
        </div>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero">
      <div>
        <div class="hero-card">
          <h1>Hi, I'm <span style="color:var(--accent)">Abdullah</span></h1>
          <p class="lead">I build clean, modern websites and designs. I love creating beautiful  and optimizing performance.</p>
          <a class="btn" href="#contact">Hire me</a>

          <h3 style="margin-top:18px">Skills</h3>
          <div class="skills">
            <div class="skill">Adobe Photoshop</div>
            <div class="skill">Adobe Illustrator</div>
            <div class="skill">Adobe Indesign </div>
            <div class="skill">canva</div>
            <div class="skill">Adobe Premier Pro</div>
          </div>
        </div>

        <section id="projects" style="margin-top:18px">
          <h2 style="margin:12px 0">Projects</h2>
          <div class="projects">
            <article class="card">
             <img src="https://i.postimg.cc/6p2V3WRW/Face-wash-tube-packaging-mockup-20100.jpg" alt="Label Design">

              <h4 style="margin:10px 0 6px">Packaging Design</h4>
              <p class="muted" style="font-size:14px;margin:0">Packaging site </p>
            </article>
            <article class="card">
              <img src="https://i.postimg.cc/8cy1qVz8/Business-Card-Mockup-3.jpg" alt="Business card ">

              <h4 style="margin:10px 0 6px">Graphic Design Mockups</h4>
              <p class="muted" style="font-size:14px;margin:0">Illustrator Design </p>
            </article>
            <article class="card">
              <img src="https://i.postimg.cc/76K8Ln87/Untitled-1-(33).png" alt="Youtube Thumbnail"
              <h4 style="margin:10px 0 6px">Photoshop Design</h4>
              <p class="muted" style="font-size:14px;margin:0">Youtube thumbnail </p>
            </article>
          </div>
        </section>
      </div>

      <aside style="position:relative">
        <div style="background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:18px;border-radius:12px;min-height:200px;">
          <h3 style="margin:0 0 6px">Contact</h3>
          <p class="muted" style="margin:0 0 10px">Email me for freelance or full-time work</p>
          <div style="font-weight:700">abdullahanwer2324@gmail.com</div>

          <div style="margin-top:22px">
            <div class="tag">Available for hire</div>
            <div style="height:12px"></div>
            <div class="muted">Location: Pakistan</div>
            <div class="muted">Phone: +92 3284785341</div>
          </div>
        </div>

        <div style="margin-top:12px;background:var(--card);padding:12px;border-radius:12px;">
          <h4 style="margin:0 0 6px">Quick links</h4>
          <div style="display:flex;flex-direction:column;gap:8px;margin-top:8px">
            <a href="#projects" class="muted">Projects</a>
            <a href="#about" class="muted">About</a>
            <a href="https://i.postimg.cc/4y35JzsJ/Youtube-thumbnail-Designer.png" class="muted">Resume (PDF)</a>
          </div>
        </div>
      </aside>
    </section>

    <section id="about" style="margin-top:36px">
      <div class="hero-card">
        <h2>About me</h2>
        <p class="muted">I design and creative on clean  accessibility and performance. I enjoy turning ideas into polished products.</p>
        <h3 style="margin-top:12px">Experience</h3>
        <ul class="muted">
          <li>Graphic Designer — Company A (2024 - 2025)</li>
        </ul>
      </div>
    </section>

    <section id="contact" style="margin-top:26px">
      <div class="hero-card">
        <h2>Get in touch</h2>
        <p class="muted">Send a message or email me directly.</p>
        <form onsubmit="sendMail(event)">
          <div style="display:flex;gap:10px;flex-wrap:wrap">
            <input id="name" placeholder="Your name" style="flex:1;padding:10px;border-radius:8px;background:transparent;border:1px solid rgba(255,255,255,0.04);color:inherit">
            <input id="email" placeholder="Your email" style="flex:1;padding:10px;border-radius:8px;background:transparent;border:1px solid rgba(255,255,255,0.04);color:inherit">
          </div>
          <textarea id="message" placeholder="Your message" style="width:100%;margin-top:10px;padding:10px;border-radius:8px;background:transparent;border:1px solid rgba(255,255,255,0.04);min-height:120px;color:inherit"></textarea>
          <div style="margin-top:10px"><button class="btn" type="submit">Send</button></div>
        </form>
      </div>
    </section>

    <footer>
      Built with ❤️ — Abdullah • <span class="muted">© 2025</span>
    </footer>
  </div>

  <script>
    function sendMail(e){
      e.preventDefault();
      const name = document.getElementById('name').value || 'No name';
      const email = document.getElementById('email').value || 'no-email@example.com';
      const message = document.getElementById('message').value || '';
      const subject = encodeURIComponent('Portfolio contact from ' + name);
      const body = encodeURIComponent('Name: ' + name + '\nEmail: ' + email + '\n\n' + message);
      window.location.href = `mailto:abdullahanwer2324@gmail.com?subject=${subject}&body=${body}`;
    }
  </script>
</body>
</html>
