<!--
  GitHub profile README for github.com/YasserSoliman25
  Source of truth: CodeNKoffee/dad-portfolio → docs/github-profile-README.md
  Edit there and copy across, so this and cappross.com stay in step.
-->

<h1 align="center">Yasser Soliman</h1>

<p align="center">
  <b>Chief Strategy Officer · Executive &amp; Board Advisor · Digital &amp; ICT Transformation</b><br/>
  Credit Risk Analytics · FinTech · Forensic Accounting Systems<br/>
  <sub>Cairo, Egypt</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/y4ssersoliman/"><img src="https://img.shields.io/badge/LinkedIn-y4ssersoliman-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://cappross.com"><img src="https://img.shields.io/badge/Portfolio-cappross.com-07111F?style=flat-square" alt="cappross.com"/></a>
  <a href="https://aaas.cappross.com"><img src="https://img.shields.io/badge/AAAS-Forensic_Screening-1E3A8A?style=flat-square" alt="AAAS"/></a>
  <a href="https://capprossbins.cappross.com"><img src="https://img.shields.io/badge/CapprossBins-Credit_Scoring-1E3A8A?style=flat-square" alt="CapprossBins"/></a>
  <a href="mailto:yasser.soliman@cappross.com"><img src="https://img.shields.io/badge/Email-yasser.soliman@cappross.com-4B5563?style=flat-square" alt="Email"/></a>
</p>

---

## Profile

Senior executive and board-level advisor with **25+ years** of leadership across ICT,
FinTech, credit risk and digital transformation — at Alcatel, Nokia, Huawei, and
CRIF / Dun &amp; Bradstreet, then as Chief Strategy Officer and Chairman's Advisor
to SMEs.

The work has consistently been the same problem in different clothing: taking a
technically complex system and turning it into a decision a board can defend.
Capital budgeting cases at Huawei, credit-scoring models at CRIF, corporate
strategy as a CSO.

Now I build the analytics instruments I spent two decades buying.

---

## What I build

| Product | What it does | Status |
| :--- | :--- | :--- |
| **[AAAS](https://aaas.cappross.com)** — Accrual Anomaly Audit Screening | Scores filed U.S. public-company annual statements for accrual-anomaly and earnings-manipulation risk. Six classical forensic layers — Beneish M-Score, Altman Z-Score, Dechow F-Score, Jones discretionary accruals, Roychowdhury REM, SOM clustering — plus a machine-learning ensemble trained on SEC enforcement actions. One 0–100 score across five risk tiers. | Free during early access |
| **[CapprossBins](https://capprossbins.cappross.com)** | Automated Weight-of-Evidence and Information-Value binning for credit scorecards. Monotonic bad-rate enforcement, special-value isolation, auto-optimal IV search, manual override. | Live |

Both are built on one principle: **a score that cannot be explained cannot be
trusted.** Every number AAAS produces carries a show-the-math audit trail from
filed line item → transformation → layer verdict → composite score, and missing
data is disclosed rather than silently imputed.

- Trained and calibrated on **207,457 company-years**
- Including **938 company-years under confirmed SEC enforcement**
- Published case study: **[Archer-Daniels-Midland FY2019](https://aaas.cappross.com)** — including the years the screen did *not* flag

> AAAS produces **screening signals, not verdicts**. It is not investment advice,
> not an audit opinion, and not an assertion that any company has committed fraud.

### Where the code lives

The engines are commercial and closed-source. The public repositories here carry
documentation, licensing and the public record:

- **[Accrual-Anomaly-Audit-Screening](https://github.com/YasserSoliman25/Accrual-Anomaly-Audit-Screening)** — methodology, layer breakdown, licence
- **[CapprossBins](https://github.com/YasserSoliman25/CapprossBins)** — binning tool documentation
- Live screen on **[Hugging Face Spaces](https://huggingface.co/spaces/Cappross-AI-Team/AAAS)** — no account, no signup

---

## Track record

| Period | Role |
| :--- | :--- |
| Jun 2023 – Present | **Business Consultant · Executive &amp; Board Advisor** (Freelance) — corporate strategy, digital transformation and investment decisions for boards and executive teams |
| Jan 2022 – May 2023 | **CRIF / Dun &amp; Bradstreet** — Global Data Analytics Projects Lead, Credit Risk. AI/ML credit scoring and decision-support models for financial institutions and credit bureaus |
| Jun 2015 – Dec 2021 | **Chief Strategy Officer &amp; Chairman's Advisor** — SMEs. Board-level strategy, P&amp;L accountability, organisation-wide transformation |
| Nov 2011 – May 2015 | **Huawei** — Regional Director, Professional Services (North Africa). Translated complex technical programmes into financial business cases for executive decision-making |
| May 2001 – Mar 2011 | **Nokia Siemens Networks / Nokia Networks** — senior global roles in business development, solution sales, network operations and service transition |
| Jul 1996 – Apr 2001 | **Alcatel** — Team Leader, fixed networks; promoted to Alcatel Certified Instructor by Alcatel France |

**Executive competencies** — Corporate &amp; Board Strategy · P&amp;L and Financial
Governance · Digital &amp; Business Transformation · Investment and Capital
Budgeting (ROI, NPV, IRR) · Credit Risk &amp; Analytics Strategy · ICT and FinTech
Leadership · Portfolio &amp; Performance Management · Executive Advisory

---

## Applied stack

| Domain | Applied to | Tools |
| :--- | :--- | :--- |
| **Forensic accounting analytics** | AAAS scoring engine — six-layer forensic ensemble over SEC filing data | `Beneish M-Score` `Altman Z` `Dechow F` `Jones DA` `Roychowdhury REM` `SOM clustering` |
| **Credit risk modelling** | Scorecard development, binning, decisioning at CRIF and in CapprossBins | `Weight of Evidence` `Information Value` `Logistic Regression` `Monotonic Binning` |
| **Machine learning** | Enforcement-trained classification ensembles, out-of-time validation | `scikit-learn` `XGBoost` `TensorFlow` `PyTorch` |
| **Data engineering &amp; analysis** | SEC XBRL panel construction, feature pipelines, model diagnostics | `Python` `pandas` `NumPy` `Jupyter` `Anaconda` `SQL` |
| **Applied AI** | Narrative and disclosure analysis layers, local model workflows | `LangChain` `Ollama` `LLM integration` |
| **Delivery** | Shipping analytical tools as usable products | `Streamlit` `Hugging Face Spaces` `Google Cloud Platform` |
| **Executive &amp; financial** | Business cases, capital allocation, board reporting | `ROI / NPV / IRR` `Financial Modelling` `Portfolio Management` |

---

## Writing

- **[From Score to Evidence: A Defensible Way to Screen Accrual-Anomaly Risk at Scale](https://www.linkedin.com/pulse/from-score-evidence-defensible-way-screen-risk-scale-yasser-soliman-ymaue/)** — why a score that cannot be explained cannot be trusted · [also on Medium](https://medium.com/@yasser.soliman_58858/from-score-to-evidence-a-defensible-way-to-screen-accrual-anomaly-risk-at-scale-1cf738d4c18c)

---

## Education &amp; credentials

**MBA** — New Orleans, Louisiana, USA<br/>
**Project Management Diploma** — University of Cambridge<br/>
**BSc, Communications &amp; Electronics Engineering** — Ain Shams University, Cairo

<p>
  <img src="https://img.shields.io/badge/DeepLearning.AI-NLP_Specialization-0A0A0A?style=flat-square" alt="NLP Specialization"/>
  <img src="https://img.shields.io/badge/IBM-Data_Science_Professional-052FAD?style=flat-square&logo=ibm&logoColor=white" alt="IBM Data Science"/>
  <img src="https://img.shields.io/badge/Udacity-Advanced_Data_Analysis-02B3E4?style=flat-square&logo=udacity&logoColor=white" alt="Udacity"/>
  <img src="https://img.shields.io/badge/Wharton_%26_Michigan-Finance,_Valuation_%26_Risk-00274C?style=flat-square" alt="Wharton and Michigan"/>
  <img src="https://img.shields.io/badge/ITIL-v3_Foundation_%26_Intermediate-EF3B39?style=flat-square" alt="ITIL v3"/>
</p>

**Languages** — Arabic (native) · English (fluent)

---

## Contact

Open to board advisory, executive consulting, and conversations with auditors,
credit teams and forensic investigators using AAAS.

**[yasser.soliman@cappross.com](mailto:yasser.soliman@cappross.com)** ·
**[LinkedIn](https://www.linkedin.com/in/y4ssersoliman/)** ·
**[Full CV](https://cappross.com/assets/pdfs/Yasser_Soliman_Executive_CV.pdf)**
