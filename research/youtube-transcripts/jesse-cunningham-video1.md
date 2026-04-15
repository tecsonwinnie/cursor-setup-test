Title: I Built an SEO Agent That Replaces Manual SEO Work (n8n)

Author: Jesse Cunningham

Link: https://www.youtube.com/watch?v=-WdA6OZ9RjE

## Overview

This video demonstrates an SEO data extraction workflow using n8n and APIs to replace expensive tools like Ahrefs and Semrush.

Core themes:
- SEO success depends on access to data
- API-based workflows can replace traditional SEO tools
- Google Sheets is used as the central data layer
- Competitor analysis is the foundation of SEO strategy
- Emphasis on identifying high-value pages and keywords


## Workflow / Process

### 1. System Overview

The workflow consists of four main processes:

1. Domain rank overview  
2. Relevant pages extraction  
3. Ranked keywords performance  
4. Competitor visibility overview  

Output:
- All data is pushed into Google Sheets for analysis

---

### 2. Data Source (API-Based)

- Uses DataForSEO API
- Pulls raw SEO data instead of using UI tools

Key difference:
- No visual dashboards
- Raw data only (via Google Sheets)

---

### 3. Domain Rank Overview

Purpose:
- Analyze overall domain performance

Metrics:
- Estimated organic traffic (e.g., 1.5M monthly searches)
- General visibility of the domain

Use case:
- Identify strong competitors in a niche

Example process:
1. Search keyword (e.g., "home security system")
2. Identify top-ranking domain
3. Analyze domain data via workflow

---

### 4. Relevant Pages Extraction

Purpose:
- Identify top-performing pages of a domain

Process:
1. Pull top ~100 pages
2. Analyze:
   - Organic rankings
   - Traffic contribution

Key metric:
- Number of #1 rankings per page

Example:
- A page ranking #1 for 486 queries = “money page”

Insights:
- Identify pages driving most traffic and revenue
- Study:
  - URL structure (slug)
  - Content format
  - monetization (e.g., affiliate links)

---

### 5. Keyword Performance Analysis

Purpose:
- Extract ranking keywords and performance data

Data includes:
- Keywords
- Search volume
- Intent type:
  - Transactional
  - Informational
  - Commercial

Observations:
- High-performing sites prioritize transactional keywords
- Informational content is less effective for monetization

Additional insight:
- AI overviews reduce value of informational content
- Risk:
  - Informational content feeds AI without driving clicks

---

### 6. Competitor Visibility Overview

Purpose:
- Identify competing domains in the same niche

Process:
1. Input a domain
2. Retrieve related competitor domains

Use case:
- Expand competitor list beyond known sites

Strategy:
- Run workflow on multiple competitors
- Repeat analysis for each

---

### 7. Iterative Competitor Analysis

Process:

1. Identify competitor domain  
2. Extract:
   - Top pages
   - Keywords  
3. Analyze:
   - Content structure
   - Internal linking
   - monetization strategy  

4. Repeat for multiple domains  

Goal:
- Build a complete understanding of the niche

---

### 8. Content Reverse Engineering

Approach:

- Study top pages:
  - Headings (H2s, structure)
  - Internal links
  - Layout

- Identify patterns:
  - Why pages rank
  - How they convert

- Apply learnings to own site

---

### 9. SEO Execution Framework

Key steps:

1. Gather data (API workflow)
2. Identify:
   - Best pages
   - High-value keywords
3. Analyze competitors
4. Emulate successful patterns
5. Build content based on insights

---

## Tools / Stack

Core tools:

- n8n – workflow automation  
- DataForSEO API – SEO data source  
- Google Sheets – data storage and analysis  

Referenced tools (comparison):

- Ahrefs  
- Semrush  

Additional context:
- Workflow operates without visual dashboards
- Focus on raw data processing


## Key Insights

### 1. Data is essential for SEO
- Cannot compete effectively without data
- APIs provide accessible alternative to expensive tools

---

### 2. Top pages drive most value
- “Money pages” identified by:
  - High number of #1 rankings
  - High traffic contribution

---

### 3. Competitor analysis is repeatable
- Same workflow applied across multiple domains
- Scalable process

---

### 4. Transactional content is prioritized
- Higher monetization potential
- Informational content less effective

---

### 5. AI overviews impact informational SEO
- Reduce click-through potential
- Shift focus toward transactional queries

---

### 6. Raw data > UI tools
- Visualization tools are optional
- Core value is in underlying data

---

### 7. SEO is pattern recognition
- Success comes from:
  - Studying competitors
  - Identifying patterns
  - Applying them strategically

---

### 8. Internal linking and structure matter
- Observing competitor structure reveals:
  - Intent alignment
  - Content hierarchy

---

### 9. Iteration is key
- Analyze → apply → repeat
- Continuous refinement of strategy

---

### 10. Low-authority opportunities exist
- Identify weaker competitors
- Target achievable rankings


## Results / Outcomes

Claimed outcomes:

- Ability to replicate functionality of expensive tools  
- Access to:
  - competitor data
  - keyword insights
  - page performance  

- Enables:
  - Traffic growth
  - revenue-focused SEO strategies  

Case reference:
- Mention of a client scaling to significant revenue growth using similar methods


## Limitations / Notes

### 1. No visual interface
- Requires comfort with raw data
- Less beginner-friendly

---

### 2. Requires API setup
- Initial setup complexity
- Pay-per-use model

---

### 3. Manual analysis required
- Data must be interpreted manually
- No automated insights layer

---

### 4. Skill-dependent
- Effectiveness depends on:
  - Ability to analyze data
  - Understanding SEO fundamentals

---

### 5. Informational content risk
- Lower ROI due to AI overviews
- Potential traffic loss

---

### 6. Strategic focus shift
- Emphasis on:
  - Revenue-driving pages
  - Transactional intent
