<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Chirag Bheemaiah PK — Portfolio</title>
  <meta name="description" content="Chirag Bheemaiah PK — Software Engineer (Distributed Systems, ML)">
  <meta id="theme-color" name="theme-color" content="#0a0a0a" />
  <link rel="icon" href="https://github.githubassets.com/favicons/favicon.png" />
  <style>
    :root{
      --bg:#0a0a0a;
      --fg:#f1f5f9;
      --muted:#9ca3af;
      --line:#27272a;
      --accent:#c2410c; /* darker orange */
      --topbg:#111111;
      --max:880px;
      --pad:40px;
      --lh:1.65;
      --h: clamp(1.9rem, 2.4vw + 1rem, 2.6rem);
    }
    .light{ --bg:#ffffff; --fg:#111827; --muted:#475569; --line:#e2e8f0; --accent:#ea580c; --topbg:#f3f4f6 }

    body{margin:0;background:var(--bg);color:var(--fg);font:17px/var(--lh) Inter, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial}
    a{color:var(--accent);text-decoration:none;font-weight:500}
    a:hover{opacity:0.85}
    .wrap{max-width:var(--max);margin:auto;padding:var(--pad) 22px}

    header{display:flex;align-items:center;justify-content:space-between;gap:16px;margin-bottom:24px}
    header.top{background:var(--topbg); border:1px solid var(--line); padding:12px 16px; border-radius:12px; position:relative}
    .brand{display:flex;align-items:center;gap:14px}
    .avatar{width:60px;height:60px;border-radius:50%;border:2px solid var(--accent)}
    .title{font-weight:800;font-size:1.3rem;color:var(--fg)}
    .muted{color:var(--fg)}
    nav{display:flex;gap:18px;flex-wrap:wrap;align-items:center}
    nav a svg{width:20px;height:20px;fill:var(--accent)}

    .toggle{background:none;border:none;cursor:pointer;font-size:1rem;position:fixed;bottom:20px;right:20px;z-index:1000;background:var(--topbg);padding:10px;border-radius:50%;box-shadow:0 2px 6px rgba(0,0,0,0.5)}
    .toggle svg{width:22px;height:22px;fill:var(--accent)}

    h1{font-size:var(--h);line-height:1.2;margin:0 0 10px;color:var(--fg)}
    h2{margin:26px 0 10px;font-size:1.02rem;text-transform:uppercase;letter-spacing:.1em;color:var(--accent)}
    .lead{color:var(--muted)}
    hr{border:none;border-top:1px solid var(--line);margin:26px 0}

    ul{list-style:none;padding:0;margin:0;display:grid;gap:12px}
    li{margin:0}

    .projects li{padding:12px 0 12px 14px;border-bottom:1px solid var(--line);position:relative}
    .projects li:last-child{border-bottom:none}
    .projects li::before{content:"";position:absolute;left:0;top:12px;bottom:12px;width:3px;background:var(--accent)}
    .repo-title{font-weight:700;font-size:1.06rem;color:var(--accent)}
    .repo-desc{font-size:.95rem;color:var(--muted)}

    footer{margin-top:36px;font-size:.9rem;color:var(--muted);text-align:center}
  </style>
</head>
<body>
  <div class="wrap">
    <header class="top">
      <div class="brand">
        <img class="avatar" src="https://github.com/chiragbheemaiah.png" alt="Chirag avatar"/>
        <div>
          <div class="title">Chirag Bheemaiah PK</div>
          <div class="muted">Software Engineer · Distributed Systems · ML</div>
        </div>
      </div>
      <nav>
        <a href="https://github.com/chiragbheemaiah" target="_blank" rel="noreferrer" aria-label="GitHub">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 .5C5.65.5.5 5.65.5 12c0 5.1 3.3 9.4 7.9 10.9.6.1.8-.3.8-.6v-2c-3.2.7-3.9-1.5-3.9-1.5-.5-1.1-1.1-1.4-1.1-1.4-.9-.6.1-.6.1-.6 1 .1 1.6 1 1.6 1 .9 1.6 2.4 1.1 3 .8.1-.6.3-1.1.6-1.3-2.5-.3-5.1-1.3-5.1-5.9 0-1.3.5-2.3 1.1-3.2-.1-.3-.5-1.5.1-3.2 0 0 .9-.3 3.3 1.1a11.3 11.3 0 016 0c2.4-1.4 3.3-1.1 3.3-1.1.6 1.7.2 2.9.1 3.2.7.9 1.1 2 1.1 3.2 0 4.6-2.6 5.6-5.1 5.9.4.3.7.9.7 1.9v2.8c0 .3.2.7.8.6 4.6-1.5 7.9-5.9 7.9-10.9C23.5 5.65 18.35.5 12 .5z"/></svg>
        </a>
        <a href="https://www.linkedin.com/in/chirag-bheemaiah/" target="_blank" rel="noreferrer" aria-label="LinkedIn">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M4.98 3.5a2.5 2.5 0 11-.01 5.01 2.5 2.5 0 01.01-5.01zM3 9h4v12H3zM9 9h3.7v1.6h.1c.5-.9 1.6-1.9 3.3-1.9 3.5 0 4.2 2.3 4.2 5.2V21h-4v-5.4c0-1.3 0-3-1.8-3s-2 1.4-2 2.9V21H9z"/></svg>
        </a>
        <a href="mailto:chirag.bheemaiah@gmail.com" aria-label="Email">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 13L.01 6.76v10.5C.01 19.55 1.46 21 3.26 21h17.48c1.8 0 3.25-1.45 3.25-3.25V6.76L12 13z"/><path d="M12 11L.01 4.5h23.98L12 11z"/></svg>
        </a>
        <a href="Chirag_Bheemaiah_CV.pdf" target="_blank" rel="noreferrer" aria-label="Resume">
          <!-- new document icon with text lines -->
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M14 2H6a2 2 0 00-2 2v16c0 1.1.9 2 2 2h12a2 2 0 002-2V8l-4-4h-4z"/><path d="M14 2v6h6"/><path d="M8 11h8M8 15h8M8 19h5"/></svg>
        </a>
      </nav>
    </header>

    <button id="theme" class="toggle" aria-label="Toggle color theme">
      <svg id="theme-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M21.64 13.65A9 9 0 1110.35 2.36a7 7 0 1011.29 11.29z"/></svg>
    </button>

    <section>
      <h1>Building reliable and scalable systems.</h1>
      <p class="lead">Performance, simplicity, and innovation in distributed systems, cloud infrastructure, and ML-powered tooling.</p>
    </section>

    <hr/>

    <section class="section">
      <h2>Experience</h2>
      <ul>
        <li><strong>FinSurge — SWE Intern</strong><br/>Built OCR pipeline (Flask API + React UI) containerized with Docker and deployed on AWS. Automated pipelines with CI/CD.</li>
      </ul>
    </section>

    <section class="section">
      <h2>Education</h2>
      <ul>
        <li><strong>Master of Computer Science</strong> — North Carolina State University <span class="muted">· GPA: 4.0/4.0</span></li>
        <li><strong>Bachelor of Information Technology</strong> — SSN College of Engineering, Anna University <span class="muted">· GPA: 9.16/10</span></li>
      </ul>
    </section>

    <section class="section">
      <h2>Certifications</h2>
      <ul>
        <li><strong>AWS Certified Cloud Practitioner</strong></li>
      </ul>
    </section>

    <section class="section">
      <h2>Key Skills</h2>
      <ul>
        <li><strong>Languages:</strong> Go, Python, C++, C, TypeScript, JavaScript, SQL</li>
        <li><strong>Distributed & Systems:</strong> Linux, Networking/Sockets, gRPC, Multithreading, Kubernetes, Kafka, system‑call tracing, fault tolerance</li>
        <li><strong>ML / AI:</strong> PyTorch, TensorFlow, scikit‑learn, ONNX Runtime, Apache TVM, YOLOv8, ByteTrack, EfficientNet, LPRNet, QLoRA, RLHF, quantization (PTQ), 2:4 pruning, JIT, vectorization/tiling</li>
        <li><strong>RAG & Code Models:</strong> CodeBERT, CodeT5, CodeLlama, LlamaIndex, LangChain, Pinecone</li>
        <li><strong>Cloud & DevOps:</strong> AWS (EC2), GCP, Docker, GitHub Actions, Terraform, CI/CD, ROS, Gazebo (headless)</li>
        <li><strong>Web/Backend:</strong> Flask, NodeJS, Express, React</li>
        <li><strong>Databases & Storage:</strong> MySQL, MongoDB</li>
        <li><strong>Testing & Tooling:</strong> PyTest, Git/GitHub</li>
      </ul>
    </section>

    <section class="section">
      <h2>Featured Projects</h2>
      <ul class="projects">
        <li>
          <a class="repo-title" href="https://github.com/chiragbheemaiah/unit-test-generation" target="_blank" rel="noreferrer">AI-Powered Automated Test Case Generation — Large Language Models</a>
          <div class="repo-desc">Automated test-suite generator using CodeBERT/CodeT5/CodeLlama with RAG (Pinecone, LlamaIndex) and RLHF.</div>
        </li>
        <li>
          <a class="repo-title" href="https://github.com/chiragbheemaiah/LPRNet_CSC591" target="_blank" rel="noreferrer">Optimized License Plate Recognition (LPR) System — ML Compiler Optimization</a>
          <div class="repo-desc">78% model compression via PTQ, 2:4 pruning, JIT, and ML-compiler optimizations; 2.2× faster inference on ONNX Runtime.</div>
        </li>
        <li>
          <a class="repo-title" href="https://github.com/chiragbheemaiah/Distributed-Threat-Detection-System" target="_blank" rel="noreferrer">Distributed Security Threat Detection System — Distributed Systems</a>
          <div class="repo-desc">Scalable, fault‑tolerant real‑time security monitoring across Kubernetes nodes; Kafka‑based event streaming and quarantine.</div>
        </li>
        <li>
          <a class="repo-title" href="https://github.com/chiragbheemaiah/Integrating-Headless-Gazebo-into-GitHub-Actions" target="_blank" rel="noreferrer">CI/CD Pipeline for Autonomous Robotic Systems using GitHub Actions — DevOps</a>
          <div class="repo-desc">Headless Gazebo simulations integrated into GitHub Actions; custom Docker images and multi‑stage workflows with tests.</div>
        </li>
        <li>
          <a class="repo-title" href="https://github.com/chiragbheemaiah/PigTracking" target="_blank" rel="noreferrer">Livestock Behavior Classification — Research Project</a>
          <div class="repo-desc">YOLOv8 + ByteTrack + EfficientNet pipeline to classify feeding, lying, and moving behaviors in video; evaluation tooling.</div>
        </li>
        <li>
          <span class="repo-title">Maverick Ticketing System — Full‑Stack Development</span>
          <div class="repo-desc">React + Express + NodeJS + MySQL web app with Docker/Kubernetes orchestration and comprehensive test coverage.</div>
        </li>
      </ul>
    </section>

    <footer>
      © <span id="year"></span> Chirag Bheemaiah PK · Built for GitHub Pages
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();

    const root = document.documentElement;
    const toggle = document.getElementById('theme');
    const metaTheme = document.getElementById('theme-color');
    const themeIcon = document.getElementById('theme-icon');
    const saved = localStorage.getItem('theme');
    if(saved === 'light') {
      root.classList.add('light');
      metaTheme.setAttribute('content', '#ffffff');
      themeIcon.innerHTML='<path d="M6.76 4.84l-1.8-1.79-1.42 1.41 1.79 1.8 1.43-1.42zm10.45-1.79l-1.79 1.79 1.42 1.42 1.8-1.79-1.43-1.42zM12 4a8 8 0 100 16 8 8 0 000-16zm0-2a10 10 0 110 20 10 10 0 010-20z"/>';
    }

    toggle.addEventListener('click', () => {
      const isLight = root.classList.toggle('light');
      localStorage.setItem('theme', isLight ? 'light' : 'dark');
      metaTheme.setAttribute('content', isLight ? '#ffffff' : '#0a0a0a');
      if(isLight){
        themeIcon.innerHTML='<path d="M6.76 4.84l-1.8-1.79-1.42 1.41 1.79 1.8 1.43-1.42zm10.45-1.79l-1.79 1.79 1.42 1.42 1.8-1.79-1.43-1.42zM12 4a8 8 0 100 16 8 8 0 000-16zm0-2a10 10 0 110 20 10 10 0 010-20z"/>';
      } else {
        themeIcon.innerHTML='<path d="M21.64 13.65A9 9 0 1110.35 2.36a7 7 0 1011.29 11.29z"/>';
      }
    });
  </script>

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Chirag Bheemaiah PK",
    "url": "https://chiragbheemaiah.github.io/",
    "sameAs": ["https://github.com/chiragbheemaiah", "https://www.linkedin.com/in/chirag-bheemaiah/"],
    "jobTitle": "Software Engineer",
    "knowsAbout": ["Distributed systems","Machine Learning","Kubernetes","Golang"]
  }
  </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Chirag Bheemaiah PK — Portfolio</title>
  <meta name="description" content="Chirag Bheemaiah PK — Software Engineer (Distributed Systems, ML)">
  <meta id="theme-color" name="theme-color" content="#0a0a0a" />
  <link rel="icon" href="https://github.githubassets.com/favicons/favicon.png" />
  <style>
    :root{
      --bg:#0a0a0a;
      --fg:#f1f5f9;
      --muted:#9ca3af;
      --line:#27272a;
      --accent:#c2410c; /* darker orange */
      --topbg:#111111;
      --max:880px;
      --pad:40px;
      --lh:1.65;
      --h: clamp(1.9rem, 2.4vw + 1rem, 2.6rem);
    }
    .light{ --bg:#ffffff; --fg:#111827; --muted:#475569; --line:#e2e8f0; --accent:#ea580c; --topbg:#f3f4f6 }

    body{margin:0;background:var(--bg);color:var(--fg);font:17px/var(--lh) Inter, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial}
    a{color:var(--accent);text-decoration:none;font-weight:500}
    a:hover{opacity:0.85}
    .wrap{max-width:var(--max);margin:auto;padding:var(--pad) 22px}

    header{display:flex;align-items:center;justify-content:space-between;gap:16px;margin-bottom:24px}
    header.top{background:var(--topbg); border:1px solid var(--line); padding:12px 16px; border-radius:12px; position:relative}
    .brand{display:flex;align-items:center;gap:14px}
    .avatar{width:60px;height:60px;border-radius:50%;border:2px solid var(--accent)}
    .title{font-weight:800;font-size:1.3rem;color:var(--fg)}
    .muted{color:var(--fg)}
    nav{display:flex;gap:18px;flex-wrap:wrap;align-items:center}
    nav a svg{width:20px;height:20px;fill:var(--accent)}

    .toggle{background:none;border:none;cursor:pointer;font-size:1rem;position:fixed;bottom:20px;right:20px;z-index:1000;background:var(--topbg);padding:10px;border-radius:50%;box-shadow:0 2px 6px rgba(0,0,0,0.5)}
    .toggle svg{width:22px;height:22px;fill:var(--accent)}

    h1{font-size:var(--h);line-height:1.2;margin:0 0 10px;color:var(--fg)}
    h2{margin:26px 0 10px;font-size:1.02rem;text-transform:uppercase;letter-spacing:.1em;color:var(--accent)}
    .lead{color:var(--muted)}
    hr{border:none;border-top:1px solid var(--line);margin:26px 0}

    ul{list-style:none;padding:0;margin:0;display:grid;gap:12px}
    li{margin:0}

    .projects li{padding:12px 0 12px 14px;border-bottom:1px solid var(--line);position:relative}
    .projects li:last-child{border-bottom:none}
    .projects li::before{content:"";position:absolute;left:0;top:12px;bottom:12px;width:3px;background:var(--accent)}
    .repo-title{font-weight:700;font-size:1.06rem;color:var(--accent)}
    .repo-desc{font-size:.95rem;color:var(--muted)}

    footer{margin-top:36px;font-size:.9rem;color:var(--muted);text-align:center}
  </style>
</head>
<body>
  <div class="wrap">
    <header class="top">
      <div class="brand">
        <img class="avatar" src="https://github.com/chiragbheemaiah.png" alt="Chirag avatar"/>
        <div>
          <div class="title">Chirag Bheemaiah PK</div>
          <div class="muted">Software Engineer · Distributed Systems · ML</div>
        </div>
      </div>
      <nav>
        <a href="https://github.com/chiragbheemaiah" target="_blank" rel="noreferrer" aria-label="GitHub">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 .5C5.65.5.5 5.65.5 12c0 5.1 3.3 9.4 7.9 10.9.6.1.8-.3.8-.6v-2c-3.2.7-3.9-1.5-3.9-1.5-.5-1.1-1.1-1.4-1.1-1.4-.9-.6.1-.6.1-.6 1 .1 1.6 1 1.6 1 .9 1.6 2.4 1.1 3 .8.1-.6.3-1.1.6-1.3-2.5-.3-5.1-1.3-5.1-5.9 0-1.3.5-2.3 1.1-3.2-.1-.3-.5-1.5.1-3.2 0 0 .9-.3 3.3 1.1a11.3 11.3 0 016 0c2.4-1.4 3.3-1.1 3.3-1.1.6 1.7.2 2.9.1 3.2.7.9 1.1 2 1.1 3.2 0 4.6-2.6 5.6-5.1 5.9.4.3.7.9.7 1.9v2.8c0 .3.2.7.8.6 4.6-1.5 7.9-5.9 7.9-10.9C23.5 5.65 18.35.5 12 .5z"/></svg>
        </a>
        <a href="https://www.linkedin.com/in/chirag-bheemaiah/" target="_blank" rel="noreferrer" aria-label="LinkedIn">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M4.98 3.5a2.5 2.5 0 11-.01 5.01 2.5 2.5 0 01.01-5.01zM3 9h4v12H3zM9 9h3.7v1.6h.1c.5-.9 1.6-1.9 3.3-1.9 3.5 0 4.2 2.3 4.2 5.2V21h-4v-5.4c0-1.3 0-3-1.8-3s-2 1.4-2 2.9V21H9z"/></svg>
        </a>
        <a href="mailto:chirag.bheemaiah@gmail.com" aria-label="Email">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 13L.01 6.76v10.5C.01 19.55 1.46 21 3.26 21h17.48c1.8 0 3.25-1.45 3.25-3.25V6.76L12 13z"/><path d="M12 11L.01 4.5h23.98L12 11z"/></svg>
        </a>
        <a href="Chirag_Bheemaiah_CV.pdf" target="_blank" rel="noreferrer" aria-label="Resume">
          <!-- new document icon with text lines -->
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M14 2H6a2 2 0 00-2 2v16c0 1.1.9 2 2 2h12a2 2 0 002-2V8l-4-4h-4z"/><path d="M14 2v6h6"/><path d="M8 11h8M8 15h8M8 19h5"/></svg>
        </a>
      </nav>
    </header>

    <button id="theme" class="toggle" aria-label="Toggle color theme">
      <svg id="theme-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M21.64 13.65A9 9 0 1110.35 2.36a7 7 0 1011.29 11.29z"/></svg>
    </button>

    <section>
      <h1>Building reliable and scalable systems.</h1>
      <p class="lead">Performance, simplicity, and innovation in distributed systems, cloud infrastructure, and ML-powered tooling.</p>
    </section>

    <hr/>

    <section class="section">
      <h2>Experience</h2>
      <ul>
        <li><strong>FinSurge — SWE Intern</strong><br/>Built OCR pipeline (Flask API + React UI) containerized with Docker and deployed on AWS. Automated pipelines with CI/CD.</li>
      </ul>
    </section>

    <section class="section">
      <h2>Education</h2>
      <ul>
        <li><strong>Master of Computer Science</strong> — North Carolina State University <span class="muted">· GPA: 4.0/4.0</span></li>
        <li><strong>Bachelor of Information Technology</strong> — SSN College of Engineering, Anna University <span class="muted">· GPA: 9.16/10</span></li>
      </ul>
    </section>

    <section class="section">
      <h2>Certifications</h2>
      <ul>
        <li><strong>AWS Certified Cloud Practitioner</strong></li>
      </ul>
    </section>

    <section class="section">
      <h2>Key Skills</h2>
      <ul>
        <li><strong>Languages:</strong> Go, Python, C++, C, TypeScript, JavaScript, SQL</li>
        <li><strong>Distributed & Systems:</strong> Linux, Networking/Sockets, gRPC, Multithreading, Kubernetes, Kafka, system‑call tracing, fault tolerance</li>
        <li><strong>ML / AI:</strong> PyTorch, TensorFlow, scikit‑learn, ONNX Runtime, Apache TVM, YOLOv8, ByteTrack, EfficientNet, LPRNet, QLoRA, RLHF, quantization (PTQ), 2:4 pruning, JIT, vectorization/tiling</li>
        <li><strong>RAG & Code Models:</strong> CodeBERT, CodeT5, CodeLlama, LlamaIndex, LangChain, Pinecone</li>
        <li><strong>Cloud & DevOps:</strong> AWS (EC2), GCP, Docker, GitHub Actions, Terraform, CI/CD, ROS, Gazebo (headless)</li>
        <li><strong>Web/Backend:</strong> Flask, NodeJS, Express, React</li>
        <li><strong>Databases & Storage:</strong> MySQL, MongoDB</li>
        <li><strong>Testing & Tooling:</strong> PyTest, Git/GitHub</li>
      </ul>
    </section>

    <section class="section">
      <h2>Featured Projects</h2>
      <ul class="projects">
        <li>
          <a class="repo-title" href="https://github.com/chiragbheemaiah/unit-test-generation" target="_blank" rel="noreferrer">AI-Powered Automated Test Case Generation — Large Language Models</a>
          <div class="repo-desc">Automated test-suite generator using CodeBERT/CodeT5/CodeLlama with RAG (Pinecone, LlamaIndex) and RLHF.</div>
        </li>
        <li>
          <a class="repo-title" href="https://github.com/chiragbheemaiah/LPRNet_CSC591" target="_blank" rel="noreferrer">Optimized License Plate Recognition (LPR) System — ML Compiler Optimization</a>
          <div class="repo-desc">78% model compression via PTQ, 2:4 pruning, JIT, and ML-compiler optimizations; 2.2× faster inference on ONNX Runtime.</div>
        </li>
        <li>
          <a class="repo-title" href="https://github.com/chiragbheemaiah/Distributed-Threat-Detection-System" target="_blank" rel="noreferrer">Distributed Security Threat Detection System — Distributed Systems</a>
          <div class="repo-desc">Scalable, fault‑tolerant real‑time security monitoring across Kubernetes nodes; Kafka‑based event streaming and quarantine.</div>
        </li>
        <li>
          <a class="repo-title" href="https://github.com/chiragbheemaiah/Integrating-Headless-Gazebo-into-GitHub-Actions" target="_blank" rel="noreferrer">CI/CD Pipeline for Autonomous Robotic Systems using GitHub Actions — DevOps</a>
          <div class="repo-desc">Headless Gazebo simulations integrated into GitHub Actions; custom Docker images and multi‑stage workflows with tests.</div>
        </li>
        <li>
          <a class="repo-title" href="https://github.com/chiragbheemaiah/PigTracking" target="_blank" rel="noreferrer">Livestock Behavior Classification — Research Project</a>
          <div class="repo-desc">YOLOv8 + ByteTrack + EfficientNet pipeline to classify feeding, lying, and moving behaviors in video; evaluation tooling.</div>
        </li>
        <li>
          <span class="repo-title">Maverick Ticketing System — Full‑Stack Development</span>
          <div class="repo-desc">React + Express + NodeJS + MySQL web app with Docker/Kubernetes orchestration and comprehensive test coverage.</div>
        </li>
      </ul>
    </section>

    <footer>
      © <span id="year"></span> Chirag Bheemaiah PK · Built for GitHub Pages
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();

    const root = document.documentElement;
    const toggle = document.getElementById('theme');
    const metaTheme = document.getElementById('theme-color');
    const themeIcon = document.getElementById('theme-icon');
    const saved = localStorage.getItem('theme');
    if(saved === 'light') {
      root.classList.add('light');
      metaTheme.setAttribute('content', '#ffffff');
      themeIcon.innerHTML='<path d="M6.76 4.84l-1.8-1.79-1.42 1.41 1.79 1.8 1.43-1.42zm10.45-1.79l-1.79 1.79 1.42 1.42 1.8-1.79-1.43-1.42zM12 4a8 8 0 100 16 8 8 0 000-16zm0-2a10 10 0 110 20 10 10 0 010-20z"/>';
    }

    toggle.addEventListener('click', () => {
      const isLight = root.classList.toggle('light');
      localStorage.setItem('theme', isLight ? 'light' : 'dark');
      metaTheme.setAttribute('content', isLight ? '#ffffff' : '#0a0a0a');
      if(isLight){
        themeIcon.innerHTML='<path d="M6.76 4.84l-1.8-1.79-1.42 1.41 1.79 1.8 1.43-1.42zm10.45-1.79l-1.79 1.79 1.42 1.42 1.8-1.79-1.43-1.42zM12 4a8 8 0 100 16 8 8 0 000-16zm0-2a10 10 0 110 20 10 10 0 010-20z"/>';
      } else {
        themeIcon.innerHTML='<path d="M21.64 13.65A9 9 0 1110.35 2.36a7 7 0 1011.29 11.29z"/>';
      }
    });
  </script>

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Chirag Bheemaiah PK",
    "url": "https://chiragbheemaiah.github.io/",
    "sameAs": ["https://github.com/chiragbheemaiah", "https://www.linkedin.com/in/chirag-bheemaiah/"],
    "jobTitle": "Software Engineer",
    "knowsAbout": ["Distributed systems","Machine Learning","Kubernetes","Golang"]
  }
  </script>
</body>
</html>
