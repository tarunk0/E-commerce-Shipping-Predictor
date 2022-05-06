## Table of Content
  * [Demo](#demo)
  * [Aim of the Project](#Aim-of-the-Project)
  * [Life Cycle of the Project](#Life-Cycle-of-the-Project)
  * [Results from the Project](#Results-from-the-Project)
  * [Directory Tree](#directory-tree)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#Technologies-Used)
  * [Future scope of project](#future-scope)

## Demo
Link: [https://e-commerce-shipping-predictor.herokuapp.com/](https://e-commerce-shipping-predictor.herokuapp.com/)


## Aim of the Project:
To build an End-to-End Web App using Data Science & Machine Learning for an International E-commerce Company to predict whether their products will reach on committed Delivery Time or not.

## Life Cycle of the Project:
1. Collected the dataset from Kaggle.   
2. Preprocessed the data well and built an ML model by tuning the Hyperparameters of RandomForest Classifier using RandomizedSearchCV. 
3. Saved the Best Performing model in a Pickle file. 
4. Built a Web App using Python at the Backend with Flask API and HTML & Bootstrap serving at the Frontend.
5. Deployed the Web App on 2 Cloud Platforms: Heroku Cloud. 
6. The Web App receives the data from the User Input, makes predictions with the saved ML model and sends a Prediction text indicating whether the order will reach on time or not. 


## Results from the Project:
* If the order will reach on time

![image](https://user-images.githubusercontent.com/92631457/167086024-2d7ffc7f-e913-411c-801e-2934a5f830f1.png)


* If the order won’t reach on time

![image](https://user-images.githubusercontent.com/92631457/167085474-3f00964a-7594-4cdc-8c86-31c1532e003b.png)

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_price.ipynb
├── e_commerce_rf.pkl
├── requirements.txt
```
## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/tarunk0/E-commerce-Shipping-Predictor/issues) here by including your search query and the expected result

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

## Future Scope

* Optimize Flask app.py
* Front-End 
