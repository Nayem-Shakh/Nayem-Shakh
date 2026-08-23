# 👋 Hi, I'm Md. Nayem Shakh

### Healthcare Data Operations | PostgreSQL | Python | Regex | EHR | Retool

I’m a healthcare operations professional with **2 years of hands-on experience as a Medical Documentation Specialist at Augmedix, now Commure**, working directly with clinicians and clinical documentation workflows.

That experience gave me something that cannot be learned from a database course alone: **real exposure to healthcare workflows, clinical documentation, EHR systems, operational edge cases, and the importance of getting structured information exactly right.**

Alongside that healthcare experience, I’ve deliberately built a technical problem-solving portfolio around **PostgreSQL, Python, Regex, data processing, and automation**.

I’m interested in Data Operations roles where these two sides meet:

> **Healthcare domain knowledge + technical problem solving + workflow thinking**

My portfolio is built around one question:

> **Can I take messy, ambiguous data and turn it into a reliable answer, repeatable workflow, or automated process?**

That means writing non-trivial PostgreSQL, building Python data pipelines, using regex for precision extraction, investigating operational anomalies, understanding EHR-driven workflows, and solving algorithmic problems that force me to reason carefully about edge cases and efficiency.

---

## 🎯 What I Bring

| Area | What I Demonstrate |
|---|---|
| 🏥 **Healthcare Operations** | 2 years at Augmedix / Commure as a Medical Documentation Specialist, working with clinicians and clinical documentation workflows |
| 🖥️ **EHR Systems** | Hands-on experience working with **NextGen, Epic, and Cerner** |
| 🛠️ **Retool** | Practical experience building internal workflow/tools projects in Retool |
| 🐘 **PostgreSQL / SQL** | 158+ SQL challenges, complex joins, subqueries, CTEs, window functions, conditional logic, aggregation |
| 🐍 **Python** | 113+ algorithmic/data problems, scripting, Pandas, data processing, automation |
| 🔎 **Regex** | Precision matching, structured extraction, negative lookaheads, non-capturing groups, noisy text parsing |
| 🧩 **Problem Solving** | 270+ combined SQL/Python challenges across LeetCode & HackerRank |
| 💳 **Healthcare Billing Concepts** | Basic familiarity with **CPT coding concepts** and healthcare documentation context; currently building deeper billing knowledge |
| 🧠 **Ambiguous Problems** | Breaking poorly structured datasets and unclear requirements into explicit, testable logic |

---

# 🏆 Problem-Solving Track Record

## SQL — 158+ Problems

### HackerRank
- ✅ **58 / 58 SQL problems solved**
- 🥇 **Rank #1**
- 🏅 Basic, Intermediate & Advanced SQL certifications

### LeetCode
- ✅ **100 targeted SQL problems solved**

### What I’ve Practiced

**Data Filtering & Regex**
- Precision string matching
- Data cleaning
- Pattern-based record extraction
- Handling messy text fields

**Relational Mapping**
- Multi-table joins
- Deep relational dependencies
- Entity matching across tables
- Avoiding duplicate records during joins

**Aggregation & Conditional Logic**
- `GROUP BY`
- Multi-level aggregation
- `CASE WHEN`
- Conditional metrics
- Outlier categorization

**Subqueries & CTEs**
- Step-by-step filtering pipelines
- Nested business logic
- Correlated reasoning across multiple levels
- Breaking large problems into readable query stages

**Window Functions**
- `RANK()`
- `LEAD()`
- `LAG()`
- Sequential event analysis
- Previous/next state comparison
- Timeline-based anomaly detection

### SQL Philosophy

I don’t treat SQL as a reporting language.

I treat it as a **problem-solving language** for transforming raw relational data into explicit, verifiable logic.

---

# 🐍 Python & Algorithmic Problem Solving — 113+ Problems

### Platform Metrics

- **HackerRank:** ~50 Python challenges
- **LeetCode:** 65 algorithmic problems
- **Combined SQL + Python practice:** 200+ problems

### Core Patterns

**Arrays & Hash Maps**
- Fast lookups
- Frequency counting
- Deduplication
- Mapping relationships efficiently

**Two Pointers**
- In-place sequence processing
- Palindrome validation
- Linear-time scanning

**Strings & Parsing**
- Structural validation
- Bracket matching
- Text transformation
- Character-level processing

**Sliding Window**
- Continuous-range analysis
- Rolling time-window logic
- Efficient `O(N)` solutions

**Binary Search**
- Searching sorted datasets
- Boundary conditions
- `O(log N)` lookup strategies

**Matrices & Logic**
- 2D traversal
- Boundary handling
- State-based logic
- Edge-case reasoning

The goal is not simply to collect solved problems.

The goal is to build the habit of asking:

**What is the structure of the problem? What can I eliminate? What state must I remember? What happens at the boundary?**

---

# 🏥 Healthcare Operations Analysis

## Hospital Operations Analysis

This project is especially relevant to my professional background because I already understand healthcare documentation and clinician-facing workflows from working in medical documentation operations.

A healthcare-focused analytics project built around a real operational question:

> **Where is the hospital process breaking down?**

Using **Python, Pandas, and Matplotlib**, I explored hospital operational data to identify patterns in patient flow and length of stay.

### Key Finding

The analysis revealed a systemic bottleneck:

**Average Length of Stay remained approximately ~15.5 days across medical conditions.**

Rather than stopping at visualization, I used the data to investigate the operational implication:

> If substantially different patient groups are showing nearly identical average stays, the constraint may be coming from a **shared operational process** rather than the clinical condition itself.

### Skills Demonstrated

- Exploratory Data Analysis
- Data quality inspection
- Grouped statistical analysis
- Operational KPI investigation
- Visualization
- Translating data patterns into business hypotheses

📁 **Project:** [Healthcare Operations Analysis](https://github.com/Nayem-Shakh/Healthcare-Operations-Analysis-Python)

---

# 🏥 Healthcare Provider Data Pipeline

## ETL + Regex + Data Standardization

A Python pipeline designed to process **chaotic, unstructured provider information** collected from legacy clinic websites and transform it into standardized, database-ready data.

### Pipeline

```text
Raw Web Text
     │
     ▼
Extraction
     │
     ▼
Regex Parsing
     │
     ▼
Validation
     │
     ▼
Normalization
     │
     ▼
Structured Data
     │
     ▼
Database-Ready Output
```

### Core Technologies

- Python
- `re` / Advanced Regex
- Pandas
- ETL principles
- Data standardization

### The Interesting Part

One of the extraction problems required identifying **website domains while ignoring email addresses appearing in the same text block**.

I solved this with a precision-focused regex approach using techniques such as:

- Negative lookaheads
- Non-capturing groups
- Structured boundary matching
- Explicit exclusion logic

This project represents the kind of problem I enjoy most:

> **The data is messy, the rules are incomplete, and the solution has to be precise.**

📁 **Project:** [Healthcare Provider Data Pipeline](https://github.com/Nayem-Shakh/Python-Regex-HealthcareData-Cleaning)

---

# 🗄️ Hospital Management System Database

A relational database architecture designed to model hospital operations, staff, and patient records.

### Focus Areas

- Relational database design
- Entity relationships
- Multi-table querying
- Data integrity
- Complex joins
- Aggregation
- Window functions

### Why I Built It

Healthcare data becomes difficult when multiple operational entities interact:

```text
Patients
   │
   ├── Visits
   │     ├── Doctors
   │     ├── Departments
   │     └── Diagnoses
   │
   ├── Appointments
   │
   └── Billing / Operational Events
```

The project helped me practice reasoning about how information should be connected **before** writing the query that retrieves it.

📁 **Project:** [Hospital Management System Database](https://github.com/Nayem-Shakh/Hospital-Management-System-SQL-Data-Analysis)

---

# 🚲 NYC Citi Bike SQL Data Analysis

A PostgreSQL analysis project using NYC Citi Bike data to investigate rider behavior and system logistics.

### Questions Explored

- Which stations are most active?
- How does rider behavior vary across the system?
- Which patterns appear across time?
- How can multiple relational tables be combined without introducing incorrect counts?
- How can window functions expose ranking and sequential patterns?

### Technical Focus

- PostgreSQL
- Data cleaning
- Complex joins
- Aggregations
- CTEs
- Window functions
- Analytical SQL

📁 **Project:** [NYC Citi Bike SQL Analysis](https://github.com/Nayem-Shakh/NYC-Citi-Bike-SQL-Analysis)

---

# 💼 Professional Healthcare Experience

## Medical Documentation Specialist — Augmedix / Commure

**2 years of hands-on healthcare operations experience**

In this role, I worked closely with **U.S. clinicians** in a clinical documentation environment, developing practical familiarity with healthcare workflows and the systems that support them.

### Experience Highlights

- Worked directly with clinicians and clinical documentation workflows.
- Worked with major **EHR platforms including NextGen, Epic, and Cerner**.
- Developed practical understanding of how clinical information moves through documentation workflows.
- Gained experience recognizing documentation inconsistencies, workflow issues, and edge cases where accuracy matters.
- Built and worked on **Retool projects** for internal workflow/tooling needs.
- Developed practical familiarity with healthcare terminology and documentation processes.
- Have a **basic working understanding of CPT codes**, while continuing to deepen my knowledge of healthcare billing and Revenue Cycle Management.

This background gives me an important advantage for healthcare Data Operations work:

> **I understand the people, workflows, systems, and documentation behind the data—not just the SQL used to query it.**

---

# 🧰 Technical Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![Regex](https://img.shields.io/badge/Regex-Precision%20Parsing-111827?style=flat)

### Data & Analytics
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=plotly&logoColor=white)

### Problem Solving
![LeetCode](https://img.shields.io/badge/LeetCode-200%2B%20SQL%2B%20Python-orange?style=flat&logo=leetcode&logoColor=white)
![HackerRank](https://img.shields.io/badge/HackerRank-SQL%20%23%201-2EC866?style=flat&logo=hackerrank&logoColor=white)

---

# 🔬 The Direction I’m Building Toward

I’m intentionally moving toward **hands-on Data Operations**, where SQL, automation, investigation, and healthcare workflow knowledge come together.

I’m not approaching healthcare data as a brand-new domain: I already have professional experience working with clinicians, medical documentation, and EHR-driven workflows. My current technical work is about extending that domain experience into deeper data and automation capabilities.

My target skill set is:

```text
                 RAW DATA
                    │
                    ▼
          ┌─────────────────┐
          │ Understand Data │
          └────────┬────────┘
                   │
                   ▼
          ┌─────────────────┐
          │ Query / Extract │
          └────────┬────────┘
                   │
                   ▼
          ┌─────────────────┐
          │ Validate Logic  │
          └────────┬────────┘
                   │
                   ▼
          ┌─────────────────┐
          │ Automate / ETL  │
          └────────┬────────┘
                   │
                   ▼
          ┌─────────────────┐
          │ Find Anomalies  │
          └────────┬────────┘
                   │
                   ▼
              ACTIONABLE
                RESULT
```

That is the direction I’m pursuing across:

- Data Operations
- Healthcare Analytics
- Revenue Cycle / Billing Analytics
- Data Quality
- Workflow Automation
- SQL-heavy Operations Engineering

---

# 💡 Why Healthcare Data Operations?

Healthcare data is especially interesting to me because I’ve worked **inside healthcare documentation workflows**, rather than approaching healthcare purely as an outside analytics domain.

From working with clinicians and EHR-driven processes, I’ve seen how small documentation, workflow, and data-quality issues can have downstream operational consequences.

The hardest problems are rarely just:

> “What does the dashboard say?”

They are closer to:

> **Why did this record behave differently?**  
> **Which event caused the anomaly?**  
> **Does the data actually make sense?**  
> **Can the logic be expressed precisely enough to automate?**  
> **Can I reproduce the answer with SQL or code instead of manually checking hundreds of records?**

That combination of **structured data + messy real-world processes + high attention to detail** is exactly the kind of work I want to specialize in.

---

# 📂 Featured Projects

My repositories intentionally combine **technical problem solving with healthcare-domain context**.

| Project | Focus | Tech |
|---|---|---|
| 🏥 [Healthcare Provider Data Pipeline](https://github.com/Nayem-Shakh/Python-Regex-HealthcareData-Cleaning) | ETL, Regex, data standardization | Python, Regex, Pandas |
| 🏥 [Healthcare Operations Analysis](https://github.com/Nayem-Shakh/Healthcare-Operations-Analysis-Python) | Operational anomaly investigation | Python, Pandas, Matplotlib |
| 🗄️ [Hospital Management System](https://github.com/Nayem-Shakh/Hospital-Management-System-SQL-Data-Analysis) | Relational database architecture | SQL |
| 🚲 [NYC Citi Bike SQL Analysis](https://github.com/Nayem-Shakh/NYC-Citi-Bike-SQL-Analysis) | Advanced analytical SQL | PostgreSQL |
| 🧩 [LeetCode & HackerRank Vault](https://github.com/Nayem-Shakh/LeetCode-and-HackerRank-Vault) | Algorithmic problem solving | SQL, Python |

---

# 📈 My Engineering Mindset

I enjoy problems that have one or more of these characteristics:

- The requirement is incomplete.
- The data is messy.
- The obvious query gives the wrong answer.
- Multiple tables must be connected correctly.
- Edge cases matter.
- A manual process should become a script.
- A pattern looks suspicious and needs investigation.
- The final result must be reproducible.

My preferred workflow is:

**Understand → Hypothesize → Query → Validate → Automate → Explain**

---

# 🚀 Next on My Roadmap

I’m actively expanding this portfolio into more production-style projects involving:

- PostgreSQL query optimization
- Healthcare billing datasets
- CPT / ICD-10 oriented data models
- Claims and payment anomaly detection
- Regex-heavy data validation
- Python automation scripts
- Data quality checks
- API-to-database ETL pipelines
- Retool internal tools and workflow automation
- Reproducible operational investigations
- Deeper healthcare revenue-cycle and billing knowledge

---

# 📫 Let's Connect

I’m interested in opportunities involving **Data Operations, Healthcare Analytics, SQL Engineering, Data Quality, ETL, and workflow automation**.

- 💼 LinkedIn: (https://www.linkedin.com/in/md-nayem-shakh/)
- 🧑‍💻 GitHub: (https://github.com/Nayem-Shakh)
- 📧 Email: (mohammadnayempersonal@gmail.com)

---

## ⭐ If you're reviewing my profile for a Data Operations role...

My profile combines three things I believe are unusually valuable together:

**1. Real healthcare operations experience**  
Two years working with clinicians, medical documentation, and EHR systems.

**2. Technical problem-solving**  
158+ SQL problems, 113+ Python/algorithmic problems, advanced Regex, PostgreSQL, Pandas, and ETL projects.

**3. Workflow mindset**  
Hands-on Retool exposure, automation-oriented projects, and a habit of investigating why a data result is happening rather than simply reporting it.

Start here:

**1.** [Healthcare Provider Data Pipeline](https://github.com/Nayem-Shakh/Python-Regex-HealthcareData-Cleaning).  
**2.** [Healthcare Operations Analysis](https://github.com/Nayem-Shakh/Healthcare-Operations-Analysis-Python)  
**3.** [NYC Citi Bike SQL Analysis](https://github.com/Nayem-Shakh/Hospital-Management-System-SQL-Data-Analysis)  
**4.** [Hospital Management System](https://github.com/Nayem-Shakh/NYC-Citi-Bike-SQL-Analysis)  
**5.** [LeetCode & HackerRank Vault](https://github.com/Nayem-Shakh/LeetCode-and-HackerRank-Vault)

The common thread across all five projects is simple:

> **I like turning difficult data problems into explicit, testable logic.**
