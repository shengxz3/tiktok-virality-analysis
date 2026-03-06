# TikTok Virality Analysis

This project analyzes factors associated with **TikTok video virality** using exploratory data analysis, natural language processing, machine learning, and causal inference.

## Dataset

The dataset contains ~19,000 TikTok videos with information on:

- engagement metrics (views, likes, comments, shares)
- creator status signals
- video transcription text
- content classification (claim vs opinion)

From these variables, engagement metrics such as **engagement rate, comment rate, and share rate** were constructed.

## Methods

The analysis combines several approaches:

- **Exploratory Data Analysis (EDA)** to understand engagement patterns  
- **Statistical testing (t-test)** to compare claim vs opinion videos  
- **NLP analysis** (sentiment and TF-IDF) to examine textual characteristics  
- **Random Forest modeling** to identify predictive signals of viral videos  
- **Propensity Score Matching (PSM)** to estimate the effect of claim-based content on share rates

## Key Findings

- Claim-based content tends to generate **higher discussion and sharing behavior**.
- Certain linguistic patterns appear more frequently in highly shared videos.
- Content framing and textual tone may influence how audiences interact with videos.

## Tools

Python, Pandas, Scikit-learn, Seaborn, TextBlob
