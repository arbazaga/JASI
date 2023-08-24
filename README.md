## Product Requirements Document

### Product Name: JASI 

### Overview

JASI is a platform that provides job seekers with a personalized Job Alignment Score (JAS), indicating how well their skills and experience match desired job postings. The platform offers tailored recommendations on resume improvement, skill development, projects, interview preparation, and more to increase users' alignment and competitiveness.

### User Personas

**Sam - Recent Graduate:** No prior professional experience. Seeking guidance tailoring his resume and skillset for new roles.

**Sarah - Career Changer:** Transitioning industries. Needs to articulate transferable skills from her background into new functions. 

**Tom - Experienced Professional:** Significant experience but looking to pivot into a new domain. Wants to showcase cross-domain expertise.

### User Journey

1. Users create JASI profile and upload resume.
2. Users search and select target job posting.
3. JASI analyzes resume against job description using NLP and machine learning. 
4. Personalized JAS (out of 100) is calculated measuring qualifications alignment.
5. Users receive targeted recommendations to improve JAS for that role.
6. As users complete recommendations, JAS will continuously improve.
7. Higher JAS leads to more interviews and competitive candidacy. 

### Key Features

**Scoring Algorithm**

- Parses resumes and job descriptions to extract keywords, skills, qualifications.
- Matches background against requirements and calculates precise JAS.
- Explains areas of strength and weakness in simple, visual format. 

**Recommendation Engine** 

- Curated advice for resume improvement, new skills, projects, courses, mock interviews.
- Tailored to user's current background, target role, and JAS goals.
- Connects users directly with relevant online courses and materials.

**Resume Builder**

- Allows users to update resumes directly on JASI platform.
- Optimize content and formatting for applicant tracking systems.

**Mock Interviews**

- Users can practice interviews tailored to their target job area.  
- Get feedback to refine interview skills and confidence.

**Project Badging** 

- Submit completed projects to showcase new skills and achievements.
- Earn verified badges to add to resume and profiles.

### Technology 

- Python Django REST API backend
- React front-end with dynamic UX
- AWS cloud infrastructure
- Machine learning for matching and recommendations 
- Resume parsing libraries like TextRazor

### Success Metrics

- User engagement 
- Average improvement in JAS score
- Click-through rate on recommendations
- Mock interviews and projects completed
- User satisfaction ratings
- Job placement rates

The goal of JASI is to make job hunting transparent, personalized, and effective by giving seekers data-driven insights to showcase their best self and connect with the right opportunities.
