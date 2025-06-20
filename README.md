# Music App Basic Analysis

## Overview
This project analyzes real music streaming data to compare user behavior and musical preferences between residents of Springfield and Shelbyville. The analysis aims to validate hypotheses about how user activity varies by city and day of the week, providing actionable insights for music app optimization.

## Features
- **Data Exploration:** Detailed review of user activity, song plays, and city-based trends.
- **Data Preprocessing:** Handling of missing values, duplicates, and inconsistent genre labels.
- **Hypothesis Testing:** Statistical analysis to validate if user activity differs by city and day.
- **Visualization:** Tables and summaries to clearly present findings.
- **Business Insights:** Recommendations for app improvements and resource allocation.

## How to Use
1. Clone this repository or download the notebook.
2. Ensure you have the required dependencies (see below).
3. Open `musica_app_analysis.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells sequentially to reproduce the analysis and results.

## Requirements
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn

Install dependencies with:
```bash
pip install -r requirements.txt
```

## Data
The analysis uses the `music_project_en.csv` dataset, which contains anonymized user activity and song play records. The data is located in the `data/` directory.

## Project Structure
```
music_app_basic_analysis/
├── musica_app_analysis.ipynb
├── data/
│   └── music_project_en.csv
└── README.md
```

## Results
- Validated that user activity varies by both city and day of the week.
- Found that Springfield users are more active than Shelbyville users on all days analyzed.
- Identified Friday as the day with the highest number of songs played, suggesting a need for increased server resources.

## License
This project is for educational and demonstration purposes.

---

