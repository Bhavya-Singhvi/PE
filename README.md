# PE
Gym members exercise tracking

Overview
This Jupyter Notebook (PE.ipynb) contains an analysis of gym members' exercise tracking data. The dataset includes various metrics such as age, gender, weight, height, heart rate, session duration, calories burned, workout type, fat percentage, water intake, workout frequency, experience level, and BMI. The notebook performs data preparation, cleaning, feature engineering, and exploratory data analysis (EDA) to gain insights into the dataset.

Dataset
The dataset used in this analysis is gym_members_exercise_tracking.csv, which contains 100 rows and 15 columns of gym members' exercise data.

Columns in the Dataset:
Age: Age of the gym member.

Gender: Gender of the gym member (Male/Female).

Weight (kg): Weight of the gym member in kilograms.

Height (m): Height of the gym member in meters.

Max_BPM: Maximum heart rate during the workout.

Avg_BPM: Average heart rate during the workout.

Resting_BPM: Resting heart rate.

Session_Duration (hours): Duration of the workout session in hours.

Calories_Burned: Calories burned during the workout.

Workout_Type: Type of workout (e.g., Yoga, HIIT, Cardio, Strength).

Fat_Percentage: Body fat percentage.

Water_Intake (liters): Water intake in liters.

Workout_Frequency (days/week): Frequency of workouts per week.

Experience_Level: Experience level of the gym member (1-3).

BMI: Body Mass Index.

Notebook Structure
Data Preparation:

The dataset is loaded using pandas.

The first 100 rows are selected for analysis.

Basic information about the dataset, such as shape and the first few rows, is displayed.

Data Cleaning:

Missing values are checked and filled using the mean for numerical columns and the mode for categorical columns.

Duplicates are removed from the dataset.

Feature Engineering:

A new feature workout_duration_category is created by categorizing session duration into 'short', 'medium', or 'long'.

Summary statistics (mean, median, mode) are computed for numerical features.

Exploratory Data Analysis (EDA):

Histograms are plotted for numerical features to visualize data distributions.

The distribution of various features such as age, weight, heart rate, and BMI is analyzed.

Data Visualization:

Histograms are used to visualize the distribution of numerical features.

The notebook uses matplotlib and seaborn for plotting.

