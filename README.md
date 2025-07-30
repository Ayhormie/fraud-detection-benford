{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Fraud Detection Using Machine Learning\
\
This project builds a fraud detection model using Python, with Random Forest and XGBoost. It handles imbalanced data using ADASYN and optimizes for high recall to detect fraudulent transactions.\
\
## Dataset\
- Source: [Kaggle Fraud Detection Dataset]([{\field{\*\fldinst{HYPERLINK "https://www.kaggle.com/code/tanvivishwanath/mobile-fraud-transactions?select=PS_20174392719_1491204439457_log.csv"}}{\fldrslt https://www.kaggle.com/code/tanvivishwanath/mobile-fraud-transactions?select=PS_20174392719_1491204439457_log.csv}}])\
- Description: ~10,000 rows, numerical and categorical features, highly imbalanced (fraud/non-fraud).\
- Download the dataset and place `fraud_data.csv` in a `data/` folder.\
\
## Installation\
```bash\
pip install -r requirements.txt}