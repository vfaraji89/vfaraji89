<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vahid Faraji | About & Projects</title>
    <meta name="description" content="Detailed overview of Vahid Faraji's focus areas, projects, and technical skills in data products and agentic systems." />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=Oswald:wght@500;600&display=swap" rel="stylesheet">
    <style>
        :root {
            color-scheme: light;
            --background: #ffffff;
            --text-primary: #1d1b1b;
            --text-secondary: #6a5b5b;
            --accent: #d85454;
            --accent-soft: #f7d7d7;
            --border-color: #e5e7eb;
            --max-width: 900px; /* Adjusted for a content-focused page */
            --transition: 180ms ease;
            --border-radius: 8px;
        }

        *, *::before, *::after { box-sizing: border-box; }

        html { scroll-behavior: smooth; }

        body {
            margin: 0;
            font-family: 'DM Sans', sans-serif;
            background-color: var(--background);
            color: var(--text-primary);
            min-height: 100vh;
            line-height: 1.6;
        }

        a { color: var(--accent); text-decoration: none; font-weight: 500; }
        a:hover { text-decoration: underline; }

        .container {
            width: min(100%, var(--max-width));
            margin: 0 auto;
            padding: clamp(1.5rem, 5vw, 4rem) clamp(1rem, 4vw, 2rem);
        }

        section {
            margin-top: clamp(3rem, 6vw, 4rem);
        }

        .section-header {
            border-left: 3px solid var(--accent);
            padding-left: 1rem;
            margin-bottom: 1.5rem;
        }

        .section-header h2 {
            margin: 0;
            font-family: 'Oswald', sans-serif;
            font-size: clamp(1.6rem, 2.5vw, 2.1rem);
            letter-spacing: 0.1em;
            text-transform: uppercase;
            line-height: 1.2;
        }

        p {
            color: var(--text-secondary);
            font-size: 1.1rem;
        }

        .flowchart {
            text-align: center;
            font-family: 'Courier New', Courier, monospace;
            color: var(--text-secondary);
            margin: 1.5rem 0;
        }

        .flowchart code {
            background-color: var(--accent-soft);
            color: var(--accent);
            padding: 0.2rem 0.5rem;
            border-radius: 4px;
            font-weight: 600;
        }

        .focus-list {
            list-style: none;
            padding-left: 0;
            font-size: 1.1rem;
            color: var(--text-primary);
        }

        .focus-list li {
            position: relative;
            padding-left: 1.75rem;
            margin-bottom: 0.75rem;
        }

        .focus-list li::before {
            content: '→';
            position: absolute;
            left: 0;
            top: 0;
            color: var(--accent);
            font-weight: 700;
        }

        /* Responsive Table Styling */
        .projects-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 2rem;
            font-size: 1rem;
        }

        .projects-table th,
        .projects-table td {
            text-align: left;
            padding: 0.75rem 1rem;
            border-bottom: 1px solid var(--border-color);
        }

        .projects-table thead {
            border-bottom: 2px solid var(--text-primary);
        }

        .projects-table th {
            font-family: 'Oswald', sans-serif;
            letter-spacing: 0.1em;
            text-transform: uppercase;
            font-size: 0.9rem;
            color: var(--text-secondary);
        }

        .projects-table td strong {
            color: var(--text-primary);
        }

        .tag {
            display: inline-block;
            background-color: var(--accent-soft);
            color: var(--accent);
            padding: 0.25rem 0.6rem;
            border-radius: 99px;
            font-size: 0.8rem;
            font-weight: 600;
            margin: 0.25rem;
        }

        .badge-group {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 0.5rem;
            margin-top: 0.5rem;
        }

        blockquote {
            margin: 2rem 0;
            padding: 1rem 1.5rem;
            border-left: 4px solid var(--accent);
            background-color: #f9fafb;
            font-size: 1.15rem;
            font-style: italic;
            color: var(--text-secondary);
        }

        hr {
            border: 0;
            border-top: 1px solid var(--border-color);
            margin: 3rem 0;
        }

        footer {
            text-align: center;
            color: var(--text-secondary);
            font-style: italic;
        }

        /* Responsive Table for Mobile */
        @media (max-width: 768px) {
            .projects-table thead {
                display: none;
            }

            .projects-table tr {
                display: block;
                margin-bottom: 1.5rem;
                border: 1px solid var(--border-color);
                border-radius: var(--border-radius);
                padding: 1rem;
            }

            .projects-table td {
                display: block;
                text-align: right;
                padding-left: 50%; /* Make space for the label */
                position: relative;
                border-bottom: 0;
                padding-bottom: 0.75rem;
            }

            .projects-table td::before {
                content: attr(data-label);
                position: absolute;
                left: 1rem;
                width: calc(50% - 2rem);
                text-align: left;
                font-weight: 600;
                color: var(--text-primary);
                font-family: 'Oswald', sans-serif;
                text-transform: uppercase;
                font-size: 0.8rem;
                letter-spacing: 0.05em;
            }
        }
    </style>
</head>
<body>

    <main class="container">

        <section id="about">
            <div class="section-header">
                <h2>About</h2>
            </div>
            <p>I build and transform raw data into products with an agentic-approach.</p>
            <div class="flowchart">
              <code>Data</code> → <code>Knowledge</code> → <code>Intelligence</code> → <code>Value</code>
            </div>
        </section>

        <section id="focus">
            <div class="section-header">
                <h2>Focus Areas</h2>
            </div>
            <ul class="focus-list">
                <li>Data Product</li>
                <li>Agentic Systems</li>
                <li>LLM-Enhanced Data</li>
                <li>Retrieval & Extraction from Text Data</li>
            </ul>
        </section>

        <section id="projects">
            <div class="section-header">
                <h2>Research & Projects</h2>
            </div>
            <table class="projects-table">
                <thead>
                    <tr>
                        <th>Project Quest</th>
                        <th>Description</th>
                        <th>Tags</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td data-label="Project"><strong>Skill Extraction</strong></td>
                        <td data-label="Description">Academic research leveraging LLMs for extracting skills from Turkish language datasets.</td>
                        <td data-label="Tags"><code class="tag">NLP</code><code class="tag">LLMs</code></td>
                    </tr>
                    <tr>
                        <td data-label="Project"><strong>Position Taxonomy</strong></td>
                        <td data-label="Description">Creating hierarchical classification systems for job positions.</td>
                        <td data-label="Tags"><code class="tag">Taxonomy</code><code class="tag">AI</code></td>
                    </tr>
                    <tr>
                        <td data-label="Project"><strong>Salary Analytics</strong></td>
                        <td data-label="Description">ETL pipelines and statistical models for market benchmarking.</td>
                        <td data-label="Tags"><code class="tag">Analytics</code></td>
                    </tr>
                    <tr>
                        <td data-label="Project"><strong>Feedback Analysis Agent</strong></td>
                        <td data-label="Description">LLM-powered system for automated customer feedback categorization and sentiment analysis.</td>
                        <td data-label="Tags"><code class="tag">Agents</code><code class="tag">NLP</code></td>
                    </tr>
                    <tr>
                        <td data-label="Project"><strong>Sales Co-pilot</strong></td>
                        <td data-label="Description">Agent system providing real-time assistance for sales representatives with product recommendations.</td>
                        <td data-label="Tags"><code class="tag">Agents</code><code class="tag">Sales</code></td>
                    </tr>
                    <tr>
                        <td data-label="Project"><strong>Data Quality Framework</strong></td>
                        <td data-label="Description">Automated system for data quality assessment and discovery for product development.</td>
                        <td data-label="Tags"><code class="tag">Data Quality</code><code class="tag">ETL</code></td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section id="toolbox">
            <div class="section-header">
                <h2>Technical Toolbox</h2>
            </div>
            <div class="badge-group">
                <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
                <img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/>
                <img src="https://img.shields.io/badge/LangChain-008639?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
                <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
                <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
                <img src="https://img.shields.io/badge/Vector DBs-9333EA?style=for-the-badge" alt="Vector DBs"/>
            </div>
            <div class="badge-group">
                <img src="https://img.shields.io/badge/Agno-000000?style=for-the-badge" alt="Agno"/>
                <img src="https://img.shields.io/badge/Replit-DD1200?style=for-the-badge&logo=replit&logoColor=white" alt="Replit"/>
                <img src="https://img.shields.io/badge/Prompt Engineering-FF6F00?style=for-the-badge" alt="Prompt Engineering"/>
                <img src="https://img.shields.io/badge/Agent Frameworks-4B5563?style=for-the-badge" alt="Agent Frameworks"/>
            </div>
        </section>

        <section id="philosophy">
            <div class="section-header">
                <h2>My Philosophy</h2>
            </div>
            <blockquote>
                "The most valuable insights emerge when we approach data with both scientific rigor and creative curiosity. Effective products require precise instructions, continuous iterations, and hard work balanced with smart work—not just immersion in pure AI hype!"
            </blockquote>
            <div class="flowchart">
                <code>Clear Instructions</code> → <code>Contextual Understanding</code> → <code>Adaptive Reasoning</code> → <code>Useful Output</code>
            </div>
        </section>

        <section id="connect">
            <div class="section-header">
                <h2>Connect</h2>
            </div>
            <div class="badge-group">
                <a href="https://www.linkedin.com/in/vahid-faraji-jobehdar" target="_blank" rel="noopener noreferrer">
                    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
                </a>
                <a href="https://vfaraji89.github.io/" target="_blank" rel="noopener noreferrer">
                    <img src="https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=github&logoColor=white" alt="Web Portfolio"/>
                </a>
                <a href="mailto:vfaraji89@gmail.com">
                    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
                </a>
                <a href="https://www.datacamp.com/profile/vfaraji89" target="_blank" rel="noopener noreferrer">
                    <img src="https://img.shields.io/badge/DataCamp-03EF62?style=for-the-badge&logo=datacamp&logoColor=white" alt="DataCamp"/>
                </a>
                <a href="https://huggingface.co/vfaraji89" target="_blank" rel="noopener noreferrer">
                    <img src="https://img.shields.io/badge/Hugging Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
                </a>
            </div>
        </section>
        
        <hr>
        
        <footer>
            <p>Building data products for the AI era</p>
        </footer>

    </main>

</body>
</html>
