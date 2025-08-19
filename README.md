# 🧠 Human-to-AI Text Analysis (H2A)

## 📌 Overview
This project analyzes and compares text written by **Humans (0)** and **AI (1)**.  
The workflow extracts linguistic features, normalizes them, and visualizes the differences between human and AI writing styles.

Key outputs include:  
- **Radar plots** showing normalized style fingerprints.  
- **Delta bar charts** highlighting which features are higher in AI vs Human.  
- **Summary tables** with mean values and differences.  

---

## 📂 Project Structure

---

## ⚙️ Features Analyzed
#  Extracted Features (from text content)

| Feature               | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **word_count**         | Number of words in the text.                                               |
| **character_count**    | Number of characters in the text.                                          |
| **sentence_count**     | Number of sentences in the text.                                           |
| **avg_sentence_length**| Average sentence length (in words).                                        |
| **avg_word_length**    | Average word length (in characters).                                       |
| **lexical_diversity**  | Ratio of unique words to total words.                                      |
| **punctuation_ratio**  | Proportion of punctuation marks relative to total characters.              |
| **flesch_reading_ease**| Readability score (higher = easier to read).                               |
| **gunning_fog_index**  | Fog Index readability measure (higher = harder to read).                   |
| **grammar_errors**     | Count/ratio of grammatical errors.                                         |
| **passive_voice_ratio**| Ratio of passive voice sentences.                                          |
| **predictability_score**| Measure of how predictable/repetitive the text is.                        |
| **burstiness**         | Variation in sentence length (consistency vs. spikes).                     |
| **sentiment_score**    | Sentiment polarity (positive / negative).                                  |
| **label**              | Original class (AI / Human).                                               |
| **label_bin**          | Numeric version of class (0 = AI, 1 = Human).                              |
  

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/Al-AugToOct/data-science-project-h2a-human-to-ai-analysis.git
   cd data-science-project-h2a-human-to-ai-analysis
