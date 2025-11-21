# Week-1-Predicting-Price-Moves-with-News-Sentiment
KIAM 8: Week 1 Challenge Repo

📊 Data Analysis & Quantitative Finance Project

A structured repository for completing analytical tasks involving Git/GitHub workflows, EDA, and Quantitative Finance using PyNance & TA-Lib.
This project demonstrates version control discipline, environment setup, data analysis, and technical financial modeling.

            📁 Repository Structure
            ├── .vscode/
            │   └── settings.json
            ├── .github/
            │   └── workflows/
            │       └── unittests.yml
            ├── .gitignore
            ├── requirements.txt
            ├── README.md
            ├── src/
            │   ├── __init__.py
            ├── notebooks/
            │   ├── __init__.py
            │   └── README.md
            ├── tests/
            │   ├── __init__.py
            └── scripts/
                ├── __init__.py
                └── README.md


This structure supports clean development, modular Python code, reproducible notebooks, testing, and CI/CD.

🧠 Task 1 — Git, GitHub & Exploratory Data Analysis (EDA)
🔧 Objectives

        Set up a Python development environment

        Implement Git version control using branching and structured commits

        Configure CI/CD using GitHub Actions

        Perform EDA on the dataset using descriptive, textual, temporal, and publisher-based analysis

        ✅ Minimum Essential Tasks (Task 1)
        1. Git & GitHub Workflow

        Create a GitHub repository for the week

        Create a working branch: task-1

        Commit at least three times per day, using descriptive commit messages

        Maintain clean branching and PR reviews

        2. Exploratory Data Analysis Requirements
        Descriptive Statistics

        Compute statistics such as:

        Headline length distributions

        Number of articles per publisher

        Publication date patterns over days or events

        Text Analysis (Topic Modeling / NLP)

        Identify:

        Top recurring keywords

        Common phrases

        High-level topics (e.g., market events, corporate actions, approvals)

        Time Series Analysis

        Evaluate:

        Publication frequency trends

        Spikes related to market-moving events

        Publishing time-of-day patterns

        Publisher Analysis

        Determine:

        Most active publishers

        Publisher-specific themes

        Domain-level insights if email-based publisher names exist

        📊 KPIs for Task 1

        Successful Python environment setup

        Correct and structured Git usage

        Functional CI/CD pipeline

        Clarity and depth of EDA insights

📈 Task 2 — Quantitative Finance Analysis with PyNance & TA-Lib
🔧 Objectives

        Load and prepare financial datasets

        Compute technical indicators

        Visualize financial metrics

        Apply quantitative analysis methods to support decision-making

        ✅ Minimum Essential Tasks (Task 2)
        1. Git Workflow

        Merge task-1 into main using a Pull Request

        Create a new branch named task-2

        Commit work with descriptive messages

        2. Prepare Financial Data

        Load stock price data into pandas

        Ensure the dataset includes:

        Open, High, Low, Close, Volume

        3. Apply TA-Lib Indicators

        Compute key indicators such as:

        Moving Averages (SMA, EMA)

        RSI

        MACD

        Bollinger Bands

        ADX, ATR, etc.

        4. Use PyNance for Advanced Metrics

        Daily/weekly/monthly returns

        Volatility

        Risk-adjusted indicators

        Drawdowns

        5. Visualize Financial Metrics

        Visualize:

        Price curves

        Indicator overlays

        Volume changes

        Indicator divergences

        📊 KPIs for Task 2

        Accurate computation of financial indicators

        Completeness of visualization and analysis

        Demonstrated self-learning through references and external sources

⚙️ Installation & Setup

        1. Clone the Repository
        git clone https://github.com/GrimVad3r/Predicting-Price-Moves-with-News-Sentiment-Week-1.git
        cd Predicting-Price-Moves-with-News-Sentiment-Week-1

        2. Create a Virtual Environment
        python -m venv venv
        source venv/bin/activate       # macOS/Linux
        venv\Scripts\activate          # Windows

        3. Install Dependencies
        pip install -r requirements.txt

🧪 Running Tests

        Tests run automatically via GitHub Actions, but can be run locally:

        pytest

        🔄 CI/CD — GitHub Actions

        A workflow for automated testing is configured in:

        .github/workflows/unittests.yml


        Every push triggers:

            Code validation

            Unit tests

            Branch protection checks
