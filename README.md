<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Natalie Thornton · Ottawa, ON</title>
  <meta name="description" content="High school graduate heading to uOttawa in fall 2025. Available for summer employment in Ottawa." />
  <link rel="stylesheet" href="css/styles.css" />
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@2.44.0/tabler-icons.min.css" />
  <style>
    .accent-bar { background: var(--nat-mid); }
    .sub-nav__links a.active { border-bottom-color: var(--nat); color: var(--nat); }
    .person-hero__avatar { border-color: var(--nat-mid); }
    .person-hero__title { color: var(--nat); }
    .stat-card { background: var(--nat-light); }
    .stat-card__num { color: #26215C; }
    .stat-card__label { color: var(--nat); }
    .pill { background: var(--nat-light); color: #3C3489; }
    .pill__dot { background: var(--nat-mid); }
    .exp-block__role { color: var(--nat); }
    .exp-block__bullet::before { color: var(--nat-mid); }
    .avail-badge { background: var(--nat); }
    .hiring-banner { background: var(--nat-light); border-color: #AFA9EC; }
    .hiring-banner__icon { background: var(--nat); }
    .hiring-banner__title { color: #26215C; }
    .hiring-banner__sub { color: var(--nat); }
    .person-footer { background: var(--nat-light); border-top-color: #AFA9EC; }
    .person-footer, .person-footer a { color: var(--nat); }
  </style>
</head>
<body>

  <nav class="site-nav">
    <a href="index.html" class="site-nav__logo">the <span>thorntons</span></a>
    <ul class="site-nav__links">
      <li><a href="jennifer.html">Jennifer</a></li>
      <li><a href="rob.html">Rob</a></li>
      <li><a href="natalie.html" class="active">Natalie</a></li>
      <li><a href="kaitlyn.html">Kaitlyn</a></li>
      <li><a href="index.html#photos">Photos</a></li>
    </ul>
  </nav>

  <div class="accent-bar"></div>

  <div style="background:#fff; border-bottom:0.5px solid var(--border);">
    <div class="page-wrap">
      <nav class="sub-nav" style="padding:0;">
        <a href="index.html" class="sub-nav__back">
          <i class="ti ti-arrow-left" style="font-size:13px;"></i> Home
        </a>
        <ul class="sub-nav__links">
          <li><a href="#about" class="active">About</a></li>
          <li><a href="#resume">Resume</a></li>
          <li><a href="#goals">Goals</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </div>

  <main>
    <div class="page-wrap">

      <!-- ── Hero ──────────────────────────────────────── -->
      <section class="person-hero" id="about">
        <!-- Replace src with images/natalie.jpg -->
        <img class="person-hero__avatar" src="images/natalie.jpg"
             alt="Natalie Thornton" />
        <div>
          <h1 class="person-hero__name">Natalie Thornton</h1>
          <p class="person-hero__title">High school graduate &nbsp;·&nbsp; uOttawa bound &nbsp;·&nbsp; Ottawa, ON</p>
          <p class="person-hero__bio">
            Graduating this spring and heading to the University of Ottawa in the fall.
            Detail-oriented, dependable, and eager to contribute — I'm looking for a summer
            position where I can learn, grow, and make a real impact.
          </p>
          <div class="btn-row">
            <a href="files/natalie-resume.pdf" class="btn-primary" style="background:var(--nat);">
              <i class="ti ti-download" style="font-size:14px;"></i> Download resume
            </a>
            <a href="#contact" class="btn-secondary" style="color:var(--nat);border-color:#AFA9EC;">
              <i class="ti ti-mail" style="font-size:14px;"></i> Get in touch
            </a>
          </div>
        </div>
      </section>

      <!-- ── uOttawa + availability banner ──────────────── -->
      <div style="padding-top:32px;">
        <div class="hiring-banner">
          <div class="hiring-banner__icon">
            <i class="ti ti-school" style="font-size:20px;color:#fff;"></i>
          </div>
          <div>
            <p class="hiring-banner__title">University of Ottawa &nbsp;·&nbsp; starting fall 2025</p>
            <p class="hiring-banner__sub">First-year student — program to be confirmed</p>
          </div>
          <span class="avail-badge">
            <span class="avail-dot"></span> Available for summer 2025
          </span>
        </div>

        <!-- ── Stats ───────────────────────────────────── -->
        <div class="stat-grid">
          <div class="stat-card">
            <span class="stat-card__num">OSSD</span>
            <span class="stat-card__label">Ontario Scholar</span>
          </div>
          <div class="stat-card">
            <span class="stat-card__num">uOttawa</span>
            <span class="stat-card__label">fall 2025</span>
          </div>
          <div class="stat-card">
            <span class="stat-card__num">Open</span>
            <span class="stat-card__label">to all opportunities</span>
          </div>
        </div>
      </div>

      <!-- ── Body grid ─────────────────────────────────── -->
      <div class="body-grid--equal body-grid" id="resume" style="padding-top:0;">

        <div>
          <p class="sec-label">Skills</p>
          <div class="pill-wrap" style="margin-bottom:28px;">
            <span class="pill"><span class="pill__dot"></span>Microsoft Office</span>
            <span class="pill"><span class="pill__dot"></span>Google Workspace</span>
            <span class="pill"><span class="pill__dot"></span>Customer service</span>
            <span class="pill"><span class="pill__dot"></span>Data entry</span>
            <span class="pill"><span class="pill__dot"></span>Written communication</span>
            <span class="pill"><span class="pill__dot"></span>Time management</span>
            <span class="pill"><span class="pill__dot"></span>Teamwork</span>
            <span class="pill"><span class="pill__dot"></span>Quick learner</span>
          </div>

          <p class="sec-label">Education</p>
          <div class="exp-block">
            <div class="exp-block__top">
              <span class="exp-block__company">Local High School, Ottawa</span>
              <span class="exp-block__date">2020 – 2025</span>
            </div>
            <p class="exp-block__role">Ontario Secondary School Diploma</p>
            <p class="exp-block__bullet">Ontario Scholar (80%+ average)</p>
            <p class="exp-block__bullet">Relevant courses: business, mathematics, communications</p>
          </div>

          <!-- Goals section -->
          <p class="sec-label" id="goals" style="margin-top:8px;">Looking ahead</p>
          <div style="background:var(--nat-light); border-radius:var(--radius-md); padding:16px 18px;">
            <p style="font-size:13px; color:#26215C; line-height:1.7;">
              I'm excited to start at uOttawa this fall and build toward a meaningful career.
              This summer, I want to gain hands-on professional experience, develop new skills,
              and contribute to a team that values reliability and a positive attitude.
            </p>
          </div>
        </div>

        <div>
          <p class="sec-label">Experience &amp; activities</p>

          <div class="exp-block">
            <div class="exp-block__top">
              <span class="exp-block__company">Part-time work</span>
              <span class="exp-block__date">2024 – present</span>
            </div>
            <p class="exp-block__role">Customer service team member</p>
            <p class="exp-block__bullet">Customer-facing service in a fast-paced environment</p>
            <p class="exp-block__bullet">Cash handling and POS operation</p>
            <p class="exp-block__bullet">Maintaining a positive, professional attitude under pressure</p>
          </div>

          <div class="exp-block">
            <div class="exp-block__top">
              <span class="exp-block__company">School activities</span>
              <span class="exp-block__date">2022 – 2025</span>
            </div>
            <p class="exp-block__role">Clubs &amp; student life</p>
            <p class="exp-block__bullet">Active participation in school clubs and events</p>
            <p class="exp-block__bullet">Demonstrated leadership and collaboration</p>
          </div>

          <div class="exp-block">
            <div class="exp-block__top">
              <span class="exp-block__company">Community volunteering</span>
              <span class="exp-block__date">2023 – 2025</span>
            </div>
            <p class="exp-block__role">Volunteer</p>
            <p class="exp-block__bullet">Community service hours in Ottawa area</p>
            <p class="exp-block__bullet">Event support and team-based tasks</p>
          </div>

          <!-- Contact -->
          <p class="sec-label" id="contact">Get in touch</p>
          <div style="background:var(--nat-light); border-radius:var(--radius-md); padding:16px 18px;">
            <p style="font-size:13px; color:#26215C; margin-bottom:10px; line-height:1.6;">
              Available for summer employment starting immediately. Happy to provide references.
            </p>
            <a href="mailto:natalie@thethorntons.ca" class="btn-primary" style="background:var(--nat); font-size:12px;">
              <i class="ti ti-mail" style="font-size:13px;"></i> natalie@thethorntons.ca
            </a>
          </div>
        </div>

      </div>

    </div>
  </main>

  <footer class="person-footer">
    <span>natalie.thethorntons.ca</span>
    <div class="person-footer__links">
      <a href="mailto:natalie@thethorntons.ca">
        <i class="ti ti-mail" style="font-size:14px;"></i> Email
      </a>
      <a href="https://linkedin.com" target="_blank" rel="noopener">
        <i class="ti ti-brand-linkedin" style="font-size:14px;"></i> LinkedIn
      </a>
    </div>
  </footer>

</body>
</html>
