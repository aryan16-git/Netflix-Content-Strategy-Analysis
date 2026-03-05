\# Netflix Content Strategy Analysis



\[!\[Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)

\[!\[Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)](https://powerbi.microsoft.com/)

\[!\[License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)



\## 📌 Project Overview



A comprehensive data analysis of Netflix's content library comprising \*\*8,800+ titles\*\* across 85 countries. This project examines content trends, growth patterns, and geographic distribution to provide strategic recommendations for content acquisition and production.



!\[Dashboard Overview](outputs/figures/dashboard\_overview.png)  \*(You'll add this screenshot later)\*



---



\## 🎯 Business Questions Answered



\- How has Netflix's content strategy evolved over time?

\- What genres and countries dominate Netflix's library?

\- Where are the content gaps and opportunities?

\- How does Netflix's content mix vary by region?

\- What strategic recommendations can be derived from the data?



---



\## 📊 Key Findings



| Insight | Finding | Business Impact |

|---------|---------|-----------------|

| \*\*Content Growth\*\* | 300% increase in titles added post-2016 | Aggressive expansion strategy |

| \*\*Content Mix\*\* | 70% Movies / 30% TV Shows | Movie-focused platform |

| \*\*Top Genres\*\* | Dramas, Comedies, Documentaries (45% of library) | Core content categories |

| \*\*US Dominance\*\* | Declined from 65% to 40% of library | Successful international expansion |

| \*\*Peak Year\*\* | 2019 with 1,800+ titles added | Maximum content investment |

| \*\*Content Age\*\* | Dropped from 15 to 3 years average | Shift from licensed to originals |



!\[Content Growth](outputs/figures/temporal\_analysis.png)



---



\## 🛠️ Tools \& Technologies



|Category|Tools Used|
|-|-|
|\*\*Programming\*\*|Python 3.8+|
|\*\*Data Processing\*\*|Pandas, NumPy|
|\*\*Visualization\*\*|Matplotlib, Seaborn, Plotly|
|\*\*Dashboard\*\*|Power BI|
|\*\*Development\*\*|Jupyter Notebooks, Git|



---



\## 📁 Repository Structure



Netflix-Content-Strategy-Analysis/

│

├── data/

│ ├── raw/ # Original Netflix dataset

│ └── processed/ # Cleaned data ready for analysis

│

├── notebooks/ # Jupyter notebooks (numbered in order)

│ ├── 01\_data\_cleaning.ipynb

│ ├── 02\_eda\_analysis.ipynb

│ ├── 03\_temporal\_analysis.ipynb

│ ├── 04\_genre\_country\_analysis.ipynb

│ └── 05\_document\_findings.ipynb

│

├── outputs/

│ ├── figures/ # All visualizations (PNG files)

│ └── reports/ # Findings and documentation

│ ├── executive\_summary.md

│ ├── presentation\_summary.txt

│ └── insights\_\*.csv

│

├── dashboard/

│ └── Netflix\_Dashboard.pbix # Interactive Power BI dashboard

│

├── requirements.txt # Python dependencies

└── README.md # Project documentation (this file)





---



\## 🔍 Analysis Performed



\### 1. Data Cleaning \& Preparation

\- Handled missing values in director, cast, and country columns

\- Parsed dates and created temporal features (year\_added, month\_added)

\- Engineered new features: content\_age, cast\_count, genre\_count, release\_decade

\- Processed multi-value columns (genres, cast, country)



\### 2. Exploratory Data Analysis

\- \*\*Content Distribution\*\*: Movies vs TV Shows analysis

\- \*\*Temporal Trends\*\*: Yearly growth patterns and seasonality

\- \*\*Genre Analysis\*\*: Top genres and evolution over time

\- \*\*Geographic Analysis\*\*: Country-wise distribution and international expansion

\- \*\*Rating Analysis\*\*: Content rating patterns by type and country



\### 3. Visualization Highlights

\- Content type distribution (pie/bar charts)

\- Yearly content additions (line charts)

\- Top genres (bar charts)

\- Country-genre heatmaps

\- Word clouds for titles and descriptions

\- Rating distribution by content type



!\[Genre Analysis](outputs/figures/genre\_analysis.png)



---



\## 📈 Key Insights \& Recommendations



\### Strategic Findings

| Category | Key Insight |

|----------|-------------|

| \*\*Content Mix\*\* | Maintain 70/30 movie/TV ratio while monitoring engagement |

| \*\*International\*\* | Increase investment in India, UK, and South Korea content |

| \*\*Genres\*\* | Strengthen Drama/Comedy while growing Documentary category |

| \*\*Ratings\*\* | Balance mature (TV-MA) with family-friendly content |

| \*\*Growth\*\* | Shift from rapid expansion to curated quality |



\### Recommendations

\- \*\*Short-term\*\*: Increase family-friendly content, boost emerging genres

\- \*\*Long-term\*\*: Target 60/40 US/International split, focus on originals



---



\## 🚀 How to Run This Project



\### Prerequisites

\- Python 3.8 or higher

\- Git

\- Power BI Desktop (for dashboard)



\### Step-by-Step Setup



1\. \*\*Clone the repository\*\*

   ```bash

   git clone https://github.com/YOUR\_USERNAME/netflix-content-strategy-analysis.git

   cd netflix-content-strategy-analysis


2. \*\*Install required packages\*\*

&nbsp;  ```bash

&nbsp;  pip install -r requirements.txt



3\. \*\*Download the dataset\*\*

&nbsp;  Get the dataset from Kaggle Netflix Titles

&nbsp;  Place netflix\_titles.csv in the data/raw/ folder



4\. \*\*Run the notebooks in order\*\*

&nbsp;  ```bash

&nbsp;  jupyter notebook



&nbsp;  Open and run notebooks in this sequence:

01\_data\_cleaning.ipynb

02\_eda\_analysis.ipynb

03\_temporal\_analysis.ipynb

04\_genre\_country\_analysis.ipynb

05\_document\_findings.ipynb



5\. \*\*View the dashboard\*\*

Open dashboard/Netflix\_Dashboard.pbix in Power BI Desktop



---



\## 📊 Dashboard Preview



The Power BI dashboard contains 3 interactive tabs:

|Tab|Description|
|-|-|
|Overview|Key KPIs, content mix, top countries, rating distribution|
|Trends|Yearly growth, seasonal patterns, content age analysis|
|Genre Deep Dive|Genre distribution, evolution over time, country-genre heatmap|



https://outputs/figures/dashboard\_trends.png



---



\## 📝 Project Documentation



All findings and insights are documented in the outputs/reports/ folder:

* executive\_summary.md - High-level overview for stakeholders
* presentation\_summary.txt - Concise summary for interviews
* content\_mix\_insights.csv - Detailed content type analysis
* genre\_insights.csv - Genre-specific findings
* country\_insights.csv - Geographic distribution insights
* temporal\_insights.csv - Time-based analysis



---



\## 👨‍💻 Author



ARYAN GUPTA



* LinkedIn: https://www.linkedin.com/in/aryan-gupta-d16m08/
* Email: aryangupta16082004@gmail.com



---



\## 📄 License



This project is licensed under the MIT License - see the LICENSE file for details.

