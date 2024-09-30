# Clustering and Visualization of Iris Dataset Using Self-Organizing Maps (SOM)
## SOM
A Self-Organizing Map (SOM) is a type of artificial neural network used for unsupervised learning, which means it works without labeled data.
The primary purpose of SOM is to reduce the dimensionality of data while preserving the topological relationships among the data points.
It maps high-dimensional data onto a 2D grid, where similar data points are placed close to each other, making it useful for clustering and data visualization.
## Visualization of Iris
In this example, we used a Self-Organizing Map (SOM) to cluster and visualize patterns in the well-known Iris dataset. 
The Iris dataset contains 150 samples of flowers from three species (Setosa, Versicolor, and Virginica), with each flower described by four features. 
First, we standardized the data to ensure that no feature dominates due to its scale. We then trained a SOM, a type of unsupervised neural network, on this data. 
The SOM mapped the high-dimensional data onto a 2D grid, clustering similar flowers together based on their feature similarities. 
After training, we visualized the SOM using a distance map, which shows regions of high and low similarity.
We marked each flower species on the map, revealing clear clusters corresponding to the three different species. 
This allowed us to see how flowers with similar characteristics were grouped together, with boundaries representing differences between species. 
The output clearly showed how SOM can reduce dimensionality and uncover hidden patterns in data without needing labeled information.
## Process
This Self-Organizing Maps (SOM) has been executed in Google Colab
Upload the given python file to Google colab to execute
![som11](https://github.com/user-attachments/assets/6c8968a1-5d3f-4543-9e28-42abffe7ba6c)
![som22](https://github.com/user-attachments/assets/017cbea7-65d2-4fbd-9d67-5e7ef05ef097)
The Image given below shows the Visualization of the Various Iris species
![som4](https://github.com/user-attachments/assets/64f6c37f-2a5a-4cdd-9e4c-1325cdee8669)
## Output
we visualized the SOM as a heatmap. This map shows how far apart nodes (or neurons) are from each other. 
The darker regions represent nodes that are close to each other (high similarity), while the lighter regions represent nodes that are further apart (lower similarity).
Markers: We plotted markers ('o', 's', 'D') on the SOM grid to represent different Iris species:
Setosa: Marked with red 'o'
Versicolor: Marked with green 's'
Virginica: Marked with blue 'D'
Each marker was placed on the node that best represents the corresponding flower sample.


The SOM clusters similar data points together, which means that samples from the same species (like Setosa, Versicolor, or Virginica) will tend to map to the same or nearby nodes in the grid.
In the distance map, lighter regions indicate boundaries between clusters, which represent the differences between species. By analyzing these clusters and boundaries, we can visually see how the data points (flowers) relate to each other in terms of their features.
