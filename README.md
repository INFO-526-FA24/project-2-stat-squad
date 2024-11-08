# Deep Learning Optimizer Dynamics

## Project 2 Overview

**Deep Learning Optimizer Dynamics** is a project that explores the different gradient descent optimizers used in machine learning and deep learning models. The goal of this project is to visualize the convergence behavior, efficiency, and suitability of popular optimizers such as Gradient Descent (GD), Stochastic Gradient Descent (SGD), Momentum, AdaGrad, RMSProp, and Adam, across various types of loss landscapes.

### Motivation

Optimizers are central to training deep learning models, yet understanding the differences in their behavior on different types of data and optimization surfaces is essential. This project provides an interactive and animated exploration of optimizer dynamics, helping students, researchers, and practitioners understand the strengths and limitations of each optimizer through visualizations.

By employing animation capabilities in R, this project aims to dynamically demonstrate the path of each optimizer across various loss surfaces, illustrating concepts like convergence speed, stability, and adaptability.

### Key Objectives

- To visualize and compare the behavior of different optimizers on different loss landscapes.
- To help users understand the impact of optimization algorithms on convergence and model performance.
- To create an interactive learning tool for educational purposes.

## Folder Structure

- **data/**: Contains all project-related datasets. The `README.md` file in this folder describes the structure and variables in the datasets used for analysis.
- **documents/**: Stores project-related documents, such as instructions, references, or any other important files.
- **presentation_images/**: This folder contains screenshots from presentations or slides related to the project.
- **styles/**: Stores CSS or other styling files used to define the visual aspects of the project's webpages or visualizations.

## Data Used

The project uses both synthetic and real-world data:

### Synthetic Data
- **Quadratic Function**: A smooth, convex paraboloid to demonstrate optimizer convergence on convex surfaces.
- **Rosenbrock Function**: A well-known non-convex function with a narrow valley, used to demonstrate optimizer behavior on complex landscapes.
- **Saddle Point Function**: A function with a saddle point at the origin, used to explore how optimizers handle mixed curvature.

### Real-World Data
We may also incorporate small real-world datasets, such as regression or classification data, to demonstrate the use of optimizers in practical scenarios.

## Approach

The project uses R for both data manipulation and visualization. Key steps include:

1. **Loss Landscapes & Visualizations**: Visualizing each optimizer’s path through various loss landscapes using animated plots.
2. **Interactive Analysis**: Displaying optimizer performance metrics such as loss vs. iterations, convergence rates, and learning rate adjustments.
3. **Comparative Analysis**: Comparing optimizers across multiple optimization surfaces and providing insights on their behavior.

## Weekly Plan

The project is divided into weekly tasks, and progress is tracked via team collaboration. Below is an overview of the major tasks and their completion status:

| Task Name                             | Status         | Assignees            | Due    | Priority  |
|---------------------------------------|----------------|----------------------|--------|-----------|
| Data Selection                        | Completed      | PG, PK, XD, RK       | Week 1 | High      |
| Data Cleaning & Preprocessing         | In Progress    | PG, PK, XD, RK       | Week 2 | High      |
| Data Visualization & Analysis         | Not Started    | PG, PK, XD, RK       | Week 3 | Moderate  |
| Working on Questions & Feedback       | Not Started    | PG, PK, XD, RK       | Week 4 | High      |
| Drafting and Reviewing Results        | Not Started    | PG, PK, XD, RK       | Week 5 | Moderate  |
| Final Report & Presentation           | Not Started    | PG, PK, XD, RK       | Week 6 | High      |

## Expected Outcomes

By the end of this project, we expect to deliver:

- **Visual Comparisons**: A set of visualizations comparing each optimizer’s convergence speed, path, and behavior across different loss surfaces.
- **Interactive Learning Tool**: An animated, interactive tool to aid in understanding the dynamics of various optimizers.
- **Insights on Optimizer Suitability**: Insights on how to choose the best optimizer for specific machine learning tasks.

## Conclusion

This project will provide a valuable educational resource for those learning about optimization techniques in machine learning, especially deep learning. By visually demonstrating how different optimizers behave on various types of loss landscapes, we aim to help learners make more informed decisions about optimizer selection for training deep learning models.

## Team

- **PG** - Prasanth Gubbala
- **PK** - Prudhvi Kandregula
- **XD** - Xenia De Gracia
- **RK** - Rishab RK

---

For more detailed information about the project's components, refer to the relevant subfolders:

- **data/**: Detailed descriptions of datasets and variables.
- **documents/**: Project-related documents and instructions.
- **presentation_images/**: Slides and screenshots from project presentations.
- **styles/**: Stylesheets for visual presentation.
