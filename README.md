# A script that can parse STAR files of EM data. 

#Original script: 

https://github.com/delarosatrevin/em-metadata

#Changes:
Now it can run on both Python 2.X and 3.x. It supports change column value and add new column with a set value that can come from an existing value. Column value can be "random" to set a random float between 0 and 360.

#Example runs:

python script.py -h #for help and script options

python script.py input_file --output output_file --change_value column_name column_value #to change the value of an existing column

python script.py input_file --output output_file --add_column_and_value column_name column_value #to add column and set its value, value can be "random" to set a random float between 0 and 360.

python script.py input_file --output output_file --add_column_and_value_from_column col1 col2 col_value #to add column (col1) and set its value from the value of an existing column (col2), col_value can be positive and negative for addition or subtraction. 
