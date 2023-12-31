The paper [[He, Zheng, and Dong (2018).pdf]] describes research carried out in 2019 that looked to identify how different [[Time Management]] behaviours exhibited in students can have an impact on their expected academic performance. Remote online learning has become more prevalent in recent years and as a result learners are less supervised which can lead to challenges with time management. The goal of this research was to focus on being able to measure and visualize trends in time management behavior among online students.

Using data collected from a university Learning Management System (LMS), researchers first developed consistent methods for visualizing the data. This data consisted of logs which detailed each individual learners interaction with the LMS including:
	1) Engagement with course content (Videos, slide decks, etc.)
	2) Time spent attending remote lectures
	3) Amount of interaction with other learners on the platform (chat & forum interaction)
This data was used to create an "Activity Vector" which was recorded for each learner each day to create a calendar like display plotting the amount of activity each day. Trends in engagement were interpreted as time management strategies employed by learners. The Activity Vector is shown below.

![[LearnerExp EX1.png]]

The data was used to train a [[Machine Learning]] (ML) model which is used by the LearnerEXP system to predict course performance (GPA) based on the engagement and time management strategies used by each learner. At the time of publication, the ML model was on average over 70% accurate at predicting GPA based on time management behaviour exhibited by students. 

This ML model was incorporated into an interactive dashboard that is designed to provide course administrators tools for visualizing the time management and engagement of their students. The dashboard was designed to provide a way for educators to visualize time management trends among groups of learners and identify individuals or groups of students who may be at risk of failing upcoming assessments. Below is an example of the LearnerExp dashboard.

![[LearnerExp EX2.png]]

In the future the researchers state that they look to develop more features into LearnerExp and further improve its ML models for GPA prediction. Further investigation into time management patters and their impact on academic performance has the potential to create systems that can actively inform and adjust student study behaviour to provide a more effective education experience.

**Key Points**
- As online and remote learning become more common, challenges to time management and course engagement become more prevalent.
- pre-existing data from LMS can be used to create ML models for analyzing trends in time management behaviours and predict course performance.
- Insights into the effect time management has on course performance can be used to inform future time management strategies.
