# Social Media and Mental Well-Being: A Data-Driven Exploration

---

This repository contains the materials, datasets, code, and analysis for the **Social Media and Mental Well-Being** project, conducted as part of the **Innovation and Marketing Analytics** course.

## 📘 Project Overview

- Course: Databases
- Academic year: 2023/2024
- Team: Mariapia Tedesco (me), Valentina Brivio, Edoardo Palombi, Arianna Zottoli

### **Abstract**
This research explores the impact of social media communities on individuals' mental well-being through a data-driven approach. The study:
- Analyzes **2847 posts** from mental health-related subreddits.
- Identifies dominant themes like depression, anxiety, stress, and relationships through topic modeling.
- Conducts sentiment-emotion analysis to assess user interactions and emotional shifts.
- Includes a survey of **215 respondents** to evaluate how social media engagement influences well-being.

---

## 📂 Repository Structure

- **`Comments_Replies_datasets/`**: Contains datasets of comments and replies extracted from social media platforms.
- **`Data_Acquisition_code/`**: Scripts used to extract data from Reddit using the Reddit API.
- **`Emotion_datasets/`**: Preprocessed data for sentiment and emotion analysis.
- **`Posts_datasets/`**: Datasets of original posts extracted from mental health-related subreddits.
- **`Sentiment_datasets/`**: Sentiment-labeled datasets created using the RoBERTa model.
- **`Sentiment_Emotion_analysis_code/`**: Scripts for performing sentiment and emotion analysis.
- **`Survey/`**: Materials related to the survey, including questions and responses.
- **`Topic_Modeling_code/`**: Scripts for topic modeling analysis.
- **`Final_Report.pdf`**: Final report documenting the project, including methodology, results, and conclusions.

---

## 🔬 Key Components

### **1. Data Acquisition**
- Extracted data using the **Reddit API** from subreddits such as `r/mentalhealth`, `r/depression`, and `r/anxiety`.
- Collected titles, post content, and comment interactions for analysis.

### **2. Topic Modeling**
- Utilized **Latent Dirichlet Allocation (LDA)** to identify dominant discussion themes.
- Key topics include mental health management, depression, stress, anger, and emotional expression.

### **3. Sentiment-Emotion Analysis**
- Employed the **Twitter-RoBERTa-base** model for sentiment and emotion detection.
- Conducted comparative analysis of sentiment changes between posts, comments, and replies.

### **4. Interactive Survey**
- Designed a 20-question survey to explore the effects of social media engagement on mental health.
- Conducted a controlled experiment with respondents exposed to different types of comments to assess their impact on emotional well-being.

---

## 📊 Key Findings

1. **Topic Modeling**:
   - Identified dominant themes like depression, anxiety, and stress, highlighting common struggles among users.
   
2. **Sentiment and Emotion**:
   - Most posts have a predominantly negative sentiment (e.g., sadness and anger).
   - Comments and replies often improve sentiment, showing positive changes.

3. **Survey Insights**:
   - Heavy social media users report lower mental well-being scores.
   - Positive and empathetic comments have a significant impact on improving user sentiment.
  
