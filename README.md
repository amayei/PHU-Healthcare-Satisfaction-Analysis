# PHU Healthcare Satisfaction Analysis

End-to-end analysis of household satisfaction with services delivered by **Peripheral Health Units (PHUs)** across the **Kambia, Kailahun and Pujehun** districts of Sierra Leone.

## Overview

The notebook works through a full survey-analysis pipeline:

- **Data preparation** — loading, structure inspection, missing-value assessment and cleaning
- **Respondent profile** — age, geographic location, sample size by district, gender, household size, marital and educational status
- **Health-service utilisation** — facility-based service use and barriers to healthcare access, by district and overall
- **Satisfaction analysis** — descriptive statistics of satisfaction levels, mean and box-plot comparisons across districts, correlation matrix, and satisfaction by specific service dimension
- **District comparison** — mean satisfaction scores and overall satisfaction (mean and proportion) for Kambia, Kailahun and Pujehun
- **Synthesis** — highest- and lowest-performing satisfaction categories, strengths and areas for improvement

## Contents

| File | Description |
| --- | --- |
| `Satisfaction Survey.ipynb` | Complete analysis notebook |

## Running the analysis

```bash
pip install -r requirements.txt
jupyter notebook "Satisfaction Survey.ipynb"
```

The notebook expects a survey dataset (`SHS-Data.csv`) in the working directory. **The source data are not distributed in this repository**; update the file path in the first cell to point to your own copy.

## Tech stack

Python · pandas · NumPy · matplotlib · seaborn · Jupyter

## Data protection

The source data are not distributed. Notebook outputs that displayed respondent-level rows, household GPS coordinates or village names were removed before publication. Re-run the notebook locally with your own authorised copy of the data to regenerate them.

## Author

**Alhassan Mayei** — Digital Health & M&E Advisor
[LinkedIn](https://www.linkedin.com/in/alhassan-mayei-058538193) · alhassanmayei@gmail.com

## License

Released under the [MIT License](LICENSE).
