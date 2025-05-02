
---

## 🧠 Core Features

- 🧹 **Text Preprocessing**: Cleans and normalizes resumes and job description texts.
- 🏷️ **TF-IDF Vectorization**: Converts raw text to numerical feature vectors.
- 🤖 **Semantic Similarity (BERT)**: Compares resumes and job descriptions at a contextual level.
- 📊 **Ranking & Scoring**: Ranks resumes by relevance score to the job.
- 🧪 **Evaluation Metrics**: Measures precision, recall, and F1-score.
- 🖥️ **(Optional UI)**: User interface for recruiters and job seekers.

---

## 📌 How It Works

1. Recruiter uploads a **job description** (`job.txt`).
2. Candidates upload their **resumes** (`.txt` files) into the `/resumes` folder.
3. The system:
   - Cleans & vectorizes text.
   - Calculates similarity scores between resumes and job description.
   - Outputs a ranked list of best-matching resumes.

---

## 📈 Evaluation

We use similarity thresholding and binary classification to evaluate:
- ✅ **Precision**
- ✅ **Recall**
- ✅ **F1 Score**

These simulate how accurately resumes match the job requirement.

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/your-username/ai-resume-screening.git
cd ai-resume-screening

# Create a virtual environment and activate it (optional)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
#if installation dosnt work just convert that npynb file in python.py file and rune it 
