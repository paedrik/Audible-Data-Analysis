# 🎧 Audible Data Analysis

This project explores my personal **Audible listening data** as the first step toward building a unified view of my **reading and listening habits** across platforms like Audible, Kindle, and Libby.

---

## 🧭 Background

I began this project with the idea of building an app that could track and visualize my **reading and listening progress** across different services.  
However, I quickly realized that there are **no public APIs** and **limited export options** from Audible, Kindle, or Libby.

To move forward, I submitted a **personal data request to Audible** under GDPR/CCPA to obtain my listening data. Once I received it (in CSV format), I began exploring it with **Python and Jupyter Notebook** to understand it and uncover insights such as:

- Total hours listened per book  
- Monthly listening trends  
- Potential re-listening patterns (overlapping play segments)

---

## 📊 Analysis Goals

1. **Understand listening behavior**
   - When and how much I listen
   - What genres or books dominate my listening time

2. **Detect re-listening patterns**
   - Using start/end timestamps to identify overlapping playback sessions

3. **Lay the groundwork**
   - For a future dashboard or app that combines data from Audible, Kindle, and Libby into a single interface

---

## 🧰 Tools & Libraries

- **Python 3.12**
- **Jupyter Notebook**
- **pandas** — data cleaning and transformation  
- **matplotlib** — basic visualizations  
- **Git & GitHub** — version control  
- *(optional)* **seaborn** — for more advanced charts  

---

## 📂 Repository Structure

```
Audible-Data-Analysis/
├── Listening.csv              # Raw Audible data from data request
├── audible_analysis.ipynb     # Main notebook for data analysis
├── calculate_overlap.py       # Function to detect overlapping listening
├── tests/                     # Unit tests for overlap detection
└── README.md
```

---

## 🧪 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/paedrik/Audible-Data-Analysis.git
   cd Audible-Data-Analysis
   ```

2. **Set up your environment**
   ```bash
   conda create -n audible-analysis python=3.12
   conda activate audible-analysis
   pip install -r requirements.txt
   ```

3. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```

4. **Open `audible_analysis.ipynb`**  
   and run all cells to reproduce the analysis.

---

## 🔐 Getting Your Audible Data

To obtain your personal Audible listening data:
1. Go to **[Audible’s Data Request Page](https://www.audible.com/datarequests)**  
2. Submit a request under your account email.  
3. After processing (typically a few days), you’ll receive a `.zip` file containing CSV exports.  
4. Look for a file named **`Listening.csv`** — that’s the one used in this analysis.

*(Optional: link to a blog post or how-to guide once you write it.)*

---

## 🚀 Future Plans

- Integrate Kindle and Libby data (if exportable)
- Continue work on a small dashboard (Replit)
- Visualize combined reading/listening patterns
- Add sentiment or genre analysis

---

## 🧠 Example Insights (to be updated)
- Total listening time: **~X hours**
- Longest single listening streak: **Y hours**
- Most re-listened book: **[Book Title]**

---

## 📜 License
This project is for **personal research and educational use**.  
If you reuse the code, please credit the source and respect Audible’s terms of service.

---

## 💬 Acknowledgments
- Audible, for providing downloadable personal data upon request  
- The open-source Python and data science community
- To ChatGPT, the oracle in the machine, for conjuring clarity from confusion.
