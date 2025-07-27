## Museum recognition system with Support Vector Machine

1. Recognize which museum the query images are pointing to built with Support Vector Machine.
2. Accuracy: 96%
3. Training set: 90 images taken from 3 different museums (UMNO, Maritime, Youth) in different durations.

#### What is Support Vector Machine (SVM)?
A **supervised** machine learning algorithm used for both classification and regression tasks (predicting continuous outputs rather than discrete classes).
It finds a hyperplane (decision boundary / line that divides data) or set of hyperplanes that best separates different classes of data points in a high-dimensional space.
The **goal is to maximize the margin**, or distance, between the hyperplane and the closest data points (support vectors) from each class.

#### Supervised Learning:
SVMs learn from **labeled** data to make predictions on new, unseen data.

#### Classification and Regression:
While SVMs are primarily known for classification, they can also be used for regression tasks by predicting continuous outputs rather than discrete classes.

#### Hyperplane:
A decision boundary that separates different classes in a multi-dimensional space. In simpler terms, it's a line (in 2D) or a plane (in 3D) that divides the data into different groups.

#### Support Vectors:
The data points closest to the hyperplane, which are crucial for determining the hyperplane's position and the margin.

#### Margin:
The distance between the hyperplane and the support vectors. SVMs aim to maximize this margin for better generalization and accuracy.

#### Kernel Trick:
When data is not linearly separable (meaning it can't be divided by a straight line or hyperplane), SVMs use a kernel function to map the data to a higher-dimensional space where it becomes separable.

#### Hard Margin vs. Soft Margin:
Hard margin SVMs try to perfectly separate the data without any misclassifications, while soft margin SVMs allow for some misclassifications to handle noisy or non-ideal data.

---

SVMs find the "best" separation between classes by maximizing the margin and using support vectors to define the decision boundary. This makes them effective for various tasks, including image classification, text categorization, and data analysis.
