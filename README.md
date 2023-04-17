# NLP-with-Transfer-Learning

### Observation
1. First Loading the reviews.csv dataset, It has 568454 rows and 10 columns but we have to
take only two columns ‘Score’ and ‘Text’.
2. In preprocessing, These two columns don’t have an NAN values.
3. Score column has score value from 1 to 5, but we have set value>3 to 1 & value < 3 to 0.
4. Splitted the data into Train and Test with 80-20 and random_state = 33.
5. Plotted Bar Graph of y_train and y_test for visualize it.
6. Created Bert Model and Applied Tokenization over top of it.
7. Finally Save all the result to pkl file and In between checked with grader function that each
step has worked properly.
8. Get Embedding from bert model and again save to final_output.pkl file in order to not run
it again.
9. Written Code for AUC with callbacks of checkpoint, reduceLRonPlateau , Tensorboard and
finally train the model
10. At eight epoch model performance become stable to 0.96 and didn’t improve after it.
11. Created Data pipeline for the Bert Model, Here we are using test.csv file and predicted the
output using pipeline function.
12. PLotted the bar graph for predicted_test.
13. And Finally from prettytable plot table and write the Train , Test Accuracy and loss of Train
and Test.
