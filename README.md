# README

## Git Logs: Explanation and Usage

### What is Git?
Git is a distributed version control system used for tracking changes in source code during software development. It enables multiple developers to work on a project simultaneously by keeping a history of changes and managing different versions of the project.

### Why Use Git?
- **Version Control**: Maintain a detailed history of code changes.
- **Collaboration**: Allow multiple contributors to work on the same project.
- **Branching**: Experiment with features without affecting the main codebase.
- **Tracking**: Understand who made specific changes and why.

### Git Actions
Git logs capture different actions performed by users, such as:
1. **Branch Created**: A new branch was added to the repository for feature development or bug fixes.
2. **Commit**: Changes were saved locally in the repository.
3. **Commit Pushed**: Committed changes were uploaded to the remote repository.
4. **Issue Opened**: A problem or feature request was reported.
5. **Issue Closed**: A previously opened issue was resolved or addressed.
6. **Pull Request**: A request to merge changes from one branch into another.
7. **Pull Request Merged**: A pull request was approved and the changes were integrated.


### Example of a Git Log
Below is an example of a Git log entry used in the project:
{
    "level": "INFO",
    "timestamp": "2024-11-19T00:00:00",
    "user": "jeanette90",
    "action": "issue closed",
    "repository": "DataForge_Project",
    "message": "User jeanette90 performed issue closed in repository DataForge_Project. Issue type: duplicate."
}


### 5 V's of the Git logs

This project demonstrates the effective use of Splunk to analyze and derive insights from log data based on the **5 V's of Big Data**. Below is an explanation of how each characteristic applies to the project:

---

## 1. Volume
- **Definition**: The total amount of data handled in the project.
- **In This Project**:
  - Data Volume: **100,000 records** were processed.
  - Log File Size: The raw data file was **16.67 MB**.

---

## 2. Velocity
- **Definition**: The speed at which data is generated and processed.
- **In This Project**:
  - Average Data Generation Rate: **45 events per day**.

---

## 3. Variety
- **Definition**: The diversity of data types and sources.
- **In This Project**:
  - Data Format: **Raw text logs**.

---

## 4. Veracity
- **Definition**: The quality, reliability, and trustworthiness of the data.
- **In This Project**:
  - **Data Cleaning**: The logs were transformed into **JSON format** for efficient indexing and querying in Splunk.

---

## 5. Value
- **Definition**: The actionable insights and business benefits derived from the data.
- **In This Project**:
  - Created **3 dashboards** to deliver meaningful insights
    1. **Activity Board**
    2. **Repository Health Monitoring**
    3. **Anomaly Detection**

