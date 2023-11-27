# Sigma Investing's WGHS Source Codes

## Project Overview

Sigma Investing is a team that focuses on providing efficient investment solutions using modern decision-making techniques. This repository contains the source code for our investment report (for our client Hilary Ash).

## Required Middleware

1. **Python 3.8** or higher - The TOPSIS implementation is built using Python language. Please ensure to install the appropriate version: https://www.python.org/downloads/
2. **Pandas** - A powerful data manipulation library in Python that makes it easy to work with structured data like CSV, Excel, and SQL databases: `pip install pandas`
3. **Numpy** - A fundamental library for mathematical operations and support for arrays and matrices: `pip install numpy`

## Directory Structure
Sigma_Investing_Sourcecodes/ \n
├── TOPSIS/ \n
│   ├── TOPSIS.py \n
│   └── TOPSIS_Results.html \n
├── ETF_Selection/ \n
│   ├── ETF.csv \n
│   └── scoreCalculation.py \n
├── Industry Selection/ \n
│   └── select.py \n
├── Sector Selection/ \n
│   ├── Long_term.py \n
│   ├── Short_term.py \n
│   └── bi-directional.py \n
├── LICENSE/ \n
└── README.md \n

## Setup and Usage

1. Clone the repository to your local machine:
`git clone https://github.com/LQ458/Sigma_Investing_Sourcecodes.git`


2. Navigate to the source code directory(projects):
example: `cd Sigma_Investing_Sourcecodes/projects`


3. Make sure Python3 and the required middleware have been installed.

4. Execute the main Python script:
`python project.py`

5. The output will be generated, showing the ranking of investment alternatives based on the TOPSIS method. Evaluate the results and make informed investment decisions accordingly.

## Support

For any queries or concerns related to the project, please contact the Sigma Investing team at: guangyu.chen40730-biph@basischina.com or yihao.qin17311-biph@basischina.com

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
