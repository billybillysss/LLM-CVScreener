
# LLM-CVScreener

LLM-CVScreener is a demonstration project that showcases how large language models (LLM) can be used to streamline the HR recruitment process. This tool helps HR professionals efficiently screen and find the best-fit candidates from a large pool of applicants by leveraging the power of LangChain to load and analyze CVs against job descriptions (JDs). It provides a summary of the screening process, highlighting the most suitable candidates.

## Features

- **Automated CV Screening:** Uses LangChain to process and evaluate CVs based on the given job description.
- **Best Match Identification:** Finds and ranks the best-fit candidates according to the job requirements.
- **Summary Report:** Generates a summary report of the screening process, providing insights into the candidate matches.

## How It Works

1. **Load CVs:** The program loads a batch of CVs using LangChain.
2. **Match with JD:** Each CV is analyzed and matched against the job description to find the best fit.
3. **Generate Summary:** A summary report is generated, highlighting the top candidates and their suitability for the job.

## Usage

The program is written in a Jupyter notebook to allow for easy monitoring and interaction with the results. 

1. **Prepare your CVs and Job Description:**
    - Place your CV files in the `data/cv` directory.
    - Create a job description file and place it in the `data/jd` directory.

2. **Run the notebook:**
    - Open the Jupyter notebook `LLM_CVScreener.ipynb` and run the cells to load the CVs, match them with the job description, and generate the summary report.

## Example

Here is an example of how to set up your directories:

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



