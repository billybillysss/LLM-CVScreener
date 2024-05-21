# 🚀 LLM-CVScreener

LLM-CVScreener is a demonstration project that showcases how large language models (LLM) can be used to streamline the HR recruitment process. This tool helps HR professionals efficiently screen and find the best-fit candidates from a large pool of applicants by leveraging the power of LangChain to load and analyze CVs against job descriptions (JDs). It provides a summary of the screening process, highlighting the most suitable candidates.

## ✨ Features

- **🤖 Automated CV Screening:** Uses LangChain and a local LLaMA instance to process and evaluate CVs based on the given job description.
- **🔍 Best Match Identification:** Finds and ranks the best-fit candidates according to the job requirements.
- **📄 Summary Report:** Generates a summary report of the screening process, providing insights into the candidate matches.

## 🛠️ How It Works

1. **📂 Load CVs:** The program loads a batch of CVs using LangChain.
2. **📝 Match with JD:** Each CV is analyzed and matched against the job description to find the best fit.
3. **🗂️ Generate Summary:** A summary report is generated, highlighting the top candidates and their suitability for the job.


## 📚 Usage

The program is written in a Jupyter notebook to allow for easy monitoring and interaction with the results. 

1. **🔧 Prepare your CVs and Job Description:**
    - Place your CV files in the `data/cv` directory.
    - Create a job description file and place it in the `data/jd` directory.

2. **🚀 Run the notebook:**
    - Open the Jupyter notebook `LLM_CVScreener.ipynb` and run the cells to load the CVs, match them with the job description, and generate the summary report.


## Directory
```
LLM-CVScreener/
├── data/
│   ├── cv/
│   │   ├── cv1.pdf
│   │   ├── cv2.pdf
│   │   └── ...
│   └── jd/
│       └── job_description.txt
|
└── LLM_CVScreener.ipynb
```

## Example Output


```
Based on the provided CVs and JD, I've highlighted the relevant experience, certificate, or education that match with the responsibilities mentioned in the JD:

CV 1: Sarah Miller

    Experience:
        Analyzed market trends and customer behavior to inform marketing strategies (matches with "Conduct research and support internal/external groups with the selection and implementation of applications and database management tools.")
        Created interactive dashboards and visualizations to present data insights (matches with "Design and automate routine and self-service reporting solutions (i.e., Power BI).")
    Education:
        Bachelor of Science in Statistics (relevant to the statistical analysis mentioned in the JD)

CV 2: Daniel Williams

    Experience:
        Designed and implemented scalable data pipelines on AWS (matches with "Identify and utilize database management systems to aggregate and analyze data.")
        Optimized ETL workflows for better performance (matches with "Write scripts to support automation, data extraction, and reporting.")

CV 3: Sophia Kim

    Experience:
        Developed machine learning models to predict customer churn (matches with "Perform ad-hoc data extraction, analysis, and interpretation.")
        Created visualizations to present data insights to stakeholders (matches with "Design and automate routine and self-service reporting solutions (i.e., Power BI).")
    Education:
        Bachelor of Science in Statistics (relevant to the statistical analysis mentioned in the JD)
    Certification:
        Certified Data Scientist (CDS) - Data Science Council of America (not directly relevant, but shows expertise in data science)

No direct match for all responsibilities was found in any of the CVs. However, some experience and education may be relevant to certain responsibilities mentioned in the JD.```