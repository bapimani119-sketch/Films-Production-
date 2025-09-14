# Films-Production-
CONTACT US FOR AUDITION WITH OUR NEW UPCOMING MOVIES
<INDEX_HTML> <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Bapi Mani Films</title>
  <meta name="description" content="Bapi Mani Films - Short films, music videos and creative content." />
  <!-- Google font (will load when online) -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --accent:#ff6b6b;
      --dark:#0f1724;
      --muted:#6b7280;
      --card:#ffffff;
      --glass: rgba(255,255,255,0.06);
    }
    *{box-sizing:border-box}
    html,body{height:100%; margin:0; font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,"Noto Sans",Arial; background:linear-gradient(180deg,#0f1724 0%, #071026 100%); color:#e6eef8;}
    a{color:inherit; text-decoration:none}
    .container{max-width:1100px; margin:28px auto; padding:16px;}
    header{display:flex;align-items:center;justify-content:space-between; gap:12px;}
    .brand{
      display:flex;align-items:center;gap:12px;
    }
    .logo{
      width:56px;height:56px;border-radius:10px;background:linear-gradient(135deg,var(--accent),#ffa94d);display:flex;align-items:center;justify-content:center;font-weight:800;color:white;font-size:20px;box-shadow:0 6px 30px rgba(0,0,0,0.35);
    }
    h1{margin:0;font-size:20px;letter-spacing:0.6px}
    header nav button{
      background:transparent;border:1px solid rgba(255,255,255,0.08);padding:8px 12px;border-radius:10px;color:#eaf4ff;font-weight:600;cursor:pointer;
    }

    /* Hero */
    .hero{
      margin-top:18px;
      background:linear-gradient(180deg, rgba(255,255,255,0.03), rgba(255,255,255,0.02));
      padding:18px;border-radius:14px;backdrop-filter: blur(6px);
      display:flex;gap:16px;align-items:center;flex-wrap:wrap;
    }
    .hero-left{flex:1 1 320px;min-width:260px}
    .hero-right{width:220px;max-width:40%;min-width:200px}
    .tag{display:inline-block;padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.04);color:var(--accent);font-weight:700;margin-bottom:12px}
    .lead{font-size:18px;margin:6px 0 12px;color:#eaf4ff}
    .cta-group{display:flex;gap:10px;flex-wrap:wrap}
    .btn{
      padding:10px 14px;border-radius:10px;border:none;font-weight:700;cursor:pointer;
      display:inline-flex;align-items:center;gap:8px;
    }
    .btn-primary{background:linear-gradient(90deg,var(--accent),#ff9a6b);color:white;box-shadow:0 8px 30px rgba(255,107,107,0.14)}
    .btn-outline{background:transparent;border:1px solid rgba(255,255,255,0.08);color:#eaf4ff}

    /* about */
    .card{margin-top:16px;padding:16px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));box-shadow:0 6px 18px rgba(0,0,0,0.35)}
    h2{margin:0 0 8px;font-size:16px}
    p{margin:0 0 10px;color:var(--muted)}

    /* gallery */
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:12px;margin-top:12px}
    .film{
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:10px;padding:0;overflow:hidden;border:1px solid rgba(255,255,255,0.03)
    }
    .thumb{height:140px;background-size:cover;background-position:center}
    .meta{padding:10px}
    .meta h3{margin:0;font-size:15px}
    .meta p{margin:6px 0 0;font-size:13px;color:var(--muted)}

    /* contact/footer */
    footer{margin-top:18px;padding:14px;border-radius:12px;text-align:center;color:var(--muted)}
    .socials{display:flex;gap:10px;justify-content:center;margin-top:10px}
    .socials a{padding:8px 12px;border-radius:10px;background:rgba(255,255,255,0.03);font-weight:700}

    /* responsive */
    @media (max-width:720px){
      .hero-right{width:100%;max-width:100%}
      header{flex-direction:column;align-items:flex-start;gap:12px}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">BM</div>
        <div>
          <h1>Bapi Mani Films</h1>
          <div style="color:var(--muted);font-size:13px">Original short films • Music videos • Storytelling</div>
        </div>
      </div>

      <nav>
        <!-- Replace with real links later -->
        <button onclick="document.getElementById('about').scrollIntoView({behavior:'smooth'})">About</button>
        <button onclick="document.getElementById('films').scrollIntoView({behavior:'smooth'})">Films</button>
      </nav>
    </header>

    <!-- HERO -->
    <section class="hero">
      <div class="hero-left">
        <div class="tag">NEW • Official</div>
        <div class="lead">Welcome to <strong>Bapi Mani Films</strong> — we craft short films, music videos and cinematic stories that move people.</div>

        <div style="display:flex;gap:8px;flex-wrap:wrap" class="cta-group">
          <!-- Put your YouTube channel link in the href below -->
          <a class="btn btn-primary" href="(YOUR_YOUTUBE_CHANNEL_URL_HERE)" target="_blank" rel="noopener noreferrer">► Visit our YouTube</a>
          <a class="btn btn-outline" href="mailto:contact@bapimanifilms.com">Contact</a>
        </div>

        <div style="margin-top:12px;color:var(--muted);font-size:13px">
          New releases every month. Subscribe on YouTube and follow us on social for behind-the-scenes.
        </div>
      </div>

      <div class="hero-right">
        <!-- Simple featured video placeholder (replace src with your embed if you want) -->
        <div style="border-radius:10px;overflow:hidden;border:1px solid rgba(255,255,255,0.04);background:#000">
          <iframe id="ytplayer" width="100%" height="170" src="" style="border:0;display:block" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        <div style="margin-top:8px;color:var(--muted);font-size:13px">Featured video — add your YouTube video ID in the code to show it here.</div>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="card" aria-labelledby="aboutTitle">
      <h2 id="aboutTitle">About Bapi Mani Films</h2>
      <p>
        Bapi Mani Films is an independent production house focused on creating short films, music videos and visual stories with an emotional core.
        We believe in honest storytelling, strong visuals and giving new talent a platform.
      </p>
      <p>
        Want to collaborate or submit a script? Use the contact button above or email us (replace contact address).
      </p>
    </section>

    <!-- FILMS / GALLERY -->
    <section id="films" class="card">
      <h2>Our Films</h2>
      <p>Selected works — click to watch on YouTube</p>

      <div class="grid">
        <!-- Example film cards: replace thumb URLs and yt links -->
        <div class="film">
          <a href="(YOUR_YOUTUBE_CHANNEL_URL_HERE)" target="_blank" rel="noopener noreferrer">
            <div class="thumb" style="background-image:url('https://via.placeholder.com/800x450?text=Film+1')"></div>
            <div class="meta">
              <h3>Short Film Title 1</h3>
              <p>Duration • 8:23 • Drama</p>
            </div>
          </a>
        </div>

        <div class="film">
          <a href="(YOUR_YOUTUBE_CHANNEL_URL_HERE)" target="_blank" rel="noopener noreferrer">
            <div class="thumb" style="background-image:url('https://via.placeholder.com/800x450?text=Music+Video')"></div>
            <div class="meta">
              <h3>Music Video Title</h3>
              <p>Duration • 4:12 • Original song</p>
            </div>
          </a>
        </div>

        <div class="film">
          <a href="(YOUR_YOUTUBE_CHANNEL_URL_HERE)" target="_blank" rel="noopener noreferrer">
            <div class="thumb" style="background-image:url('https://via.placeholder.com/800x450?text=Short+Film+2')"></div>
            <div class="meta">
              <h3>Short Film Title 2</h3>
              <p>Duration • 12:04 • Social message</p>
            </div>
          </a>
        </div>

        <!-- Add more cards similarly -->
      </div>
    </section>

    <!-- CONTACT & SOCIAL -->
    <section class="card" style="text-align:center">
      <h2>Stay Connected</h2>
      <p>Follow us for BTS, updates and new releases.</p>
      <div class="socials">
        <a href="(YOUR_INSTAGRAM_URL_HERE)" target="_blank" rel="noopener noreferrer">Instagram</a>
        <a href="(YOUR_FACEBOOK_URL_HERE)" target="_blank" rel="noopener noreferrer">Facebook</a>
        <a href="mailto:(YOUR_EMAIL_HERE)">Email</a>
        <a href="(YOUR_YOUTUBE_CHANNEL_URL_HERE)" target="_blank" rel="noopener noreferrer">YouTube</a>
      </div>
    </section>

    <footer>
      © <strong>Bapi Mani Films</strong> • All rights reserved<br>
      <small style="color:var(--muted)">Unauthorized copying or redistribution of our content is prohibited.</small>
    </footer>
  </div>

  <script>
    // Small script to inject featured YouTube video if you add an ID
    // Replace the variable below with your favorite video ID (just the ID part)
    const featuredVideoId = ""; // e.g. "dQw4w9WgXcQ"
    const ytFrame = document.getElementById('ytplayer');
    if(featuredVideoId && ytFrame){
      ytFrame.src = "https://www.youtube.com/embed/" + featuredVideoId + "?rel=0&showinfo=0";
    } else if(ytFrame){
      // if no video set, show a simple poster image
      ytFrame.style.display = "none";
      const right = document.querySelector('.hero-right');
      const poster = document.createElement('div');
      poster.style.height = '170px';
      poster.style.borderRadius = '8px';
      poster.style.overflow = 'hidden';
      poster.style.backgroundImage = "url('https://via.placeholder.com/800x450?text=Add+Your+Featured+Video')";
      poster.style.backgroundSize = 'cover';
      poster.style.backgroundPosition = 'center';
      right.querySelector('div').appendChild(poster);
    }

    // Optional: smooth scroll for internal links (supported above)
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', e=>{
        e.preventDefault();
        const id = a.getAttribute('href').slice(1);
        document.getElementById(id)?.scrollIntoView({behavior:'smooth'});
      });
    });
  </script>
</body>
</html>
