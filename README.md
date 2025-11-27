<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Safe Space Kenya Foundation</title>
  <meta name="description" content="Safe Space Kenya Foundation — mental health support, youth empowerment and community resources." />

  <style>
    :root{
      --bg:#f7fbfb;
      --card:#ffffff;
      --accent:#1f8a8b; /* teal */
      --accent-2:#6fbfbc;
      --muted:#6b7280;
      --radius:14px;
      --max-width:1100px;
      --container-padding:20px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:#0f172a;line-height:1.5}
    .wrap{max-width:var(--max-width);margin:0 auto;padding:30px var(--container-padding)}

    /* Header/Nav */
    header{background:linear-gradient(90deg, rgba(31,138,139,0.08), rgba(111,191,188,0.04));backdrop-filter: blur(4px);position:sticky;top:0;z-index:40}
    nav{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:48px;height:48px;border-radius:10px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700}
    .navlinks{display:flex;gap:18px;align-items:center}
    .navlinks a{text-decoration:none;color:var(--muted);font-weight:600}
    .cta{background:var(--accent);color:#fff;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:700}

    /* Hero */
    .hero{display:grid;grid-template-columns:1fr;gap:30px;padding:48px 0;align-items:center}
    .hero-inner{background:linear-gradient(180deg, rgba(255,255,255,0.9), rgba(255,255,255,0.8));padding:28px;border-radius:var(--radius);box-shadow:0 6px 20px rgba(15,23,42,0.06)}
    h1{font-size:28px;margin:0 0 8px}
    p.lead{color:var(--muted);margin:0 0 18px}
    .hero-buttons{display:flex;gap:12px}

    /* Cards */
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:20px}
    .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(15,23,42,0.04)}
    .card h3{margin:0 0 8px}
    .card p{margin:0;color:var(--muted)}

    /* Sections */
    section{padding:30px 0}
    .two-col{display:grid;grid-template-columns:1fr 360px;gap:24px}
    .programs li{margin-bottom:10px}

    /* Contact */
    form{display:flex;flex-direction:column;gap:10px}
    input,textarea{padding:10px;border-radius:8px;border:1px solid #e6e9ee}
    button{border:0;padding:12px 14px;border-radius:10px;font-weight:700}

    footer{padding:18px 0;color:var(--muted);font-size:14px}

    /* Responsive */
    @media (max-width:900px){
      .grid{grid-template-columns:repeat(2,1fr)}
      .two-col{grid-template-columns:1fr}
      nav{padding:8px 0}
    }
    @media (max-width:600px){
      .grid{grid-template-columns:1fr}
      h1{font-size:22px}
    }

  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <nav>
        <div class="brand">
          <div class="logo">SS</div>
          <div>
            <div style="font-weight:800">Safe Space Kenya</div>
            <div style="font-size:12px;color:var(--muted)">Foundation</div>
          </div>
        </div>
        <div class="navlinks">
          <a href="#about">About</a>
          <a href="#programs">Programs</a>
          <a href="#resources">Resources</a>
          <a href="#contact">Contact</a>
          <a class="cta" href="#donate">Donate</a>
        </div>
      </nav>
    </div>
  </header>

  <main class="wrap">
    <section class="hero">
      <div class="hero-inner">
        <div style="display:flex;flex-direction:column;gap:14px">
          <h1>Safe Space Kenya Foundation — supporting mental health and empowering young people across Kenya</h1>
          <p class="lead">We provide community counselling, peer-support groups, youth mentorship, and resources that help young Kenyans thrive. We approach mental health with dignity, confidentiality, and cultural sensitivity.</p>

          <div class="hero-buttons">
            <a class="cta" href="#contact">Get Support</a>
            <a style="padding:10px 14px;border-radius:10px;background:transparent;border:2px solid var(--accent);text-decoration:none;color:var(--accent);font-weight:700" href="#programs">Our Programs</a>
          </div>
        </div>

        <div style="margin-top:10px">
          <div class="grid" style="grid-template-columns:repeat(3,1fr)">
            <div class="card">
              <h3>24/7 Helpline</h3>
              <p>Short description: confidential support and crisis referrals. (Helpline number placeholder)</p>
            </div>
            <div class="card">
              <h3>Youth Mentorship</h3>
              <p>Skill-development, school support and career guidance for young people.</p>
            </div>
            <div class="card">
              <h3>Community Workshops</h3>
              <p>Trainings for families, schools and local leaders on mental health and resilience.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="about">
      <div class="two-col">
        <div>
          <h2>About Safe Space Kenya</h2>
          <p>Safe Space Kenya Foundation is a registered non-profit working to improve mental health outcomes for Kenyan youth and communities. We operate peer-support networks, counselling services, and education programs designed to reduce stigma and increase access to care.</p>

          <h3>Our approach</h3>
          <ul>
            <li>Community-led: we train local volunteers and peer counsellors.</li>
            <li>Accessible: services in both English and Kiswahili.</li>
            <li>Trauma-aware: evidence-informed methods and referral pathways to clinical care when needed.</li>
          </ul>
        </div>

        <aside class="card" style="align-self:start">
          <h3>Quick facts</h3>
          <p><strong>Founded:</strong> 2025</p>
          <p><strong>Focus:</strong> Youth, mental health, empowerment</p>
          <p><strong>Coverage:</strong> Nairobi, Kiambu, Nakuru (expandable)</p>
        </aside>
      </div>
    </section>

    <section id="programs">
      <h2>Programs & Services</h2>
      <div class="grid programs">
        <div class="card">
          <h3>Peer Support Groups</h3>
          <p>Weekly safe-space meetings led by trained peer facilitators focusing on coping skills, relationship support and school stress.</p>
        </div>
        <div class="card">
          <h3>Counselling & Referrals</h3>
          <p>Short-term counselling with clear referral pathways for specialized clinical care.</p>
        </div>
        <div class="card">
          <h3>Skills & Mentorship</h3>
          <p>Vocational guidance, life skills training and mentorship for at-risk youth to improve employability.</p>
        </div>
      </div>
    </section>

    <section id="resources">
      <h2>Resources</h2>
      <p>Below are short resources we provide; link them to PDFs or dedicated pages when you publish the site.</p>
      <ul>
        <li><strong>How to support a friend:</strong> practical do's and don'ts when someone is struggling.</li>
        <li><strong>When to seek professional help:</strong> signs that referral is needed.</li>
        <li><strong>Self-care checklist:</strong> daily practices to stabilise mood and energy.</li>
      </ul>
    </section>

    <section id="donate">
      <h2>Support our work</h2>
      <p>Your donations keep our helpline running, fund training for peer counsellors, and support community workshops.</p>
      <div style="display:flex;gap:12px;flex-wrap:wrap">
        <!-- Replace href with your PayPal / Mpesa / Flutterwave link -->
        <a class="cta" href="#" onclick="alert('Replace this link with your payment processor (PayPal, Mpesa, Flutterwave)')">Donate — PayPal</a>
        <a style="padding:12px 14px;border-radius:10px;border:2px solid var(--accent);text-decoration:none;color:var(--accent);font-weight:700" href="#">Donate — MPESA</a>
        <a style="padding:12px 14px;border-radius:10px;border:2px solid var(--accent);text-decoration:none;color:var(--accent);font-weight:700" href="#">Become a Volunteer</a>
      </div>
    </section>

    <section id="contact">
      <h2>Contact & Get Support</h2>
      <div class="two-col">
        <div>
          <p>If you need immediate support, call our helpline at <strong>+254 700 000 000</strong> (placeholder). For general enquiries, use the contact form — we respond within 48 hours on business days.</p>

          <!-- Formspree example; replace action with your endpoint or backend -->
          <form action="https://formspree.io/f/yourformid" method="POST">
            <label for="name">Full name</label>
            <input id="name" name="name" placeholder="Your full name" required />

            <label for="email">Email</label>
            <input id="email" type="email" name="email" placeholder="you@example.com" required />

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5" placeholder="Tell us how we can help" required></textarea>

            <button type="submit" style="background:var(--accent);color:#fff">Send message</button>
          </form>
        </div>

        <aside class="card">
          <h3>Office</h3>
          <p>Street: Placeholder Road, Nairobi</p>
          <p>Email: <a href="mailto:info@safespacekenya.org">info@safespacekenya.org</a></p>
          <p>Follow us on social media for updates.</p>
        </aside>
      </div>
    </section>

    <footer>
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <div>© Safe Space Kenya Foundation — All rights reserved.</div>
        <div style="display:flex;gap:12px">
          <a href="#about">Privacy</a>
          <a href="#about">Terms</a>
        </div>
      </div>
    </footer>

  </main>

</body>
</html>
# SAFESPACEKENYA-FOUNDATION-
