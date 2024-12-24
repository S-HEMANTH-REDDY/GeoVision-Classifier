GeoVision Classifier

GeoVision Classifier is an image classification application designed to automatically categorize images of landscapes into six specific categories: buildings, forests, glaciers, mountains, seas, and streets. This project serves as a proof-of-concept application, showcasing the potential of deploying machine learning models for automated image classification.

Why Image Classification Matters

Image recognition is a critical component of artificial intelligence with applications in search engines, robotics, self-driving vehicles, and security systems. For consumers, it simplifies the task of organizing personal photo collections, offering automation for processes that would otherwise be tedious and time-consuming.

Data Source

The dataset used in this project was sourced from Kaggle and originally published on Analytics Vidhya as part of an image classification challenge by Intel. It contains 24,034 images split into training, validation, and test sets across six classes. A validation set was created by splitting the training data to enhance model development and evaluation.

Challenges

The main difficulty lies in distinguishing similar categories, such as mountains and glaciers or buildings and streets, as these classes often share overlapping features.

Process

The project follows the CRISP-DM framework:
	•	Business and data understanding.
	•	Data preparation and preprocessing.
	•	Iterative modeling and evaluation.
	•	Deployment of the best-performing model via a web application.

Modeling

A baseline model using a simple neural network was developed initially, but it underperformed with a 15% accuracy. Improved results were achieved with convolutional neural networks (CNNs). The final model achieved an 81% test accuracy, demonstrating its potential for practical use despite minor class misclassifications.

Success Criteria

The goal was to achieve at least 85% accuracy while minimizing overfitting. While the final model fell slightly short, the results indicate strong performance in most scenarios, with misclassifications often occurring in visually similar classes.

Deployment

A demo web application was created for local deployment, allowing users to sort a pre-defined set of images. Predictions were pre-processed and stored for demonstration purposes, showcasing the application’s functionality.

Future Developments
	•	Employing transfer learning for improved performance.
	•	Introducing an “other” category for unclassified images.
	•	Adding sub-categories for similar classes.
	•	Expanding the dataset to include more image categories.
	•	Developing an upload platform for user-provided images.

GeoVision Classifier is a step towards leveraging machine learning for seamless image organization, with future iterations focusing on scalability and enhanced usability.
