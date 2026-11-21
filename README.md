### Hey, I'm Begüm

I'm a third-year Data Science & Analytics student at Manisa Celal Bayar University. Alongside classes I work part-time at the university's Project Coordination Center, where I help run TÜBİTAK, TEKNOFEST and Erasmus+ projects and turn the project data into reports with Python, R and Power BI.

The project I'm proudest of so far is KAPAN. Four of us built an anti-money-laundering platform that looks for rented ("money mule") bank accounts, and in October 2026 we came second in Türkiye at the TEKNOFEST Financial Technologies Competition. I was the team captain.

#### Things I've built

**KAPAN** (private, TEKNOFEST 2026, 2nd place)<br>
Scores every transaction in real time using the last 24 hours of account activity, looks at how accounts are connected to each other, and uses SHAP so an analyst can see why something was flagged. Built with XGBoost, NetworkX, FastAPI, PostgreSQL, Redis, React and Docker. The code stays private because of the competition, but I'm happy to show a demo.

**[Turkish tweet sentiment](https://github.com/beguumcetin/x-sentiment-analysis)**<br>
My summer 2026 internship project at the Istanbul Chamber of Commerce (İTO). I hand-labelled a gold set, compared three Turkish BERT models and fine-tuned the best one with LoRA. Accuracy went from 61.5% to 81%, and the neutral tweets were the hardest part.

**[Weekly economy bulletin](https://github.com/beguumcetin/weekly-bulletin-generator)**<br>
Also from İTO. It pulls exchange rates, gold prices and inflation from the Central Bank's EVDS API, stores them in Supabase and has Gemini write a neutral weekly bulletin, so anyone in the office can make one without touching code.

**[Coffee shop decision support](https://github.com/beguumcetin/Kafe-Karar-Destek-Sistemi)**<br>
A Streamlit app for a small café: sales forecasts, customer segments, unusual days in the data and a simulator for "what happens if we run this discount?"

**[Olist e-commerce analysis](https://github.com/beguumcetin/olist-ecommerce-analytics)** ([live dashboard](https://beguumcetin.github.io/olist-ecommerce-analytics/))<br>
A SQL-first analysis of 99,000 orders from a Brazilian marketplace, run in DuckDB. 97% of customers order only once, and a late delivery costs about 1.5 review points even after holding the product, the state and the order size fixed. The findings are in a dashboard I built as a single HTML page.

**[Gold price prediction](https://github.com/beguumcetin/gold_prediction_project)**<br>
One of my first projects: predicting the next day's gram gold price from five years of daily data, with linear regression written from scratch.

During the internship I also built a Tableau dashboard of Istanbul job postings across 39 districts and 50 sectors, using data I scraped myself.

#### What I work with

Python and R most days, SQL, and Power BI or Tableau for dashboards. For models I mostly use pandas, scikit-learn, XGBoost, SHAP and Hugging Face. Lately I've been using more FastAPI, Docker and the Gemini API.

#### Right now

I'm learning how to deploy and monitor models properly, working on my English, and looking for a data science or analytics internship for 2027. I'm also building a day-ahead forecast of Türkiye's electricity demand and comparing it with the grid operator's own load plan.

You can find me on [LinkedIn](https://www.linkedin.com/in/beguumcetin) or write to begumcetin22@gmail.com.
