# Perceptron Algorithm on Placement Dataset
---
- This repo. demonstrates the implementation of the Perceptron algorithm on a real-world dataset — placement.csv.The main goal is to classify or predict outcomes based on features related to student placement, such as academic scores, specialization, or other relevant factors.

##### Why I have created this repository on my GitHub account
- Learning Purpose: As a self-learner on a Data Science journey, this repo. showcases practical understanding of supervised machine learning and the foundational Perceptron algorithm.
- Model Exploration: The Perceptron is a simple yet powerful algorithm — a key building block for modern deep learning. Implementing it helps solidify core ML concepts like linear classification and weight updates.
- Hands-on Practice: Working with real datasets like this helps bridge the gap between theory and practice.
![WhatsApp Image 2025-08-07 at 04 33 35_494275fc](https://github.com/user-attachments/assets/92643bc1-f22a-4de9-a7b1-c73c54f5eaa6)
<img width="1317" height="503" alt="Screenshot 2025-08-07 013521" src="https://github.com/user-attachments/assets/e1fe09d8-ca06-4c57-81d2-72bf413ad10b" />

---
# Problem with perceptron algorithm 

- Perceptron only classify linearly separable data
  - The Perceptron algorithm is a linear classifier, meaning it tries to find a single linear decision boundary (a line in 2D, a plane in 3D, or a hyperplane in higher dimensions) that separates data into two classes.
- What is linearly separable data?
  - Data is linearly separable if there exists a straight line (or hyperplane) that can completely separate the two classes without any overlap or misclassification.
  - **Linearly separable**: Two clusters of points separated by a straight line.
  - **Not linearly separable**: Concentric circles (inner circle = class 0, outer circle = class 1). No straight line can separate them.
- What happens if data is not linearly separable?
If data is linearly separable, the perceptron will converge to a solution in a finite number of steps.
If data is not linearly separable, the algorithm fails to converge and keeps updating weights indefinitely.

****In real situations, if the data cannot be separated by a straight line, the perceptron may keep changing its decision boundary again and again (never settling), or it may stop at a boundary that is not good and still makes mistakes in classifying some points.****
