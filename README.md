# Sleep Productivity Dashboard

## Overview
The **Sleep Productivity Dashboard** is an analytical tool built with Tableau to explore the intricate relationships between sleep patterns, lifestyle habits, and productivity. The project incorporates raw data analysis, visualizations, and interactive dashboards to provide actionable insights.

## Features
- **Interactive Visualizations:** Dive into key metrics such as sleep duration, quality, and their impact on productivity.
- **Comprehensive EDA:** A detailed exploratory data analysis (EDA) notebook is included for transparency and reproducibility.
- **Customizable Filters:** Focus on specific demographics or lifestyle factors using interactive dashboard features.

## Dataset Description
The dataset used in this project (`Sleep Productivity Analysis Dataset.csv`) includes 374 observations and 15 features. Key columns include:

- `Person id`: Unique identifier for individuals.
- `Gender`: Gender of participants.
- `Age`: Age of participants.
- `Occupation`: Profession of individuals.
- `Sleep Duration (hours)`: Total hours of sleep per night.
- `Quality of Sleep (%)`: A rating of sleep quality (1-10 scale).
- `Physical Activity level (%)`: Daily activity levels.
- `Stress level`: Stress rating on a scale of 1-10.
- `BMI Category`: Classification of body mass index.
- `Blood Pressure`: Includes `BP_HIGH` and `BP_LOW` measurements.
- `Daily Steps`: Number of steps taken daily.
- `Sleep Disorders`: None, Mild, or Severe.

## Files in the Repository
1. **Sleep Productivity Analysis Dashboard.twbx**: Tableau Packaged Workbook containing the interactive dashboard.
2. **Sleep Productivity Analysis Dataset.csv**: The raw dataset used for analysis.
3. **Sleep Productivity Analysis EDA.ipynb**: Jupyter Notebook detailing the exploratory data analysis process.
4. **README.md**: Documentation explaining the project and its components.

## Getting Started
To use or explore this project, follow these steps:

### Prerequisites
- **Tableau Desktop**: Download and install [Tableau](https://www.tableau.com/) to open and interact with the dashboard.
- **Python (optional)**: Required to run the EDA notebook. Install necessary libraries using:
  ```bash
  pip install pandas matplotlib seaborn jupyter
  ```

### Instructions
1. **Open the Dashboard:**
   - Download the `Sleep Productivity Analysis Dashboard.twbx` file.
   - Open it in Tableau Desktop to explore visualizations and insights.

2. **Explore the Dataset:**
   - Open `Sleep Productivity Analysis Dataset.csv` to review the raw data.
   - Use the EDA notebook to view data cleaning, visualizations, and preliminary insights.

3. **Customize the Dashboard:**
   - Use Tableau’s interactive filters to tailor the visualizations to your interests.

## Insights and Key Findings
- **Optimal Sleep Duration:** Productivity peaks with 7-8 hours of sleep per night.
- **Impact of Sleep Quality:** Higher sleep quality scores strongly correlate with improved productivity.
- **Physical Activity:** Moderate activity levels are associated with better health and productivity outcomes.
- **Stress Levels:** High stress negatively affects productivity, even with adequate sleep.

## Repository Structure
```plaintext
|-- Sleep Productivity Analysis Dashboard.twbx
|-- Sleep Productivity Analysis Dataset.csv
|-- Sleep Productivity Analysis EDA.ipynb
|-- README.md
```

## Future Enhancements
- Include advanced metrics such as stress and physical activity trends over time.
- Develop predictive models to forecast productivity based on sleep and lifestyle patterns.
- Deploy an interactive web-based version of the dashboard for greater accessibility.

## Contact
For any questions or suggestions, please reach out:
- **Email:** [nidhi.bangar2004@gmail.com]

