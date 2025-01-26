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

## Analysis and Key Insights

### Topic-Wise Performance
We analyzed performance by grouping data by topics to calculate:
- Average Score
- Maximum Score
- Average Accuracy

#### Visualization: Average Scores by Topic
![Average Scores by Topic](avg_score_by_topic.png)

From the analysis:
- **Body Fluids and Circulation** has the highest average score (86.67).
- Topics like **Respiration and Gas Exchange** show relatively lower performance (24.0 average score).

### Accuracy Analysis
Further insights include:
- Higher scores generally correlate with higher accuracy percentages.
- Certain topics show significant variability in user performance.

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

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/vedanta2003/assign.git
   ```

2. Install the required libraries:
   ```bash
   pip install pandas matplotlib
   ```

3. Run the analysis:
   Execute the Jupyter notebook `main.ipynb` to reproduce the analysis and generate visualizations.

## Submission Guidelines:
Please submit the source code via a GitHub link, including:
- A README with setup instructions, project overview, and approach description.
- Screenshots of key visualizations and a summary of insights.
- A 2-5 minute video demonstrating the script/API with sample inputs, outputs, and a brief explanation of the logic and recommendations.

## Requirements:
- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- scikit-learn
- Jupyter Notebook

## Contributions and Future Work

Contributions are welcome! Future improvements could include:
- Adding more visualizations, such as trends over time or topic comparisons.
- Applying advanced analytics or machine learning to predict user performance.

Feel free to open issues or submit pull requests.

## Contact
For queries or suggestions, reach out to **Vedanta Yadav** via GitHub.




