AI Automation Engineer — 10-Project Companion Package
A complete hands-on companion package for AI Automation Engineer — Learn, Build, Portfolio Edition.

This repository contains the implementation assets for 10 practical AI automation projects designed to help learners move from concepts to working applications and portfolio-ready demonstrations.

🚀 What You'll Build
The package includes ten complete project workspaces covering data analysis, customer support, HR workflows, inventory, sales, auditing, document processing, email automation, reporting, and business intelligence.

01 — AI Data Analyst Assistant
Analyze CSV data, generate business insights, create charts, and produce executive-ready summaries.

Technologies: Python, Pandas, FastAPI, Streamlit, SQL, n8n

02 — AI Customer Support Bot
Build a controlled AI support assistant that answers knowledge-base questions and escalates requests when human intervention is required.

Technologies: Python, FastAPI, SQL, n8n, LLM API

03 — AI HR Recruitment Assistant
Extract skills from CVs, compare candidates with job requirements, and prepare human-reviewed recruitment workflows.

Technologies: Python, PDF parsing, SQL, n8n, LLM API

04 — AI Inventory Management System
Monitor inventory levels and generate data-driven reorder recommendations.

Technologies: Python, Pandas, FastAPI, SQL, n8n

05 — AI Sales Dashboard Generator
Calculate sales KPIs, generate dashboards, visualize performance, and create management commentary.

Technologies: Python, Pandas, Plotly, Streamlit, SQL, LLM API

06 — AI Restaurant Audit Assistant
Capture inspection results, identify compliance risks, and generate corrective-action reports.

Technologies: Python, FastAPI, SQL, OCR-ready workflows, n8n

07 — AI Document Processing System
Extract structured information from documents, validate the results, and route records through approval workflows.

Technologies: Python, FastAPI, OCR/LLM APIs, SQL, n8n

08 — AI Email Automation Platform
Classify incoming emails, draft responses, create tasks, and escalate high-priority messages.

Technologies: Python, IMAP/SMTP, FastAPI, SQL, n8n, LLM API

09 — AI Report Generator
Transform business data into professional reports containing KPIs, tables, charts, and PDF/DOCX exports.

Technologies: Python, Pandas, ReportLab, python-docx, LLM API

10 — AI Business Intelligence Assistant
Allow users to ask natural-language questions about governed business data through controlled, read-only SQL workflows.

Technologies: Python, FastAPI, SQL, PostgreSQL/SQLite, LLM API, n8n

📦 Repository Structure
Each project follows a consistent professional structure:

01_ai_data_analyst_assistant/
├── README.md
├── data/
│   └── sample.csv
├── app/
│   ├── __init__.py
│   └── main.py
├── sql/
│   ├── schema.sql
│   └── seed.sql
├── n8n/
│   └── workflow.json
├── docs/
│   ├── architecture.md
│   ├── api.md
│   ├── deployment.md
│   └── troubleshooting.md
├── tests/
│   └── test_api.py
├── portfolio/
│   └── case-study.md
├── .env.example
├── requirements.txt
└── Dockerfile
The same structure is used across the companion projects, with project-specific application code and documentation.

🛠️ Installation
1. Clone the repository
git clone https://github.com/JuwadNath/AI-Automation-Engineer-10-Project-Companion.git
cd AI-Automation-Engineer-10-Project-Companion
Replace YOUR-USERNAME with your GitHub username.

2. Open a project
For example:

cd 01_ai_data_analyst_assistant
3. Create a virtual environment
python -m venv .venv
4. Activate the environment
Windows:

.venv\Scripts\activate
macOS/Linux:

source .venv/bin/activate
5. Install dependencies
pip install -r requirements.txt
6. Configure environment variables
Copy the example configuration:

cp .env.example .env
On Windows, you can manually copy .env.example to .env.

Add the required API keys, database settings, and other configuration values described in the project's README.

7. Start the API
For FastAPI projects:

uvicorn app.main:app --reload
Then open:

http://127.0.0.1:8000
🔄 n8n Workflows
Each project includes an exported n8n workflow inside:

n8n/workflow.json
The workflows are designed as implementation starters and can be imported into n8n and adapted to your own environment.

Before using them in production, configure:

API endpoints
Authentication
Credentials
Environment variables
Database connections
Error handling
Rate limits
Monitoring
🗄️ SQL Database
Projects that use relational data include:

sql/schema.sql
sql/seed.sql
schema.sql creates the required database structures.

seed.sql provides sample records for testing and demonstrations.

The projects can be adapted for databases such as SQLite or PostgreSQL depending on the implementation.

🧪 Testing
Each project includes a starter test suite:

tests/test_api.py
Run tests with:

pytest
Use these tests as a foundation for expanding coverage as the application develops.

📚 Documentation
Every project includes documentation covering:

Architecture — system components and data flow
API — endpoints and request/response examples
Deployment — deployment and production considerations
Troubleshooting — common problems and solutions
These documents are intended to help turn the projects into demonstrable portfolio pieces rather than simple code exercises.

💼 Portfolio Development
Each project includes:

portfolio/case-study.md
The case study helps you present the project professionally by documenting:

Business problem
Proposed solution
Technology stack
Architecture
Automation workflow
Implementation
Testing
Security considerations
Deployment
Business impact metrics
You can adapt the case studies for your GitHub portfolio, personal website, CV, LinkedIn profile, or client proposals.

🔐 Security & Production Considerations
The projects are educational implementation starters and should be hardened before production deployment.

Consider implementing:

HTTPS
Authentication and authorization
Secure secret management
Input validation
Rate limiting
Database security
Logging and monitoring
Backups
Error handling
Idempotency
Access controls
Audit trails
Human review for high-impact decisions
Never commit real API keys, passwords, database credentials, or other secrets to GitHub.

Use .env for local configuration and keep sensitive values out of source control.

🎯 Who This Package Is For
This companion package is designed for:

Aspiring AI automation engineers
Python developers
Automation professionals
Data analysts
Backend developers
Business analysts
Freelancers
Consultants
Technical students
Developers building AI portfolios
It is particularly useful for learners who want to move beyond tutorials and demonstrate practical AI automation systems.

📖 Companion Book
This repository accompanies:

AI Automation Engineer — Learn, Build, Portfolio Edition

The book provides the learning framework, while this repository provides practical implementation assets that can be studied, modified, tested, and extended.

⚠️ Important Note
The projects are provided as educational and portfolio-building resources. Before deploying any project in a real business environment, review the implementation, security controls, data protection requirements, authentication, monitoring, and infrastructure configuration for your specific use case.

AI systems used in high-impact areas should include appropriate human oversight and organizational controls.

⭐ Getting Started
Start with:

01_ai_data_analyst_assistant
Read its README.md, install the dependencies, run the API, inspect the SQL and n8n workflow, execute the tests, and review the portfolio case study.

Then progress through the remaining projects to build a complete collection of AI automation implementations.

Build it. Run it. Test it. Document it. Put it in your portfolio.
