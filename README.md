# Learning Analytics SQL Project

This project showcases SQL analytics skills using real-world data from the Stepik online learning platform.

## Dataset Overview

The data comes from the Stepik course platform and represents a simplified version of a real learning analytics dataset. It contains partial records of students' activities to ensure fast and efficient analysis.

### Course Structure
- The course is divided into **modules**.
- Each module contains several **lessons**, and each lesson consists of **steps**.
- Steps have a position within the lesson.

### Student Activity
- Users register for the course and provide a name.
- All student activity is tracked, including:
  - Which steps they completed
  - Whether answers were correct
  - How many attempts were made
  - Timestamps of submissions
- If a student completes the course, a certificate issue date is recorded.

This kind of data is the foundation for **learning analytics**, a field focused on measuring, collecting, analyzing, and reporting data about learners and their contexts to better understand and improve learning outcomes.

## Dataset Specifics

The dataset used in this project includes a subset of users and steps, chosen to reflect typical student behavior while keeping the data volume manageable:

- A representative sample of **64 users** was selected based on the number of completed tasks.
- Only steps from **lessons 1.2, 2.2, and 2.4** are included.
- The final dataset includes **over 2,000 step attempts**.

> Note: All student names have been anonymized.

## Project Goal

The main objective of this project is to:
- **Demonstrate SQL querying and analysis skills**
- Extract insights about student learning behavior
- Identify patterns such as:
  - Repeated attempts
  - Correct/incorrect submission sequences
  - Learning trajectories

The project includes several SQL case studies and visual explanations of learning trends.

## Contents

- `student_course_analysis.ipynb` – Main Jupyter Notebook with SQL queries and insights
- `images/` – Visualizations used in the notebook
- `README.md` – This file

## How to Run

To open this notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/viktory-koroliova/sql-students-project/blob/main/sql-students-project.ipynb)

## 🧩 Tools & Technologies

- SQLite
- Jupyter Notebook
- Pandas
- SQL (CTEs, window functions, joins, aggregations)
