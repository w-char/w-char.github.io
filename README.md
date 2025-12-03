# Analytics Work
## Home Credit Default Project

### Business Problem & Project Objective
Home Credit strives for financial inclusion among clients who are struggling to get a loan. They are looking for a more reliable way to identify customers that are able to make repayments in order to lessen defaults. In addition to losses from defaulting, rejecting clients who are likely to repay their loan also leads to lost revenue, and finding new clients is costly. The purpose of this project is to generate a default risk model that can maximize assessment accuracy using a variety of alternative data for this project. This will result in having more approved loans with controlled risk, less defaults, improved profitability, and improved financial opportunities for customers struggling with the traditional credit system.  

### Group Solution

Our group's solultion to Home Credit's default project was to use a Boosted Tree model as a a baseline to evaluate rejected loan applications in order to find additional commonalities and more unconventional predictors. This way, Home Credit could both approve more loans and eventually be more financially inclusive for the underserved clients. Although it does not give them the immediate ability to expand financial inclusion to the underserved population, it will help them achieve this goal in the long term.

Our Boosted Tree Model had an AUC of 0.74 and a kaggle score of 0.697. 

### Individual Contribution

My individual contributions and efforts towards this group project include the following:
- Modeling Individual Notebook (Used for model comparison and and team efforts in finding the best performing model for Home Credit.)
  - Examine Data
    - Check for missing values
    - Factor necessary data
  - Clean Data
    - Drop columns that have more than 40% Null values
    - Examine the dropped columns to determine what was left and what was removed from the dataset
  - 5-Fold Cross-Validation
    - Split the data 80/20 for train and test sets
    - Impute the missing values
    - Cross Validation
  - GLM Model (AUC of 0.739)
  - Random Forest (AUC of 0.704, Kaggle Score of 0.6871)
  - Identifying Best Predictors from the Random Forest model
  - Causal Forest (Kaggle Score of 0.5084)
  - Boosted Tree Model (AUC of 0.726)
- Compiled text responses used for each section of our group's individual modeling notebooks and utilized them to write the introduction, data preparation, modeling process, and results sections used in our modeling assignment.
- Created slides for the business recommendations and the project summary for the presentation
- Presented on the business impact and business recommendations for Home Credit
- Attended all group meetings
- Shared duties of task delegation to other group members, organizing group work deadlines, and setting up group meetings
- Thoroughly reviewed group efforts before submission

### Business Value of the Solution

The business value of the solution is that by using the Boosted Tree Model our group recommended, Home Credit can reduce the toll of financial losses from defaulting customers, approve more loans, and eventually promote financial inclusion for customers with a limited traditional credit history. The Boosted Tree Model can help Home Credit identify high-risk borrows more accurately and after approving more loans, they will be able to find more commonalities between borrowers and identify more unconventional predictors to increase loan inclusivity. This Boosted Tree Model will also lower Home Credit's spending in acquiring new customers since the model will reduce the risk of defaults from customers. 

Ultimately, these steps would increase Home Credit's revenue while achieving their long term goal of financial inclusivity for previously underserved clients. 

### Difficulties Encountered

Difficulties that my group encountered during this project included the run time of the models, differing schedules between groupmates, and finding a way to adhere to Home Credit's overall mission of financial inclusion while still getting effective performance results from our models. The long run time in R made it difficult for us to complete work at the same time and analyze performance results together. We already had some difficulties with busy schedules and a group member often in and out of town so the run time was an additional factor to take into account on top of that. Our group was able to meet consistently throughout the project but our schedules made it hard to meet for last minute alterations or unexpected problems. To make up for this, we were highly responsive to each other and very communicative throughout the project. Our difficulty adhering to Home Credit's goal of financial inclusion was something that we did not realize soon enough. Ultimately, we lost sight of the main goal and became too focused on producing a model with good performance. Eventually once we realized this, we had to make alterations to our project in order to follow Home Credit's initital objective. 

### Project Takeaways and Reflection

From the technical aspect of the project, I learned a lot about data preparation and modeling through this project. When I worked on the modeling assignment I recognized that there may have been some data leakage that I only noticed later in hindsight. I had little experience in data preparation and modeling previously so there was a bit of a steep learning curve but this project helped me understand the data process and good data practices better. I also lacked experience in github but this project forced me to get more familiar with using github so that we could work effectively as a team, and I believe that it was a huge improvement for my personal progress.

In regards to teamwork, I believe that we worked effectively for the most part but something I learned is that when relying on others for teamwork, it is best to be more ahead of schedule than you would normally think is necessary. There are often conflicts in schedule between multiple people and being ahead of schedule made it possible for us to implement plan b's and c's if someone was not able to finish their delegated tasks. I think that the way in which we assigned tasks was very efficient, and I learned a lot about the data preparation and modeling process from my groupmates during the modeling portion of the project. 

### Individual Modeling Notebook
- Generalized Linear Model
- Random Forest
- Boosted Tree Model
- Causal Forest
- Gradient Boosting Model
- Evaluated with AUC
- [View Code on Github](https://github.com/w-char/IS6812-Practice-Project)

---

## Skills

**Languages:** R, SQL  
**Machine Learning:** Gradient Boosted Model, Random Forest, Causal Forest, Logistic Regression  
**Tools:** RStudio, Git, GitHub  

---

## Contact
- GitHub: https://github.com/w-char 
- LinkedIn: https://www.linkedin.com/in/charlotte-wang2428/
- Email: u0915843@umail.utah.edu
