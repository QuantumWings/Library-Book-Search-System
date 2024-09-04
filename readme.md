# Visualization of library book search system indicators

## Introduction

This project is an interactive web application for visualizing various performance indicators of library book search systems. It simulates a library environment, with a particular focus on searching for Harry Potter-related books, and provides rich metrics and visualization tools to evaluate search performance.

Check out the demo [here](https://quantumwings.github.io/Library-Book-Search-System/).

Key features include:
- Adjustable search parameters
- Real-time updated performance metrics
- Interactive chart display
- Responsive design to adapt to different screen sizes

This tool will be a valuable resource for librarians, information science researchers, and system developers to better understand and optimize search algorithms.

## Main functions

1. **Parameter adjustment**:
 - Total number of books (100-1,000,000)
 - Number of Potter books (1-10,000)
 - Relevance threshold
 - efficiency slope
 - Efficiency intercept
 - Search accuracy
 - Search for midpoint

2. **Visual charts**:
 - Linear regression line
 - Threshold classifier step function
 -Sigmoid function curve
 - Interactive Plotly charts that support zoom, pan and hover functions

3. **Performance Index**:
 - True Positive Rate (TPR)/Recall Rate
 - Accuracy
 - F1 score
 - False positive rate (FPR)
 - False Negative Rate (FNR)
 - Accuracy
 - ROC curve and AUC
 - PR curve and average accuracy
 - Confusion matrix

4. **Other functions**:
 - Customized chart controls (switch annotations, add sample points, etc.)
 - Real-time updated indicator calculations
 - Responsive design

## Installation and Setup Guide

### Environmental requirements
- Modern web browser (supports HTML5, CSS3 and ES6+)
- Internet connection (for loading external JavaScript libraries)

### How to use
1. Download the project file to your local computer.
2. Open the `index.html` file using a web browser.
3. Make sure your network connection is working properly so that necessary external resources can be loaded.

## Instructions for use

### Operation steps
1. After opening the application, you will see the control panel on the left, the chart area in the middle, and the indicator panel on the right.
2. Adjust various parameters on the left panel:
 - Use the input boxes to change the total number of books and the number of Potter books.
 - Use the sliders to adjust other parameters.
3. Observe the changes in the middle chart. The chart will update in real time to reflect your settings.
4. View various performance indicators on the right panel, which will also be updated as parameters change.
5. Use the control buttons above the chart for additional interactions, such as adding sample points or switching annotations.

### Example
Let's say you want to simulate a 100,000-book library containing 500 Potter-related books:
1. Set "Total Books" to 100000 in the left panel.
2. Set "Potter Books" to 500.
3. Adjust the "Relevance Threshold" slider and observe the impact on search performance.
4. Look at the changes in metrics in the right panel, paying special attention to the changes in recall and precision.

## Project structure

- `index.html`: Contains all the necessary HTML, CSS and JavaScript code to build and display the interactive interface of the library search system.

Main category structure:
- `SearchModel`: processing data and calculation logic
- `SearchView`: manages user interface and chart updates
- `SearchController`: coordinates models and views, handles user input

## Contribution Guidelines
If you would like to contribute to this project, please follow these steps:
1. Fork this repository and clone it to the local environment.
2. Create a new branch for development (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add some feature').
4. Push the changes to your branch (git push origin feature-branch).
5. Submit a Pull Request.

## Authorization information
This project is licensed under the terms of [MIT](https://opensource.org/licenses/MIT).

## Contact Information
If you have any questions or suggestions, please contact the project maintainer: quantumwingslab@gmail.com

## Other information
- This project uses the following external libraries:
 - Plotly.js: for creating interactive charts
 - Math.js: for advanced mathematical calculations
- It is recommended to use the latest version of Chrome, Firefox or Safari browser for the best experience.
- This project is primarily for educational and research purposes and is not recommended for use in production environments without adequate testing.
