# 📊 Social Media Impact on Teen Mental Health — Power BI Dashboard

## 📌 Project Overview

This project is an interactive **Power BI dashboard** that analyzes the
impact of social media usage on the mental health of teenagers (ages 13–19).
The dataset was sourced from **Kaggle** and contains 1,200 student records
across 13 variables including anxiety, stress, addiction, sleep, and
academic performance.

---

## 🖼️ Dashboard Preview

![Dashboard Preview](dashboard_preview.png)

<img width="1008" height="676" alt="image" src="https://github.com/user-attachments/assets/24620f8b-313a-4dc8-b8a2-8f69ebb317bb" />


---

## 📂 Dataset

| Property | Details |
|---|---|
| Source | Kaggle |
| Records | 1,200 students |
| Age Range | 13 – 19 years |
| Platforms | Instagram, TikTok, Both |
| Variables | 13 columns |
| File | `Social_Media_Impact_on_Teen_Mental_Health.csv` |

### Columns Used
- `age` — Teen's age
- `gender` — Male / Female
- `daily_social_media_hours` — Hours spent on social media per day
- `platform_usage` — Instagram / TikTok / Both
- `sleep_hours` — Average sleep duration
- `screen_time_before_sleep` — Screen exposure before bed
- `academic_performance` — GPA (0–4 scale)
- `physical_activity` — Hours of physical activity per day
- `social_interaction_level` — Low / Medium / High
- `stress_level` — Score 0–10
- `anxiety_level` — Score 0–10
- `addiction_level` — Score 0–10
- `depression_label` — 0 (No) / 1 (Yes)

---

## 📊 Dashboard Visuals

| Visual | Description |
|---|---|
| KPI Cards | Avg social media hours, sleep, GPA, stress, physical activity |
| Bar Chart | Depression count by media usage category |
| Donut Chart | Platform distribution (Instagram vs TikTok vs Both) |
| Line Chart | Addiction level trend across ages 13–19 |
| Table | Platform-wise avg stress, anxiety & addiction scores |
| Bar Chart | Academic GPA distribution (student count per GPA band) |
| Grouped Bar | Gender comparison — anxiety, depression, stress, addiction |

---

## 🔍 Key Findings

- 📱 Average daily social media usage is **4.54 hours**
- 😴 Average sleep is only **6.45h** — below the WHO recommended 8–10h
- 😰 Average anxiety level is **5.64 / 10** across all teens
- 🧠 Depression prevalence is **2.6%** overall but rises to **14.3%** at 8h+ usage
- 📈 Addiction scores peak at **age 19 (5.91)** and dip at **age 14 (5.20)**
- ⚠️ Zero depression cases found in teens using social media **under 4h/day**
- 👩‍🎓 Females show slightly higher anxiety (5.7) and depression rate (2.9%) than males (2.3%)
- 📚 Academic GPA is evenly distributed — no single GPA band dominates

---

## 🛠️ Tools Used

- **Power BI Desktop** — Dashboard design & visualization
- **Microsoft Excel / CSV** — Data source
- **Python (pandas)** — Exploratory data analysis & statistics
- **Kaggle** — Dataset source

---

## 🚀 How to Use

1. Clone this repository
```bash
   git clone https://github.com/your-username/teen-mental-health-social-media-analysis.git
```

2. Open **Power BI Desktop**

3. Open the file `Teen_Mental_Health_Dashboard.pbix`

4. If data doesn't load, go to:
   `Home → Transform Data → Data Source Settings`
   and update the path to the CSV file on your local machine

5. Click **Refresh** to reload the data

---

---

## 🎓 About

This project was built as part of my **Data Analyst learning journey**.
It demonstrates skills in data cleaning, exploratory analysis, DAX measures,
and professional dashboard design using Power BI.

---

## 📬 Connect

If you found this project useful, feel free to ⭐ star the repo
and connect with me on LinkedIn!

---

*Dataset credit: Kaggle — Social Media Impact on Teen Mental Health*
