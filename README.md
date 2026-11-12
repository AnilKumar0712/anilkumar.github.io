# anilkumar.github.io
Personal Healthcare Data Analytics Portfolio

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Anil Kumar | Healthcare Data Analyst</title>

  <meta name="description"
    content="Anil Kumar's professional portfolio in healthcare analytics, data analysis and business intelligence.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #080d18;
      color: #f1f5f9;
      font-family: Arial, sans-serif;
      line-height: 1.7;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 24px 8%;
      border-bottom: 1px solid #1e293b;
    }

    .logo {
      color: #60a5fa;
      font-size: 22px;
      font-weight: bold;
    }

    nav a {
      color: #cbd5e1;
      text-decoration: none;
      margin-left: 20px;
      font-size: 14px;
    }

    .hero {
      min-height: 75vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 80px 12%;
      background:
        radial-gradient(ellipse at top right,
        #16345a 0%, #080d18 65%);
    }

    .tag {
      color: #60a5fa;
      font-size: 14px;
      letter-spacing: 2px;
      text-transform: uppercase;
    }

    h1 {
      font-size: clamp(40px, 7vw, 76px);
      line-height: 1.15;
      margin: 20px 0;
    }

    h1 span {
      color: #60a5fa;
    }

    .intro {
      color: #94a3b8;
      max-width: 650px;
      font-size: 18px;
    }

    .buttons {
      display: flex;
      gap: 16px;
      margin-top: 32px;
      flex-wrap: wrap;
    }

    .btn {
      padding: 12px 24px;
      border-radius: 7px;
      text-decoration: none;
      font-weight: bold;
    }

    .primary {
      background: #2563eb;
      color: white;
    }

    .secondary {
      border: 1px solid #475569;
      color: white;
    }

    section {
      padding: 75px 12%;
    }

    h2 {
      font-size: 32px;
      margin-bottom: 20px;
    }

    .muted {
      color: #94a3b8;
      max-width: 750px;
    }

    .projects {
      display: grid;
      grid-template-columns:
        repeat(auto-fit, minmax(230px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .card {
      background: #111c2d;
      border: 1px solid #26364d;
      padding: 25px;
      border-radius: 12px;
    }

    .card h3 {
      color: #93c5fd;
      margin-bottom: 12px;
    }

    .card p {
      color: #94a3b8;
      font-size: 14px;
    }

    footer {
      text-align: center;
      padding: 30px;
      color: #64748b;
      border-top: 1px solid #1e293b;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        gap: 12px;
      }

      nav a {
        margin: 0 7px;
      }

      .hero {
        padding: 65px 7%;
      }

      section {
        padding: 55px 7%;
      }
    }
  </style>
</head>

<body>

  <nav>
    <div class="logo">AK.</div>

    <div>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <header class="hero">
    <p class="tag">Healthcare | Data | Analytics</p>

    <h1>
      Hi, I'm Anil Kumar.<br>
      I turn data into
      <span>insights.</span>
    </h1>

    <p class="intro">
      Aspiring Healthcare Data Analyst with a
      Bachelor of Pharmacy background and
      experience in healthcare operations,
      digital marketing and client coordination.
      Passionate about data analysis and
      business intelligence.
    </p>

    <div class="buttons">
      <a href="#projects" class="btn primary">
        Explore My Projects
      </a>

      <a href="#contact" class="btn secondary">
        Contact Me
      </a>
    </div>
  </header>

  <section id="about">
    <h2>About Me</h2>

    <p class="muted">
      I hold a Bachelor of Pharmacy degree and
      have professional experience in healthcare
      pathology operations and digital marketing.
      I am developing my analytical skills to
      combine healthcare domain knowledge with
      data-driven decision making.
    </p>
  </section>

  <section id="skills">
    <h2>Technical Skills</h2>

    <div class="projects">
      <div class="card">
        <h3>Microsoft Excel</h3>
        <p>Data organisation and analysis.</p>
      </div>

      <div class="card">
        <h3>SQL</h3>
        <p>Database querying and data extraction.</p>
      </div>

      <div class="card">
        <h3>Power BI</h3>
        <p>Data visualisation and dashboards.</p>
      </div>

      <div class="card">
        <h3>Healthcare Analytics</h3>
        <p>Healthcare operations and performance analysis.</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Featured Projects</h2>

    <p class="muted">
      Practical analytics projects demonstrating
      my technical skills and problem-solving approach.
    </p>

    <div class="projects">
      <div class="card">
        <h3>Hospital Analytics</h3>
        <p>
          Patient visits, admissions and
          hospital performance analysis.
        </p>
      </div>

      <div class="card">
        <h3>Pharmacy Analytics</h3>
        <p>
          Pharmacy sales, inventory and
          stock movement analysis.
        </p>
      </div>

      <div class="card">
        <h3>Healthcare SQL Analysis</h3>
        <p>
          Healthcare dataset exploration
          using SQL queries.
        </p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Let's Connect</h2>

    <p class="muted">
      Interested in healthcare analytics,
      data analysis and business intelligence.
      Let's connect professionally.
    </p>

    <div class="buttons">
      <a href="https://www.linkedin.com/"
         class="btn primary">
        LinkedIn
      </a>

      <a href="https://github.com/"
         class="btn secondary">
        GitHub
      </a>
    </div>
  </section>

  <footer>
    © 2026 Anil Kumar | Healthcare Data Analytics Portfolio
  </footer>

</body>
</html>
