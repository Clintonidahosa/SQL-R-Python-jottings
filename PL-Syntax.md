
---

## 1. Dataset Importation

### SQL
- `LOAD DATA INFILE`: Load data from a file into a table.
- `INSERT INTO`: Insert data into a table.
- `SELECT`: Retrieve data from a table.

### Python (Pandas)
- `pd.read_csv()`: Import CSV files.
- `pd.read_excel()`: Import Excel files.
- `pd.read_sql()`: Import data from SQL database.

### R
- `read.csv()`: Import CSV files.
- `read_excel()`: Import Excel files (from `readxl` package).
- `dbReadTable()`: Import data from SQL databases (from `DBI` package).

---

## 2. Dataset Cleaning

### SQL
- `UPDATE`: Modify existing records in a table.
- `DELETE`: Remove records.
- `ALTER TABLE`: Modify table structure.
- `IS NULL`: Check for NULL values.
- `TRIM()`, `REPLACE()`: String manipulation.

### Python (Pandas)
- `df.dropna()`: Remove missing data.
- `df.fillna()`: Fill missing values.
- `df.drop()`: Drop rows or columns.
- `df.duplicated()`, `df.drop_duplicates()`: Detect and remove duplicates.
- `df.replace()`: Replace specific values.

### R
- `na.omit()`: Remove missing data.
- `is.na()`: Identify missing values.
- `replace()`: Replace values.
- `duplicated()`, `unique()`: Handle duplicates.

---

## 3. Exploratory Data Analysis (EDA)

### SQL
- `GROUP BY`: Group data.
- `ORDER BY`: Sort data.
- `COUNT()`, `AVG()`, `SUM()`, `MIN()`, `MAX()`: Aggregate functions.
- `JOIN`: Combine tables.

### Python (Pandas & NumPy)
- `df.describe()`: Get summary statistics.
- `df.groupby()`: Group data.
- `df.corr()`: Correlation matrix.
- `np.mean()`, `np.median()`, `np.std()`, `np.var()`: Statistical functions.

### R
- `summary()`: Summary statistics.
- `aggregate()`: Group data.
- `cor()`: Correlation matrix.
- `mean()`, `median()`, `var()`, `sd()`: Statistical functions.

---

## 4. Data Visualization

### SQL
- SQL itself doesn’t directly support visualization but can export data for visualization tools like Power BI, Tableau.

### Python (Matplotlib, Seaborn, Plotly)
- `plt.plot()`, `plt.scatter()`, `plt.bar()`: Line, scatter, and bar plots (`matplotlib`).
- `sns.heatmap()`, `sns.boxplot()`, `sns.pairplot()`: Heatmaps, boxplots, pair plots (`seaborn`).
- `px.line()`, `px.scatter()`: Interactive plots (`plotly`).

### R (ggplot2)
- `ggplot()`: Create a plot object.
- `geom_line()`, `geom_point()`, `geom_bar()`: Line, scatter, and bar plots.
- `facet_wrap()`, `facet_grid()`: Multi-panel plots.
- `heatmap()`: Heatmap visualization.

---

## 5. Data Transformation & Manipulation

### SQL
- `CASE`: Conditional expressions.
- `COALESCE`: Return first non-null value.
- `CAST()`, `CONVERT()`: Convert data types.

### Python (Pandas)
- `df.apply()`: Apply function to data.
- `df.pivot()`, `df.melt()`: Reshape data.
- `df.merge()`, `df.join()`: Combine data frames.

### R
- `mutate()`, `transmute()`: Create/modify columns (`dplyr`).
- `gather()`, `spread()`: Reshape data (`tidyr`).
- `merge()`, `cbind()`, `rbind()`: Combine datasets.

---

## 6. Machine Learning & Predictive Modeling

### SQL
- SQL doesn’t have built-in ML, but data can be prepared for ML tools (e.g., Python, R).
- Use platforms like BigQuery ML for running models directly in SQL.

### Python (Scikit-learn)
- `train_test_split()`: Split dataset into train and test sets.
- `StandardScaler()`, `MinMaxScaler()`: Data normalization.
- `LinearRegression()`, `RandomForestClassifier()`, `KNeighborsClassifier()`: ML models.
- `model.fit()`, `model.predict()`: Train and predict.
- `cross_val_score()`: Cross-validation.

### R (caret, randomForest)
- `train()`: Train a model (`caret` package).
- `predict()`: Make predictions.
- `randomForest()`: Random forest classifier.
- `lm()`: Linear regression.
- `kmeans()`: K-means clustering.

---

## 7. Database Management

### SQL
- `CREATE DATABASE`: Create a new database.
- `CREATE TABLE`: Create a new table.
- `DROP DATABASE`, `DROP TABLE`: Remove database or table.
- `ALTER TABLE`: Modify table.
- `GRANT`, `REVOKE`: Manage user permissions.

### Python (SQLAlchemy)
- `create_engine()`: Connect to a database.
- `execute()`: Run SQL commands.
- `session.add()`, `session.commit()`: Add and commit changes to the database.

### R (DBI, RSQLite)
- `dbConnect()`: Connect to a database.
- `dbWriteTable()`: Write a data frame to a database.
- `dbSendQuery()`: Run SQL commands.

---

