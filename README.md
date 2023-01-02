# Unsupervised-machine-learning-challenge

My assignment can be viewed in Data.ipynb file.

Instructions
This activity is broken down into four parts:

# Part 1: Prepare the Data
Read myopia.csv into a Pandas DataFrame.

Note: This file can be found in your Module 20 Challenge files.
Remove the "MYOPIC" column from the dataset.

Note: The target column is needed for supervised machine learning, but it will make an unsupervised model biased. After all, the target column is effectively providing clusters already!
Standardise your dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values.

![image](https://user-images.githubusercontent.com/107616415/210191318-b2ec9039-e2be-4df2-a079-c363947095f2.png)


# Part 2: Apply Dimensionality Reduction
Perform dimensionality reduction with PCA. How did the number of the features change?
Hint: Rather than specify the number of principal components when you instantiate the PCA model, state the desired explained variance. For example, say that a dataset has 100 features. Using PCA(n_components=0.99) creates a model that will preserve approximately 99% of the explained variance, whether that means reducing the dataset to 80 principal components or 3. For this assignment, preserve 90% of the explained variance in dimensionality reduction.
Further reduce the dataset dimensions with t-SNE and visually inspect the results. To do this, run t-SNE on the principal components, which is the output of the PCA transformation.

Create a scatter plot of the t-SNE output. Are there distinct clusters?

![image](https://user-images.githubusercontent.com/107616415/210191328-c731a991-4478-4879-af9a-5cb3d9a830c8.png)



# Part 3: Perform a Cluster Analysis with K-means
Create an elbow plot to identify the best number of clusters. Make sure to do the following:

Use a for loop to determine the inertia for each k between 1 through 10.

If possible, determine where the elbow of the plot is, and at which value of k it appears.

![image](https://user-images.githubusercontent.com/107616415/210191351-0bffe7cc-f194-47d2-b85d-58f54d86583a.png)


# Part 4: Make a Recommendation
Based on your findings, write up a brief (one or two sentences) recommendation for your supervisor in your Jupyter Notebook. Can the patients be clustered? If so, into how many clusters?

![image](https://user-images.githubusercontent.com/107616415/210191365-311d8508-b58c-4dd4-b05f-10315ebfe80c.png)


# Thank you
