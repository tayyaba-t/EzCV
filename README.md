# EzCV
Enginnering Project
**Project Overview**

This project presents the development of a web application called EzCV that functions as a resume builder, a live job market, and an applicant tracker, all designed to ease and speed up the hiring process.

The system is primarily aimed at helping job seekers create industry-approved, ATS-friendly resumes suitable for multiple applications. At the same time, employers can filter job applications based on their specific requirements.

Some of the advanced features implemented in the system include:

Real-time job hunting, enabling job seekers to apply directly for available positions.

An intelligent recommendation system that suggests relevant skills, certifications, and related courses that best match the candidate’s profile.

These features ensure that job seekers are not left behind in today’s competitive job market.

**Project Purpose**

The aim of EzCV is to:

Help users build strong resumes

Provide guidance through skill and course recommendations

Help job seekers find and apply for relevant jobs

Enable employers to filter and track applications efficiently

**Technologies Used**
**Frontend**

HTML

CSS

Bootstrap

**Backend**

Django

Django Rest Framework (if used)

**Database
**
SQL Server (Microsoft SQL Server)
**Other**

Skill & Course Recommendations: Identifies missing or weak skills by comparing resumes to job descriptions and suggests relevant Coursera courses in real time.

Resume Parsing: Extracts text from PDFs using PyPDF and structures key information (education, experience, skills) with the Gemini API.

BERT + Cosine Similarity Filtering: Uses semantic text analysis to calculate ATS scores and filter candidates by relevance.

Job Aggregation (LinkedIn Scraping): Fetches live job listings based on job title and country for real-time job discovery.

Course Recommendation (Coursera Scraping): Finds appropriate learning resources to address identified skill gaps.

CSV Job Ranking System: Logs applied jobs, attaches ATS scores, and automatically sorts them to highlight best-matched opportunities.
