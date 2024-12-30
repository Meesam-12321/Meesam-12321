<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meesam Imran - CV</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Arial', sans-serif;
      background-color: #f4f7fc;
      color: #333;
      line-height: 1.6;
      padding: 20px;
    }

    h1 {
      text-align: center;
      font-size: 2.5em;
      color: #4b4bff;
      animation: fadeIn 2s ease-in-out;
    }

    p {
      text-align: center;
      font-size: 1.1em;
      color: #555;
    }

    a {
      color: #4b4bff;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    a:hover {
      color: #ff5733;
    }

    section {
      margin: 30px 0;
    }

    .section-title {
      font-size: 1.8em;
      color: #2d2d2d;
      text-align: center;
      margin-bottom: 10px;
      text-transform: uppercase;
      letter-spacing: 2px;
      animation: slideInFromLeft 1.5s ease;
    }

    .content {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 1000px;
      margin: auto;
      animation: fadeIn 2s ease-in-out;
    }

    .content div {
      padding: 10px;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .content div:hover {
      transform: scale(1.05);
      box-shadow: 0 10px 15px rgba(0, 0, 0, 0.15);
    }

    .content .title {
      font-weight: bold;
      color: #4b4bff;
    }

    .content .description {
      margin-top: 10px;
      color: #777;
    }

    .content .list {
      list-style: none;
      margin-top: 10px;
    }

    .content .list li {
      margin-bottom: 10px;
    }

    .skills, .achievements {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      animation: fadeIn 2s ease-in-out;
    }

    .skills .skill, .achievements .achievement {
      background-color: #f8f8f8;
      padding: 15px;
      border-radius: 8px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .skills .skill:hover, .achievements .achievement:hover {
      transform: scale(1.05);
      box-shadow: 0 10px 15px rgba(0, 0, 0, 0.15);
    }

    .footer {
      text-align: center;
      margin-top: 30px;
      color: #777;
    }

    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }

    @keyframes slideInFromLeft {
      0% { transform: translateX(-100%); }
      100% { transform: translateX(0); }
    }

  </style>
</head>
<body>

  <h1>Meesam Imran</h1>
  <p>
    <a href="mailto:meesamimran1042@gmail.com">meesamimran1042@gmail.com</a> — 
    <a href="https://www.linkedin.com/in/meesam-imran-9b2780235/">LinkedIn</a> — 
    <a href="https://leetcode.com/u/Meesam1214/">LeetCode Profile</a> — 
    0322-8556114
  </p>

  <section>
    <h2 class="section-title">🎓 Education</h2>
    <div class="content">
      <div>
        <p class="title">Bachelor of Science in Computer Science</p>
        <p>June 2025 - Namal University Mianwali, Lahore</p>
      </div>
    </div>
  </section>

  <section>
    <h2 class="section-title">💼 Experience</h2>
    <div class="content">
      <div>
        <p class="title">Lead Backend Developer and DevOps Engineer</p>
        <p>EZMDSolutions, YANA Medical Project (August 2024 - Present)</p>
        <ul class="list">
          <li>Led a team of backend developers for YANA Medical, overseeing the design and implementation of scalable APIs.</li>
          <li>Optimized cloud infrastructure on AWS, GCP, and Azure.</li>
          <li>Automated infrastructure provisioning using Terraform and Ansible.</li>
        </ul>
      </div>
      <div>
        <p class="title">Research Assistant</p>
        <p>Centre of AI and Big Data (CAID), Namal University (February 2024 - August 2024)</p>
        <ul class="list">
          <li>Contributed to configuring Pakistan’s fastest supercomputer for AI applications.</li>
          <li>Developed edge computing solutions on RISC-V architecture.</li>
          <li>Built and deployed web apps using JavaScript, HTML, and CSS on supercomputers.</li>
        </ul>
      </div>
      <div>
        <p class="title">Co-Founder and Technical Lead</p>
        <p>Innoware Labs (Registered with SECP) (December 2023 - Present)</p>
        <ul class="list">
          <li>Co-founded a software services company.</li>
          <li>Led development of multiple client projects, ensuring timely delivery and high-quality results.</li>
        </ul>
      </div>
    </div>
  </section>

  <section>
    <h2 class="section-title">🚀 Featured Projects</h2>
    <div class="content">
      <div>
        <p class="title">Hotel Management Software with Auth & Stripe Integration</p>
        <ul class="list">
          <li>Developed a full-fledged hotel management system with booking, payment (Stripe), and authentication.</li>
        </ul>
      </div>
      <div>
        <p class="title">Chat Application</p>
        <ul class="list">
          <li>Developed a responsive chat platform with real-time communication and dynamic chatrooms.</li>
        </ul>
      </div>
      <div>
        <p class="title">YANA Medical Front-End & Backend</p>
        <ul class="list">
          <li>Led front-end and backend development for YANA Medical with cloud-based solutions for scalability and security.</li>
        </ul>
      </div>
    </div>
  </section>

  <section>
    <h2 class="section-title">🛠️ Skills</h2>
    <div class="skills">
      <div class="skill">Python</div>
      <div class="skill">JavaScript</div>
      <div class="skill">React</div>
      <div class="skill">Node.js</div>
      <div class="skill">AWS</div>
      <div class="skill">MongoDB</div>
    </div>
  </section>

  <section>
    <h2 class="section-title">🏆 Achievements</h2>
    <div class="achievements">
      <div class="achievement">1st Prize: National Tech Expo (May 2024)</div>
      <div class="achievement">2nd Position: Inter-University Hackathon (Codex) (May 2024)</div>
      <div class="achievement">Best Project Award: Namal Tech Expo (May 2024)</div>
    </div>
  </section>

  <section>
    <h2 class="section-title">📚 Courses & Learning</h2>
    <div class="content">
      <div>
        <p class="title">100 Days of ML and 100 Days of DL</p>
        <p>Completed courses from CampusX, an online platform.</p>
      </div>
      <div>
        <p class="title">Flutter Complete Course</p>
        <p>Udemy certified course by Riwaan Ranawat.</p>
      </div>
      <div>
        <p class="title">JavaScript Course</p>
        <p>Course by Jonas Schmedtmann, Udemy.</p>
      </div>
    </div>
  </section>

  <div class="footer">
    <p>Created with 💻 by Meesam Imran</p>
  </div>
</body>
</html>
