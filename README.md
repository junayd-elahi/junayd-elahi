# Hi, I'm Junayd 👋

I'm a data analyst in London. I build data pipelines and machine learning projects, mostly with healthcare data.

I care about clean data, work other people can rerun, and being honest about what a model can and can't do. Some of my favourite results are the ones that didn't go to plan, like a model that stopped beating the baseline once I fixed a data leak.

- **Now:** Data Analyst at Coldwell Banker, where I own the team's data workflows and automation
- **Studied:** BSc Computer Science (AI), University of Greenwich, 2:1
- **Looking for:** Data Engineering, Data Science and ML roles in London. Healthcare is a bonus.

[![Portfolio](https://img.shields.io/badge/Portfolio-junaydelahi.dev-111827?style=for-the-badge&logo=googlechrome&logoColor=white)](https://junaydelahi.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/junayd-elahi-2029b9213/)
[![Email](https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:Junaydelahi@outlook.com)

## Selected projects

**[NHS Antibiotic Prescribing Outliers](https://github.com/junayd-elahi/nhs-antibiotic-prescribing)** · Python, DuckDB, SQL\
A pipeline over two years of public NHS prescribing data that finds GP practices prescribing antibiotics far above the national rate, adjusted for seasonality. 40 practices stayed above 1.5× the national rate in all 24 months.

**[Healthcare ELT Pipeline](https://github.com/junayd-elahi/Healthcare-ELT)** · dbt, Snowflake, Airflow, Docker\
~160K rows of synthetic patient data loaded into Snowflake and modelled with dbt into a star schema. 39 data-quality tests gate every build, with CI on every pull request and Airflow orchestration in Docker.

**[Keystroke Dynamics for Parkinson's](https://github.com/junayd-elahi/parkinsons-typing-biomarker)** · scikit-learn, XGBoost (final-year project)\
Tests whether typing rhythm separates Parkinson's patients from controls once data leakage is removed with subject-wise nested cross-validation. Shows that earlier results on this dataset don't hold up under leakage-resistant evaluation.

**[Pneumonia Detection from Chest X-Rays](https://github.com/junayd-elahi/pneumonia-detection-cnn)** · PyTorch\
A CNN that classifies chest X-rays as normal or pneumonia, benchmarked against logistic regression. 0.98 recall on the test set, with the false-positive tradeoff and overfitting analysed.

**[Sensor Streaming Backend](https://github.com/junayd-elahi/teton-streaming)** · Go, PostgreSQL, Docker\
A service for room sensors that ingests events, tracks device health and occupancy, and publishes fall alarms that consumers can resume after a disconnect.

**[Cell Coverage Estimation](https://github.com/junayd-elahi/Cell-Coverage)** · Python, image analysis\
Estimates how much of a fluorescence microscopy image is covered by cells using Otsu thresholding, checked against expert reference masks (19.7 pp mean error).

More write-ups are on [junaydelahi.dev](https://junaydelahi.dev).

## Toolkit

**Data engineering:** dbt · Snowflake · DuckDB · Airflow · Docker · Kubernetes · GitHub Actions · AWS · Cloudflare Workers\
**Languages and analysis:** Python · SQL · Go · R · Pandas · NumPy · PostgreSQL · Power BI\
**Machine learning:** scikit-learn · XGBoost · PyTorch · TensorFlow · computer vision
