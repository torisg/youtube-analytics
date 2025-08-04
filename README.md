# 🎥 YouTube Data Collection & Sentiment Analysis

This project demonstrates how to collect YouTube video data using the `tuber` package in R, analyze viewer comments, generate a word cloud, and perform sentiment analysis.

---

## 📊 Features
✅ Authenticates with the YouTube Data API (v3)  
✅ Collects video statistics, details, and comments  .
✅ Cleans and processes comments for text analysis .
✅ Generates a *word cloud of frequent terms .
✅ Performs sentiment analysis with NRC lexicon  
✅ Visualizes emotional tone of viewer comments  

---

## 📂 Files in This Repo
- youtube_analytics.Rmd– Clean, portfolio‑ready R Markdown  
- README.md – This project overview and instructions  
 


---

## 🚀 How to Run
1️⃣ Clone this repo or download it as a ZIP.  
2️⃣ Install required packages in R:  
```r
install.packages(c("tuber", "tm", "SnowballC", "wordcloud", "syuzhet"))
```
3️⃣ Get your YouTube API credentials from Google Cloud Console.  
4️⃣ Open `youtube_analytics.Rmd` in **RStudio** and replace placeholders:
```r
client_id = "YOUR_CLIENT_ID"
client_secret = "YOUR_CLIENT_SECRET"
```
5️⃣ Knit the R Markdown file to render the **HTML report**.

---


---

## 🔑 Authentication Setup

This project uses the **YouTube Data API (v3)** via the `tuber` R package.

When you run this code for the first time:

1️⃣ You will see a browser window asking you to log in to your Google/YouTube account.  
2️⃣ R will prompt you with:  
   Use a local file (.httr-oauth) to cache OAuth access credentials between R sessions?  
   ✅ **Type 1 (Yes)** to save your login.  
3️⃣ This will create a **.httr-oauth** file in your project directory.  

**Important:**  
 
- Anyone else cloning this repo must authenticate with **their own** YouTube API credentials.
