# stackoverflow-developer-survey-analysis
## Exploratory data analysis of the Stack Overflow Developer Survey using Python, Pandas, SQLite, and Matplotlib.
## Data Analyst Capstone Project
Author: Naznin Sharmin Shishir

## Project Overview
This capstone project explores the Stack Overflow Developer Survey to understand developer demographics, work patterns, compensation, job satisfaction, and technology preferences. It demonstrates an exploratory data analysis workflow using Python, Pandas, SQLite, Matplotlib, and IBM Cognos Analytics supported by visualizations and a presentation of findings.

The project is intended for entry-level data analysts, hiring teams, educators, and technology decision-makers who want to understand patterns in the developer ecosystem.

## Objectives and Questions
The analysis is organized around questions such as:
- How do compensation and job satisfaction vary by age and professional experience?
- Which employment groups and work arrangements are represented?
- Which programming languages, databases, and platforms do developers currently use or want to use?
- What can survey responses tell us about technology adoption and developer preferences?

## Tools and Technologies
- Python – analysis workflow
- Pandas – data inspection, cleaning, transformation, and aggregation
- SQLite – storing and querying survey data
- Matplotlib – data visualization
- IBM Cognos Analytics - data visualization
- Jupyter Notebook – recommended environment for documenting and rerunning the analysis
## Methodology
1. Data inspection: Review the dataset structure, columns, data types, and missing values.
2. Data cleaning: Convert compensation and satisfaction fields to numeric formats where appropriate.
3. Data transformation: Split semicolon-separated multi-select responses before counting technology preferences.
4. Exploratory analysis: Group responses by age, employment, country, and professional experience to examine patterns and calculate summary statistics.
5. Visualization: Use histograms, box plots, scatter/bubble plots, stacked bar charts, and line charts to communicate patterns.
6. Interpretation: Discuss findings alongside data limitations, including missing values, self-reported responses, and the distinction between association and causation.
## Topics Explored
- Developer demographics, including age and country
- Employment and remote-work arrangements
- Professional experience
- Compensation
- Job satisfaction
- Programming language usage and preferences
- Database and platform preferences
- Technology trends, including AI adoption
## Selected Context from the Official 2025 Survey
The presentation references the official Stack Overflow Developer Survey 2025 published results. It highlights the following published aggregate figures:
- 84% of respondents use or plan to use AI tools in development.
- 46% distrust the accuracy of AI output, compared with 33% who trust it.
- Python adoption increased by 7 percentage points year over year.
- Rust leads the admired programming languages in the cited results.

## Key Takeaways
The presentation emphasizes several practical implications:
- SQL and widely used programming languages remain important foundations for technology careers.
- Python is relevant to analytics, AI, and back-end development, and its adoption has been growing.
- Database knowledge, including PostgreSQL, is valuable to continue exploring.
- AI tool adoption is high, but trust in AI-generated output remains mixed.
- Survey insights should be treated as directional evidence and validated against the cleaned project dataset and current job-market information.

## Limitations
- Survey responses are self-reported and may contain missing or inconsistent values.
- Self-selection can affect how representative the survey is of all developers.
- Compensation distributions may contain outliers; medians can be more informative than means.
- Relationships shown in scatter plots are associations and do not establish causation.
- Multi-select responses must be split and counted consistently.
- Exact project-specific statistics should be refreshed by running the analysis on the original CSV.

## Repository Contents
This repository currently contains the capstone presentation. If you add the analysis files, a useful structure would be:
stackoverflow-developer-survey-analysis/
├── README.md
├──Data-Analyst-Capstone-Project.pptx
├──survey_analysis.ipynb
├──survey_analysis.py
├── README.md
└── dashboard-screenshots

## How to Reproduce the Analysis
The presentation describes a workflow based on the Stack Overflow Developer Survey CSV, Python, Pandas, Matplotlib, and SQLite. To make the analysis reproducible for other users:
1. Download the CSV file.
2. Place the CSV in the project data folder.
3. Install the required Python packages.
4. Open and run the notebook or scripts from top to bottom.

Author
Naznin Sharmin Shishir
Data Analyst Capstone Project
This repository presents an exploratory analysis project and its accompanying presentation.
