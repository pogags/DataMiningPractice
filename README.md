# DataMiningPractice
Data Mining is described as the art of combing through data to discover hidden patterns, connections, and trends. It uses methods at the intersection of machine learning, statistics, programming, and AI. Like any skill, it requires practice and knowledge, and these short forays into Data Mining served as exercises to build the muscles needed to undertake more complex projects later on.
The purpose of this repository is two fold; present my experience and skills with data mining and serve as a home for recursive code to be used later.
  
All notebooks come furnished with a data exploration section and conclusion, and some sport classes and functions created to make for easy reproduction of models.

*Project completed in collaboration with [Dblash](https://github.com/dblash), [Joshua Dobbins](https://github.com/JoshuaCD), and [DonnaMulkern](https://github.com/donnamulkern)*

## [Iris Dataset Exploration](https://github.com/pogags/DataMiningPractice/blob/main/iris_dataset_exploration.ipynb)

Using the infamous Iris dataset, explored techniques of initial data exploration. Determine how the Iris dataset features relate to eachother and obtain general mathematic information relating to the features.

![image](https://user-images.githubusercontent.com/60637235/145641736-91f752cf-ca17-4879-91cd-a0430ba23cf2.png)

## [Iris Clustering](https://github.com/pogags/DataMiningPractice/blob/main/iris_clustering.ipynb)

Employ multiple *clustering* techniques on the same Iris Dataset, utilize a PCA (Principal Component Analysis), and visualize the results. Additionally, this was used to evaluate multiple clustering techniques against eachother to determine the best suited one for this dataset.

![image](https://user-images.githubusercontent.com/60637235/145642140-cb57069f-8a9d-46ff-86c1-beae2a283af3.png)

## [Iris Review](https://github.com/pogags/DataMiningPractice/blob/main/iris_review.ipynb)

Rather than using clustering, this is a exploration of *classification* techniques when applied to the Iris Dataset. **17** classification methods from the [sklearn library](https://scikit-learn.org/stable/) are utilized. These classifications are again evaluated against eachother, and all methods used are outlined as well as their advantages and disadvantages described.

## [California Housing Regression](https://github.com/pogags/DataMiningPractice/blob/main/california_housing_regression.ipynb)

*Regression* models are investigated in this notebook using the California Housing dataset, with the target variable being Median House Value. 8 models and 5 methods are compared, again all from [sklearn](https://scikit-learn.org/stable/)

![image](https://user-images.githubusercontent.com/60637235/145643396-88602e20-fb2b-457a-86f0-2105fa571a85.png)

## [Mushroom Stew](https://github.com/pogags/DataMiningPractice/blob/main/mushroom_stew.ipynb)

Using data in the (expanded.csv)[https://github.com/pogags/DataMiningPractice/blob/main/expanded.csv], determine what a forager might want to look for when picking mushrooms to ensure a safe and appealing stew. The records in this dataset represent mushrooms, and the data has 22 features and 1 target class which is ofcourse whether the mushroom is edible or poisonous. This notebook uses both data exploration as well as classification techniques to determine the best way to forage, and includes a bonus section that could be employed to pick safe mushrooms if the forager in question lost their sense of smell (scent had the highest feature importance generally).

![image](https://user-images.githubusercontent.com/60637235/145644290-b455865b-c907-4946-bbb1-dece42a5f0f0.png)

![image](https://user-images.githubusercontent.com/60637235/145644267-012a6b8c-1397-4d1f-9dd9-8e5ccb91d6db.png)

