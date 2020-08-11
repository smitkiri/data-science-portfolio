# Data Science Portfolio

This website lists all the data science project's that I've worked on for academic, self-learning or hobby purposes. 

For a more visually appealing portfolio experience, visit [smitkiri.github.io](https://smitkiri.github.io/)

### Machine Learning
- [News QA](https://github.com/smitkiri/news-qa): Developed a question answering transformer model for news articles by fine-tuning BERT and DistilBERT using PyTorch. Deployed the model on GCP using FastAPI. The front end UI was built using HTML, Bootstrap and jQuery. The front-end would make jQuery AJAX call to the back-end API to get the predictions. The [website](https://smitkiri.github.io/newsqa) is deployed on github pages.
- [Stock Trend Prediction](https://github.com/smitkiri/stock-trend-prediction): Developed a time-series model using LSTM that predicts if the stock would go up, down or stay the same next day based on current day news and past 60 days stock data. Used keras `functional` api to combine seperate models with stock data as input and with news data as input. Tried several techniques for using text data including Bag-of-Words, TF-IDF and Glove Vector Embeddings.
- [Fashion Product Recommendation](https://github.com/smitkiri/fashion-product-recommendation): Developed a recommender system that gives similar fashion product images based on user's input image. Used T-Stochiastic Neighbor Embeddings, Principal Component Analysis, K-Means and Gaussian Mixture Models. The dataset used for this project had about 12,000 colored images belonging to approximately 12-14 product categories.
- [Dengue Fever Prediction](https://github.com/smitkiri/predicting-dengue-fever): Used techniques like LSTM, ARIMA and Prophet to predict dengue fever outbreaks for two cities: San Juan and Iquitos. The dataset for both cities had about 25 climate features and number of dengue cases per week for 10 years. 
- [PyTorch Applications](https://github.com/smitkiri/pytorch-applications): Used convolutional neural netowrks to classify images (into 10 classes) in CIFAR 10 dataset using PyTorch. Implemented logistic regression using pytorch and used it for binary classification on Sonar Returns dataset. The dataset has 60 features representing sonar signals which is classified as reflected from a rock or a metal. Also applied feed-forward neural networks on this dataset using PyTorch.
- [ML from scratch](https://github.com/smitkiri/ml-from-scratch): Developed Decision Tree and AdaBoost algorithms from scratch using python numpy. Also implemented various evaluation metrics like accuracy, precision, recall, confusion matrix and classification report.
- [Species Detector](https://gitlab.com/smit.kiri/species-detector): Developed a deep learning model using convolutional neural networks that classified animal/bird images to their species. Built a [website](https://species-detector.ue.r.appspot.com/) and deployed it on google cloud that allows a user to upload a single image/folder containing multiple images and get the top-3 species for each image with their probabilities.


**Tools**: scikit-learn, pytorch, pandas, numpy, spacy, keras, flask, fastapi, google cloud

### Data Analysis and Vizualization
- [Black Friday Sales](https://github.com/smitkiri/black-friday-sales): Exploratory Data Analysis of black friday sales data (data source: kaggle) and reporting interesting observations and vizualizations using python.
- [PlayStore Apps](https://github.com/smitkiri/playstore-apps): Cleaning and analyzing Google Playstore Apps data (data source: kaggle) and vizualizing interesting observations using python.
- [Student Exam Performance](https://github.com/smitkiri/student-exam-performance): Exploring the exam scores of students in public schools along with other factors that may have impact on them using python.
- [911 Calls](https://github.com/smitkiri/911-calls): Exploratory data analysis of 911 calls dataset (data scource: kaggle). Demonstrates extraction of useful features from different variables using python.
- [Schengen Visa](https://github.com/smitkiri/schengen-visa): Exploring schengen visa statistics and trying to identify factors that may have an impact on visa approval using R.

**Python**: pandas, matplotlib, seaborn, plotly
**R**: dplyr, ggplot, tidyr, rworldmap

### Micro Projects
- [Urban Sound Classification](https://github.com/smitkiri/urban-sound-classification): Classified 4-second audio clips into 10 classes using PyTorch models. Performed exploratory data analysis and transformations on audio signals using `librosa` package. This was an online challenge hosted by [Analytics Vidhya](https://datahack.analyticsvidhya.com/contest/practice-problem-urban-sound-classification/#About) to classify different daily sounds such as air-conditioners, jackhammer, drilling and other different sounds found in an urban environment. 
- [Twitter Analysis](https://github.com/smitkiri/twitter-analysis): Developed a [website](http://twitter-analysis1.herokuapp.com/) that provides analysis of a given user's tweets by dislaying several plots. Used plotly for vizualizations, flask for web app development and deployed on Heroku.
- [Predicting Graduate Admissions](https://github.com/smitkiri/predicting-graduate-admissions): Performing exploratory data analysis and data cleaning on USC graduate admissions data and applied machine learning models to predict factors most important for a positive admission decision.
- [iTeach](): A Hackathon at DAIICT, Gandhinagar, India. Led a team of 4 at a Hackathon to build a project and complete various Capture the Flag (CTF) challenges using Flask, MySQL, JavaScript; Secured a place in top 10 teams overall with 2nd rank for the CTF challenges.

**Tools**: scikit-learn, pytorch, librosa, pandas, numpy, plotly, matplotlib, seaborn, tweepy, flask, heroku