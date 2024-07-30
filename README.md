# Data Science Project 
## Fashion Apparel Classification

## Team members:   
• Asmaa Thabet
• Youssef ELMOUMEN
• Ali Abed Al Hadi 
• Doha Djellit

### Dataset - Fashion MNIST
The Fashion MNIST dataset is a modern alternative to the traditional MNIST dataset typically used for benchmarking machine learning algorithms. Created by Zalando Research, it contains 70,000 grayscale images of 10 fashion categories, each image sized at 28x28 pixels. The dataset aims to serve as a direct drop-in replacement for the original MNIST dataset for machine learning and deep learning purposes, offering a bit more complexity for classification tasks without the need for the high computational power required by larger color images.
The dataset contains 70,000 instances. Each instance is a 28x28 pixel grayscale image, which translates to 784 features (each pixel is a feature). It is split into a training set of 60,000 images and a test set of 10,000 images. The classes include T-shirts/tops, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots, providing a varied array of apparel for classification.
In fact, MNIST is often the first dataset researchers try. "If it doesn't work on MNIST, it won't work at all", they said. "Well, if it does work on MNIST, it may still fail on others."
Dataset link: https://www.kaggle.com/datasets/zalando-research/fashionmnist 
Dataset Source website: https://github.com/zalandoresearch/fashion-mnist 

### Why did we choose this idea? 
In the fast-paced world of fashion, understanding and classifying different types of apparel is crucial for inventory management, trend analysis, and customer recommendation systems. With the continual shift in fashion trends and the significant volume of new clothing items produced, automated classification can aid in managing large inventories and enhance the shopping experience for consumers. Moreover, it supports designers and retailers in quickly categorizing and recommending new styles and trends to customers.

### About the Project
This project will utilize the Fashion MNIST dataset to train a Convolutional Neural Network (CNN) model for the classification of different types of apparel. The goal is to achieve high accuracy in identifying the category of clothing items depicted in the images. This endeavor not only serves as an excellent opportunity for practical application of deep learning techniques but also has real-world utility in enhancing e-commerce platforms, streamlining inventory management, and personalizing shopping experiences.

### Major Tasks: 
•	Data Loading: Given the manageable size of the dataset, the entire dataset will be utilized for this project. The task involves loading the dataset into Python for preprocessing and model training.
•	Data Visualization & Exploration: Initial data exploration will include visualizing the different apparel classes within the dataset to understand the distribution of categories and the characteristics of images in each class.
•	Data Preprocessing & Image Augmentation: This includes normalizing the image pixel values, encoding the categorical class labels, and possibly augmenting the dataset to improve model generalizability.
•	Build, Train, and Test CNN Model: Design a CNN architecture suited for the classification task. The process involves experimenting with different layers, activation functions, and hyperparameters to find the optimal model.
•	Analyze and Visualize Results: Evaluate the model's performance using metrics such as accuracy and loss. Visualize the classification results to assess how well the model is performing across different apparel categories.
Through these tasks, this project aims to develop a robust model capable of classifying fashion apparel with high accuracy, contributing valuable insights to the fields of computer vision and fashion retail.
