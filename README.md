# Electric Vehicle Sentiment Analysis Project

## Project Overview

This repository explores public perceptions and sentiments toward electric vehicles (EVs) in the digital age. As the world shifts toward sustainable transportation, understanding how people truly feel about EVs, beyond headlines and policy debates, is crucial. This project dives into diverse internet data sources to capture genuine public discourse, comparing them with traditional media perspectives.

## What We're Investigating

The core question: **How accurately can Large Language Models (LLMs) capture public sentiment on electric vehicles, and how does online discourse differ from established media narratives?**

We collected data from multiple sources:
- **Reddit**: Real conversations from EV enthusiasts, skeptics, and curious consumers
- **The New York Times**: Professional journalism representing mainstream media perspectives
- **LLM Analysis**: Using Groq (an advanced LLM) to interpret and categorize sentiments

This multi-source approach lets us compare grassroots online opinions with curated media coverage, revealing patterns in how EVs are perceived across different platforms.

## Repository Structure

The project is organized into clear sections:

### 📁 Electronic_Vehicle_Sentiment/
Main project directory containing all analysis components:

#### WebScrapping/
Data collection scripts and outputs:
- **LLM/**: Large Language Model processing pipeline
  - `LLMSentiment.ipynb`: Jupyter notebook for LLM-based sentiment extraction
  - `LLM_cleaning.html` & `.qmd`: Data cleaning workflow and reports
  - `LLM_model.csv`: Raw LLM sentiment predictions
  - `cleaned_llm.csv`: Processed sentiment data
  - `filtered_LLM_model.csv`: Refined dataset for analysis
  - `sentimentLLM.csv`: Final sentiment classifications

- **NYT/**: New York Times data scraping and processing
  - Contains scripts for extracting EV-related articles
  - Structured data from professional journalism sources

- **Reddit/**: Reddit data collection
  - Community discussions and comments extraction
  - Authentic user perspectives on EVs

#### Statistical Test/
Rigorous statistical analysis comparing sentiment across sources

#### Visualizations/
Charts, graphs, and visual comparisons of findings

#### WorkableData/
Cleaned, consolidated datasets ready for analysis

### 📄 EVSentimentAnalysisProjectPaper.pdf
Comprehensive research paper documenting:
- Methodology and research design
- Data collection strategies
- LLM performance evaluation
- Key findings and insights
- Comparative analysis across data sources

## Key Technologies

- **Python**: Core programming language for data processing
- **Jupyter Notebooks**: Interactive analysis and documentation (22.9% of codebase)
- **HTML/JavaScript**: Web scraping and visualization (44.3% + 31.5%)
- **R**: Statistical testing and analysis (1.3%)
- **Groq LLM**: Advanced sentiment analysis
- **Reddit API & NYT API**: Data collection tools

## Research Methodology

1. **Data Collection**: Scraped Reddit discussions and NYT articles about EVs
2. **LLM Processing**: Used Groq to analyze sentiment in collected text
3. **Cleaning & Filtering**: Removed noise, standardized formats
4. **Statistical Analysis**: Compared sentiment distributions across sources
5. **Visualization**: Created interpretable charts of findings
6. **Validation**: Assessed LLM accuracy against human-labeled samples

## What Makes This Interesting

- **Multi-Source Comparison**: See how Reddit users vs. NYT journalists frame EV discussions
- **LLM Capabilities**: Evaluate cutting-edge AI in real-world sentiment analysis
- **Temporal Insights**: Track how EV sentiment evolves over time
- **Practical Applications**: Findings can inform policy, marketing, and public communication strategies

## Usage Notes

This project was developed as part of **SURV727** (Survey Research Methods) coursework, demonstrating applied data science techniques in social research. The code and notebooks are designed to be reproducible—you can explore the analysis pipeline, modify parameters, or apply similar methods to other topics.

### Running the Analysis

1. Navigate to `Electronic_Vehicle_Sentiment/WebScrapping/LLM/`
2. Open `LLMSentiment.ipynb` in Jupyter
3. Follow the documented workflow for data processing
4. Check visualization outputs in the `/Visualizations` folder

## Authors & Credits

**Sagnik Chakravarty** (sagnikch@umd.edu)  
**Namit Shrivastava** (namit507@umd.edu)  
University of Maryland, College Park

*Completed: December 2024*

## Academic Context

This work aligns with AAPOR (American Association for Public Opinion Research) standards for survey methodology and data transparency. It bridges computational methods (LLMs, web scraping) with social science research questions about public opinion formation.

---

**For detailed findings and methodology, see the full research paper: `EVSentimentAnalysisProjectPaper.pdf`**

*Keywords: Electric Vehicles (EVs), Public Sentiment, Large Language Models (LLMs), Groq, Sentiment Analysis, Reddit, The New York Times, Internet Data Sources, Comparative Analysis*
