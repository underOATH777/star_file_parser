# star_file_parser

#Original script: 

https://github.com/delarosatrevin/em-metadata

#Changes:
Now it can run on both Python 2.X and 3.x. It supports change column value and add new column with a set value.

#Example runs:

python script.py -h #for help and script options
python script.py input_file --output output_file --change_value column_name column_value #to change the value of an existing column
python script.py input_file --output output_file --add_column_and_value column_name column_value #to add column and set its value
