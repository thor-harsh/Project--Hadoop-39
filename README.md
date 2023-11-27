# Project--Hadoop-39(Challenges)

<table>
  
**In this project We will use Spark with Python to do an amazing stuff.Here we will work on the Spark DataFrame which will read the csv files attached above as our dataset and complete the challenges as provided by Jose Portilla .** <br></br>

**Here is the Problem Statement!** <br></br>

**Congratulations!** You've been contracted by Hyundai Heavy Industries to help them build a predictive model for some ships.<br> Hyundai Heavy Industries is one of the world's largest ship manufacturing companies and builds cruise liners.You've been flown to their headquarters in Ulsan, South Korea to help them give accurate estimates of how many crew members a ship will require.<br></br>They are currently building new ships for some customers and want you to create a model and use it to predict how many crew members the ships will need. **So our job is to find the no. of crews required in each ship.** <br></br>

Here is what the data looks like so far:<br></br>
**Description:** Measurements of ship size, capacity, crew, and age for 158 cruise
ships.<br></br>


Variables/Columns<br></br>
Ship Name     1-20<br></br>
Cruise Line   21-40<br></br>
Age (as of 2013)   46-48<br></br>
Tonnage (1000s of tons)   50-56<br></br>
passengers (100s)   58-64<br></br>
Length (100s of feet)  66-72<br></br>
Cabins  (100s)   74-80<br></br>
Passenger Density   82-88<br></br>
Crew  (100s)   90-96<br></br>

It is saved in a csv file for you called "cruise_ship_info.csv". Your job is to create a regression model that will help predict how many crew members will be needed for future ships. The client also mentioned that they have found that particular cruise lines will differ in acceptable crew counts, so it is most likely an important feature to include in your analysis!<br></br>

Once you've created the model and tested it for a quick check on how well you can expect it to perform, make sure you take a look at why it performs so well!<br></br>

**Before jumping to the code lets understand Spark and Linear Regression First**...<br></br>

**What is Apache Spark?** <br></br>

Apache Spark™ is a multi-language engine for executing data engineering, data science, and machine learning on single-node machines or clusters.<br></br>
Unify the processing of your data in batches and real-time streaming, using your preferred language: Python, SQL, Scala, Java or R.
Execute fast, distributed ANSI SQL queries for dashboarding and ad-hoc reporting. Runs faster than most data warehouses.<br></br>
Perform Exploratory Data Analysis (EDA) on petabyte-scale data without having to resort to downsampling.
Train machine learning algorithms on a laptop and use the same code to scale to fault-tolerant clusters of thousands of machines.<br></br>

**What is Spark DataFrames**?<br></br>

**1**: Spark 2.0 shifted towards DataFrame syntax<br></br>
**2**: are now the standard way of using Spark's ML Capabilties<br></br>
**3**: Spark Docs are still new<br></br>
**4**: DataFrame is very familiar to Pandas DataFrames<br></br>
**5**: Columns = features<br></br>
**6**: Rows = records<br></br>

**What is Linear Regression**?<br></br>
 Linear Regression is the supervised Machine Learning model in which the model finds the best fit linear line between the independent and dependent variable i.e it finds the linear relationship between the dependent and independent variable.<br></br>


**Important Note: Go through the cruise_ship_info.csv file before jumping to the code.**


</table>

**So what are you waiting for...? Jump to the code to get started. As usual for any doubt or query see you in pull request section 😁😂. Thanks!**


