# AI Employment Sentiment & Text Analytics  
**Automation Anxiety and AI Narratives Across Platforms (2017–2025)**

---

## Project Overview
This project analyzes **public discourse around AI-driven job displacement** across **Twitter, Reddit, and news media** to understand how people talk about automation, job loss, reskilling, and the future of work.

Using nearly **one million text records**, the study applies **topic modeling, sentiment analysis, and statistical testing** to uncover how **emotional tone and narratives differ by platform**.

**Key idea:**  
There is no single public opinion about AI and jobs — **each platform amplifies different emotions and themes**.

---

## Who This Is For
- **Non-technical audiences**: policymakers, managers, students, and the general public  
- **Technical audiences**: data analysts, data scientists, NLP practitioners  
- **Academic audiences**: conference reviewers, faculty, and researchers  

---

## Research Questions
- What themes dominate discussions about AI-driven job loss?
- How does sentiment differ across platforms?
- Where do fear and optimism about AI appear most strongly?
- Do platforms shape how AI and employment are discussed?

---

## Data Summary
| Platform | Volume | What It Represents |
|--------|--------|--------------------|
| Twitter | 893,000 posts | Real-time reactions and information sharing |
| Reddit | 885 comments | In-depth discussion, anxiety, and debate |
| News Media | 1,000 articles | Institutional and policy framing |

**Time period:** 2017–2025

---

## Methodology (CRISP-DM Inspired)
This project follows a structured **CRISP-DM workflow**, combining inductive and deductive text analytics:

- **Topic Modeling (LDA)** – uncover dominant themes  
- **Sentiment Analysis (VADER)** – positive, neutral, negative tone  
- **Fear vs. Optimism Dictionary** – theory-driven emotional framing  
- **Chi-Square Statistical Testing** – test platform–sentiment relationships  

All methods are interpretable and reproducible.

---

## Key Findings

### 1️⃣ Platform Narratives Are Fundamentally Different
- **News media** frame AI as progress and opportunity
- **Reddit** surfaces fear, uncertainty, and human impact
- **Twitter** is mostly neutral and informational

There is no unified narrative — **platform norms shape perception**.

![Common terms across platforms](Figures/WC_CommonTerms.png)

---

### 2️⃣ Sentiment Distribution Varies by Platform
**What we observe:**
- News articles are overwhelmingly positive
- Reddit contains the highest proportion of negative sentiment
- Twitter is largely neutral

**Why this matters:**  
Where people discuss AI strongly influences how they feel about it.

![Sentiment heatmap by platform](Figures/Sentiment_Heatmap.png)

---

### 3️⃣ Fear vs. Optimism Is Platform-Dependent
- Optimism dominates **news and Twitter**
- Reddit shows significantly higher **fear-related language**
- Statistical testing confirms this difference is **significant**

**Interpretation:**  
Reddit acts as an early indicator of workforce anxiety.

---

### 4️⃣ Topic Modeling Reveals Different Emphases
**Major themes identified:**
- Job displacement  
- Reskilling and education  
- Automation and innovation  
- Inequality and ethics  
- Productivity and efficiency  

**Platform differences:**
- News focuses on a **single dominant institutional narrative**
- Reddit and Twitter show **broader, multi-dimensional discussions**

---

### 5️⃣ Language Reflects Platform Values
**Vocabulary patterns:**
- **Twitter**: future, innovation, technology  
- **Reddit**: people, work, risk, replace  
- **News**: companies, growth, policy, economy  

Words reveal what each platform prioritizes.

---

## Why This Project Matters
- Helps **policymakers** understand where anxiety is forming
- Helps **organizations** tailor AI communication strategies
- Helps **researchers** track automation anxiety at scale
- Demonstrates how **platform design shapes public perception**

---

## Practical Recommendations
- Use **news media** for opportunity-focused messaging
- Use **Reddit** to acknowledge concerns and explain trade-offs
- Use **Twitter** for concise, factual updates
- Promote **digital literacy and reskilling pathways** across platforms

---

##  Repository Structure
├── Datasets/              # Raw and processed datasets
├── Figures/               # All visualizations used in analysis
├── Final Paper (PDF)      # Conference-style research paper
├── Code Appendix (PDF)    # Reproducible analysis code
└── README.md              # Project summary (this file)

---

## Full Paper
**Automation Anxiety and AI Narratives Across News, Reddit, and Twitter (2017–2025)**  
The complete Hawaii International Conference on System Sciences (HICSS) paper is included in this repository as a PDF.

---

## Author
**Dheeraj Shetty**  
MS Business Analytics & Artificial Intelligence  
American University  

---

## Future Work
- Time-series sentiment analysis around major AI events
- Transformer-based topic models (e.g., BERTopic)
- Expansion to LinkedIn, YouTube, and professional forums
- Linking discourse to labor-market and reskilling data

---
**Keywords:**  
Text Mining · NLP · Topic Modeling · Sentiment Analysis · Computational Social Science · AI & Employment

