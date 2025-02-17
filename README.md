**PINCODE GENERATION USING MAPS API:**

This Python script uses the Google Places API to gather detailed information about postgraduate degree colleges based on a list of pincodes provided in an Excel file. It processes the data and saves the results into a new Excel file.

Replace api_key with a valid OpenAI API key.
In input file the question column should be named as “Pincode”.
Modify input_excel_path and output_excel_path to set custom file locations.
The output file should be closed while running  the code or else “Permisson Denied” Error occurs.
In file path only “\\” is allowed if “\” is present then 'unicodeescape' error occurs.  
In line no.24 change the prompt as per your requirements.(Ex. If you require engineering colleges replace “Post graduate Degree” with “Engineering”).

**Job roles**

This Python script automates the process of extracting specific job role details using OpenAI's GPT-3.5 API. It takes a list of job roles from an input Excel file, generates information for each job role (experience, skills, and responsibilities), and saves the results in an output Excel file.

Replace api_key with a valid OpenAI API key.
In input file the question column should be named as “Job Role”.
Modify input_excel_path and output_excel_path to set custom file locations.
The output file should be closed while running  the code or else “Permisson Denied” Error occurs.
In file path only “\\” is allowed if “\” is present then 'unicodeescape' error occurs.  
