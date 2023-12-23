# TimelyProject
Project steps described below:
- First we have imported pandas module and used it to load the two given csv files namely Services.csv and Appointments.csv
- Then to view the data we used head() function to view the records.
- Next we changed the name of 'Name' column in Services data into 'Service' so that we can combine the two given data sets based on a common series.
- Now as we have a common column in both data sets, we can merge them together to form one dataframe.
- next step is to identify the datatype of each column for this I have used dtypes keyword.
- Now as we know the data types and how the records appear in the merged dataset we can work on transforming the data.
- User defined function is created to make the stylist and customer names format like the one shown in the sample data set.
- applied the function created to format the names
- dropped unnecessary columns from the data.
- now we combined the date and time columns to create one single column for start time
- further we need end time as well, for this we were supposed to add duration column to start time column.
- this step was achieved by converting the duration unit into minutes and converting the start date and time column into datetime format and then adding them together to create end time column.
- again dropped unnecessary columns from the data
- as a last step now we added a new column named as location in the begining of the data. this column consist of Clinic string in all its rows.
- finally we saved the data in excel format with .xlsx extension.
