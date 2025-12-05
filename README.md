<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Baatah Fahed Braimah — Cybersecurity Expert</title>
  <meta name="description" content="Baatah Fahed Braimah — Cybersecurity Expert. CEO Baatah Cyber Academy, Baatah Consultancy (upcoming), Co-founder Baitul Zakireen. Contact: baatahfahed182@gmail.com" />
  <!-- Google Font (optional) -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b1220; /* deep navy */
      --card:#0f1724;
      --muted:#cbd5e1;
      --accent:#1e90ff; /* blue */
      --white:#ffffff;
      --glass: rgba(255,255,255,0.03);
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;
      background: linear-gradient(180deg,var(--bg), #07101a);
      color:var(--muted);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.5;
    }

    a{color:var(--accent); text-decoration:none}
    a.button{display:inline-block; background:var(--accent); color:var(--white); padding:10px 16px; border-radius:10px; font-weight:600}
    header{padding:36px 20px; max-width:1100px; margin:0 auto}
    main{max-width:1100px; margin:0 auto; padding:12px 20px 80px}

    .hero{
      text-align:center; padding:42px 20px;
    }
    .hero h1{font-size:2.6rem; margin:0 0 10px; color:var(--white)}
    .hero h1 .accent{color:var(--accent)}
    .hero p.lead{color: #cbd5e1; font-size:1.05rem; margin:10px 0 18px; max-width:820px; margin-left:auto; margin-right:auto}
    .hero .actions{margin-top:18px; display:flex; gap:10px; justify-content:center; flex-wrap:wrap}

    .grid{display:grid; gap:18px}
    .grid.cols-3{grid-template-columns:repeat(3,1fr)}
    .card{background:var(--card); border-radius:12px; padding:18px; box-shadow: 0 6px 20px rgba(2,6,23,0.6); border:1px solid rgba(255,255,255,0.03)}
    h2.section-title{font-size:1.5rem; color:var(--white); margin:0 0 12px}
    p.lead-muted{color:#9aa8b9}

    /* Responsive */
    @media (max-width:900px){
      .grid.cols-3{grid-template-columns:repeat(2,1fr)}
    }
    @media (max-width:600px){
      .grid.cols-3{grid-template-columns:1fr}
      .hero h1{font-size:1.8rem}
    }

    /* Floating WhatsApp button */
    .whatsapp-btn{
      position:fixed;
      right:18px;
      bottom:18px;
      z-index:999;
      background:#25D366;
      color:#fff;
      border-radius:999px;
      padding:13px 16px;
      display:flex;
      gap:10px;
      align-items:center;
      box-shadow:0 6px 18px rgba(0,0,0,0.25);
      transition:transform .14s ease;
      text-decoration:none;
      font-weight:700;
    }
    .whatsapp-btn img{width:20px;height:20px; display:block}

    .whatsapp-btn:hover{transform:translateY(-4px);}

    footer{padding:24px 20px; text-align:center; color:#94a3b8; font-size:.95rem}

    /* simple navbar (optional) */
    .nav{display:flex; gap:12px; align-items:center; justify-content:space-between}
    .nav .brand{font-weight:700; color:var(--white)}
    .nav a{color:var(--muted)}

    /* small utilities */
    .muted{color:#94a3b8}
    .pill{display:inline-block;background:var(--glass);padding:6px 10px;border-radius:999px;color:var(--muted);font-weight:600}
  </style>
</head>
<body>

  <header>
    <div class="nav" style="max-width:1100px;margin:0 auto">
      <div class="brand">Baatah Fahed Braimah</div>
      <div class="links" style="display:flex;gap:12px;align-items:center">
        <a href="#about">About</a>
        <a href="#brands">Brands</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero card" style="background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));">
      <h1>Baatah <span class="accent">Fahed Braimah</span></h1>
      <p class="lead">Cybersecurity Expert • Founder • Tech Entrepreneur</p>
      <p class="lead-muted">Protecting lives, businesses, and organizations through cybersecurity education, consulting, and digital innovation. CEO — Baatah Cyber Academy; CEO (upcoming) — Baatah Consultancy; Co-Founder — Baitul Zakireen.</p>

      <div class="actions" style="margin-top:18px;">
        <a class="button" href="mailto:baatahfahed182@gmail.com">Hire Me</a>
        <!-- Replace the href below with your actual CV file link (PDF) -->
        <a class="button" href="assets/Baatah-Fahed-Braimah-CV.pdf" style="background:#ffffff;color:var(--bg);">Download CV</a>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" style="margin-top:28px">
      <h2 class="section-title">About Me</h2>
      <div class="card">
        <p>I am a cybersecurity expert, educator, and technology entrepreneur based in Ghana. I am the CEO and Founder of <strong>Baatah Cyber Academy</strong>, the CEO of the soon-to-launch <strong>Baatah Consultancy</strong>, and a Co-Founder of <strong>Baitul Zakireen</strong>. My focus is on cybersecurity training, digital security consulting, and mentoring the next generation of tech professionals across Africa.</p>
      </div>
    </section>

    <!-- BRANDS -->
    <section id="brands" style="margin-top:28px">
      <h2 class="section-title">My Brands & Leadership</h2>
      <div class="grid cols-3" style="margin-top:12px">
        <div class="card">
          <h3 style="margin-top:0;color:#fff">Baatah Cyber Academy</h3>
          <p class="muted">Founder & CEO — Professional cybersecurity training and practical labs for beginners and professionals.</p>
        </div>

        <div class="card">
          <h3 style="margin-top:0;color:#fff">Baatah Consultancy</h3>
          <p class="muted">CEO — Upcoming digital security & technology consulting firm delivering practical security solutions.</p>
        </div>

        <div class="card">
          <h3 style="margin-top:0;color:#fff">Baitul Zakireen</h3>
          <p class="muted">Co-Founder — Community and education-focused initiative supporting learning and development.</p>
        </div>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="services" style="margin-top:28px">
      <h2 class="section-title">Core Services</h2>
      <div class="grid cols-3" style="margin-top:12px">
        <div class="card">
          <h4 style="margin:0 0 8px;color:#fff">Cybersecurity Training</h4>
          <p class="muted">Hands-on education from beginner labs to real-world scenarios and practical skills.</p>
        </div>

        <div class="card">
          <h4 style="margin:0 0 8px;color:#fff">Security Consulting</h4>
          <p class="muted">Vulnerability assessments, awareness training, and tailored security solutions.</p>
        </div>

        <div class="card">
          <h4 style="margin:0 0 8px;color:#fff">Tech Leadership & Mentorship</h4>
          <p class="muted">Mentoring, training programs and career guidance for aspiring tech professionals.</p>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" style="margin-top:28px">
      <h2 class="section-title">Contact</h2>
      <div class="card" style="display:flex;flex-direction:column;gap:10px">
        <div>
          <strong>Email:</strong> <a href="mailto:baatahfahed182@gmail.com">baatahfahed182@gmail.com</a>
        </div>
        <div>
          <strong>Location:</strong> Ghana
        </div>
        <div>
          <strong>Availability:</strong> Training, Consulting & Speaking engagements
        </div>
      </div>
    </section>

  </main>

  <footer>
    © <span id="year"></span> Baatah Fahed Braimah — Cybersecurity Expert
  </footer>

  <!-- WHATSAPP FLOATING BUTTON -->
  <!-- IMPORTANT: Replace 233XXXXXXXXX with your real WhatsApp number (country code + number, no + or spaces).
       Example: https://wa.me/233245123456  -->
  <a id="whatsapp" class="whatsapp-btn" href="https://wa.me/233XXXXXXXXX" target="_blank" rel="noopener noreferrer">
    <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='%23ffffff'><path d='M20.52 3.48A11.86 11.86 0 0 0 12 .5C5.65.5.86 5.29.86 11.64c0 2.04.57 3.95 1.66 5.63L.5 23.5l6.54-1.72a11.63 11.63 0 0 0 5.46 1.3h.01c6.35 0 11.14-4.79 11.14-11.14 0-3-1.17-5.78-3.14-7.76zM12 21.4h-.01a10.12 10.12 0 0 1-5.21-1.4l-.37-.22-3.9 1.03 1.04-3.8-.24-.39A9.86 9.86 0 0 1 2.1 11.64c0-5.37 4.35-9.74 9.77-9.74 2.61 0 5.06 1.02 6.9 2.85 1.83 1.83 2.85 4.28 2.85 6.9 0 5.43-4.4 9.77-9.66 9.77z'/></svg>" alt="whatsapp" />
    <span style="font-size:0.95rem">Chat on WhatsApp</span>
  </a>

  <script>
    // Insert current year in footer
    document.getElementById('year').textContent = new Date().getFullYear();

    // Smooth scrolling for internal links
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', function(e){
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if(target) target.scrollIntoView({behavior:'smooth', block:'start'});
      });
    });

    // Optional: Prompt visitor if WhatsApp number not set (simple check)
    (function(){
      const wa = document.getElementById('whatsapp');
      if(wa && wa.href.includes('XXXXXXXXX')) {
        wa.title = "Replace the placeholder number with your WhatsApp number in index.html";
      }
    })();
  </script>
</body>
</html><!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Baatah Fahed Braimah — Cybersecurity Expert</title>
  <meta name="description" content="Baatah Fahed Braimah — Cybersecurity Expert. CEO Baatah Cyber Academy, Baatah Consultancy (upcoming), Co-founder Baitul Zakireen. Contact: baatahfahed182@gmail.com" />
  <!-- Google Font (optional) -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b1220; /* deep navy */
      --card:#0f1724;
      --muted:#cbd5e1;
      --accent:#1e90ff; /* blue */
      --white:#ffffff;
      --glass: rgba(255,255,255,0.03);
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;
      background: linear-gradient(180deg,var(--bg), #07101a);
      color:var(--muted);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.5;
    }

    a{color:var(--accent); text-decoration:none}
    a.button{display:inline-block; background:var(--accent); color:var(--white); padding:10px 16px; border-radius:10px; font-weight:600}
    header{padding:36px 20px; max-width:1100px; margin:0 auto}
    main{max-width:1100px; margin:0 auto; padding:12px 20px 80px}

    .hero{
      text-align:center; padding:42px 20px;
    }
    .hero h1{font-size:2.6rem; margin:0 0 10px; color:var(--white)}
    .hero h1 .accent{color:var(--accent)}
    .hero p.lead{color: #cbd5e1; font-size:1.05rem; margin:10px 0 18px; max-width:820px; margin-left:auto; margin-right:auto}
    .hero .actions{margin-top:18px; display:flex; gap:10px; justify-content:center; flex-wrap:wrap}

    .grid{display:grid; gap:18px}
    .grid.cols-3{grid-template-columns:repeat(3,1fr)}
    .card{background:var(--card); border-radius:12px; padding:18px; box-shadow: 0 6px 20px rgba(2,6,23,0.6); border:1px solid rgba(255,255,255,0.03)}
    h2.section-title{font-size:1.5rem; color:var(--white); margin:0 0 12px}
    p.lead-muted{color:#9aa8b9}

    /* Responsive */
    @media (max-width:900px){
      .grid.cols-3{grid-template-columns:repeat(2,1fr)}
    }
    @media (max-width:600px){
      .grid.cols-3{grid-template-columns:1fr}
      .hero h1{font-size:1.8rem}
    }

    /* Floating WhatsApp button */
    .whatsapp-btn{
      position:fixed;
      right:18px;
      bottom:18px;
      z-index:999;
      background:#25D366;
      color:#fff;
      border-radius:999px;
      padding:13px 16px;
      display:flex;
      gap:10px;
      align-items:center;
      box-shadow:0 6px 18px rgba(0,0,0,0.25);
      transition:transform .14s ease;
      text-decoration:none;
      font-weight:700;
    }
    .whatsapp-btn img{width:20px;height:20px; display:block}

    .whatsapp-btn:hover{transform:translateY(-4px);}

    footer{padding:24px 20px; text-align:center; color:#94a3b8; font-size:.95rem}

    /* simple navbar (optional) */
    .nav{display:flex; gap:12px; align-items:center; justify-content:space-between}
    .nav .brand{font-weight:700; color:var(--white)}
    .nav a{color:var(--muted)}

    /* small utilities */
    .muted{color:#94a3b8}
    .pill{display:inline-block;background:var(--glass);padding:6px 10px;border-radius:999px;color:var(--muted);font-weight:600}
  </style>
</head>
<body>

  <header>
    <div class="nav" style="max-width:1100px;margin:0 auto">
      <div class="brand">Baatah Fahed Braimah</div>
      <div class="links" style="display:flex;gap:12px;align-items:center">
        <a href="#about">About</a>
        <a href="#brands">Brands</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero card" style="background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));">
      <h1>Baatah <span class="accent">Fahed Braimah</span></h1>
      <p class="lead">Cybersecurity Expert • Founder • Tech Entrepreneur</p>
      <p class="lead-muted">Protecting lives, businesses, and organizations through cybersecurity education, consulting, and digital innovation. CEO — Baatah Cyber Academy; CEO (upcoming) — Baatah Consultancy; Co-Founder — Baitul Zakireen.</p>

      <div class="actions" style="margin-top:18px;">
        <a class="button" href="mailto:baatahfahed182@gmail.com">Hire Me</a>
        <!-- Replace the href below with your actual CV file link (PDF) -->
        <a class="button" href="assets/Baatah-Fahed-Braimah-CV.pdf" style="background:#ffffff;color:var(--bg);">Download CV</a>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" style="margin-top:28px">
      <h2 class="section-title">About Me</h2>
      <div class="card">
        <p>I am a cybersecurity expert, educator, and technology entrepreneur based in Ghana. I am the CEO and Founder of <strong>Baatah Cyber Academy</strong>, the CEO of the soon-to-launch <strong>Baatah Consultancy</strong>, and a Co-Founder of <strong>Baitul Zakireen</strong>. My focus is on cybersecurity training, digital security consulting, and mentoring the next generation of tech professionals across Africa.</p>
      </div>
    </section>

    <!-- BRANDS -->
    <section id="brands" style="margin-top:28px">
      <h2 class="section-title">My Brands & Leadership</h2>
      <div class="grid cols-3" style="margin-top:12px">
        <div class="card">
          <h3 style="margin-top:0;color:#fff">Baatah Cyber Academy</h3>
          <p class="muted">Founder & CEO — Professional cybersecurity training and practical labs for beginners and professionals.</p>
        </div>

        <div class="card">
          <h3 style="margin-top:0;color:#fff">Baatah Consultancy</h3>
          <p class="muted">CEO — Upcoming digital security & technology consulting firm delivering practical security solutions.</p>
        </div>

        <div class="card">
          <h3 style="margin-top:0;color:#fff">Baitul Zakireen</h3>
          <p class="muted">Co-Founder — Community and education-focused initiative supporting learning and development.</p>
        </div>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="services" style="margin-top:28px">
      <h2 class="section-title">Core Services</h2>
      <div class="grid cols-3" style="margin-top:12px">
        <div class="card">
          <h4 style="margin:0 0 8px;color:#fff">Cybersecurity Training</h4>
          <p class="muted">Hands-on education from beginner labs to real-world scenarios and practical skills.</p>
        </div>

        <div class="card">
          <h4 style="margin:0 0 8px;color:#fff">Security Consulting</h4>
          <p class="muted">Vulnerability assessments, awareness training, and tailored security solutions.</p>
        </div>

        <div class="card">
          <h4 style="margin:0 0 8px;color:#fff">Tech Leadership & Mentorship</h4>
          <p class="muted">Mentoring, training programs and career guidance for aspiring tech professionals.</p>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" style="margin-top:28px">
      <h2 class="section-title">Contact</h2>
      <div class="card" style="display:flex;flex-direction:column;gap:10px">
        <div>
          <strong>Email:</strong> <a href="mailto:baatahfahed182@gmail.com">baatahfahed182@gmail.com</a>
        </div>
        <div>
          <strong>Location:</strong> Ghana
        </div>
        <div>
          <strong>Availability:</strong> Training, Consulting & Speaking engagements
        </div>
      </div>
    </section>

  </main>

  <footer>
    © <span id="year"></span> Baatah Fahed Braimah — Cybersecurity Expert
  </footer>

  <!-- WHATSAPP FLOATING BUTTON -->
  <!-- IMPORTANT: Replace 233XXXXXXXXX with your real WhatsApp number (country code + number, no + or spaces).
       Example: https://wa.me/233245123456  -->
  <a id="whatsapp" class="whatsapp-btn" href="https://wa.me/233XXXXXXXXX" target="_blank" rel="noopener noreferrer">
    <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='%23ffffff'><path d='M20.52 3.48A11.86 11.86 0 0 0 12 .5C5.65.5.86 5.29.86 11.64c0 2.04.57 3.95 1.66 5.63L.5 23.5l6.54-1.72a11.63 11.63 0 0 0 5.46 1.3h.01c6.35 0 11.14-4.79 11.14-11.14 0-3-1.17-5.78-3.14-7.76zM12 21.4h-.01a10.12 10.12 0 0 1-5.21-1.4l-.37-.22-3.9 1.03 1.04-3.8-.24-.39A9.86 9.86 0 0 1 2.1 11.64c0-5.37 4.35-9.74 9.77-9.74 2.61 0 5.06 1.02 6.9 2.85 1.83 1.83 2.85 4.28 2.85 6.9 0 5.43-4.4 9.77-9.66 9.77z'/></svg>" alt="whatsapp" />
    <span style="font-size:0.95rem">Chat on WhatsApp</span>
  </a>

  <script>
    // Insert current year in footer
    document.getElementById('year').textContent = new Date().getFullYear();

    // Smooth scrolling for internal links
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', function(e){
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if(target) target.scrollIntoView({behavior:'smooth', block:'start'});
      });
    });

    // Optional: Prompt visitor if WhatsApp number not set (simple check)
    (function(){
      const wa = document.getElementById('whatsapp');
      if(wa && wa.href.includes('XXXXXXXXX')) {
        wa.title = "Replace the placeholder number with your WhatsApp number in index.html";
      }
    })();
  </script>
</body>
</html><!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Baatah Fahed Braimah — Cybersecurity Expert</title>
  <meta name="description" content="Baatah Fahed Braimah — Cybersecurity Expert. CEO Baatah Cyber Academy, Baatah Consultancy (upcoming), Co-founder Baitul Zakireen. Contact: baatahfahed182@gmail.com" />
  <!-- Google Font (optional) -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b1220; /* deep navy */
      --card:#0f1724;
      --muted:#cbd5e1;
      --accent:#1e90ff; /* blue */
      --white:#ffffff;
      --glass: rgba(255,255,255,0.03);
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;
      background: linear-gradient(180deg,var(--bg), #07101a);
      color:var(--muted);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.5;
    }

    a{color:var(--accent); text-decoration:none}
    a.button{display:inline-block; background:var(--accent); color:var(--white); padding:10px 16px; border-radius:10px; font-weight:600}
    header{padding:36px 20px; max-width:1100px; margin:0 auto}
    main{max-width:1100px; margin:0 auto; padding:12px 20px 80px}

    .hero{
      text-align:center; padding:42px 20px;
    }
    .hero h1{font-size:2.6rem; margin:0 0 10px; color:var(--white)}
    .hero h1 .accent{color:var(--accent)}
    .hero p.lead{color: #cbd5e1; font-size:1.05rem; margin:10px 0 18px; max-width:820px; margin-left:auto; margin-right:auto}
    .hero .actions{margin-top:18px; display:flex; gap:10px; justify-content:center; flex-wrap:wrap}

    .grid{display:grid; gap:18px}
    .grid.cols-3{grid-template-columns:repeat(3,1fr)}
    .card{background:var(--card); border-radius:12px; padding:18px; box-shadow: 0 6px 20px rgba(2,6,23,0.6); border:1px solid rgba(255,255,255,0.03)}
    h2.section-title{font-size:1.5rem; color:var(--white); margin:0 0 12px}
    p.lead-muted{color:#9aa8b9}

    /* Responsive */
    @media (max-width:900px){
      .grid.cols-3{grid-template-columns:repeat(2,1fr)}
    }
    @media (max-width:600px){
      .grid.cols-3{grid-template-columns:1fr}
      .hero h1{font-size:1.8rem}
    }

    /* Floating WhatsApp button */
    .whatsapp-btn{
      position:fixed;
      right:18px;
      bottom:18px;
      z-index:999;
      background:#25D366;
      color:#fff;
      border-radius:999px;
      padding:13px 16px;
      display:flex;
      gap:10px;
      align-items:center;
      box-shadow:0 6px 18px rgba(0,0,0,0.25);
      transition:transform .14s ease;
      text-decoration:none;
      font-weight:700;
    }
    .whatsapp-btn img{width:20px;height:20px; display:block}

    .whatsapp-btn:hover{transform:translateY(-4px);}

    footer{padding:24px 20px; text-align:center; color:#94a3b8; font-size:.95rem}

    /* simple navbar (optional) */
    .nav{display:flex; gap:12px; align-items:center; justify-content:space-between}
    .nav .brand{font-weight:700; color:var(--white)}
    .nav a{color:var(--muted)}

    /* small utilities */
    .muted{color:#94a3b8}
    .pill{display:inline-block;background:var(--glass);padding:6px 10px;border-radius:999px;color:var(--muted);font-weight:600}
  </style>
</head>
<body>

  <header>
    <div class="nav" style="max-width:1100px;margin:0 auto">
      <div class="brand">Baatah Fahed Braimah</div>
      <div class="links" style="display:flex;gap:12px;align-items:center">
        <a href="#about">About</a>
        <a href="#brands">Brands</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero card" style="background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));">
      <h1>Baatah <span class="accent">Fahed Braimah</span></h1>
      <p class="lead">Cybersecurity Expert • Founder • Tech Entrepreneur</p>
      <p class="lead-muted">Protecting lives, businesses, and organizations through cybersecurity education, consulting, and digital innovation. CEO — Baatah Cyber Academy; CEO (upcoming) — Baatah Consultancy; Co-Founder — Baitul Zakireen.</p>

      <div class="actions" style="margin-top:18px;">
        <a class="button" href="mailto:baatahfahed182@gmail.com">Hire Me</a>
        <!-- Replace the href below with your actual CV file link (PDF) -->
        <a class="button" href="assets/Baatah-Fahed-Braimah-CV.pdf" style="background:#ffffff;color:var(--bg);">Download CV</a>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" style="margin-top:28px">
      <h2 class="section-title">About Me</h2>
      <div class="card">
        <p>I am a cybersecurity expert, educator, and technology entrepreneur based in Ghana. I am the CEO and Founder of <strong>Baatah Cyber Academy</strong>, the CEO of the soon-to-launch <strong>Baatah Consultancy</strong>, and a Co-Founder of <strong>Baitul Zakireen</strong>. My focus is on cybersecurity training, digital security consulting, and mentoring the next generation of tech professionals across Africa.</p>
      </div>
    </section>

    <!-- BRANDS -->
    <section id="brands" style="margin-top:28px">
      <h2 class="section-title">My Brands & Leadership</h2>
      <div class="grid cols-3" style="margin-top:12px">
        <div class="card">
          <h3 style="margin-top:0;color:#fff">Baatah Cyber Academy</h3>
          <p class="muted">Founder & CEO — Professional cybersecurity training and practical labs for beginners and professionals.</p>
        </div>

        <div class="card">
          <h3 style="margin-top:0;color:#fff">Baatah Consultancy</h3>
          <p class="muted">CEO — Upcoming digital security & technology consulting firm delivering practical security solutions.</p>
        </div>

        <div class="card">
          <h3 style="margin-top:0;color:#fff">Baitul Zakireen</h3>
          <p class="muted">Co-Founder — Community and education-focused initiative supporting learning and development.</p>
        </div>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="services" style="margin-top:28px">
      <h2 class="section-title">Core Services</h2>
      <div class="grid cols-3" style="margin-top:12px">
        <div class="card">
          <h4 style="margin:0 0 8px;color:#fff">Cybersecurity Training</h4>
          <p class="muted">Hands-on education from beginner labs to real-world scenarios and practical skills.</p>
        </div>

        <div class="card">
          <h4 style="margin:0 0 8px;color:#fff">Security Consulting</h4>
          <p class="muted">Vulnerability assessments, awareness training, and tailored security solutions.</p>
        </div>

        <div class="card">
          <h4 style="margin:0 0 8px;color:#fff">Tech Leadership & Mentorship</h4>
          <p class="muted">Mentoring, training programs and career guidance for aspiring tech professionals.</p>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" style="margin-top:28px">
      <h2 class="section-title">Contact</h2>
      <div class="card" style="display:flex;flex-direction:column;gap:10px">
        <div>
          <strong>Email:</strong> <a href="mailto:baatahfahed182@gmail.com">baatahfahed182@gmail.com</a>
        </div>
        <div>
          <strong>Location:</strong> Ghana
        </div>
        <div>
          <strong>Availability:</strong> Training, Consulting & Speaking engagements
        </div>
      </div>
    </section>

  </main>

  <footer>
    © <span id="year"></span> Baatah Fahed Braimah — Cybersecurity Expert
  </footer>

  <!-- WHATSAPP FLOATING BUTTON -->
  <!-- IMPORTANT: Replace 233XXXXXXXXX with your real WhatsApp number (country code + number, no + or spaces).
       Example: https://wa.me/233245123456  -->
  <a id="whatsapp" class="whatsapp-btn" href="https://wa.me/233XXXXXXXXX" target="_blank" rel="noopener noreferrer">
    <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='%23ffffff'><path d='M20.52 3.48A11.86 11.86 0 0 0 12 .5C5.65.5.86 5.29.86 11.64c0 2.04.57 3.95 1.66 5.63L.5 23.5l6.54-1.72a11.63 11.63 0 0 0 5.46 1.3h.01c6.35 0 11.14-4.79 11.14-11.14 0-3-1.17-5.78-3.14-7.76zM12 21.4h-.01a10.12 10.12 0 0 1-5.21-1.4l-.37-.22-3.9 1.03 1.04-3.8-.24-.39A9.86 9.86 0 0 1 2.1 11.64c0-5.37 4.35-9.74 9.77-9.74 2.61 0 5.06 1.02 6.9 2.85 1.83 1.83 2.85 4.28 2.85 6.9 0 5.43-4.4 9.77-9.66 9.77z'/></svg>" alt="whatsapp" />
    <span style="font-size:0.95rem">Chat on WhatsApp</span>
  </a>

  <script>
    // Insert current year in footer
    document.getElementById('year').textContent = new Date().getFullYear();

    // Smooth scrolling for internal links
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', function(e){
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if(target) target.scrollIntoView({behavior:'smooth', block:'start'});
      });
    });

    // Optional: Prompt visitor if WhatsApp number not set (simple check)
    (function(){
      const wa = document.getElementById('whatsapp');
      if(wa && wa.href.includes('XXXXXXXXX')) {
        wa.title = "Replace the placeholder number with your WhatsApp number in index.html";
      }
    })();
  </script>
</body>
</html>
