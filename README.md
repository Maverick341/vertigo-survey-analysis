## Vertigo & Imbalance Survey — Presentation Notes

This README provides a presentation-ready summary of the SVQ-based analysis of vertigo/imbalance symptoms in IT workers. It is designed to be used directly in slides or reports without showing code.

---

### 1) Study Overview
**Objective:** Quantify the prevalence and severity of vertigo/imbalance symptoms and explore associations with workplace exposures (screen time and earphone usage).

**Population:** IT workers (N = 114)

**Instrument:** Situational Vertigo Questionnaire (SVQ)
- SVQ uses a 0–4 scale per item.
- Higher scores indicate stronger visual-vertigo sensitivity.

**Severity Categories (SVQ Interpretation):**
- Minimal/No Symptoms (0–1)
- Moderate Symptoms (2–3)
- High Sensitivity (≥4)

---

### 2) Primary Results
**Prevalence of symptoms (Moderate + High):** 68.42%

**Severity Distribution:**
- Minimal/No Symptoms: 36 (31.6%)
- Moderate Symptoms: 68 (59.6%)
- High Sensitivity: 10 (8.8%)

**Age Distribution:**
- 20–29: 80 (69.57%)
- 30–39: 28 (24.35%)
- 40–50: 7 (6.09%)

**Group Comparisons:**
- Gender differences in SVQ scores were statistically significant (non-parametric test).
- Job role comparisons (n ≥ 10 per group) showed no statistically significant differences.

---

### 3) Key Visuals (Embedded)

#### Table 1 — Descriptive Statistics
![Table 1](https://raw.githubusercontent.com/Maverick341/vertigo-survey-analysis/main/output/Table1_descriptive_statistics.png)

#### SVQ Item Response Distribution (0–4)
![SVQ Item Response Distribution](https://raw.githubusercontent.com/Maverick341/vertigo-survey-analysis/main/output/svq_item_response_stacked_bar.png)

#### Severity Distribution (Bar)
![Severity Distribution Bar](https://raw.githubusercontent.com/Maverick341/vertigo-survey-analysis/main/output/severity_distribution.png)

#### Severity Distribution (Pie)
![Severity Distribution Pie](https://raw.githubusercontent.com/Maverick341/vertigo-survey-analysis/main/output/svq_severity_pie_chart.png)

#### Age Group Distribution
![Age Group Distribution](https://raw.githubusercontent.com/Maverick341/vertigo-survey-analysis/main/output/age_group_distribution.png)

#### Gender vs SVQ Score (Boxplot)
![Gender vs SVQ Score](https://raw.githubusercontent.com/Maverick341/vertigo-survey-analysis/main/output/gender_svq_boxplot.png)

#### Job Role vs SVQ Score (Boxplot)
![Job Role vs SVQ Score](https://raw.githubusercontent.com/Maverick341/vertigo-survey-analysis/main/output/job_role_svq_boxplot.png)

#### Correlation Heatmap (Screen Time, Earphone Usage, SVQ Score)
![Correlation Heatmap](https://raw.githubusercontent.com/Maverick341/vertigo-survey-analysis/main/output/correlation_heatmap.png)

---

### 4) Interpretation Notes
- **Most participants reported moderate symptoms**, suggesting visual-vertigo sensitivity is prevalent in this cohort.
- **High sensitivity is present but less common**, indicating a smaller subgroup may need targeted interventions.
- **Age distribution is skewed toward younger workers**, which may influence symptom prevalence patterns.
- **Gender differences warrant further exploration**, while job-role differences were not significant in this sample.
- **Correlation analysis** provides directional insight but does not imply causality.

---

### 5) Data & Reproducibility
- Raw data: [public/files/raw_vertigo_survey_form_responses.csv](https://raw.githubusercontent.com/Maverick341/vertigo-survey-analysis/main/public/files/raw_vertigo_survey_form_responses.csv)
- Full workflow: [vertigo_survey_analysis_main.ipynb](https://raw.githubusercontent.com/Maverick341/vertigo-survey-analysis/main/vertigo_survey_analysis_main.ipynb)

---

### 6) Suggested Slide Flow
1. Study Objective + Population
2. Severity Distribution (Bar/Pie)
3. Age Distribution
4. Key Group Comparisons (Gender, Job Role)
5. Exposure Associations + Correlation Heatmap
6. Summary & Recommendations
