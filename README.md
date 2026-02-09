# 🚀 AI-Powered LinkedIn Resume Automation System

An end-to-end 🤖 AI-driven system that automatically scrapes live LinkedIn job postings using Apify, evaluates and ranks them through a custom relevance engine, and dynamically rewrites a professional XeLaTeX resume using Gemini AI for each job description. The system produces 📄 ATS-optimized, Overleaf-ready resumes based on real market data.

------------------------------------------------------------

🔍 HIGH-LEVEL OVERVIEW

This project automates resume customization by combining real-time job data, intelligent job filtering, and controlled generative AI. Instead of manually editing resumes for each application, the system generates job-specific resumes at scale while preserving factual accuracy.

------------------------------------------------------------

🏗️ ARCHITECTURE

LinkedIn Jobs (Apify) 
   ➜ Job Scraping and Metadata Extraction 
   ➜ Skill and Experience Relevance Engine 
   ➜ Gemini AI Resume Transformation 
   ➜ XeLaTeX Resume Output (Overleaf-Ready)

------------------------------------------------------------

✨ KEY FEATURES

📡 LIVE LINKEDIN JOB SCRAPING
- Fetches real-time job postings using Apify
- Collects job title, company name, job description, and job link
- Ensures resume customization uses real market data

🧠 INTELLIGENT JOB RANKING
- Weighted skill-based matching (Java, Spring Boot, Microservices, REST APIs)
- Backend-role signal detection
- Experience extraction using regex and NLP patterns
- Senior-role penalty and optional-skill normalization
- Filters only high-relevance, realistic job roles

🤖 AI-POWERED RESUME CUSTOMIZATION
- Integrates Gemini API by embedding the API key in the script
- Accepts a base XeLaTeX resume template
- Rewrites resume content based on job descriptions
- Does not invent skills or experience
- Returns strictly valid XeLaTeX code

📄 PROFESSIONAL RESUME GENERATION
- Uses a custom XeLaTeX resume template
- Generates one resume per job posting
- Stores job link, job title, and company metadata
- Output is Overleaf-ready and ATS-friendly

------------------------------------------------------------

🛠️ TECH STACK

- Python 🐍
- Apify (LinkedIn Jobs Scraper API)
- Gemini AI API
- XeLaTeX / Overleaf
- Regex and NLP-based text processing

------------------------------------------------------------

⚙️ HOW IT WORKS

1️⃣ Create Apify and Gemini API keys  
2️⃣ Add the API keys directly into the Python script  
3️⃣ Scrape live LinkedIn job data using Apify  
4️⃣ Rank and filter jobs using skill and experience relevance  
5️⃣ Send base resume and job description to Gemini  
6️⃣ Generate job-specific XeLaTeX resumes  
7️⃣ Save resumes with job metadata for traceability  

------------------------------------------------------------

📂 OUTPUT STRUCTURE

/DD-MM-YYYY/
  /resume/
    CompanyName_1234.tex
    CompanyName_5678.tex

Each generated .tex file contains:
- Job link 🔗
- Job title 💼
- Company name 🏢
- AI-generated resume content 🤖

------------------------------------------------------------

🌟 WHY THIS PROJECT STANDS OUT

- Uses real LinkedIn job data instead of sample descriptions
- Applies generative AI with strict constraints
- Produces resumes aligned with actual hiring requirements
- Demonstrates strong backend engineering and applied AI skills
- Fully automates resume customization at scale

This is not just a resume builder.
It is a **resume intelligence system** 🧠📄

------------------------------------------------------------

⚠️ DISCLAIMER

This project is intended for educational and personal use only.
Ensure compliance with LinkedIn, Apify, and Gemini API terms of service.

------------------------------------------------------------

👤 AUTHOR

Mohamed Jafer  
Java Backend Developer  

🔗 LinkedIn: https://www.linkedin.com/in/mohamedjafer  
💻 GitHub: https://github.com/JaferDevEngineer
