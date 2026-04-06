# 📊 Academic Research Survey Engine

A custom-built, auto-scoring digital survey instrument designed for academic research in Human Physiology. 

## 🔬 Research Focus
**Topic:** The Impact of Sleep Deprivation and Anxiety on JAMB CBT Performance.
This tool collects quantitative data from students preparing for the JAMB UTME exams to analyze the physiological and psychological factors affecting cognitive performance.

## ⚙️ Features
This application is more than a standard form; it includes built-in computational logic tailored to established medical and psychological scales:

* **The Westside Test Anxiety Scale:** Automatically calculates the user's aggregate anxiety score (1.0 to 5.0) based on 10 Likert-scale questions and categorizes their anxiety level instantly.
* **Pittsburgh Sleep Quality Index (PSQI) Adaptation:** Collects precise quantitative sleep metrics (bedtime, latency, wake time, total duration) and automatically flags individuals who meet the criteria for "Severe Sleep Deprivation" (< 6 hours).
* **Automated Data Pipeline:** Bypasses manual data entry. Responses are parsed, scored on the client side, and pushed securely via REST API to a private Google Sheets database in real-time.
* **Participant Isolation:** Utilizes a secret Student Identification Code to track demographic cohorts without collecting personally identifiable information (PII).

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Backend Database:** Google Sheets (via Google Apps Script Web App)
* **Hosting:** GitHub Pages

## 📝 How it Works
1. Participants open the live web link on any device.
2. They input their unique identification code and demographic data.
3. They complete the 10-item Westside Test Anxiety Scale and the 6-item Sleep Quality assessment.
4. Upon submission, the JavaScript engine calculates the exact physiological markers.
5. A JSON payload containing the raw data and the calculated scores is sent to the cloud database.

## 👨‍🔬 Researcher
Developed for data collection in Human Physiology studies, analyzing the correlation between sleep latency, test anxiety, and standardized exam (CBT) outcomes.
