# Flight Delay Prediction and Analysis

**CS 418: Data Science – Final Project**

## Project Overview
This project aims to analyze and predict flight delays using a combination of:
- **Historical flight data** (Bureau of Transportation Statistics)
- **Real-time flight tracking** (OpenSky Network / Flightradar24)
- **Weather conditions** (NOAA / OpenWeatherMap)
- **Any other related datasets

*_(This is tentative, and may change as the project progresses)_*


We will explore how factors like time of day, airline, airport congestion, and weather influence delays, and build predictive models to forecast future delays. Ultimately, we plan to create an interactive dashboard that displays live delay predictions and historical trends.

## Goals
1. **Collect and Clean Data**: Gather and preprocess flight, weather, and airport congestion data.
2. **Exploratory Data Analysis (EDA)**: Identify patterns, correlations, and seasonal trends in delays.
3. **Machine Learning Models**: Implement regression or classification models to predict delay durations or the likelihood of delay.
4. **Interactive Dashboard**: Provide real-time visualizations and predictions for operational decision-making and passenger information.

## How to Get Started

### 1. Clone the Repository
To get a local copy of the project, run:
```bat
git clone https://github.com/<YourUserName>/flight-delay-analysis.git
cd flight-delay-analysis
```
### 2. Set Up a Virtual Environment
We recommend using a virtual environment to manage dependencies:
```bat
python -m venv venv
source venv/bin/activate (On Windows: venv\Scripts\activate)
```

### 3. Install Dependencies
We will maintain a `requirements.txt` file with necessary Python libraries. Once available, install dependencies inside your virtual environment using:
```bat
pip install -r requirements.txt
```

### 4. Explore the Folder Structure
```
This repository follows a structured approach for easy navigation:
flight-delay-analysis/
  ├── data/          # Contains raw and cleaned data files (or references to external datasets)
  ├── notebooks/     # Jupyter notebooks for EDA, modeling, and experimentation
  ├── scripts/       # Python scripts for data processing and ML models
  ├── docs/          # Documentation, reports, proposal slides, and references
  ├── .gitignore     # Git ignore rules for unnecessary files
  └── README.md      # Project overview and setup instructions
```

### 5. Contribute to the Project
Here’s how you can contribute to our collaborative workflow: 
- **Create a New Branch**  
  Before making changes, create a new branch for your feature or experiment:
  ```bat
  git checkout -b my-feature-branch
  ```

- **Make Your Changes and Commit**  
  After implementing changes, stage and commit them:
  ```bat
  git add .
  git commit -m "Added EDA notebook with initial visualizations"
  ```

- **Push to GitHub and Create a Pull Request**  
  Push your changes and open a pull request (PR) to merge into `main`:
  ```bat
  git push origin my-feature-branch
  ```

- **Review and Merge**  
  Any Team members can review your PR before merging it into the `main` branch.

## Project Status
- [x] Data Collection & Preprocessing  
- [ ] Exploratory Data Analysis (EDA)  
- [ ] Machine Learning Model Development  
- [ ] Interactive Dashboard Development  
- [ ] Final Report & Presentation  

We will update this checklist as we make progress.

## Team Members
| Name      | UIC Email        | GitHub Handle     |
|-----------|------------------|-------------------|
| Ricky M   | fmass3@uic.edu  | @fmassa1   |
| Sai C  | schit7@uic.edu  | @Sschittala   |
| Maryann O | aolug3@uic.edu  | @MaryannO45  |
| Matt J  | mwilkj2@uic.edu  | @mattwilk1017  |
| Jeremiah B | jbenj2@uic.edu  | @juebenjamin   |

## Acknowledgments
- Bureau of Transportation Statistics for historical flight data
- OpenSky and Flightradar24 for real-time tracking APIs
- NOAA and OpenWeatherMap for weather data
- CS 418 course instructors for guidance
