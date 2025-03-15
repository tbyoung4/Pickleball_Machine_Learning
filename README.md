# Pickleball Machine Learning
Post Hoc Analysis of Masters Thesis Data 

This repository showcases my machine learning skills utilitizing static ankle range of motion data from my masters thesis to predict the question: 
Do biomechanical subgroups, based on pre- and post-pickleball movement ankle range of motions, emerge with distinct demographic profiles?

The primary purpose of the thesis was to determine if an acute stretching session could elongate the Achilles Tendon in pickleball players. 
This required two visits to the biomechaincs lab where one day was a baseline while the other day was identical with the addition of 4 minutes of static dorsiflexion stretching in the knees extended position as well as the knees flexed.

An abstract was accepted by The University of Tennessee Knoxville for the 2025 Graduate Student Colloquium and is attached as a pdf.
A powerpoint presentation will also be uploaded soon.

A code book is avalaible as a pdf to understand the variables of interest.
This analysis was performed in google colab and is avaliable as a py and ipynb file.

# Overall of Analysis Performed 
1. Data processed in excel 
2. Apply t-SNE to reduce the 76 goniometer measurements to 2 dimensions for visualization.
3. K-Means clustering to group 
4. Assign each data point a label corresponding to its cluster assignment
5. Split the data into training and testing sets
6. ML Algorithms ultilized
7. Evaluate the clustering performance

# Important Notes 
- This data set is a prelimenary analysis as it only contains 31 people. The complete data set contains 40 people and will be uploaded when data processing is complete.
- The value "-99" is set as a missing variable as not all subjects came back for a second assessment, so only 29 people are included in the pre processing step.
