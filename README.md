<div align = "center">
     <h1> Small Business Administration 7(a) Loan Classification </h1>

     
 
<img src = "https://i.pinimg.com/originals/74/fe/58/74fe58b6918fa081662612578de66dc1.gif" height = 600, width = 600 />
</div>


<h2>Background</h2> 
The goal of this project is to create a deployable machine learning classification model using SBA 7(a) loan data for Q1 2023. Classifying the number of jobs supported using the most relevant features.
This model will serve as a tool to help SBA make effective loan application approvals and reduce fraud. 



<h2> Part I: Exploratory Data Analysis <img src ="https://th.bing.com/th/id/OIP.j5Vj7VYXdSuB0Cho-HbMpgHaHa?pid=ImgDet&rs=1" height = 25, width = 25 />
</h2>



<h3>Data</h3> 

The dataset comes from the <a href="https://data.sba.gov/dataset/7-a-504-foia">Small Business Administration</a> official site.

<h3>Features Selected</h3>

* Gross Approval
* Initial Interest Rate
* Term in Months
* Revolver Status
* Startup (binary variable, yes = 1, no = 0)



<h2> Part II: Supervised Learning

<img src ="https://th.bing.com/th/id/OIP.4u9QjWljrMuY5CL7nGzRkQHaFj?w=273&h=205&c=7&r=0&o=5&dpr=1.3&pid=1.7" height = 25, width = 25 />
</h2>
     

The classification models tested were: 

* Random Forest
* Decision Tree
* XGBoost
* Extra Trees
* KNN 
* Deep Learning
* AdaBoost
* Gradient Boosting
* Voting

     
<h3>Supervised Model Best Results</h3>
     
The tuned XGBoostclassifier model performed the best out of the models with The biggest finding for this project was the validation of the potential for deployable classification model.  

     
<h2> Part III: Evaluation & Future Project Ideas 
<img src ="https://th.bing.com/th/id/R.b8644db24930cf9363566896d5253aec?rik=7SL6mGoqlQ0TNQ&riu=http%3a%2f%2fmedia.istockphoto.com%2fvectors%2fsaturn-vector-id165600450%3fk%3d6%26m%3d165600450%26s%3d612x612%26w%3d0%26h%3drEvVMsd4l40ib7bcrQzr1TzjkbLgRpcYPYGpYhJ9Nxo%3d&ehk=KabbCN8zzWnhbNSUIRMIS8eS0lrYNF2gRndPFaAxmOg%3d&risl=&pid=ImgRaw&r=0" height = 25, width = 25 />

</h2> 
     
<h3> Evaluation:</h3>



<h3>Future Projects</h3>

Future projects may:

* Perform additional feature engineering to increase model accuracy.

* Deploy the model into a web app.

* Build this project with a regression model to predict actual job supported numbers. 

     

