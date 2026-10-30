# 📊 Data Science & AI Complete Curriculum Portfolio

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-Advanced-orange.svg?logo=postgresql&logoColor=white)](#)
[![Streamlit](https://img.shields.io/badge/Streamlit-App%20Dev-FF4B4B.svg?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-F7931E.svg?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Deep Learning](https://img.shields.io/badge/Deep%20Learning-PyTorch%20%2F%20TF-EE4C2C.svg?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![GenAI](https://img.shields.io/badge/GenAI-Transformers%20%26%20LLMs-yellow.svg?logo=huggingface&logoColor=white)](https://huggingface.co/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An end-to-end knowledge base and assignment repository tracking core concepts across the entire modern data stack—from foundational Python and relational database management to Computer Vision, Deep Learning, and Generative AI systems.

---

## 📌 Repository Structure

```text
├── assignments/                          # Individual date-wise markdown assignments
│   ├── 01_Oct_04_Python_Arithmetic.md
│   ├── 02_Oct_12_Functions_Arguments.md
│   ├── ...
│   └── 23_Feb_28_NLP_Transformers.md
├── docs/                                 # Generated PDFs and DOCX files for export
├── scripts/
│   └── export_assignments.py             # Script to split master file & generate PDF/DOCX
├── data_science_assignments_master.md   # Unified single-source master reference
├── requirements.txt                      # Python environment dependencies
├── .gitignore
├── LICENSE
└── README.md
```

---

## 📅 Curriculum Breakdown

| # | Date | Module | Core Topics |
| :---: | :---: | :--- | :--- |
| **01** | `04 Oct` | **Python Core** | Modulo `%` arithmetic, floor division `//`, division edge cases |
| **02** | `12 Oct` | **Python Functions** | Parameters vs. arguments, dynamic dispatch, `*args`, `**kwargs` |
| **03** | `25 Oct` | **Function Mechanics** | Return signatures, implicit tuple packing, scope isolation |
| **04** | `26 Oct` | **Data Structures** | Tuples, immutability guarantees, mutable objects within tuples |
| **05** | `01 Nov` | **Data Structures** | Sets, hash collision mechanics, `remove()` vs `discard()`, set theory |
| **06** | `16 Nov` | **Data Ingestion** | File handling, native `csv` vs. `pandas.DataFrame`, appending buffers |
| **07** | `22 Nov` | **SQL Fundamentals** | `ORDER BY`, multi-column tiebreakers, ascending/descending mechanics |
| **08** | `23 Nov` | **SQL Querying** | `DISTINCT` filtering, compound columns, hashing vs. `GROUP BY` |
| **09** | `29 Nov` | **SQL Logic & Filtering** | Boolean precedence (`AND` over `OR`), bracket grouping, `LIKE`, `BETWEEN` |
| **10** | `30 Nov` | **SQL Aggregations** | `COUNT(*)` vs `COUNT(col)` vs `COUNT(DISTINCT)`, NULL handling |
| **11** | `06 Dec` | **SQL Advanced Functions** | Aggregate vs Scalar functions, case-normalization cleaning routines |
| **12** | `07 Dec` | **App Engineering** | Streamlit reactive runtime, WebSocket architecture, model serving |
| **13** | `14 Dec` | **UI/UX Design** | Streamlit sidebars, input layout hierarchy, UX ergonomics |
| **14** | `21/27 Dec` | **Machine Learning** | Core taxonomy, optimization loops, traditional code vs ML paradigms |
| **15** | `28 Dec` | **Tree Algorithms** | Decision Trees, recursive splitting, `max_depth` regularization |
| **16** | `03 Jan` | **Ensemble Learning** | Random Forest, bagging, bootstrap sampling, subspace feature splits |
| **17** | `31 Jan` | **Computer Vision** | OpenCV framework, BGR vs RGB color spaces, `VideoCapture` streams |
| **18** | `01 Feb` | **Image Processing** | Spatial resampling, pixel interpolation, `INTER_AREA` vs `INTER_LINEAR` |
| **19** | `14 Feb` | **Multi-Page Web Apps** | Streamlit filesystem routing, modular UI architecture |
| **20** | `15 Feb` | **Inference Systems** | Production ML interfaces, DataFrame marshalling, `@st.cache_resource` |
| **21** | `21 Feb` | **Deep Learning** | Perceptrons, activation non-linearities, backpropagation, batching |
| **22** | `22 Feb` | **AI Taxonomy** | Concentric hierarchy: Artificial Intelligence $\supset$ ML $\supset$ DL $\supset$ GenAI |
| **23** | `28 Feb` | **NLP & Transformers** | NLTK vs spaCy, Hugging Face transformers, virtual environment isolation |

---

## 🛠️ How to Generate Individual Date-Wise PDF & DOCX Files

This repository includes an automated utility script (`scripts/export_assignments.py`) that reads the master handbook, splits each assignment into its own Markdown file, and converts them to `.docx` and `.pdf` files inside the `docs/` folder.

### 1. Set Up Environment
```bash
# Clone the repository
git clone https://github.com/<your-username>/data-science-portfolio-assignments.git
cd data-science-portfolio-assignments

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate       # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### 2. Run the Generator Script
```bash
python scripts/export_assignments.py
```
This produces:
*   `assignments/`: 23 individual date-wise `.md` files.
*   `docs/docx/`: 23 individual Microsoft Word documents.
*   `docs/pdf/`: 23 individual PDF files.

---

## 💻 Tech Stack & Tools Covered
*   **Languages:** Python 3.10+, SQL (PostgreSQL / ANSI SQL)
*   **Data Manipulation:** Pandas, NumPy
*   **Web Dashboards:** Streamlit
*   **Machine Learning:** Scikit-Learn
*   **Computer Vision:** OpenCV (`cv2`)
*   **Deep Learning & NLP:** PyTorch / TensorFlow, spaCy, NLTK, Hugging Face Transformers

---

## 📄 License
This repository is open-source and available under the [MIT License](LICENSE).