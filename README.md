<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DSDelectronics</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f0f2f5;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #4a90e2;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
      background: #357ABD;
      padding: 10px;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    /* Hero Section with Animation */
    .hero {
      background: url('https://source.unsplash.com/1600x600/?technology,nature') no-repeat center center/cover;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 4px #000;
      text-align: center;
      animation: fadeZoom 1.5s ease-out forwards;
    }

    .hero h1 {
      font-size: 3em;
      margin-bottom: 10px;
      overflow: hidden;
      white-space: nowrap;
      border-right: 2px solid white;
      width: 0;
      animation: typing 3s steps(20) 0.5s forwards, blink 0.7s infinite;
    }

    .hero img {
      margin-top: 15px;
      width: 100px;
      opacity: 0;
      animation: fadeUp 1s ease-out 3s forwards;
    }

    .hero p {
      margin-top: 15px;
      font-size: 1.2em;
      opacity: 0;
      animation: fadeUp 1s ease-out 3.5s forwards;
    }

    /* Animations */
    @keyframes fadeZoom {
      from {
        opacity: 0;
        transform: scale(0.95);
      }
      to {
        opacity: 1;
        transform: scale(1);
      }
    }

    @keyframes typing {
      to {
        width: 100%;
      }
    }

    @keyframes blink {
      50% {
        border-color: transparent;
      }
    }

    @keyframes fadeUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .content {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
      text-align: center;
    }

    .content h2 {
      font-size: 2em;
      margin-bottom: 20px;
    }

    .content p {
      font-size: 1.1em;
      margin-bottom: 20px;
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Welcome to Dsd Electronics</h1>
    <p>discipline • Responsive • Professional</p>
  </header>

  <!-- Navigation -->
<nav data-aos="fade-down" data-aos-duration="800">
  <ul>
    <li data-aos="fade-right" data-aos-delay="100"><a href="#">Home</a></li>
    <li data-aos="fade-right" data-aos-delay="200"><a href="#about">About</a></li>
    <li data-aos="fade-right" data-aos-delay="300"><a href="#services">Services</a></li>
    <li data-aos="fade-right" data-aos-delay="400"><a href="#Our products">Our products</a></li>
    <li data-aos="fade-right" data-aos-delay="500"><a href="#Careers">Careers</a></li>
    <li data-aos="fade-right" data-aos-delay="600"><a href="#contact">Contact</a></li>
  </ul>
</nav>

  <!-- Hero Section with Animations -->
  <section class="hero">
    <div>
      <h1>DSD Electronics</h1>
      <div>
        <img src="E:\official\logo\pcb.png" alt="Centered image" />
      </div>
      <p>designing your PCB & manufacturing</p>
    </div>
  </section>

</body>
</html>


  <!-- About Section -->
  <section class="content" id="about">
    <h2>About Us</h2>
    <p>we provide answers to your electronics questions and offer a full range of custom PCB design services — from schematics to layout. All design work is done in-house, and manufacturing is handled by our trusted partners. Our mission is to bring your electronic ideas to life with precision, quality, and flexibility.

</section>

  <!-- Services Section -->
  <section class="content" id="services">
    <h2>Our Services</h2>
    <p>Ask question about Electronics,Custom PCB design, manufacuring, Searching Jobs ,Internship</p>
  </section>

 <!-- Our product Section -->
  <section class="content" id="Our products">
<h2>Our products</h2>
<p>1. Designed a compact and efficient USB-C power supply with a custom enclosure! This project focuses on reliable power delivery, sleek integration, and ease of use. Excited to explore more in power electronics and embedded systems!"
 I designed custom box for making final product.</section>
<div style="text-align: center;">
  <img src="E:\official\my works\pcb ddesign\1.png" alt="Centered image" style="width: 200px;" />

<section class="content" id="Our products">
<div style="text-align: center;">
<p>2. developed an embedded Arduino-based speed reader system integrated with an external infrared (IR) sensor to measure speed with precision and efficiency. This project allowed me to enhance my skills in sensor integration, data processing, and embedded system design. Using IR technology for accurate, real-time speed detection opens up a range of applications in areas like robotics, sports, and traffic monitoring..</section>
</div>
<div style="text-align: center;">
<img src="E:\official\my works\pcb ddesign\2.jpeg" alt="Centered image" style="width: 400px;" />
</div>

 <!-- Careers Section -->
  <section class="content" id="Careers">
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Job Portal - DSD Electronics</title>
  <style>
    body {
      font-family: Arial;
      background: #f7f7f7;
      padding: 20px;
    }
    section {
      background: #fff;
      padding: 20px;
      margin-bottom: 30px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      max-width: 800px;
      margin-left: auto;
      margin-right: auto;
    }
    input, textarea, button {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background: #007bff;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background: #0056b3;
    }
    .job-card {
      border: 1px solid #ccc;
      padding: 15px;
      border-radius: 5px;
      background: #fdfdfd;
      margin-bottom: 15px;
    }
  </style>
</head>
<body>

<!-- Job Post Form -->
<section>
  <h2>Post a Job or Internship</h2>
  <form id="jobForm">
    <label>Company Name:</label>
    <input type="text" id="company" required>

    <label>Job/Internship Title:</label>
    <input type="text" id="title" required>

    <label>Description:</label>
    <textarea id="description" rows="4" required></textarea>

    <label>Application Email or Link:</label>
    <input type="text" id="apply" required>

    <button type="submit">Post Job</button>
  </form>
</section>

<!-- Job Listings -->
<section>
  <h2>Open Jobs & Internships</h2>
  <div id="jobList"></div>
</section>

<script>
  const form = document.getElementById("jobForm");
  const jobList = document.getElementById("jobList");

  const JOB_STORAGE_KEY = "dsd_jobs";

  // Load existing jobs from localStorage and remove old ones
  function loadJobs() {
    const stored = JSON.parse(localStorage.getItem(JOB_STORAGE_KEY)) || [];
    const now = Date.now();
    const maxAge = 90 * 24 * 60 * 60 * 1000; // 90 days

    const validJobs = stored.filter(job => now - job.createdAt < maxAge);
    localStorage.setItem(JOB_STORAGE_KEY, JSON.stringify(validJobs));

    validJobs.forEach(job => displayJob(job));
  }

  // Display a single job
  function displayJob(job) {
    const jobCard = document.createElement("div");
    jobCard.className = "job-card";
    jobCard.innerHTML = `
      <h3>${job.title}</h3>
      <p><strong>Company:</strong> ${job.company}</p>
      <p>${job.description}</p>
      <p><strong>Apply:</strong> <a href="${job.apply}" target="_blank">${job.apply}</a></p>
    `;
    jobList.prepend(jobCard);
  }

  // Add new job
  form.addEventListener("submit", function (e) {
    e.preventDefault();

    const newJob = {
      company: document.getElementById("company").value,
      title: document.getElementById("title").value,
      description: document.getElementById("description").value,
      apply: document.getElementById("apply").value,
      createdAt: Date.now()
    };

    let jobs = JSON.parse(localStorage.getItem(JOB_STORAGE_KEY)) || [];
    jobs.push(newJob);
    localStorage.setItem(JOB_STORAGE_KEY, JSON.stringify(jobs));

    displayJob(newJob);
    form.reset();
  });

  // On page load
  loadJobs();
</script>

</body>
</html>




<section style="max-width: 600px; margin: 0 auto; padding: 20px;">
  <h2>Ask a Question or Requirement</h2>
  <form action="https://formspree.io/f/xzzggpwg" method="POST">
    <label for="name">Your Name:</label><br />
    <input type="text" id="name" name="name" required style="width: 100%;"><br /><br />

    <label for="email">Your Email:</label><br />
    <input type="email" id="email" name="email" required style="width: 100%;"><br /><br />

    <label for="question">Your Question or Requirement:</label><br />
    <textarea id="question" name="question" rows="5" required style="width: 100%;"></textarea><br /><br />

    <button type="submit">Submit</button>
  </form>
</section>




  <!-- Contact Section -->
  <section class="content" id="contact">
    <h2>Contact Us</h2>
    <p>Email me at: <strong>dsdelectronics06@gmail.com</strong></p>
    <p>Or call me: <strong>+94 779242832</strong></p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Dulara srimantha | Dsd product</p>
  </footer>

</body>
</html>
