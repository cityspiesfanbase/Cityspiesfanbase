<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>City Spies Fan Hub</title>
  <style>
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial;margin:0;background:#0b0f14;color:#e8eef5}
    header{padding:22px;border-bottom:1px solid #223047;background:#111827}
    .wrap{max-width:900px;margin:0 auto;padding:18px}
    .card{background:#111827;border:1px solid #223047;border-radius:14px;padding:16px;margin:12px 0}
    a{color:#9fd0ff}
    .btn{display:inline-block;padding:10px 12px;border-radius:12px;border:1px solid #2b3a5c;background:#16213a;color:#e8eef5;text-decoration:none}
    .btn:hover{background:#1a2a4a}
    ul{line-height:1.6}
    .muted{color:#9fb2c8}
    .grid{display:grid;gap:12px;grid-template-columns:1fr 1fr}
    @media (max-width:700px){.grid{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <h1 style="margin:0 0 6px">City Spies Fan Hub</h1>
      <div class="muted">A safe place to find other fans, share creations, and talk about the series.</div>
    </div>
  </header>

  <main class="wrap">
    <div class="card">
      <h2 style="margin-top:0">Welcome</h2>
      <p>
        This is a community hub for people who love <b>City Spies</b>.
        We do prompts, share fan creations, and help new readers get into the series.
      </p>
      <p class="muted"><b>Safety note:</b> Don’t share personal info (full name, school, address, phone, private socials). If you’re under 18, keep conversations public and moderated.</p>
    </div>

    <div class="grid">
      <div class="card">
        <h2 style="margin-top:0">Get Involved</h2>
        <ul>
          <li>Join the community (link below)</li>
          <li>Submit fan art / fanfic (with permission)</li>
          <li>Monthly “Mission Prompt” writing challenge</li>
        </ul>
        <p><a class="btn" href="#" id="communityLink">Community Link (add yours)</a></p>
        <p class="muted">Tip: Use a moderated Discord or a subreddit. If you use Discord, turn on verification and limit DMs.</p>
      </div>

      <div class="card">
        <h2 style="margin-top:0">Rules</h2>
        <ul>
          <li>Be respectful. No bullying.</li>
          <li>No spoilers without warning.</li>
          <li>No NSFW content.</li>
          <li>No sharing personal info.</li>
          <li>Report problems to the mod team.</li>
        </ul>
      </div>
    </div>

    <div class="card">
      <h2 style="margin-top:0">Fan Creations</h2>
      <p class="muted">You can add images, links, or embed posts here later.</p>
      <ul>
        <li>Featured prompt: “Operation: Museum Night”</li>
        <li>Featured prompt: “Brooklyn POV — The Control Room”</li>
        <li>Featured prompt: “Sydney’s Dry-Funny Debrief”</li>
      </ul>
    </div>

    <div class="card">
      <h2 style="margin-top:0">Contact</h2>
      <p class="muted">
        Want something added to the site? Use a safe contact method like a Google Form (no personal info required).
      </p>
      <p><a class="btn" href="#" id="formLink">Suggestion Form (add yours)</a></p>
    </div>

    <p class="muted">© Fan-made community site. Not affiliated with the author or publisher.</p>
  </main>

  <script>
    // Replace these with your real links when you're ready:
    document.getElementById("communityLink").href = "https://example.com";
    document.getElementById("formLink").href = "https://example.com";
  </script>
</body>
</html>
