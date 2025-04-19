<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vahid Faraji-Jobehdar | Data Science Researcher</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --text-primary: #37352f;
      --text-secondary: #6b7280;
      --bg-primary: #ffffff;
      --bg-secondary: #f5f5f5;
      --accent: #2563eb;
      --border: #e5e5e5;
      --spacing-sm: 0.5rem;
      --spacing-md: 1rem;
      --spacing-lg: 2rem;
      --spacing-xl: 3rem;
    }
    
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Inter', sans-serif;
      background-color: var(--bg-primary);
      color: var(--text-primary);
      line-height: 1.7;
      max-width: 860px;
      margin: 0 auto;
      padding: var(--spacing-lg);
    }
    
    .container {
      width: 100%;
    }
    
    h1 {
      font-weight: 600;
      font-size: 2.5rem;
      margin-bottom: var(--spacing-lg);
      color: var(--text-primary);
    }
    
    h2 {
      font-weight: 500;
      font-size: 1.5rem;
      margin: var(--spacing-lg) 0 var(--spacing-md);
      display: flex;
      align-items: center;
      gap: var(--spacing-sm);
      color: var(--text-primary);
    }
    
    p {
      margin-bottom: var(--spacing-md);
      color: var(--text-secondary);
    }
    
    .header {
      margin-bottom: var(--spacing-xl);
    }
    
    .role {
      font-size: 1.2rem;
      color: var(--text-secondary);
      margin-bottom: var(--spacing-lg);
    }
    
    .section {
      margin-bottom: var(--spacing-xl);
      border-bottom: 1px solid var(--border);
      padding-bottom: var(--spacing-lg);
    }
    
    .section:last-child {
      border-bottom: none;
    }
    
    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: var(--spacing-sm);
      margin: var(--spacing-md) 0;
    }
    
    .tag {
      background-color: var(--bg-secondary);
      padding: 0.3rem 0.8rem;
      border-radius: 4px;
      font-size: 0.85rem;
      font-weight: 500;
    }
    
    .project {
      margin-bottom: var(--spacing-md);
      padding: var(--spacing-md);
      border-radius: 4px;
      border: 1px solid var(--border);
    }
    
    .project-title {
      font-weight: 500;
      font-size: 1.1rem;
      margin-bottom: var(--spacing-sm);
    }
    
    .project-desc {
      font-size: 0.95rem;
      color: var(--text-secondary);
    }
    
    .links {
      display: flex;
      gap: var(--spacing-md);
      margin-top: var(--spacing-lg);
    }
    
    .link {
      display: flex;
      align-items: center;
      gap: var(--spacing-sm);
      color: var(--accent);
      text-decoration: none;
      font-size: 0.95rem;
      padding: var(--spacing-sm) var(--spacing-md);
      border-radius: 4px;
      border: 1px solid var(--border);
      transition: all 0.2s ease;
    }
    
    .link:hover {
      background-color: var(--bg-secondary);
    }
    
    .tech-stack {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
      gap: var(--spacing-md);
      margin-top: var(--spacing-md);
    }
    
    .tech-item {
      display: flex;
      align-items: center;
      gap: var(--spacing-sm);
      padding: var(--spacing-sm);
      border-radius: 4px;
      font-size: 0.9rem;
    }
    
    .focus-list {
      list-style-type: none;
    }
    
    .focus-item {
      margin-bottom: var(--spacing-sm);
      display: flex;
      align-items: center;
      gap: var(--spacing-sm);
    }
    
    .icon {
      width: 18px;
      display: inline-flex;
      justify-content: center;
    }
    
    .profile-highlight {
      background-color: #f8f9ff;
      border-left: 3px solid var(--accent);
      padding: var(--spacing-md);
      margin: var(--spacing-md) 0;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>Vahid Faraji-Jobehdar</h1>
      <div class="role">Data Science Researcher | Data Product Architect</div>
      <div class="profile-highlight">
        Turn messy data into powerful products. Design internal agentic tools that elevate teams. Operate at the intersection of <strong>Data × AI × Product Thinking</strong>.
      </div>
    </div>

    <div class="section">
      <h2><i class="fas fa-bullseye"></i> Research Focus</h2>
      <ul class="focus-list">
        <li class="focus-item"><i class="fas fa-database icon"></i> Data Product Architecture & Governance</li>
        <li class="focus-item"><i class="fas fa-robot icon"></i> Agentic Systems for Internal Automation</li>
        <li class="focus-item"><i class="fas fa-users icon"></i> People and Company Data Enrichment</li>
        <li class="focus-item"><i class="fas fa-brain icon"></i> LLM-Enhanced Data Solutions</li>
        <li class="focus-item"><i class="fas fa-plug icon"></i> Agno, Replit, MCP Protocol Integration</li>
      </ul>
    </div>

    <div class="section">
      <h2><i class="fas fa-flask"></i> Research Projects</h2>
      
      <div class="project">
        <div class="project-title">Skill Extraction via LLMs</div>
        <div class="project-desc">Research project with academic paper leveraging Large Language Models for skill extraction and classification from Turkish language datasets.</div>
        <div class="tags">
          <span class="tag">NLP</span>
          <span class="tag">LLMs</span>
          <span class="tag">Skill Taxonomy</span>
        </div>
      </div>
      
      <div class="project">
        <div class="project-title">Position Taxonomy Architecture</div>
        <div class="project-desc">LLM-based classification and taxonomy structuring for job positions, creating hierarchical organization of roles across industries.</div>
        <div class="tags">
          <span class="tag">Taxonomy</span>
          <span class="tag">Classification</span>
          <span class="tag">AI</span>
        </div>
      </div>
      
      <div class="project">
        <div class="project-title">Salary Analytics System</div>
        <div class="project-desc">Developed ETL pipelines and analytics framework for salary market benchmarking with statistical validation methods.</div>
        <div class="tags">
          <span class="tag">ETL</span>
          <span class="tag">Analytics</span>
          <span class="tag">Benchmarking</span>
        </div>
      </div>
    </div>

    <div class="section">
      <h2><i class="fas fa-tools"></i> Technical Expertise</h2>
      <div class="tech-stack">
        <div class="tech-item"><i class="fab fa-python"></i> Python</div>
        <div class="tech-item"><i class="fas fa-database"></i> SQL</div>
        <div class="tech-item"><i class="fas fa-link"></i> LangChain</div>
        <div class="tech-item"><i class="fas fa-project-diagram"></i> LangGraph</div>
        <div class="tech-item"><i class="fas fa-table"></i> Pandas</div>
        <div class="tech-item"><i class="fas fa-calculator"></i> NumPy</div>
        <div class="tech-item"><i class="fas fa-chart-bar"></i> Data Visualization</div>
        <div class="tech-item"><i class="fas fa-cogs"></i> ETL</div>
      </div>
    </div>

    <div class="section">
      <h2><i class="fas fa-graduation-cap"></i> Academic Background</h2>
      <p>My research focuses on the application of artificial intelligence and machine learning techniques to solve data engineering challenges, with particular emphasis on knowledge extraction and taxonomic classification.</p>
    </div>

    <div class="section">
      <h2><i class="fas fa-globe"></i> Connect</h2>
      <div class="links">
        <a href="https://www.linkedin.com/in/vahid-faraji-jobehdar" class="link"><i class="fab fa-linkedin"></i> LinkedIn</a>
        <a href="mailto:vfaraji89@gmail.com" class="link"><i class="fas fa-envelope"></i> Email</a>
        <a href="https://github.com/vfaraji89" class="link"><i class="fab fa-github"></i> GitHub</a>
        <a href="https://www.datacamp.com/profile/vfaraji89" class="link"><i class="fas fa-code"></i> DataCamp</a>
      </div>
    </div>
  </div>
</body>
</html>
