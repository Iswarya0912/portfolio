# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Iswarya B. Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    /* Global Styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Inter', sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f7f9fc;
    }
    a {
      text-decoration: none;
      color: #4CAF50;
      transition: color 0.3s;
    }
    a:hover {
      color: #388E3C;
    }
    section {
      max-width: 1000px;
      margin: auto;
      padding: 60px 20px;
    }
    h2 {
      color: #4CAF50;
      margin-bottom: 20px;
      font-weight: 700;
      border-bottom: 2px solid #4CAF50;
      display: inline-block;
      padding-bottom: 5px;
    }

    /* Header */
    header {
      background: #4CAF50;
      color: #fff;
      text-align: center;
      padding: 80px 20px 60px 20px;
    }
    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2em;
    }

    /* Contact */
    .contact {
      text-align: center;
      margin-top: 10px;
    }
    .contact a {
      margin: 0 10px;
      font-weight: 600;
    }

    /* Skills */
    .skills ul {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      list-style: none;
      padding: 0;
    }
    .skills li {
      background: #e6f4ea;
      color: #2e7d32;
      padding: 10px 15px;
      border-radius: 8px;
      font-weight: 600;
    }

    /* Projects */
    .projects {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 25px;
    }
    .project-card {
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.05);
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .project-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    }
    .project-card h3 {
      margin-bottom: 10px;
      color: #2e7d32;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .projects {
        grid-template-columns: 1fr;
      }
      header h1 {
        font-size: 2.5em;
      }
    }

  </style>
</head>
<body>

<header>
  <h1>Iswarya B.</h1>
  <p>Engineering Professional | IoT & Embedded Systems | Data Analysis</p>
  <div class="contact">
    📧 <a href="mailto:your.email@example.com">your.email@example.com</a> | 
    📞 +91 XXXXX XXXXX | 
    🔗 <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a> | 
    💻 <a href="https://github.com/yourprofile" target="_blank">GitHub</a>
  </div>
</header>

<section>
  <h2>About Me</h2>
  <p>
    Enthusiastic engineering professional with hands-on experience in IoT, embedded systems, Python-based data analysis, and EV powertrain simulation. Skilled in designing automated data collection systems, performing statistical and machine learning-based analysis, and developing efficient solutions for industrial applications.
  </p>
</section>

<section class="skills">
  <h2>Skills</h2>
  <ul>
    <li>Python, C, MATLAB</li>
    <li>LabVIEW, Streamlit, MQTT, MySQL</li>
    <li>NI-DAQ, Excel Automation</li>
    <li>Vibration Analysis, FFT, Coherence</li>
    <li>EV Simulation, IoT, Smart Manufacturing</li>
    <li>Problem-solving, Teamwork</li>
  </ul>
</section>

<section>
  <h2>Projects</h2>
  <div class="projects">
    <div class="project-card">
      <h3>Vibration Data Logging & Analysis</h3>
      <p>Real-time vibration logging using NI DAQ and Python. Automated Excel batch logging via MQTT/WebSocket, feature extraction, and ML-based defect detection.</p>
    </div>
    <div class="project-card">
      <h3>EV Powertrain Simulation</h3>
      <p>Simulated realistic EV battery pack dynamics with SOC, efficiency, and thermal modeling. Performed physics-based powertrain calculations for performance prediction.</p>
    </div>
    <div class="project-card">
      <h3>Expense Tracker Web App</h3>
      <p>Developed Python Streamlit app for tracking, categorizing, and managing expenses with secure login and dynamic report generation.</p>
    </div>
    <div class="project-card">
      <h3>C Programming Systems</h3>
      <p>Built Dynamic Configuration Loader, Hospital Patient Management, and Student Records Management systems using linked lists, files, and error handling.</p>
    </div>
  </div>
</section>

<section>
  <h2>Education</h2>
  <p>B.E. in [Your Branch], [Your University], [Year of Passing]</p>
</section>

<section>
  <h2>Certifications</h2>
  <p>NPTEL – Introduction to Industry 4.0 & Industrial IoT</p>
</section>

<section>
  <h2>Achievements & Interests</h2>
  <ul>
    <li>Developed real-time industrial data analysis applications for smart manufacturing.</li>
    <li>Passionate about IoT, automation, and predictive analytics.</li>
  </ul>
</section>

</body>
</html>
