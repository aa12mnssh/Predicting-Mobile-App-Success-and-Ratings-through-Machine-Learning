# Predicting-Mobile-App-Success-and-Ratings-through-Machine-Learning
This predictive model aids developers in making informed decisions about their app's features, thereby enhancing the likelihood of favorable user ratings and increased installations.
Contrary to traditional business models, where financial gains are
the primary indicator of success, the app industry often prioritizes
user ratings and the number of installations. These metrics provide
valuable insights into user satisfaction and popularity, which, in
turn, influence an app's success in the competitive market.

To gain a deeper understanding of the factors influencing an app's
success, Kaggle emerges as a valuable resource. Kaggle, aplatform known for hosting datasets and fostering collaborative
data science projects, provides a comprehensive dataset containing
attributes such as app name, category, reviews, ratings, and
pricing. Leveraging this dataset, a predictive model can be
developed using Python libraries and packages like sklearn,
statsmodel, seaborn, and matplotlib.

The analysis would involve extracting meaningful features from
the dataset, considering aspects such as app category, user reviews,
and pricing. Through the application of machine learning
algorithms, particularly those available in sklearn, predictions can
be made regarding the app's rating. This predictive model aids
developers in making informed decisions about their app's features,
thereby enhancing the likelihood of favorable user ratings and
increased installations.

Methodology

![image](https://github.com/aa12mnssh/Predicting-Mobile-App-Success-and-Ratings-through-Machine-Learning/assets/102961461/16050179-0ef7-4cc5-8540-c611b0958195)

DATASET DESCRIPTION

The dataset, ‘Google Play Store Apps’ was obtained from Kaggle and used for this study. No of observation (rows): 10840 https://www.kaggle.com/lava18/google-play-store-apps Indepdendent variables
i. App: This contains the application name
ii. Category: Category of the app
iii. Reviews: No. of user reviews
iv. Size: Size of the app
v. Installs: Number of user installs
vi. Type: Paid or Free
vii. Price: Price of the app
viii. Content Rating: Age group the app is targeted at - Children / Mature 21+ / \

Adult ix. Genres: multiple genres (For eg, a game can belong to Music, Game, Family genres. x. Last Updated: Date when the app was last updated xi. Current Ver: Current version of the app available on Play Store xii. Android Ver: Min required Android version.





Frequency for the category of apps (showing the number of app per category)
![image](https://github.com/aa12mnssh/Predicting-Mobile-App-Success-and-Ratings-through-Machine-Learning/assets/102961461/8d2cc444-eed5-4cb6-b3be-34941b83d5eb)

The dataset is split into train and test set. The model is trained using train test and then values are predicted using this model with test set as input. Train set: 70% and Test set: 30%.

we train the model using LinearRegression() function.

Residuals versus fits plot.

![image](https://github.com/aa12mnssh/Predicting-Mobile-App-Success-and-Ratings-through-Machine-Learning/assets/102961461/b499bec1-8226-4e8c-b4f0-52d6d89ae12e)

Model Fitting and coefficients
![image](https://github.com/aa12mnssh/Predicting-Mobile-App-Success-and-Ratings-through-Machine-Learning/assets/102961461/3891d24d-90e7-4f4c-a8c1-e574c21c2d86)


Regression equation

![image](https://github.com/aa12mnssh/Predicting-Mobile-App-Success-and-Ratings-through-Machine-Learning/assets/102961461/79a3ce63-d493-43f8-9a2d-7f8283128b62)



Bar Graph Predicted Vs Actual Values
![image](https://github.com/aa12mnssh/Predicting-Mobile-App-Success-and-Ratings-through-Machine-Learning/assets/102961461/2a1bd12f-ee7d-4e7e-920f-1032a13ae5e2)





