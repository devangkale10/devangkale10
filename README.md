<h1 align="center">Hi, I'm Devang Kale 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=2F81F7&center=true&vCenter=true&width=640&lines=Data+Scientist+%7C+GenAI+%E2%80%A2+ML+%E2%80%A2+Data+Engineering;I+build+RAG+assistants+that+find+the+right+data;LLM+pipelines+with+measured+accuracy;Data+systems+that+give+teams+hours+back" alt="Data Scientist | GenAI, Machine Learning, Data Engineering" />
</p>

<p align="center">
  <b>I turn messy institutional data into AI products people actually use, and I measure whether they work.</b><br/>
  4+ years across finance, healthcare, and higher education &nbsp;·&nbsp; 📍 Based in the USA
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/devang-kale/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxjaXJjbGUgY3g9IjUuNCIgY3k9IjUuMiIgcj0iMi4xIi8%2BPHJlY3QgeD0iMy42IiB5PSI4LjciIHdpZHRoPSIzLjYiIGhlaWdodD0iMTIiIHJ4PSIwLjMiLz48cGF0aCBkPSJNOS44IDguN2gzLjR2MS43Yy42LTEgMS45LTIgMy44LTIgMy44IDAgNC41IDIuNSA0LjUgNS43djYuNmgtMy42VjE1YzAtMS40IDAtMy4xLTEuOS0zLjFzLTIuMiAxLjUtMi4yIDN2NS44SDkuOHoiLz48L3N2Zz4%3D" alt="LinkedIn" /></a>
  <a href="mailto:devang.r.kale@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://drive.google.com/file/d/1KPcXbrV3DnTY0SXdlL1jy5kvs-ns5LXq/view?usp=sharing"><img src="https://img.shields.io/badge/Resume-2F81F7?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Resume" /></a>
  <a href="https://public.tableau.com/app/profile/devang.kale8055/vizzes"><img src="https://img.shields.io/badge/Tableau%20Public-E97627?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxyZWN0IHg9IjMiIHk9IjEyIiB3aWR0aD0iNCIgaGVpZ2h0PSI5IiByeD0iMSIvPjxyZWN0IHg9IjEwIiB5PSI3IiB3aWR0aD0iNCIgaGVpZ2h0PSIxNCIgcng9IjEiLz48cmVjdCB4PSIxNyIgeT0iMyIgd2lkdGg9IjQiIGhlaWdodD0iMTgiIHJ4PSIxIi8%2BPC9zdmc%2B" alt="Tableau Public" /></a>
</p>

> [!TIP]
> **Short on time?** I build RAG assistants, LLM classification pipelines, and Snowflake data workflows end to end: data modeling, prompting and retrieval, evaluation, and deployment. My focus is **Data Science, Applied AI, and ML Engineering** on systems that run in production. Start with the numbers below or grab my [resume](https://drive.google.com/file/d/1KPcXbrV3DnTY0SXdlL1jy5kvs-ns5LXq/view?usp=sharing).

## 📈 Impact at a Glance

<table>
  <tr>
    <td align="center" width="25%">
      <h3>60% → 85%</h3>
      <sub>Recall@5 on a RAG data-discovery assistant</sub>
    </td>
    <td align="center" width="25%">
      <h3>~90%</h3>
      <sub>agreement with human labels on 16K+ posts a year</sub>
    </td>
    <td align="center" width="25%">
      <h3>250 hrs</h3>
      <sub>of manual documentation saved across 20K+ columns</sub>
    </td>
    <td align="center" width="25%">
      <h3>350 hrs/yr</h3>
      <sub>of staff time saved by automated reporting</sub>
    </td>
  </tr>
</table>

## 🚀 What I've Shipped

<sub>Production work at the University of Florida. The code is internal, but I'm happy to walk through the architecture and design decisions.</sub>

### 🤖 RAG Data Discovery Assistant
Helps UF staff discover what institutional data exists and turn vague questions into well-scoped data requests.
- **How:** LangChain + ChromaDB retrieval with hybrid search and reranking, grounded in an LLM-built data dictionary, served through Streamlit
- **Result:** Recall@5 improved from **60% to 85%**; deployed for staff on the UF network

`LangChain` `ChromaDB` `Hybrid Search` `Reranking` `Streamlit`

### 📚 LLM-Powered Data Dictionary
Generates grounded definitions, data types, and value descriptions for **~200 tables and 20K+ columns** directly from Snowflake.
- **How:** GPT-5 grounded in real schema and column values, with a human review step for the columns that most need checking
- **Result:** ~**250 hours** of manual documentation saved; it is also the knowledge base behind the RAG assistant above

`GPT-5` `Snowflake` `Python` `Human-in-the-Loop`

### 🧭 Student Concern Routing with LLMs
A weekly pipeline that classifies r/ufl posts and routes high-priority student concerns to the right one of **15 Student Life units**.
- **How:** Reddit API → GPT-5 multi-label classification (few-shot prompts, schema-constrained JSON) → Snowflake → Power BI dashboard
- **Result:** **16K+ posts a year** classified at **~90% agreement** with a manually labeled gold set

`GPT-5` `Reddit API` `Structured Outputs` `Snowflake` `Power BI`

### ⚙️ Automated Analytics Pipeline
A Snowflake + Python reporting pipeline that integrates **10 data sources** and replaces recurring manual reporting.
- **Result:** ~**350 staff hours a year** saved

`Python` `Snowflake` `SQL` `Automation`

## 🧪 Open-Source Projects

<table>
  <tr>
    <td width="50%" valign="top">

### 🔐 [PII Detection & Redaction](https://github.com/devangkale10/PII-Redaction-System)
A hybrid pipeline combining **spaCy NER, Hugging Face Transformers, and regex** to find and redact sensitive information in free text.

**Result:** 80% detection accuracy on sensitive fields

`Python` `spaCy` `Hugging Face` `pandas` `pytest`

  </td>
    <td width="50%" valign="top">

### 🛍️ [Visual Product Recommender](https://github.com/devangkale10/Product-Recommendation-using-NLP-and-CNN)
Recommends similar items across **16K+ apparel products** by combining **NLP title matching** with **VGG-16 image features**.

**Why it matters:** surfaces items that look alike, not just ones with similar titles

`Python` `scikit-learn` `TensorFlow/Keras` `NLP` `Computer Vision`

  </td>
  </tr>
</table>

## 🧠 How I Work

- 📏 **Measure before shipping.** Recall@k for retrieval, agreement with gold labels for classifiers, hours saved for automation.
- 🧷 **Ground LLMs in real data.** Retrieval over trusted sources, schema-constrained outputs, and human review where mistakes are costly.
- 🔁 **Build things that keep running.** Scheduled pipelines with failure alerts, not one-off notebooks.

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,aws,docker,postgres,mongodb,git,githubactions" alt="Python, PyTorch, TensorFlow, scikit-learn, AWS, Docker, PostgreSQL, MongoDB, Git, GitHub Actions" />
</p>

| Area | Tools |
| --- | --- |
| **GenAI & NLP** | ![OpenAI](https://img.shields.io/badge/OpenAI%20APIs-412991?style=flat-square) ![LiteLLM](https://img.shields.io/badge/LiteLLM-6E56CF?style=flat-square) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-2F81F7?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white) |
| **Machine Learning** | ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![SHAP](https://img.shields.io/badge/SHAP%20%7C%20LIME-555555?style=flat-square) |
| **Data & Engineering** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) ![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) |
| **Cloud & Dev Tools** | ![AWS](https://img.shields.io/badge/AWS-S3%20%7C%20Lambda%20%7C%20EC2%20%7C%20Redshift-FF9900?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) |
| **Analytics & BI** | ![A/B Testing](https://img.shields.io/badge/A%2FB%20Testing-6E7781?style=flat-square) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![statsmodels](https://img.shields.io/badge/statsmodels-4B0082?style=flat-square) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) |

## 💼 Experience

| Role | Organization | Dates |
| --- | --- | --- |
| **Data Analyst II** | University of Florida | Nov 2024 – Present |
| **Data Scientist Intern** | Changing The Present | Aug 2024 – Nov 2024 |
| **AI/ML Research Assistant** | PRISMAP Labs, University of Florida | May 2023 – Aug 2023 |
| **Data Engineer** | Infosys | Nov 2020 – Jul 2022 |

## 🎓 Education

- **M.S. in Computer Science**, University of Florida
- **B.E. in Information Technology**, University of Pune

## 📬 Let's Talk

I'm always up for a conversation about applied AI, ML engineering, or a data problem that needs untangling. The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/devang-kale/) or [email](mailto:devang.r.kale@gmail.com).

<p align="center">
  <sub>Thanks for stopping by ✨</sub>
</p>
