# Data Visualization and Product Design: An Analysis of CSE Department Research

This project presents an in-depth analysis and visualization of the research output from the Computer Science and Engineering (CSE) department at Dr. B. R. Ambedkar National Institute of Technology, Jalandhar (NITJ).

## Table of Contents

* [About The Project](#about-the-project)
* [Key Features](#key-features)
* [Visualizations](#visualizations)
* [Methodology](#methodology)
* [Technology Stack](#technology-stack)
* [Project Documentation](#project-documentation)
* [Team](#team)
* [Getting Started](#getting-started)
* [Conclusion](#conclusion)


## About The Project

The primary goal of this project is to explore trends, themes, and patterns within the research contributions of the CSE department's faculty. By transforming raw publication data into intuitive visual representations, we provide key insights into:

* Faculty expertise and core research areas
* Publication trends over time
* Collaboration networks and co-authorship patterns
* Unexplored or emerging research domains

This analysis aims to support institutional goals such as strategic resource allocation, faculty development, and fostering interdisciplinary research collaborations.

## Key Features

* **Comprehensive Data Collection:** Data was aggregated from multiple academic sources including Google Scholar, Web of Science, and IRINS.
* **Advanced Preprocessing:** Utilized predictive modeling (XGBoost) to impute missing data points with high accuracy.
* **In-depth Statistical Analysis:** Employed dimensionality reduction (UMAP, t-SNE) and clustering (K-Means) to identify distinct faculty profiles.
* **Hypothesis Testing:** Conducted T-tests to validate hypotheses, such as the impact of discipline specialization on citation counts.
* **Purity Matrix Analysis:** Developed a purity matrix to identify under-researched and potential interdisciplinary research areas.


## Visualizations

Our analysis is presented through a variety of visualizations to make complex data accessible and understandable.

| Line Chart | Bar Graph | Box Plot |
| :--------: | :-------: | :------: |
|            |           |          |

*Tracks yearly citation growth for individual faculty members.* | *Compares total citation counts across all professors.* | *Shows the distribution of h-indices by academic position.*

| Pie Chart | Network Graph | Correlation Matrix |
| :-------: | :-----------: | :----------------: |
|           |               |                    |

*Displays the distribution of research topics across the department.* | *Maps the relationships and co-occurrence between research domains.* | *Visualizes the relationships between different research metrics.*


## Methodology

Our project followed a structured data analysis workflow:

1.  **Data Extraction:** Automated data collection from web sources using Python scripts (`scholarly`) and web scraping techniques.
2.  **Data Preprocessing & Cleaning:** Handled missing values, removed noise, and performed data reduction to ensure data quality.
3.  **Data Analysis:** Applied statistical methods and machine learning algorithms to uncover patterns and relationships.
4.  **Data Visualization:** Used libraries like Matplotlib and Seaborn to create informative visual representations of the findings.
5.  **Interpretation & Insights:** Drew actionable conclusions from the visualized data to address the project's objectives.


## Technology Stack

* **Programming Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (KMeans, StandardScaler, PCA), UMAP
* **Web Scraping:** Scholarly


## Project Documentation

For a complete overview of our research, methodology, and detailed findings, please refer to our full project report.

**[Link to Full Project Document]** <--- *https://drive.google.com/file/d/10U3n0WAAXAC1X-rtn0tI8n6AyAS3GNVB/view?usp=share_link*


## Team

This project was a collaborative effort by:

* Harshvir Mangla
* Luson Basumatary
* Manjushwar Khairkar
* Kartik Kaushal
* Ateekurrahman

Under the guidance of **Dr. Banalaxmi Brahma**.


## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have Python and pip installed on your system.

### Installation

1.  Clone the repo
    ```sh
    git clone [https://github.com/your_username/your_repository_name.git](https://github.com/your_username/your_repository_name.git)
    ```
2.  Navigate to the project directory
    ```sh
    cd your_repository_name
    ```
3.  Install the required packages
    ```sh
    pip install -r requirements.txt
    ```
    *(You may need to create a `requirements.txt` file)*

### Usage

Run the main analysis script to reproduce the results:
```sh
python main_analysis.py
```

---

## Conclusion

This project successfully provides a comprehensive, data-driven overview of the research landscape within the NITJ CSE department. The insights generated can be instrumental for strategic planning, fostering collaboration, and enhancing the department's overall research impact. Future work could involve expanding this analysis to other departments or creating a real-time interactive dashboard.
