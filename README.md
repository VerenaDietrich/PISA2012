# PISA 2012

Udacity project on PISA 2012 data

For this project I chose the "PISA Data" with the results from the PISA survey 2012.

Question of investigation: 
How does the teacher's relationship influence the children's success?

Main findings:
- It can be seen that the relationship between teacher and student does not have a big impact on the scoring.
- Boys more often rate the relationship as extreme positive or negative than girls.
- With a positive teacher student relationship the scores are on average higher (confirmed by a hypothesis test) in each subject independent of the gender.
- A very good relationship between the teacher and the student correlated with a decreased score for all subjects and independent from the gender.
I had some findings beyond the question of investigation which I don't want to discuss because they are not in focus.

For the explanatory analysis, I couldn't demonstrate all my findings. 
I dicided to chose those plots, which give the best insights to answer how the teacher's relationship influences the student's success:
- There are much more stundents with a positive realtionship to their teacher than negative.
- A good student teacher relationship influence the students success positively, but not strongly.
- Additinally to the increased scores the confidence intervall of the results is much smaller and therefore the greater success is more certain.
- Surprisingly, a very good student teacher relationship correlates with decreased scores independet of the subject and the gender.

Resources:
I used https://stackoverflow.com/, https://seaborn.pydata.org, https://www.w3schools.com, https://matplotlib.org/ to taggle my problems.
Furthermore this is an interesting source to get more information about insights about PISA 2012: https://www.oecd.org/pisa/keyfindings/pisa-2012-results.html, https://www.oecd.org/pisa/49012097.pdf

Generate Slides:
jupyter nbconvert slide_deck_StudentTeacherRelationship.ipynb --to slides --template output_toggle.tpl --reveal-prefix=reveal.js
