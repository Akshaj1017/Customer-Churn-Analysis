# Customer Churn Analysis #
Churn analysis is the evaluation of a company's customer loss rate in order to reduce it. Also referred to as customer attrition rate, churn can be minimized by assessing your product and how people use it.

# Introduction #
## What is Customer Churning:
  * Customer Churning refers to the process by which customers discontinue their relationship with a business, stop using their products or services, and move on to a      competitor or alternative solution. In other words, it is the rate at which customers leave a business over a specific period. Customer churn is a critical metric for    any business, as it has a direct impact on the company's revenue and growth prospects. A high customer churn rate can indicate that a business is not meeting the       needs of its customers, leading to a loss of business, while a low churn rate can indicate that customers are satisfied with the company's products or services. Thus,     minimizing customer churn is a priority for businesses looking to achieve sustainable growth.

## What are the different Churn Scenarios ?
  * Tariff Plan Churn
  * Service Churn
  * Product Churn
  * Usage Churn

## Decision Cycle of a Subscriber
![image](https://user-images.githubusercontent.com/92584055/225849258-4d5f6843-b504-47ad-90e6-0a90d5453430.png)

## The different Churn Segments:
  #### Conditionally Loyal Subscriber
   * Frequently re-evaluates purchase decisions
   * Choose brand on rational basis
   * Likes to change to test new products
  #### Conditional Churner
  #### Lifestyle Migrator
   * Uncontrollable change in needs/usage
   * Bheaviour
   * Involuntary Churn
  #### Unsatisfied Churner
   * Unsatisfied Customer

## In this repository, we have performed the end to end Exploratory Data Analysis, and idenfitied the characteristics of the customers that are more likely to churn, and I have used them wisely to create a model, and lately, have deployed the model.

### 🟢 For EDA, please refer to : Churn Analysis - EDA.ipynb  
### 🟢 For Model Building, please refer to: Churn Analysis - Model Building.ipynb  
### 🟢 For Model Deployment, please refer to main.py  
### 🟢 Creating the flask API

''' python
app = Flask("__name__")
'''

The loadPage method calls our home.html.

code(@app.route("/")  
def loadPage():  
	return render_template('home.html', query="")  )
	

The predict method is our POST method, which is basically called when we pass all the inputs from our front end and click SUBMIT.  

code(@app.route("/", methods=['POST'])  
def predict():  )

The run() method of Flask class runs the application on the local development server.  

code(app.run()  )
