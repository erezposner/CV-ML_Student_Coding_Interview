# CV/ML Student Coding Interview
**Version:** 1.0  
**Last Update:** November 2023

## Introduction
Welcome to the CV/ML Student Coding Interview! This coding interview is designed to assess your ability to apply classic computer vision algorithms to solve real-world problems. During this interview, you will be asked to work on Python code for various computer vision tasks. You are expected to write the code from scratch and use any Python libraries you prefer. After completing each task, you will have a 15-30 minute explanation session to discuss your approach and the algorithms you used.

## Getting Started
Before you begin, please make sure to follow these steps:

1. **Clone** this GitLab repository to your local environment.
2. Create a **new branch** in the repository to work on the interview tasks. Name the branch something descriptive.
3. **Commit** your code changes to the branch, not the 'main' branch.

## Interview Details
- **Estimated Duration:** 90 minutes
- **Language:** Python

## Interview Tasks
You will be tasked with solving the following computer vision challenges:

### Task 1
Given several images located in the "images" folder, each capturing a white page with text written in marker, you are required to write a Python code that accomplishes the following tasks:

1.1. Load the images and preprocess them as you see fit.  
1.2. Implement an algorithm to create a binary mask where all pixels belonging to the white page are set to 255 (white) and all pixels belonging to the text or characters are set to 0 (black).  
1.3. Develop an algorithm that, given a binary mask, counts the number of letters or characters present.

### Task 2
To further evaluate the performance of your algorithm for Task 1.2 and 1.3, you should implement a metric to measure the quality of the binary mask and character counting results. The metric should provide quantitative feedback on how accurately your algorithm accomplishes these tasks. Please explain the chosen metric and include it in your code for each task.

## Instructions for Each Task
For each task, you should create a Python script to complete the assigned challenge. Ensure that your code is well-documented, follows best coding practices, and is easy to understand. You can use any Python libraries or tools that you prefer for these tasks.

In your script, please provide a brief explanation of your algorithm and methodology used to solve the problem. You should be prepared to discuss your code and the underlying algorithms during the explanation session.

## Evaluation and Performance
To evaluate the performance of your algorithm for Task 1.2 and 1.3, consider using metrics such as Intersection over Union (IoU) for the binary mask and character recognition accuracy for counting. These metrics can help quantify the accuracy of your results.

## Repository Structure
The repository structure contains an "images" folder with sample images to be used for Task 1. Please refer to these images as needed in your Python code.

Feel free to reach out if you encounter any issues or have any questions during the interview.

Best of luck with your coding interview!
