# Kaggle Notebook

**Handling Missing Values**

**Techniques**<br>
1. Droping row using df.dropna(axis=0)
2. Droping column using df.dropna(axis=1)
3. Filling null values if it is numerical values df["Age"] = df["Age"].fillna(df["Age"].mean) or df["Age"] = df["Age"].fillna(df["Age"].median) for categorial data df["Name"] = df["Name"].fillna(df["Name"].mode)
4. Forward and Backward filing Imputation using bfill() or ffill() df["Age"] = df["Age"].ffill() or df["Age"] = df["Age"].bfill()
