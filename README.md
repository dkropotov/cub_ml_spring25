# CUB Machine Learning, Spring 2025

This course makes introduction to Machine Learning (ML) field. ML is a branch of artificial intelligence (AI) that enables computers to learn from data and make decisions or predictions without being explicitly programmed. ML is used in applications like speech recognition, internet search engines, recommendation systems, and so on. The course presents different methods for solving supervised regression and classification problems like linear and logistic regression, support vector machines and decision trees. Then the course discusses composition of ML algorithms, the problem of bias-variance decomposition and the methods like random forest and gradient boosting. The course also covers topics of relevant feature selection, unsupervised ML problems and ranking. Together with ML-related material the course includes necessary discussion of basic mathematical tools actively used in ML like probability and statistics, optimization algorithms and vector-matrix calculus. 

**Instructor**: Dmitry Kropotov

**Teaching assistants**: Maksim Nakhodnov, Ivan Shchekotov

**Timetable**: the classes are scheduled on Fridays 8:15 - 11:00 in SAC, Hall 3. The first lecture is scheduled on the 7th of February.

**Telegram chat for questions and discussion**: [link](https://t.me/+izhIIZ9W5Fs1NDM6)

**Assignments**: All assignments are given and checked in the corresponding Teams space

## Course assessment

Written examination, Duration: 120 min, Weight: 100 %

Completion: To pass this module, the exam must be passed with at least 45%.

## Home assignments and mid-term exam

In the course there will be given several home assignments in the form of Jupyter notebooks and theoretical assignments on vector-matrix calculus. Completing these assignments is fully optional. However, there will be a small bonus for making these assignments (5% to the final course grade in case of total assignments grade between 30% and 65%, and 10% to the final course grade in case of total assignments grade higher than 65%). 

In the middle of the course a mid-term written exam is planned. This exam helps students better understand the types of problems that are expected in the final course exam. For successfull passing of this mid-term exam a small bonus is supposed (5% to the final course grade in case of mid-term grade between 45% and 70%, and 10% to the final course grade in case of mid-term grade higher than 70%).

The described bonuses can't exceed together 10% and are given only in case of basic exam grade is higher than 45%.

## Exam 

The final written exam is scheduled on the 23rd of May (Friday) at 9:00. Test exams for the previous year: [test mid-term](Materials/midterm_exam_test.pdf), [test mid-term reference solution](Materials/midterm_exam_test_reference.pdf), [test final exam](Materials/exam_test.pdf), [test final exam reference solution](Materials/exam_test_reference.pdf)

## Lectures

| Date | Number | Topic | Materials |
| :---: | :---: | --- | --- |
| 07.02.25 | 01 | Introduction to the course. Basic terminology in ML, feature types, standard ML problem types. Overfitting and cross-validation. Pandas library and exploratory data analysis.	| [Presentation](Materials/01-intro.pptx)<br> [ipynb](https://colab.research.google.com/drive/1XBc5gGHwtK7gh-Ajft_1o2hB1tq9Pq5v?usp=sharing)<br> Videos: [1](https://player.vimeo.com/video/908116908?h=3f3f70101a&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [2](https://player.vimeo.com/video/908117286?h=bc61876ce5&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [3](https://player.vimeo.com/video/908117581?h=0e1d114484&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [4](https://player.vimeo.com/video/908118001?h=2bb61615b3&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479) |
| 14.02.25 | 02 | Linear regression. Loss functions for regression. Regularization. Matrix-vector manipulation and differentiation.	| [Presentation](Materials/02-linreg-diff.pptx)<br> Videos: [1](https://player.vimeo.com/video/911660805?h=083262749d&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [2](https://player.vimeo.com/video/911661433?h=9afd6ead19&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [3](https://player.vimeo.com/video/911663153?h=96abba6d75&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [4](https://player.vimeo.com/video/914134535?h=e620483653&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [5](https://player.vimeo.com/video/914136337?h=bb09deb776&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [6](https://youtu.be/fU4z6iReJyg), [7](https://youtu.be/tlaBauP72nQ) |
| 21.02.25 | 03 | Linear regression: numerical optimization methods and data normalization. Stochastic optimization.	| [Presentation](Materials/03-linreg-optim-norm.pptx)<br> Videos: [1](https://player.vimeo.com/video/914135366?h=83b7790e52&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [2](https://player.vimeo.com/video/914135974?h=1cc29f88e6&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [3](https://player.vimeo.com/video/916211716?h=43452d4eab&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [4](https://player.vimeo.com/video/916212036?h=cf9e3d0196&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [5](https://player.vimeo.com/video/916212476?h=f76e8ca07f&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [6](https://player.vimeo.com/video/916213126?h=cbf8e32e8b&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479) |
| 28.02.25 | 04 | Linear regression: probabilistic view. Linear classification.	| [Presentation](Materials/04-linreg-prob-linclass.pptx)<br> Videos: [1](https://player.vimeo.com/video/914136487?h=95577d7d2f&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [2](https://player.vimeo.com/video/914136707?h=4dd94c5ee7&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [3](https://player.vimeo.com/video/915697217?h=5bc02b8674&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [4](https://player.vimeo.com/video/915698609?h=d2c3105260&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479) |
| 07.03.25 | 05 | Constrained optimization. Support Vector Machine (SVM).	| [Presentation](Materials/05-cond-opt-svm.pptx)<br> Videos: [1](https://player.vimeo.com/video/915694575?h=c3d4ea946c&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [2](https://player.vimeo.com/video/915696075?h=85ca3a73bb&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [3](https://player.vimeo.com/video/920683731?h=769dcbc592&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [4](https://player.vimeo.com/video/920684597?h=4fb7df2a00&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [5](https://player.vimeo.com/video/920685621?h=9c2b7a5dea&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479) |
| 14.03.25 | 06 | Linear regression: Bayesian view. Logistic Regression, probability calibration. Multi-class classification. |  [Presentation](Materials/06-bayes-logreg-multiclass.pptx)<br> Videos: [1](https://player.vimeo.com/video/923723841?h=8015805703&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [2](https://player.vimeo.com/video/923724058?h=aa49f1332d&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [3](https://player.vimeo.com/video/923724135?h=3756d737a8&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [4](https://player.vimeo.com/video/923723916?h=3e467950d1&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479)  |
| 21.03.25 | 07 | Decision Trees for regression and classification. Working with missing values and categorical features. | [Presentation](Materials/07-decision-trees.pptx)<br> Videos: [1](https://player.vimeo.com/video/928466801?h=fabc6e4336&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [2](https://player.vimeo.com/video/928467452?h=54288e605f&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [3](https://player.vimeo.com/video/928467877?h=1665aedb69&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [4](https://player.vimeo.com/video/928468224?h=1ec6545c1d&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479)   |
| 28.03.25 | 08 | Mid-term exam |    |
| 04.04.25 | 09 | Bias-Variance Decomposition. Random Forest, Gradient Boosting. | [Presentation](Materials/09-bvd-rf-gb.pptx)<br> Videos: [1](https://player.vimeo.com/video/931031033?h=477004b30c&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [2](https://player.vimeo.com/video/931031340?h=24a9173769&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [3](https://player.vimeo.com/video/931032144?h=6af1ef6723&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [4](https://player.vimeo.com/video/933860585?h=744d5cb4c3&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [5](https://player.vimeo.com/video/933861720?h=383a451a5d&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479), [6](https://player.vimeo.com/video/933862957?h=b90e30d40d&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479)   |
| 11.04.25 | 10 | Efficient implementation of gradient boosting: XGBoost, LightGBM. Blending and Stacking. | [Presentation](Materials/10-gb-impl-stacking.pptx)  |
| 18.04.15 | -- | *Semester break. No classes.*   |

## Literature
1.	T. Hastie, R. Tibshirani, J. Friedman, The Elements of Statistical Learning: Data Mining, Inference, and Prediction, 2nd edition, Springer, 2008.
2.	S. Shalev-Shwartz, Shai Ben-David: Understanding Machine Learning, Cambridge University Press, 2014.
3.	C. Bishop, Pattern Recognition and Machine Learning, Springer, 2006.
4.	T.M. Mitchell, Machine Learning, Mc Graw Hill India, 2017.
