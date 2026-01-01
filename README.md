# My-website-<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8" />
  <title>Rokeyo Universe</title>

  <style>
    body { font-family: Arial; margin: 0; background:#f7f7f7; }
    header { background:#1f2937; color:white; padding:16px; text-align:center; }
    nav { display:flex; gap:10px; justify-content:center; padding:14px; background:#e5e7eb; }
    nav a { text-decoration:none; padding:8px 14px; border-radius:14px; background:white; }
    .page { max-width:900px; margin:auto; padding:18px; }
    .card { background:white; padding:16px; border-radius:16px; box-shadow:0 10px 20px rgba(0,0,0,.08); margin:10px 0; }
    footer { text-align:center; padding:14px; color:#6b7280; }
  </style>

  <script>
    function show(page){
      document.querySelectorAll('.page').forEach(p => p.style.display='none');
      document.getElementById(page).style.display='block';
    }
  </script>
</head>

<body>
<header><h1>Rokeyo Universe ✨</h1></header>

<nav>
  <a onclick="show('home')">Home</a>
  <a onclick="show('about')">About</a>
  <a onclick="show('contact')">Contact</a>
</nav>

<div id="home" class="page">
  <div class="card">
    <h2>Welcome to My Creative World 🌍</h2>
    <p>This is my website project made using free hosting.</p>

    <img src="https://images.unsplash.com/photo-1503264116251-35a269479413?w=900"
         style="width:100%; border-radius:14px;">
    <br><br>

    <div style="aspect-ratio:16/9;">
      <iframe width="100%" height="100%"
              src="https://www.youtube.com/embed/dQw4w9WgXcQ"
              frameborder="0" allowfullscreen></iframe>
    </div>
  </div>
</div>

<div id="about" class="page" style="display:none;">
  <div class="card">
    <h2>About 💡</h2>
    <p>This website shows text, images, video and pages — created for my project.</p>
  </div>
</div>

<div id="contact" class="page" style="display:none;">
  <div class="card">
    <h2>Contact 📩</h2>
    <p>Send your message (project purpose only).</p>
  </div>
</div>

<footer>© 2026 Rokeyo Universe</footer>
</body>
</html>
