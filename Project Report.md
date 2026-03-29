1. Introduction
Real-world problem solving is changing as a result of artificial intelligence (AI) and machine learning (ML). Ineffective time management and inadequate study planning are two common problems that students encounter. Choosing which subjects to prioritize can be difficult for students, particularly when there are several deadlines and different levels of difficulty.

The AI-Based Smart Study Planner project seeks to offer a clever solution that aids students in efficiently organizing their coursework. The system creates an ideal study schedule based on deadlines and subject difficulty using heuristic-based decision making and machine learning techniques.

2. Problem Description

Students frequently deal with the following issues:

Incapacity to successfully prioritize topics
Stress caused by ineffective time management
Absence of organized study schedules
Managing several subjects with varying deadlines can be challenging.

Conventional planning techniques are labor-intensive and ineffective. An intelligent system that can automatically produce an ideal study plan is therefore required.

3. Goal

This project's primary goals are:

to create an AI-powered system that aids students in organizing their study time
To forecast subject priority using machine learning
To put in place a mechanism for making decisions based on input parameters
To offer an easy-to-use interface for communication
To better comprehend the study plan by visualizing it

4. Methodology

The project follows a structured approach:

Data Collection
A dataset containing subject difficulty, days left, and priority was created.
Data Processing
The dataset is loaded and split into input features and output labels.
Model Training
A machine learning model is trained using the dataset.
User Input Handling
Users provide subject name, difficulty, and deadline.
Priority Prediction
The system predicts priority using the trained model.
Scheduling
Subjects are sorted based on predicted priority.
Visualization
Results are displayed using a graphical interface.

5. Algorithms Used
 1. Linear Regression (Machine Learning)
Used to predict the priority score of subjects
Takes inputs:
Difficulty
Days left
Outputs:
Priority score

Linear Regression works by fitting a line to the data and predicting values based on learned patterns.

 2. Heuristic-Based Sorting
Subjects are sorted based on predicted priority
Higher priority subjects are scheduled first

This approach mimics AI search and decision-making techniques.

6. Implementation

The project is implemented using Python and consists of three main modules:

 1. Model Module (model.py)
 Trains the machine learning model
 Predicts priority values
 2. Planner Module (planner.py)
 Uses the trained model
 Generates a sorted study schedule
 3. User Interface (app.py)
 Built using Streamlit
 Takes user input
 Displays results and graphs
 Technologies Used:
 Python
 Pandas
 Scikit-learn
 Streamlit
 Matplotlib

7. Results

The system successfully:

Accepts multiple subjects as input
Predicts priority for each subject
Generates an optimized study plan
Displays results in sorted order
Visualizes priorities using bar graphs
Output Example:
Subjects with higher difficulty and fewer days are given higher priority
The generated plan helps students focus on important subjects first

8. Challenges

During development, several challenges were faced:

Import errors due to module structure
File path issues while loading dataset
Handling empty or invalid user inputs
Debugging Streamlit blank screen issues
Managing Python module dependencies

These challenges were resolved through debugging, restructuring code, and simplifying project architecture.

9. Conclusion

The AI-Based Smart Study Planner successfully demonstrates how AI and ML can be applied to solve real-world problems like study planning.

The system provides:

Intelligent decision-making
Efficient scheduling
User-friendly interface

This project aligns with AI concepts such as:

Intelligent agents
Machine learning models
Problem-solving techniques
