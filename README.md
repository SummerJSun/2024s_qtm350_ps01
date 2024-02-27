# PROJECT TITLE 
![Vanessa Wei](https://img.shields.io/static/v1?label=VanessaWei&message=Collaborator&color=blue&logo=github)
![Jinghan Sun](https://img.shields.io/static/v1?label=JinghanSun&message=Collaborator&color=blue&logo=github)
![Marco Ren](https://img.shields.io/static/v1?label=MarcoRen&message=Collaborator&color=blue&logo=github)



## I.  Introduction
***Description***   
Over the years, the gaming industry has grown rapidly, offering a wide range of genres to an expanding audience. From the action-packed adventure games to the immersive role-playing games, each genre has its own unique appeal. However, with such an abundance of choices, it is critical to determine which genres resonate best with the consumers and drive higher sales. Given the importance of understanding consumer preferences and market trends for developers, publishers, and stakeholders, this project delves into a large amount of game sales data across a wide range of game genres. By analyzing the dataset in detail, we seek to identify trends, correlations, and underlying factors that influence the success of various game genres and to predict the best-selling game genres in the gaming market.

</br>

***Objective***  
The primary goals of the project are to uncover patterns and insights in game sales data and predict the best-selling game genres by analyzing the sales data across a wide range of game genres. To accomplish this goal, the data will first be preprocessed and then different machine learning advanced classification models will be used to predict the sales of game genres. Eventually, the effectiveness of these models in predicting game genres will be evaluated using metrics such as accuracy, precision, and recall. Visualization techniques will be employed in presenting the insights effectively, contributing to the overarching goal of identifying the key factors influencing the success of different game genres and predicting the best-selling game genres in the gaming market.

</br>


</br> 

## II. Dataset

### Dataset Description
The dataset hosted on Kaggle, titled "Video Game Sales," is a collection of sales data for video games across various platforms. Compiled by a Kaggle user named GregorUT, the dataset aims to provide a detailed overview of video game sales figures, offering insights into the commercial success of video games since they released until its last update.

Key features of the dataset include:

`Rank`: The ranking of the game in terms of overall sales.</br> 
`Name`: The name of the game.</br> 
`Platform`: The platform on which the game was released (e.g., PC, PlayStation 4, Xbox One, etc.).</br> 
`Year`: The year of the game's release.</br> 
`Genre`: The genre of the game.</br> 
`Publisher`: The name of the game's publisher.</br> 
`NA_Sales`: Sales figures in North America (in millions).</br> 
`EU_Sales`: Sales figures in Europe (in millions).</br> 
`JP_Sales`: Sales figures in Japan (in millions).</br> 
`Other_Sales`: Sales figures in other regions (in millions).</br> 
`Global_Sales`: Total worldwide sales figures (in millions).</br> 

In total, there are 16,598 records. 2 records were dropped due to incomplete information. This dataset serves as a resource for analyzing trends in the video game industry in terms of genre, understanding consumer preferences in different regions, and evaluating the commercial success of games on various platforms. Our groups want to leverage this data for market analysis, predictive modeling, and historical inspection of the video game industry.

### Dataset Source URL
[Dataset webite](https://www.kaggle.com/datasets/gregorut/videogamesales)


</br> 

## III. Methods
***Data Preprocessing***   
In addition to our target variable, Genre, the dataset includes three additional nominal attributes. To prepare the data for analysis, we will apply one-hot encoding to these non-numeric columns, transforming them into binary representations. For the numerical attributes, we will normalize them using min-max normalization to ensure their values fall within the range of 0 and 1.

To address dimensionality and enhance training efficiency, we will employ principal component analysis (PCA). PCA will allow us to reduce noise and retain only the most relevant features.

</br>

***Classification***  
Our classification task involves predicting the genre of games based on various attributes in the dataset, with Genre serving as our label. This attribute comprises five distinct categories. To accomplish this, we will explore a range of models and assess their performance. The models we plan to utilize include:

* Decision Tree
* K Nearest Neighbor (KNN)
* Random Forest
* Naive Bayes
* Neural Network

To enhance the performance of each model, we will employ parameter tuning through grid search methodology, aiming for optimal results. For robust assessment, we will utilize 5-fold cross-validation, maintaining a train-test split ratio of 70:30.

</br>

***Evaluation and Visualization***  
We will evaluate the performance of our models using metrics such as accuracy, precision, and recall. Additionally, we will employ appropriate visualization techniques, such as scatterplots and line graphs, to illustrate the results effectively. Through this analysis, we aim to identify any correlations between `Genre` and other features, as well as assess the predictive capabilities of the selected models for this particular task.

</br>

---
## Contributions

Vanessa Wei: Responsible for the writing of Section 3 *Method*.
</br> 
Marco Ren: Responsible for the writing of Section 1 *Introduction*.
</br> 
Jinghan Sun: Responsible for writing of Section 2 Dataset and Challenges
</br> 

## Challenges
-Using Github to collaborate and track the progress</br> 
-Finding the appropriate dataset that clean and large enough for our project</br> 
-Select the most accurate model for prediction and hyperparameters (if applicable)</br> 

How to Solve:
-Learning through course material and google</br> 
-Searching on platforms such as Kaggle and Google Dataset Search to find useable dataset</br> 
-Using model seletion and assessment techniques to find the most suitable mode</br> 

</br> 

## References
Dataset url: [text](https://www.kaggle.com/datasets/gregorut/videogamesales)


