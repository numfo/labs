---
layout: default
title: Home
---

<style>
  .hero {
    text-align: center;
    padding: 60px 20px;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    border-radius: 10px;
    margin-bottom: 40px;
  }
  
  .logo-container {
    margin-bottom: 20px;
  }
  
  .hero h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
    font-weight: 700;
  }
  
  .hero p {
    font-size: 1.2em;
    opacity: 0.95;
    max-width: 600px;
    margin: 0 auto;
  }
  
  .topics-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
    margin: 40px 0;
  }
  
  .topic-card {
    background: #f8f9fa;
    border: 2px solid #e9ecef;
    border-radius: 8px;
    padding: 30px;
    transition: all 0.3s ease;
    text-align: center;
  }
  
  .topic-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    border-color: #667eea;
  }
  
  .topic-icon {
    font-size: 3em;
    margin-bottom: 15px;
  }
  
  .topic-card h3 {
    color: #2d3748;
    margin-bottom: 10px;
  }
  
  .topic-card p {
    color: #718096;
    line-height: 1.6;
  }
  
  .cta-section {
    text-align: center;
    padding: 40px 20px;
    background: #f7fafc;
    border-radius: 8px;
    margin: 40px 0;
  }
  
  .cta-section h2 {
    color: #2d3748;
    margin-bottom: 15px;
  }
  
  .tech-stack {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
    margin-top: 20px;
  }
  
  .tech-badge {
    background: white;
    border: 2px solid #667eea;
    color: #667eea;
    padding: 8px 16px;
    border-radius: 20px;
    font-weight: 600;
    font-size: 0.9em;
  }
  
  @media (max-width: 768px) {
    .hero h1 {
      font-size: 2em;
    }
    .topics-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="hero">
  <div class="logo-container">
    <svg width="120" height="120" viewBox="0 0 120 120" xmlns="http://www.w3.org/2000/svg">
      <!-- Circuit board background -->
      <rect width="120" height="120" rx="15" fill="#ffffff" opacity="0.1"/>
      
      <!-- Central processor chip -->
      <rect x="40" y="40" width="40" height="40" rx="3" fill="#ffffff" stroke="#ffffff" stroke-width="2"/>
      
      <!-- Chip pins -->
      <line x1="30" y1="50" x2="40" y2="50" stroke="#ffffff" stroke-width="2"/>
      <line x1="30" y1="60" x2="40" y2="60" stroke="#ffffff" stroke-width="2"/>
      <line x1="30" y1="70" x2="40" y2="70" stroke="#ffffff" stroke-width="2"/>
      
      <line x1="80" y1="50" x2="90" y2="50" stroke="#ffffff" stroke-width="2"/>
      <line x1="80" y1="60" x2="90" y2="60" stroke="#ffffff" stroke-width="2"/>
      <line x1="80" y1="70" x2="90" y2="70" stroke="#ffffff" stroke-width="2"/>
      
      <line x1="50" y1="30" x2="50" y2="40" stroke="#ffffff" stroke-width="2"/>
      <line x1="60" y1="30" x2="60" y2="40" stroke="#ffffff" stroke-width="2"/>
      <line x1="70" y1="30" x2="70" y2="40" stroke="#ffffff" stroke-width="2"/>
      
      <line x1="50" y1="80" x2="50" y2="90" stroke="#ffffff" stroke-width="2"/>
      <line x1="60" y1="80" x2="60" y2="90" stroke="#ffffff" stroke-width="2"/>
      <line x1="70" y1="80" x2="70" y2="90" stroke="#ffffff" stroke-width="2"/>
      
      <!-- AI brain symbol -->
      <circle cx="55" cy="55" r="8" fill="none" stroke="#667eea" stroke-width="2.5"/>
      <circle cx="65" cy="55" r="8" fill="none" stroke="#667eea" stroke-width="2.5"/>
      <path d="M 55 63 Q 60 68 65 63" fill="none" stroke="#667eea" stroke-width="2.5"/>
      
      <!-- Circuit traces -->
      <circle cx="20" cy="20" r="3" fill="#ffffff"/>
      <circle cx="100" cy="20" r="3" fill="#ffffff"/>
      <circle cx="20" cy="100" r="3" fill="#ffffff"/>
      <circle cx="100" cy="100" r="3" fill="#ffffff"/>
      
      <path d="M 20 20 L 40 40" stroke="#ffffff" stroke-width="1.5" opacity="0.6"/>
      <path d="M 100 20 L 80 40" stroke="#ffffff" stroke-width="1.5" opacity="0.6"/>
      <path d="M 20 100 L 40 80" stroke="#ffffff" stroke-width="1.5" opacity="0.6"/>
      <path d="M 100 100 L 80 80" stroke="#ffffff" stroke-width="1.5" opacity="0.6"/>
    </svg>
  </div>
  
  <h1>IoT, AI & Embedded Systems</h1>
  <p>Exploring the intersection of hardware, software, and intelligence. Practical tutorials, code examples, and deep dives into modern development.</p>
</div>

<div class="topics-grid">
  <div class="topic-card">
    <div class="topic-icon">🔌</div>
    <h3>Embedded Systems</h3>
    <p>ESP32, Arduino, and microcontroller projects. From sensor networks to real-time control systems with C++ and Python.</p>
  </div>
  
  <div class="topic-card">
    <div class="topic-icon">🤖</div>
    <h3>AI & Machine Learning</h3>
    <p>Edge AI, TinyML, and intelligent IoT devices. Implementing ML models on resource-constrained hardware.</p>
  </div>
  
  <div class="topic-card">
    <div class="topic-icon">⚙️</div>
    <h3>Software Design</h3>
    <p>Architecture patterns, API design with FastAPI, and best practices for scalable IoT backends and firmware.</p>
  </div>
</div>

<div class="cta-section">
  <h2>Tech Stack</h2>
  <p>Technologies and tools covered in tutorials and projects</p>
  <div class="tech-stack">
    <span class="tech-badge">Python</span>
    <span class="tech-badge">C++</span>
    <span class="tech-badge">FastAPI</span>
    <span class="tech-badge">ESP32</span>
    <span class="tech-badge">MQTT</span>
    <span class="tech-badge">Arduino</span>
    <span class="tech-badge">TensorFlow Lite</span>
    <span class="tech-badge">Docker</span>
  </div>
</div>

## Latest Posts

<!-- This section will automatically populate with your blog posts -->
<div class="posts-list">
  {% for post in site.posts limit:5 %}
    <article class="post-preview">
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
      <p>{{ post.excerpt }}</p>
    </article>
  {% endfor %}
</div>

<style>
  .posts-list {
    margin-top: 30px;
  }
  
  .post-preview {
    padding: 20px;
    border-left: 4px solid #667eea;
    margin-bottom: 25px;
    background: #f8f9fa;
    border-radius: 0 8px 8px 0;
  }
  
  .post-preview h3 {
    margin-top: 0;
    margin-bottom: 8px;
  }
  
  .post-preview h3 a {
    color: #2d3748;
    text-decoration: none;
  }
  
  .post-preview h3 a:hover {
    color: #667eea;
  }
  
  .post-meta {
    color: #718096;
    font-size: 0.9em;
    margin-bottom: 10px;
  }
</style>
