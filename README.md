# CV/ML Student Coding Interview
**Version:** 1.0  
**Last Update:** November 2023

## Introduction
Welcome to the CV/ML Student Coding Interview! This coding interview is designed to assess your ability to apply classic computer vision algorithms to solve real-world problems. During this interview, you will be asked to work on Python code for various computer vision tasks. You are expected to write the code from scratch and use any Python libraries you prefer. After completing each task, you will have a 15-30 minute explanation session to discuss your approach and the algorithms you used.

## Environment Setup Requirements
The interview should be run on your own computer, To prepare for the coding interview, ensure your computer environment is set up correctly. This chapter outlines the essential requirements for your computer environment.
### Computer Setup
You must have your own computer with an active internet connection. Ensure you have administrator privileges on your computer. Additionally, this interview project is hosted on a Git repository, so you should have Git installed to clone the project and create a branch for your work.

### Python Libraries
You will need specific Python libraries for the interview. These libraries will be listed in a file named requirements.txt. To install them:
```shell
pip install -r requirements.txt
### Integrated Development Environment (IDE)
Choose your preferred IDE, but have one ready for the interview. Ensure it's configured for Python development.

Popular IDEs include Visual Studio Code, PyCharm, and Jupyter Notebook (for data science).

## Getting Started
Before you begin, please make sure to follow these steps:

1. **Clone** this GitLab repository to your local environment.
2. Create a **new branch** in the repository to work on the interview tasks. Name the branch in the format of `{firstname_lastname}`.
3. **Commit** your code changes to the branch, not the 'main' branch.

## Interview Details
- **Interview Duration:** up to 120 minutes
- **Language:** Python

## Interview Tasks
You will be tasked with solving the following computer vision challenges, each implemented within separate functions:

### Task 1
Given several images located in the "images" folder, each capturing a white page with text written in marker, you are required to write a Python code that accomplishes the following tasks, each within separate functions:

1.1. Load the images and preprocess them as you see fit.  
1.2. Implement a function to create a binary mask where all pixels belonging to the white page are set to 255 (white) and all pixels belonging to the text or characters are set to 0 (black).  

> **Note:** Task 1.3 depends on the completion of Task 1.2. However, you can proceed to Task 2 and include a metric for Task 1.2.

1.3. Develop a function that, given a binary mask, counts the number of letters and characters present.

### Task 2
To further evaluate the performance of your algorithm for Task 1.2 and 1.3, you should implement a metric to measure the quality of the binary mask and character counting results. The metric should provide quantitative feedback on how accurately your algorithm accomplishes these tasks. Please explain the chosen metric and include it in your code for each task.

## Repository Structure
The repository structure contains an "images" folder with sample images to be used for Task 1. Please refer to these images as needed in your Python code.


