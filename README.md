# IBM Proof of Technology - Data Science Experience

## Description:

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/DSX.png" height="150"/>](http://datascience.ibm.com/) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/bluemix-logo.png" height="150"/>](https://www.ibm.com/cloud-computing/bluemix/solutions) [<img src="https://github.com/jpatter/LMCO/blob/master/Lab-1/images/DB2Warehouse.png" height="150"/>](https://www.ibm.com/analytics/us/en/technology/cloud-data-services/dashdb/)

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/jupyter.png" height="150"/>](http://jupyter.org/) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/spark.png" height="150"/>](http://spark.apache.org/)

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/RStudio2.png"/>](https://www.rstudio.com/) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/shiny.png"/>](https://shiny.rstudio.com/)

Use IBM’s Data Science Experience (DSX) and IBM cloud services to create a working cloud-based application from start to finish.  Participants will be led through a series of three labs that build upon one another so it is important that they are completed in order. A fourth lab will explore additional features of the Data Science Experience. 

1. [Lab-1](Lab-1) - The first lab will begin with loading raw delimited data into DB2 Warehouse for Cloud and interacting with that data from a Jupyter notebook in DSX with python.

1. [Lab-2](Lab-2) - The second lab will leverage Spark machine learning (SparkML) on the loaded data to create categorical predictions using pyspark and a supervised learning model and store the results back to the database.

1. [Lab-3](Lab-3) - The third lab will guide participants in creating an R notebook and Shiny UI in DSX using RStudio.

1. [Lab-4](Lab-4) - Time permitting there will be two labs to choose from for Lab 4. The first one features Watson Machine Learning, a point and click capability to build a machine learning model and deploy it. The second lab features the Canvas- a visual programming tool to create a machine learning pipeline. 

## Instructions:

### Step 1. Sign up for the IBM Data Science Experience (DSX).   We recommend using the Firefox browser.

__NOTE__: If you already have a DSX account, please skip to __Step 2__.

#### Create an account.

1.  Go to [http://datascience.ibm.com/](http://datascience.ibm.com/)

2.  Click the signup button on the top right

> <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Sign%20Up%20Image.png" width="624" height="300">

3. Enter your email, click to accept the terms, and click Next. Note: If you already have an IBM id you can click Sign in with your IBM id -- if you don't have a DSX account one will be created for you.

> <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Try%20Watson%20Data%20Platform.png" width="624" height="300">

4. On the next page, fill in the corresponding fields and click Create Account

 >  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Try%20IBM%20Cloud.png" width="624" height="300">

5. You will see the following screen. You need to go to your e-mail account to complete the sign up process.

 > <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Thanks.png" width="624" height="300"/>

6. In your e-mail inbox, there should be a message from The Bluemix Team.

 >  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Gmail.png"/>

7. Open the e-mail and click on Confirm Account.

 >  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Gmail%202.png"/>

8. Go back to the DSX session, and enter your DSX user id (e-mail account) and click Continue. Or, skip to step 10 if the system automatically logs you in. 

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Sign%20into%20IBM.png"/>

9.  Enter your password and click Sign in.

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Enter%20Password.png"/>

10. Select the IBM Cloud Account (IBM), select the organization (your e-mail), and then select the space (dev) and click Continue.

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Select%20Organization.png"/>

11. It may take several minutes to set up the account. You will see several screens pop-up (e.g. Registering User, Initializing Environment). Wait until you see the following screen and then click on Get Started.

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Done.png"/>


 > You are now in the Data Science Experience landing page. From here you can explore any of the tutorials, videos, sample notebooks, tutorials or articles in the community.

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Welcome.png"/>

### Step 2. Create a project

1. Click on Projects > View All Projects to see a list of your projects. 

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/View%20All%20Projects.png"/>

2. Click on the create project icon on the top right of the project list.

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/create-new-project.png?raw=true" />

3. Type a name for your project. For instance, "DSX Lab". A Spark service and an object storage will be automatically selected as well as a container with a default name. A container is a directory on the object storage. Click on Create.

 > You are now in your new project where you can create notebooks and data assets as well as add collaborators.

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/create-project.png?raw=true" width="512" height="499" />

You are now ready to begin [Lab-1](Lab-1/).
