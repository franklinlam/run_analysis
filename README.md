# run_analysis
<p>run_analysis( data_path = "UCI HAR Dataset" )
<p>Argument:
<p>data_path - path of data set
<p>Details:
<p>The program will read the 'features' from features.txt and use the feature names given to label the columns. An 'Avg.' prefix is added in the lablel. It will produce the required data file 'tidy.txt', which contains the following columns:

1. Activity 
2. Subject
3. Averge of each mean/std of measurements for each activity and subject
