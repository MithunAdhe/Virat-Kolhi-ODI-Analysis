# Virat Kohli ODI Performance - Exploratory Data Analysis

## 🌟 Project Overview
This project dives deep into the ODI performance of one of the greatest cricketers, **Virat Kohli**. Using a comprehensive dataset of his ODI matches, I’ve explored key aspects of his performance including:
- Top venues where he excels.
- His highest average scores against opposition teams.
- His performance across different batting positions, innings, and match scenarios.

**Objective**:  
To uncover hidden patterns and insights that reveal Virat Kohli’s consistency and strengths as an ODI player.

## 🧹 Data Cleaning
The dataset was carefully cleaned to ensure accuracy. The steps included:
- **Missing Value Handling**: All missing values were identified and managed.
- **Duplicate Removal**: Ensured no duplicate entries that could skew analysis.
- **Standardization**: Data formats (e.g., dates, numerical columns) were standardized for smooth processing.

## 📊 Exploratory Data Analysis (EDA)
Below are the key questions I addressed through this analysis, along with their visual insights.

### 1. **Top 5 Grounds Where Virat Kohli Scored the Most Runs**
*Key Insight*: These venues have seen Kohli dominate the field with massive run totals.  
![Top 5 Grounds](images/Top_5_Ground.png)

### 2. **Opposition Against Whom He Has the Highest Average Score**
*Key Insight*: Kohli tends to perform exceptionally well against certain teams.  
![Top Opposition](images/Avg_Runs_Against.png)

### 3. **Distribution of His Scores (Runs) in ODIs**
*Key Insight*: Visualizing how frequently Kohli scores in different ranges.  
![Run Distribution](images/Distribution_of_runs.png)

### 4. **Strike Rate Distribution Across Different Innings (First vs. Second)**
*Key Insight*: How his strike rate varies between chasing and setting targets.  
![Strike Rate Distribution](images/sr_distribution.png)

### 5. **Scoring Pattern Based on Number of Boundaries (4s and 6s)**
*Key Insight*: Kohli’s boundary-hitting ability analyzed.  
![Boundary Scoring Pattern](images/Runs_Vs_Bondries.png)

### 6. **Distribution of Balls Faced in an Inning**
*Key Insight*: How many balls Kohli tends to face in his ODI innings.  
![Balls Faced Distribution](images/Distribution_Of_BF.png)

### 7. **How Batting Position Affects Runs Scored**
*Key Insight*: Kohli’s performance across different positions in the batting order.  
![Batting Position and Runs](images/Runs_By_Batting_POS.png)

### 8. **Most Frequent Types of Dismissals for Virat Kohli**
*Key Insight*: Understanding how Kohli often gets out, which informs his vulnerabilities.  
![Dismissals](images/Types_Of_Dismissal.png)

### 9. **Venues with His Best Performances (Centuries and Half-Centuries)**
*Key Insight*: A look at where Kohli has produced his best match-winning knocks.  
![Best Venues](images/Best_Venus.png)

## 🛠️ Technologies Used
- **Python**: For data manipulation and analysis (Pandas)
- **Data Visualization**: Matplotlib and Seaborn for creating detailed graphs.
- **Jupyter Notebooks**: To document and present the EDA.

## 📈 How to Run the Project

To run this project locally, follow these steps:

1. **Clone the Repository**:  
   Open your terminal or command prompt and run the following command to clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/virat-kohli-odi-performance-analysis.git

2. **Navigate to the Project Directory**:
Change into the project directory using:

    ```bash
    cd virat-kohli-odi-performance-analysis

3. **Set Up a Virtual Environment (Optional but Recommended)**:
It’s a good practice to create a virtual environment for Python projects to manage dependencies. You can do this with the following commands:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate     # On Windows
    
4. **Install Required Dependencies**:
Install the necessary packages using pip. If you have a requirements.txt file, run:

    ```bash
    pip install -r requirements.txt
  
5. **Open the Jupyter Notebook**:
Start Jupyter Notebook with the following command:

    ```bash
    jupyter notebook
