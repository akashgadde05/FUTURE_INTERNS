# FUTURE_INTERNS – College Event Feedback Analysis 📊

**By Akash**

---

## 📌 Overview

This project analyzes student feedback collected via Google Forms (CSV files) from college events like tech fests, workshops, and cultural activities. Through NLP and data visualization, it uncovers satisfaction levels and highlights areas for improvement.

---

## 🧾 Datasets

- `student_feedback.csv`: Individual student ratings per question (e.g. subject expertise, presentation quality, assignment difficulty).
- `Student_Satisfaction_Survey.csv`: Aggregated feedback with response counts and weighted averages by question.

---

## 🛠️ Tools & Libraries

| Library        | Purpose                                      |
|----------------|----------------------------------------------|
| `pandas`       | Data loading, cleaning, and aggregation      |
| `matplotlib` / `seaborn` | Visualization (histograms, bar charts, heatmaps) |
| `TextBlob`     | Sentiment analysis (happy/concerned text)    |
| `wordcloud`    | Visualizing frequent keywords                |

---

## 🚀 How it Works

1. **Load & Clean Data**
   - Remove unnecessary columns like `Unnamed: 0`
   - Strip whitespace from column names
2. **Compute Averages**
   - Student-level: average scores across rating questions
   - Question-level: compute weighted averages using response frequency
3. **Visualizations**
   - Histogram of student average scores
   - Bar chart of question-level averages
   - Word cloud to highlight recurring question themes
4. **Insights & Recommendations**
   - Identify questions with low average scores (< 3.5)
   - Suggest focus areas for improvement

---

## 📂 Repository Structure

```
/
├── data/
│   ├── student_feedback.csv
│   └── Student_Satisfaction_Survey.csv
├── notebooks/
│   └── analysis.ipynb           # Python notebook with all analyses
├── src/
│   └── data_cleaning.py         # Functions to clean and process data
└── README.md
```

---

## 🧪 Usage Instructions

```bash
# Clone the repository
git clone https://github.com/akashgadde05/FUTURE_INTERNS.git
cd FUTURE_INTERNS

# Install dependencies
pip install pandas matplotlib seaborn textblob wordcloud

# Run the analysis notebook
jupyter notebook notebooks/analysis.ipynb
```

---

## 📊 Key Visualizations

- **Histogram**: distribution of average student satisfaction
- **Bar Plot**: average score per question, to compare performance
- **Word Cloud**: top feedback themes or frequently asked questions

---

## 🔍 How to Improve the Project

- Apply sentiment analysis on open‑text feedback to capture tone.
- Add a **correlation heatmap** among rating categories to identify related metrics.
- Merge and dedupe repetitive survey questions in `df2` using aggregation.
- Extract top positive & negative keywords using TextBlob or `spaCy`.
- Export summary results into a CSV, Excel, or automatically generated report (PDF/PowerPoint).

---

## 🤝 Contributions

Contributions are welcome! To add improvements:
1. Fork the repo  
2. Create a topic branch  
3. Submit a Pull Request  
4. Ensure code is well documented

Please follow typical cleanliness and ethical feedback handling.

---

## 📄 License

[MIT License](LICENSE)

---

## 📬 Contact

**Akash**  
📧 Email: [akashgadde05@gmail.com](mailto:akashgadde05@gmail.com)  
🔗 GitHub: [akashgadde05](https://github.com/akashgadde05)

---


