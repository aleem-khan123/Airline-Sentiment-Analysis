# ✈️ Airline Sentiment Analysis

##  Project Overview
This project analyzes customer sentiments towards different airlines based on Twitter reviews.  
Using **Natural Language Processing (NLP)** techniques, the goal is to identify which airlines receive positive, neutral, or negative feedback.  

Due to Twitter API restrictions, live tweet fetching was not possible. Instead, a publicly available dataset of airline tweets was used for the analysis.

---

##  Objectives
- Perform sentiment analysis on airline customer reviews.  
- Identify airlines with the most positive and negative feedback.  
- Compare dataset-provided sentiment labels with TextBlob sentiment analysis.  
- Provide a professional report summarizing findings.  

---

## 🛠 Methodology
1. **Dataset**  
   - Raw dataset of airline tweets with labeled sentiments.  

2. **Data Cleaning**  
   - Removed emojis, symbols, and unnecessary characters.  
   - Preprocessed tweets for analysis.  

3. **Sentiment Analysis**  
   - Applied **TextBlob** to calculate sentiment polarity.  
   - Classified tweets as Positive, Negative, or Neutral.  

4. **Validation**  
   - Built a confusion table to compare original dataset labels vs. TextBlob results.  
   - Agreement Rate: **44.6%**  

5. **Visualization**  
   - Created graphs to show sentiment distribution across airlines.  

---

##  Key Findings
- **Best Performing Airlines:** Delta Airlines, Southwest Airlines  
- **Worst Performing Airlines:** United Airlines, US Airways  
- **Mixed Sentiments:** American Airlines  

---

##  Why Twitter Live API Was Not Used?
In 2023–24, Twitter changed its developer access policy:
- Free API access was discontinued.  
- Paid subscription is required for even basic queries.  
- Approval delays and subscription costs made live API infeasible for this project.  

Therefore, a **publicly available dataset** was used to complete the analysis effectively and on time.

---

##  Project Structure
📁 Airline-Sentiment-Analysis
-📄 Tweets.csv # Original dataset
-📄 scored_tweets.csv # Cleaned dataset with sentiment scores
-📄 Task 3 Report(Airline Sentiment Analysis).pdf # Professional project report
-📄 TH Task 03.ipynb # Jupyter Notebook code
-📄 graphs/ # Visualizations (PNG files)
-📄 README.md # Project documentation

---

## 📌 Tools & Libraries
- Python 🐍  
- Pandas, NumPy  
- TextBlob (for sentiment analysis)  
- Matplotlib / Seaborn (for graphs)  
- Jupyter Notebook  

---

## 📖 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/aleem-khan123/Airline-Sentiment-Analysis.git

- Navigate into the project folder
cd Airline-Sentiment-Analysis

- Install required libraries
pip install -r requirements.txt

- Run the Jupyter Notebook
TH Task 03.ipynb

## Results

- Positive reviews highlighted good staff service & helpfulness.

- Negative reviews mostly focused on delays, poor communication, and bad gate service.

- Accuracy of TextBlob compared to dataset labels was 44.6%.

 ## Author

- Aleem Shoukat
- Gmail- iamaleemmm@gmail.com
- Linked in-www.linkedin.com/in/aleem-shoukat-9bb3b6356

⭐ If you found this project useful, feel free to star this repository!
