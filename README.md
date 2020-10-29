# Performing Linear Regression Using Tensor Flow

## Abstract
In this developer code pattern, we will create a Jupyter Notebook that contains Python code for defining linear regression and then using Tensor Flow to implement it. The notebook will be running on IBM Cloud Pak for Data as a Service on IBM Cloud. The IBM Cloud Pak for Data platform provides additional support, such as integration with multiple data sources, built-in analytics, Jupyter Notebooks, and machine learning. It also offers Scalability by distributing processes across multiple computing resources.

## Introduction
Defining a linear regression in simple terms, is the approximation of a linear model used to describe the relationship between two or more variables. In a simple linear regression there are two variables, the dependent variable, which can be seen as the "state" or "final goal" that we study and try to predict, and the independent variables, also known as explanatory variables, which can be seen as the "causes" of the "states".

When more than one independent variable is present the process is called multiple linear regression.
When multiple dependent variables are predicted the process is known as multivariate linear regression.

The equation of a simple linear model is
<p align="center">
𝑌=𝑎𝑋+𝑏
</p>

Where Y is the dependent variable and X is the independent variable, and a and b being the parameters we adjust. a is known as "slope" or "gradient" and b is the "intercept". You can interpret this equation as Y being a function of X, or Y being dependent on X.

#### Let’s get started!

## Incuded components
1.	[IBM Cloud Pak for Data](https://www.ibm.com/in-en/products/cloud-pak-for-data): Development platform for AI Applications.
2.	[Jupyter Notebook](https://jupyter.org/): An open source web application that allows you to create and share documents that contain live code, equations, visualizations, and explanatory text.

## Featured technologies
1.	[Python](https://www.python.org/): Python is a programming language that lets you work more quickly and integrate your systems more effectively.
2.	[TensorFlow](https://www.tensorflow.org/): The core open source library to help you develop and train ML models

## Steps:
Following steps are involved in the process and are explained below in detail with screenshots for convenience:
1.	Create your IBM Cloud Account and access the IBM Cloud Pak for Data as a Service.
2.	Create a new project.
3.	Associate the Watson Machine Learning service with the project.
4.	Add a Notebook to your project.
5.	Run the Notebook.

### Step 1:
-	Sign up or Sign in to [IBM Cloud](https://ibm.biz/BdqtVY). 
-	Search for Watson Studio / CPDaaS Service.
-	Create the service by selecting the region and pricing plan of your preference
<p align="center">
<img src="https://github.com/IBM/Performing-Linear-Regression-Using-Tensor-Flow/blob/master/doc/source/images/Searchforcpd.png?raw=true"  width="800">
</p>

<p align="center">
<img src="https://github.com/IBM/Performing-Linear-Regression-Using-Tensor-Flow/blob/master/doc/source/images/createcpd.png?raw=true"  width="800">
</p>
