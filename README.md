<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>IgniteGrapple – AI Wrestling Coach</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; }
    body { background: #050711; color: #f9fafb; line-height: 1.6; }
    header { padding: 24px 18px; border-bottom: 1px solid #1f2933; position: sticky; top: 0; background: rgba(5,7,17,0.96); backdrop-filter: blur(10px); }
    .nav { max-width: 960px; margin: 0 auto; display: flex; align-items: center; justify-content: space-between; }
    .logo { font-weight: 800; letter-spacing: 0.08em; font-size: 14px; text-transform: uppercase; }
    .logo span { color: #38bdf8; }
    .btn-primary, .btn-ghost {
      display: inline-block; padding: 10px 18px; border-radius: 999px;
      font-size: 14px; text-decoration: none; font-weight: 600; border: 1px solid transparent;
    }
    .btn-primary { background: linear-gradient(135deg,#38bdf8,#a855f7); color: #0b1020; }
    .btn-ghost { border-color:#4b5563; color:#e5e7eb; margin-left: 8px; }
    main { max-width: 960px; margin: 0 auto; padding: 32px 18px 60px; }
    .hero { display: grid; gap: 32px; align-items: center; }
    .tag { display:inline-flex; align-items:center; gap:6px; padding:4px 10px; border-radius:999px; background:#0b1120; border:1px solid #1f2937; font-size:11px; text-transform:uppercase; letter-spacing:.12em; }
    .tag span { width:7px; height:7px; border-radius:999px; background:#22c55e; }
    h1 { font-size: 34px; line-height:1.1; margin:16px 0 12px; }
    h1 span { background: linear-gradient(135deg,#38bdf8,#a855f7); -webkit-background-clip: text; color: transparent; }
    .hero p { color:#9ca3af; font-size:15px; max-width: 460px; }
    .hero-actions { margin-top: 18px; display:flex; flex-wrap:wrap; gap:10px; }
    .hero-note { margin-top: 10px; font-size: 12px; color:#6b7280; }
    .card { background: radial-gradient(circle at top,#111827,#020617); border-radius:20px; border:1px solid #111827; padding:18px; margin-top: 24px; }
    .card h2 { font-size:18px; margin-bottom: 10px; }
    .grid { display:grid; gap:14px; margin-top:10px; }
    .pill { font-size:12px; padding:5px 9px; border-radius:999px; background:#020617; border:1px solid #1f2937; display:inline-flex; justify-content:space-between; align-items:center; gap:10px; }
    .pill span { font-size:11px; color:#9ca3af; }
    h3 { margin-top: 32px; margin-bottom: 6px; font-size: 16px; }
    ul { margin-left:18px; color:#9ca3af; font-size: 14px; }
    li { margin-bottom: 4px; }
    .cta-box { margin-top:28px; padding:16px; border-radius:16px; border:1px solid #1f2937; background:#020617; font-size:13px; color:#9ca3af; }
    .cta-box strong { color:#e5e7eb; }
    footer { text-align:center; font-size:11px; color:#6b7280; padding:18px; border-top:1px solid #111827; margin-top: 40px; }
    @media (min-width: 768px) {
      h1 { font-size:44px; }
      .hero { grid-template-columns: minmax(0, 1.2fr) minmax(0, 1fr); }
    }
  </style>
</head>
<body>
<header>
  <div class="nav">
    <div class="logo">IGNITE<span>GRAPPLE</span></div>
    <div>
      <a href="#how" class="btn-ghost">How it works</a>
      <a href="#waitlist" class="btn-primary">Join beta</a>
    </div>
  </div>
</header>

<main>
  <section class="hero">
    <div>
      <div class="tag"><span></span> AI-powered wrestling coach</div>
      <h1>Turn every practice into a <span>championship-level session</span>.</h1>
      <p>
        IgniteGrapple is your digital assistant coach. Break down live training,
        track athlete progress, and get instant, informed feedback – 24/7.
      </p>
      <div class="hero-actions">
        <a href="#waitlist" class="btn-primary">Get early access</a>
        <a href="#features" class="btn-ghost">View features</a>
      </div>
      <p class="hero-note">No credit card. Built for clubs, coaches, and serious wrestlers.</p>
    </div>

    <div class="card">
      <h2>Sample AI breakdown</h2>
      <p style="font-size:13px; color:#e5e7eb; margin-bottom:8px;">
        Drill: Single-leg finish • Athlete: HS 152 lbs
      </p>
      <div class="grid">
        <div class="pill">
          Hip position: Strong
          <span>Good drive through contact.</span>
        </div>
        <div class="pill">
          Head placement: Fix
          <span>Keep your head tight to the ribs to cut the corner.</span>
        </div>
        <div class="pill">
          Finish option: Recommended
          <span>Switch to dump finish when opponent sprawls heavy.</span>
        </div>
      </div>
    </div>
  </section>

  <section id="features">
    <h3>What IgniteGrapple helps you do</h3>
    <ul>
      <li><strong>Upload practice film</strong> and get quick breakdowns for each athlete.</li>
      <li><strong>Create custom training plans</strong> based on age, weight class, and skill level.</li>
      <li><strong>Track progress</strong> across takedowns, mat returns, riding, and escapes.</li>
      <li><strong>Share reports</strong> with parents and athletes in one tap.</li>
    </ul>
  </section>

  <section id="how">
    <h3>How it works</h3>
    <ul>
      <li>Record practice or matches on your phone.</li>
      <li>Upload clips into IgniteGrapple.</li>
      <li>AI tags positions, weaknesses, and key moments.</li>
      <li>You get clear action items for the next practice.</li>
    </ul>
  </section>

  <section id="waitlist">
    <h3>Join the coach & club beta</h3>
    <div class="cta-box">
      <p>
        <strong>Want to be one of the first teams on IgniteGrapple?</strong><br />
        Send an email to <strong>your-email-here@example.com</strong> with:
      </p>
      <ul>
        <li>Your name & role (coach, parent, wrestler).</li>
        <li>Team / club name and city.</li>
        <li>How many athletes you work with.</li>
      </ul>
      <p style="margin-top:8px;">
        We’ll reply with next steps and private beta pricing once the platform is live.
      </p>
    </div>
  </section>

  <footer>
    © <span id="year"></span> IgniteGrapple. Built for wrestlers who want more than “just drill harder.”
  </footer>
</main>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>
