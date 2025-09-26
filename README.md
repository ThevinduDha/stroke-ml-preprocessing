Stroke ML Preprocessing — README

Project: ML Preprocessing & EDA for stroke dataset
Goal: Each group member implements one preprocessing task + visualization. Outputs are saved to data/processed/ and combined in a group pipeline.
Dataset used: healthcare-dataset-stroke-data.csv

Team & Responsibilities

Member 1: Missing Data Handling + Label Encoding — notebooks/member1_missing_labelencoding.ipynb

Member 2: One-Hot Encoding (1/0 table proof) — notebooks/member2_onehot_encoding.ipynb

Member 3: Outlier Detection & Removal (IQR) — notebooks/member3_outlier_removal.ipynb

Member 4: Feature Scaling / Normalization — notebooks/member4_scaling.ipynb

Member 5: Feature Engineering & Selection (engineered features + SelectKBest) — notebooks/member5_feature_engineering.ipynb

Member 6: Dimensionality Reduction (PCA) + PCA scatter — notebooks/member6_pca.ipynb

Group pipeline: Combine steps → notebooks/group_pipeline.ipynb

(Replace notebook filenames with your exact filenames if they differ.)






stroke-ml-preprocessing/
│
├── data/
│   ├── raw/                 # put original CSV here (readonly)
│   │   └── healthcare-dataset-stroke-data.csv
│   └── processed/           # each member saves their output here
│       ├── member1_missing_labelencoded.csv
│       ├── member2_onehot.csv
│       ├── member3_outliers_removed.csv
│       ├── member4_scaled_standard.csv
│       ├── member5_features.csv
│       ├── member6_pca2.csv
│       └── group_final_processed.csv/.xlsx
│
├── notebooks/
│   ├── member1_missing_labelencoding.ipynb
│   ├── member2_onehot_encoding.ipynb
│   ├── member3_outlier_removal.ipynb
│   ├── member4_scaling.ipynb
│   ├── member5_feature_engineering.ipynb
│   ├── member6_pca.ipynb
│   └── group_pipeline.ipynb
│
├── plots/                   # saved high-quality figures (png)
├── README.md
├── requirements.txt
└── .gitignore
