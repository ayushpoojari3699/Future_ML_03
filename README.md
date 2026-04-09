# Resume Screening & Ranking System (ML Task 3)

##  Overview
This project builds a Machine Learning-based system to automatically screen and rank resumes based on a given job description.

It helps recruiters:
- Shortlist candidates faster
- Identify skill gaps
- Rank candidates objectively

---

##  How It Works

### 1. Text Preprocessing
- Converted text to lowercase
- Removed special characters
- Removed stopwords

### 2. Resume–Job Matching
- Used **TF-IDF Vectorization**
- Applied **Cosine Similarity**
- Each resume gets a **similarity score**

### 3. Skill Extraction
- Extracted skills using keyword matching
- Example skills:
  - Python, SQL, Machine Learning, Data Analysis

### 4. Skill Gap Analysis
- Compared resume skills with job skills
- Identified **missing skills**

### 5. Final Scoring Formula

Final Score =  
0.7 × Similarity Score + 0.3 × Skill Match Score

---

##  Output

Each resume includes:
- Final Score
- Extracted Skills
- Missing Skills

Example:
