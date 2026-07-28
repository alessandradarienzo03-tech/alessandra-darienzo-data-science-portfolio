{\rtf1\ansi\ansicpg1252\cocoartf2870
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Predictive Financial & ESG Analytics for Private Companies\
\
An end-to-end machine learning framework for forecasting financial and\
sustainability performance across private companies in Campania, Italy.\
\
## Overview\
\
This project investigates whether historical financial and ESG information\
can be used to forecast private-company performance and identify firms\
combining economic strength with sustainability potential.\
\
The analysis was developed as part of the Campania Predictive Challenge at\
the University of Naples Federico II.\
\
## Project Highlights\
\
- Processed an initial dataset of 12,422 private companies and 117 features.\
- Built a final modelling dataset containing 7,660 companies.\
- Forecast Sales Revenue, EBITDA, Net Income and ESG performance.\
- Benchmarked Linear Regression, Random Forest, XGBoost, Prophet and LSTM.\
- Selected Random Forest as the best-performing model with an MSE of 0.00285.\
- Evaluated model reliability across firm size, province and macro-sector.\
- Developed an LLM-assisted web-search workflow to recover missing geographic information.\
- Designed an Economic\'96Sustainability Positioning Matrix for decision support.\
\
## Business Question\
\
Can historical financial and ESG data help anticipate company performance\
and identify firms with both economic and sustainability potential?\
\
## Machine Learning Pipeline\
\
1. Data-quality assessment\
2. Financial plausibility checks\
3. Missing-value treatment\
4. Outlier management\
5. Business-driven company segmentation\
6. Feature scaling\
7. Model benchmarking\
8. Financial and ESG forecasting\
9. Cluster-level model evaluation\
10. Decision-oriented visualization\
\
## Models\
\
| Model | MSE |\
|---|---:|\
| Random Forest | **0.00285** |\
| LSTM | 0.00287 |\
| XGBoost | 0.00292 |\
| Linear Regression | 0.00299 |\
| Prophet | 0.00392 |\
\
## Technology Stack\
\
- Python\
- Pandas\
- NumPy\
- Scikit-learn\
- XGBoost\
- Keras\
- Prophet\
- LangChain\
- LangGraph\
- Groq\
- Llama 3.1\
\
## Repository Structure\
\
```text\
campania-financial-esg-forecasting/\
\uc0\u9500 \u9472 \u9472  notebooks/\
\uc0\u9500 \u9472 \u9472  src/\
\uc0\u9500 \u9472 \u9472  results/\
\uc0\u9474    \u9500 \u9472 \u9472  figures/\
\uc0\u9474    \u9492 \u9472 \u9472  tables/\
\uc0\u9500 \u9472 \u9472  paper/\
\uc0\u9500 \u9472 \u9472  data/\
\uc0\u9474    \u9492 \u9472 \u9472  sample/\
\uc0\u9492 \u9472 \u9472  tests/}