# Snaps used
•	File Reader – to access “Trng_EmpData.csv”
•	CSV Parse – to parse  “Trng_EmpData.csv”


•	File Reader – to access “Trng_DeptData.csv”
•	CSV Parse – to parse  “Trng_DeptData.csv”


•	Join – Join the records by department $DEPT 

•	Aggregate – to COUNT && GROUP By "$DEPT"
•	CSV Formatter – to format in CSV
•	File Writer – writer in City/Dept+EmpCount.csv      // Problem with file when I download file change '/' in '_'


Route error date to error views – Error0
•	JSON Formatter – to format errors in JSON format
•	File Writer – in “error.json”
