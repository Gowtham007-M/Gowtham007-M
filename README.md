<style>
  @keyframes slideInDown {
    from {
      opacity: 0;
      transform: translateY(-30px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  
  @keyframes fadeInUp {
    from {
      opacity: 0;
      transform: translateY(20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  
  @keyframes glow {
    0%, 100% {
      text-shadow: 0 0 5px rgba(0, 150, 255, 0.3), 0 0 10px rgba(0, 150, 255, 0.2);
    }
    50% {
      text-shadow: 0 0 15px rgba(0, 150, 255, 0.6), 0 0 25px rgba(0, 150, 255, 0.4);
    }
  }
  
  @keyframes slideRight {
    from {
      width: 0;
      opacity: 0;
    }
    to {
      width: 100%;
      opacity: 1;
    }
  }
  
  @keyframes pulse {
    0%, 100% {
      opacity: 1;
    }
    50% {
      opacity: 0.7;
    }
  }
  
  @keyframes shimmer {
    0% {
      background-position: -1000px 0;
    }
    100% {
      background-position: 1000px 0;
    }
  }
  
  @keyframes float {
    0%, 100% {
      transform: translateY(0px);
    }
    50% {
      transform: translateY(-8px);
    }
  }
  
  body {
    background: #fafafa;
  }
  
  .header-container {
    animation: slideInDown 0.8s ease-out;
    padding-bottom: 20px;
    border-bottom: 2px solid #0096ff;
    margin-bottom: 30px;
  }
  
  h1 {
    animation: glow 3s ease-in-out infinite;
  }
  
  .content-section {
    animation: fadeInUp 0.8s ease-out;
  }
  
  .badge-link {
    transition: all 0.3s ease;
    animation: float 3s ease-in-out infinite;
  }
  
  .badge-link:hover {
    transform: translateY(-5px);
    filter: drop-shadow(0 4px 8px rgba(0, 150, 255, 0.3));
  }
  
  .skill-bar {
    margin: 12px 0;
    animation: slideRight 0.6s ease-out forwards;
  }
  
  .skill-label {
    font-weight: 600;
    color: #0096ff;
    font-size: 0.9em;
    margin-bottom: 4px;
    display: inline-block;
  }
  
  .progress-container {
    background: #e0e0e0;
    border-radius: 10px;
    height: 6px;
    overflow: hidden;
    box-shadow: inset 0 1px 3px rgba(0,0,0,0.1);
  }
  
  .progress-bar {
    background: linear-gradient(90deg, #0096ff, #00d4ff);
    height: 100%;
    border-radius: 10px;
    animation: slideRight 1s ease-out forwards;
    box-shadow: 0 0 10px rgba(0, 150, 255, 0.5);
  }
  
  hr {
    border: none;
    border-top: 2px solid #0096ff;
    margin: 30px 0;
    opacity: 0.3;
  }
  
  .project-card {
    padding: 15px;
    margin: 12px 0;
    border-left: 3px solid #0096ff;
    background: #f5f5f5;
    border-radius: 4px;
    transition: all 0.3s ease;
  }
  
  .project-card:hover {
    border-left: 3px solid #00d4ff;
    background: #ffffff;
    box-shadow: 0 4px 12px rgba(0, 150, 255, 0.15);
    transform: translateX(5px);
  }
  
  .stack-tag {
    display: inline-block;
    background: #0096ff;
    color: white;
    padding: 2px 8px;
    border-radius: 12px;
    font-size: 0.8em;
    margin: 2px 2px 2px 0;
    animation: fadeInUp 0.5s ease-out;
  }
  
  .competency-table {
    animation: fadeInUp 0.8s ease-out;
  }
  
  .cta {
    animation: glow 2.5s ease-in-out infinite;
    color: #0096ff;
  }
</style>

<div class="header-container">
  <h1 align="center" style="font-size: 2.8em; font-weight: 900; letter-spacing: -1px; color: #000;">⚡ GOWTHAM M</h1>
  <h3 align="center" style="font-size: 1.1em; font-weight: 600; letter-spacing: 0.05em; color: #0096ff; margin-top: -10px;">Google Cloud Certified ML Engineer · AI/ML Specialist</h3>
</div>

<p align="center" style="margin-top: 20px;">
  <a href="https://www.linkedin.com/in/gowtham-off" target="_blank" style="text-decoration: none; margin: 0 8px;" class="badge-link">
    <img src="https://img.shields.io/badge/LINKEDIN-0096FF?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/Gowtham007-M" target="_blank" style="text-decoration: none; margin: 0 8px;" class="badge-link">
    <img src="https://img.shields.io/badge/GITHUB-000?style=flat-square&logo=github&logoColor=white" />
  </a>
  <a href="mailto:40eecgowtham@gmail.com" style="text-decoration: none; margin: 0 8px;" class="badge-link">
    <img src="https://img.shields.io/badge/EMAIL-0096FF?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <a href="https://off-portfolio-lemon.vercel.app/" target="_blank" style="text-decoration: none; margin: 0 8px;" class="badge-link">
    <img src="https://img.shields.io/badge/PORTFOLIO-000?style=flat-square&logo=vercel&logoColor=white" />
  </a>
</p>

---

## 📊 PROFESSIONAL EXPERIENCE

<div class="project-card">

### Data & AI Engineer — TVS Next, Chennai _(Apr 2025 – Nov 2025)_

- Engineered production-grade **predictive maintenance systems** using MCMC, RQA, FFT for equipment failure forecasting
- Built real-time **vibration analysis & anomaly detection pipelines** for manufacturing asset health monitoring
- Developed neural network-based **inventory optimization models** improving supply chain accuracy
- Delivered process efficiency improvements through advanced ML algorithms and statistical modeling

</div>

---

## CERTIFICATIONS & CREDENTIALS

| Certification                          | Issuer             | Valid Until |
| -------------------------------------- | ------------------ | ----------- |
| Professional Machine Learning Engineer | Google Cloud       | Mar 2028    |
| Data Science & Big Data Analytics      | Dr. Ganesh Academy | Jan 2026    |

---

## 🚀 CORE PROJECTS

<div class="project-card">

### Vehicle Number Plate Recognition System

Real-time computer vision system for automated license plate detection and logging.  
<span class="stack-tag">Python</span> <span class="stack-tag">OpenCV</span> <span class="stack-tag">OCR</span> <span class="stack-tag">Computer Vision</span>

</div>

<div class="project-card">

### Face Tracking Camera for Video Conferencing

Real-time ML-based face tracking with dynamic participant framing in live video streams.  
<span class="stack-tag">Python</span> <span class="stack-tag">OpenCV</span> <span class="stack-tag">ML Inference</span> <span class="stack-tag">Real-time Processing</span>

</div>

<div class="project-card">

### Smart Home Automation Platform

IoT-integrated home automation system with sensor integration and intelligent control.  
<span class="stack-tag">Arduino</span> <span class="stack-tag">ESP32</span> <span class="stack-tag">IoT</span> <span class="stack-tag">Sensor Integration</span>

</div>

---

## 🛠️ TECHNICAL SKILLS

### Languages

<div class="skill-bar" style="animation-delay: 0s;">
  <span class="skill-label">Programming Proficiency</span>
  <div class="progress-container">
    <div class="progress-bar" style="width: 90%; animation-delay: 0.2s;"></div>
  </div>
  <span style="font-size: 0.85em; color: #666;">Python · C · C++ · JavaScript</span>
</div>

### Machine Learning & AI

<div class="skill-bar" style="animation-delay: 0.1s;">
  <span class="skill-label">ML Expertise</span>
  <div class="progress-container">
    <div class="progress-bar" style="width: 95%; animation-delay: 0.3s;"></div>
  </div>
  <span style="font-size: 0.85em; color: #666;">Neural Networks · Predictive Analytics · Anomaly Detection · Computer Vision · OCR · Statistical Modeling (MCMC, RQA, FFT)</span>
</div>

### Data Science

<div class="skill-bar" style="animation-delay: 0.2s;">
  <span class="skill-label">Data Engineering</span>
  <div class="progress-container">
    <div class="progress-bar" style="width: 88%; animation-delay: 0.4s;"></div>
  </div>
  <span style="font-size: 0.85em; color: #666;">Big Data Analytics · Data Engineering · Real-Time Data Pipelines</span>
</div>

### Cloud & Databases

<div class="skill-bar" style="animation-delay: 0.3s;">
  <span class="skill-label">Cloud Platform Mastery</span>
  <div class="progress-container">
    <div class="progress-bar" style="width: 92%; animation-delay: 0.5s;"></div>
  </div>
  <span style="font-size: 0.85em; color: #666;">Google Cloud Platform · MySQL · PostgreSQL · Git</span>
</div>

### Tools & Frameworks

<div class="skill-bar" style="animation-delay: 0.4s;">
  <span class="skill-label">Framework Knowledge</span>
  <div class="progress-container">
    <div class="progress-bar" style="width: 90%; animation-delay: 0.6s;"></div>
  </div>
  <span style="font-size: 0.85em; color: #666;">OpenCV · Jupyter · TensorFlow</span>
</div>

---

## 🎯 CORE COMPETENCIES

<div class="competency-table">

|        Domain        |                           Expertise                            |
| :------------------: | :------------------------------------------------------------: |
| 🤖 Machine Learning  | Neural networks, predictive analytics, optimization algorithms |
|  👁️ Computer Vision  |    Real-time image processing, inference, detection systems    |
| ☁️ Cloud Engineering |         GCP ML pipelines, scalable data infrastructure         |
|   📊 Data Science    |  Statistical modeling, big data processing, anomaly detection  |

</div>

---

<p align="center" style="margin-top: 40px; padding: 20px; background: linear-gradient(135deg, #f5f5f5 0%, #ffffff 100%); border-left: 4px solid #0096ff; border-radius: 4px;">
  <span class="cta"><strong>🔍 Available for ML Engineering | AI Solution Development | Data Architecture</strong></span>
</p>
