# Personalized Student Recommendations

This Python-based solution analyzes quiz performance and provides students with personalized recommendations to improve their preparation. The system leverages current and historical quiz data to offer insights, identify weak areas, and generate actionable steps for improvement.

## App Link:
[NEET Testline - on Google Play](https://play.google.com)

## Data Overview:
You will work with two datasets:

1. **Current Quiz Data**: 
   - Details of the user's latest quiz submission, including questions, topics, and responses, etc. 
   - **API Endpoint**: Quiz Submission Data.

2. **Historical Quiz Data**: 
   - Performance data from the last 5 quizzes for each user, including scores and response maps (Key: Question Id, Value: Selected Option Id). 
   - **API Endpoint**: Historical Quiz Data.

## Task Breakdown:
### 1. **Analyze the Data**:
   - Explore the schema and identify patterns in student performance by topics, difficulty levels, and response accuracy.

### 2. **Generate Insights**:
   - Highlight weak areas, improvement trends, and performance gaps for a given user.

### 3. **Create Recommendations**:
   - Propose actionable steps for the user to improve, such as suggested topics, question types, or difficulty levels to focus on.

### 4. **Bonus Points**:
   - Analyze and define the student persona based on patterns in the data.
   - Highlight specific strengths and weaknesses with creative labels or insights.

## Steps in the Python Notebook:
1. **Loading Data**:
   - Import and clean the datasets.
   - Ensure the data is ready for analysis.
   
2. **Analyzing Data**:
   - Explore the dataset to identify key features such as topics, difficulty levels, and accuracy.
   - Analyze student performance trends.

3. **Highlight Weak Areas**:
   - Identify subjects or question types where the student is struggling.
   - Analyze the user's past quizzes to find consistent problem areas.

4. **Generate Recommendations**:
   - Suggest topics, question types, and difficulty levels to focus on for improvement.

5. **Student Persona**:
   - Define the student persona based on performance patterns and trends.
   - Label strengths and weaknesses creatively.

6. **Visualizations**:
   - Provide visualizations to showcase insights like topic accuracy, score trends, and improvement potential.

## Submission Guidelines:
Please submit the source code via a GitHub link, including:
- A README with setup instructions, project overview, and approach description.
- Screenshots of key visualizations and a summary of insights.
- A 2-5 minute video demonstrating the script/API with sample inputs, outputs, and a brief explanation of the logic and recommendations.

## Setup Instructions:
1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   ```

2. **Install Required Libraries**:
   Install the required Python libraries using the following command:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**:
   Open the Jupyter notebook and run all cells to load, analyze, and generate recommendations based on the quiz data.

## Requirements:
- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- scikit-learn
- Jupyter Notebook

## License:
This project is licensed under the MIT License.

---

