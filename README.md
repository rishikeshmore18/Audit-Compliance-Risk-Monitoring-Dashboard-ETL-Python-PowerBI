# Audit-Compliance-Risk-Monitoring-Dashboard-ETL-Python-PowerBI
An analytics pipeline for fraud detection, compliance (SOX/GDPR), transactional risk visualization, and audit-tailored insights.

Author: Rishikesh More

# 🧠 Why This Project Matters
This project exemplifies a comprehensive analytics solution that mirrors real-world enterprise needs—spanning data engineering, risk intelligence, compliance analytics, and interactive reporting. It's built to support internal audit, enterprise risk, and compliance teams with actionable, real-time insights and anomaly alerts.

# 🔍 Project Summary
A full-scale analytics pipeline that automates financial fraud detection, flags compliance violations (SOX/GDPR), and visualizes transactional risk using advanced Power BI dashboards. The system processes raw financial records, applies machine learning for anomaly detection, and delivers visually compelling insights tailored for audit and risk professionals.

# 🚀 Key Features
🔄 ETL Pipeline: Extracts, transforms, and loads financial data using Python (Pandas, NumPy, SQLAlchemy) and SQL.

⚠️ Anomaly Detection: Leverages Isolation Forest to detect suspicious/high-risk transactions.

✅ Compliance Checks: Applies regulatory logic to flag SOX and GDPR violations.

📈 Interactive Dashboards: Power BI dashboards designed with DAX to show:

Transaction distribution by region & type (Credit, Debit, Transfer)

Risk score and compliance status per transaction

Trends in high-risk activity over time

Breakdown of compliance issues (Compliant, SOX Violation, Fraud Alert)

🔁 Automation Ready: Built to support scheduling via Task Scheduler (Windows) or Cron Jobs (Linux) for automated refreshes.

# 📊 Sample Dashboard Preview

<img width="720" alt="Screenshot 2025-04-14 204754" src="https://github.com/user-attachments/assets/11d31ddc-ba72-4fea-be0e-34277eee9254" />


# 💻 Technical Skills Demonstrated
✅ Python & SQL for structured data processing
✅ Machine Learning (Isolation Forest) for anomaly detection
✅ Power BI for interactive dashboards and dynamic visuals
✅ Regulatory Knowledge of frameworks like SOX and GDPR
✅ ETL Best Practices for clean and reproducible pipelines
✅ Automation Skills via OS-level job scheduling

# 📂 Repository Structure
File/Notebook	Description
etl_pipeline.ipynb	Full Jupyter Notebook for ETL logic
financial_transactions.csv	Raw transactional dataset
processed_financial_transactions.csv	Cleaned and structured data
financial_trans.pbix	Power BI dashboard file
README.md	This project documentation

# ⚙️ How to Run
Clone the repository
git clone https://github.com/[your-username]/Automated-Audit-Compliance-Risk-Assessment.git
cd Automated-Audit-Compliance-Risk-Assessment
Install dependencies
pip install pandas numpy sqlalchemy scikit-learn
Run ETL Notebook
jupyter notebook etl_pipeline.ipynb
Open the Power BI file Use financial_trans.pbix in Power BI Desktop to explore the live dashboard.
 
# About the Creator
👋 I'm Rishikesh More, a data analytics enthusiast passionate about turning raw data into strategic intelligence. This project reflects my commitment to building scalable, compliance-ready, and impactful analytics tools.

GitHub: github.com/rishikeshmore18

LinkedIn: www.linkedin.com/in/more-rishikesh-p07
