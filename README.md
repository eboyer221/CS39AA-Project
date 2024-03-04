# RateMyProfessor NLP Analysis
#This project was completed as part of Dr. Steven Geinitz's CS39AA Natural Language Processing course at the Metropolitan State University of Denver.

The majority, if not all, educational institutions employ student feedback as a means of evaluating their professors. This feedback typically comprises both ratings and open-ended comments from students. However, in most cases this information is kept confidential and isn't disclosed to either current or prospective students. RateMyProfessors.com (RMP) is one popular, publicly-available platform where students anonymously rate various facets of their instructors' performance, such as clarity, helpfulness, and easiness. Additionally, they can provide open-ended comments.

I would like to use this data to better understand what qualitative factors contribute to a professor's rating on RMP. The first goal is to determine whether automatic text classification can distinguish between professors with a high rating (>= 3.5) vs. professors with an average to low rating (< 3.5). I also want to examine student comments to isolate which factors are valued most by students, and whether differences emerge in those factors depending on the department the professor teaches in.

The dataset used for this project is taken from https://data.mendeley.com/datasets/fvtfjyvw7d/2 and includes ratings and comments for 4406 unique professors. The data set scraped from RMP includes 18 variables. The variable that I am primarily focused on predicting is the star rating of the professor's overall quality, which each student provides along with their review, and which is also combined into an average overall score. According to RMP’s official standard, a rating of 3.5-5.0 is good, 2.5-3.4 is average and 1.0-2.4 is poor. The goal is to develop a model that can automatically analyze and understand the sentiment and content of the comments provided by each student in order to predict the corresponding star rating.

Dataset Citation: He, Jibo (2020), “Big Data Set from RateMyProfessor.com for Professors' Teaching Evaluation”, Mendeley Data, V2, doi: 10.17632/fvtfjyvw7d.2
