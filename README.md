# AI vs Human Econometric Analysis

## Overview
This project evaluates the reliability gap between AI-generated and human-performed econometric analysis using real-world economic data.

The study compares outputs from AI models (ChatGPT, Claude, and an agentic framework) against a traditional Python-based econometric pipeline.

---

## Dataset
- **Source:** Ghana Economic Growth Data (1975–2014)
- **File:** `data/WDI_Ghana_data.csv`

---

## Methodology
- Implemented econometric modeling using Python
- Applied ARDL-based analysis on economic indicators
- Provided identical analytical tasks to AI systems
- Compared outputs using structured evaluation criteria

---

## Evaluation Criteria
- Accuracy  
- Methodology  
- Efficiency  
- Insight  
- Consistency  

---

## Project Structure
project/
├── notebooks/ # Jupyter notebooks for analysis
├── data/ # Dataset
├── results/ # Outputs (plots, logs, summaries)
├── docs/ # Reference papers
└── README.md


---

## Results
- Human-driven analysis showed higher consistency and methodological accuracy  
- AI models produced variable results depending on prompt structure  
- Agentic workflows improved performance but still showed limitations  

---

## Conclusion
This project highlights the importance of domain expertise in econometric analysis and identifies key reliability gaps in AI-generated outputs.

---

## Security Note
API keys are not included in this repository.  
Environment variables are used to securely manage credentials.

---

## Requirements
- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- statsmodels  
- openai  

---

## How to Run
1. Clone the repository  
2. Create a `.env` file and add your API key: OPENROUTER_API_KEY=your_api_key_here
3. Install dependencies: pip install -r requirements.txt
4. 4. Run the notebooks in the `notebooks/` folder  

---

## Author
Supritha Nallavolu
