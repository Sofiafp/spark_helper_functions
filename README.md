# Spark Helper Functions
Helper and common functions in pyspark 

- [date_dimension](./date_dimension.ipynb)
  - Full notebook for the creation of a standard date dimension with pyspark
- [flatten_json](./flatten_json.ipynb)
  - Function to dinamically flatten a json file
  - Negates the need to manually write out every column and paramenter of the json
  - The function cannot handle paramenters with the same names, even if they are nested under different atributes
  - Not my function, i got it from [this link](https://medium.com/@thomaspt748/how-to-flatten-json-files-dynamically-using-apache-pyspark-c6b1b5fd4777)
