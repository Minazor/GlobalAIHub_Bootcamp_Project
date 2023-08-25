# GlobalAIHub_Bootcamp_Project

<h1>Health Insurance Data Analysis</h1>

<p>This repository contains an exploratory data analysis of a health insurance dataset. We have investigated various features like age, BMI, smoking habits, number of children, and region against medical charges.</p>

<h2>Dataset Overview</h2>
<p>The dataset comprises the following columns:</p>
<ul>
    <li><strong>Age</strong>: Age of the insured.</li>
    <li><strong>Sex</strong>: Gender of the insured (0 for male, 1 for female).</li>
    <li><strong>BMI</strong>: Body Mass Index.</li>
    <li><strong>Children</strong>: Number of children/dependents covered by the insurance.</li>
    <li><strong>Smoker</strong>: Smoking status (0 for non-smoker, 1 for smoker).</li>
    <li><strong>Region</strong>: Region of the insured (coded as integers).</li>
    <li><strong>Charges</strong>: Medical costs billed by health insurance.</li>
</ul>


<h2>1. BMI Distribution</h2>
<br>
<p>The distribution of BMI appears normal with a slight right skew, indicating that most insured individuals have a BMI in the range of 25-35.</p>

![image](https://github.com/Minazor/GlobalAIHub_Bootcamp_Project/assets/33224492/424c3faf-9250-4fc1-bc41-c0c2ca047646)


<h2>2. Impact of Smoking on Medical Charges</h2>
<br>
<p>From the data, it's evident that smokers incur significantly higher medical charges than non-smokers. This underscores the health risks and associated costs of smoking.</p>

![image](https://github.com/Minazor/GlobalAIHub_Bootcamp_Project/assets/33224492/624f2c41-4719-46ef-8d64-804e35af4e03)
![image](https://github.com/Minazor/GlobalAIHub_Bootcamp_Project/assets/33224492/ba52c8c0-68f7-4a59-b01f-af9d316d4002)


<h2>3. Smoking Habits Across Regions</h2>
<br>
<p>The number of smokers is relatively consistent across all regions. This suggests that region doesn't play a substantial role in influencing smoking habits.</p>

![image](https://github.com/Minazor/GlobalAIHub_Bootcamp_Project/assets/33224492/37646bc5-cbad-420f-82fe-e6c23da6bbe1)


<h2>4. BMI Based on Gender</h2>
<br>
<p>Both genders display similar median BMI values. The spread of BMI across males and females varies slightly but not drastically.</p>

![image](https://github.com/Minazor/GlobalAIHub_Bootcamp_Project/assets/33224492/2b459e35-61b0-4478-a4c8-cf531bc3b415)


<h2>5. Relation between Age and BMI</h2>
<br>
<p>The dataset does not show a clear trend between age and BMI, suggesting that in this dataset, age doesn't play a substantial role in BMI.</p>

![image](https://github.com/Minazor/GlobalAIHub_Bootcamp_Project/assets/33224492/a9103d94-1ff1-4b56-8e7f-bf76ec39917c)


<h2>6. Relation between Number of Children and BMI</h2>
<br>
<p>As the number of children increases, there is a slight decrease in median BMI. However, this relationship isn't pronounced.</p>

![image](https://github.com/Minazor/GlobalAIHub_Bootcamp_Project/assets/33224492/96f21a37-4789-4f21-ae47-1a02b94afe6d)


<h2>7. Relationship between BMI and Medical Charges</h2>
<br>
<p>There is no a distinct pattern. It is a little bit messy. For low charges, there ara low and high BMIs. However, after a certain point, the increase is seen more regularly.</p>

![image](https://github.com/Minazor/GlobalAIHub_Bootcamp_Project/assets/33224492/12e97b41-61ce-4f9f-96b2-39d136ab61cc)


<h2>8. BMI and Smoking Status Across Regions</h2>
<br>
<p>Across all regions, the number of smokers and non-smokers is very close to each other.</p>

![image](https://github.com/Minazor/GlobalAIHub_Bootcamp_Project/assets/33224492/ae3b3480-b96a-4b27-9fc3-b2bd2d721d18)


<h2>9. BMI Outliers</h2>
<br>
<p>There are a few potential outliers on the higher side of BMI, as indicated by the box plot.</p>

![image](https://github.com/Minazor/GlobalAIHub_Bootcamp_Project/assets/33224492/cb137182-5e4c-4931-a5ac-6eebe416fd8e)

<h1>Model Scores and Comments:</h1>
<h2>Model: Linear Regression</h2>
Model Score: 0.7441781064585251<br>
Mean Squared Error: 0.0377726981136018<br>
Mean Absolute Error: 0.11574108284292886<br>

<h2>Model: Decision Tree</h2>
Model Score: 1.0<br>
Mean Squared Error: 0.014925373134328358<br>
Mean Absolute Error: 0.014925373134328358<br>

<h2>Model: Random Forest</h2>
Model Score: 0.9863045721925133<br>
Mean Squared Error: 0.012483955223880594<br>
Mean Absolute Error: 0.02414179104477612<br>

<h2>Model: Gradient Boosting</h2>
Model Score: 0.9813266103565634<br>
Mean Squared Error: 0.014679694859181813<br>
Mean Absolute Error: 0.03190696330982849<br>
<br>
<p>Based on the results and evaluation metrics, the Random Forest model stands out as the most effective in predicting outcomes with low errors. The model scores also solidify this inference. However, the perfect score of the Decision Tree model is concerning, as it hints at potential overfitting. Gradient Boosting, with its impressive results and score, serves as a reliable alternative to Random Forest.</p>

<h2>Tools Used</h2>
<ul>
    <li><strong>Python</strong>: Primary programming language used for analysis.</li>
    <li><strong>Pandas</strong>: Data manipulation and analysis.</li>
    <li><strong>Matplotlib & Seaborn</strong>: Data visualization.</li>
</ul>
