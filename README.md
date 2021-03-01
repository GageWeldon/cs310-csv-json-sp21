# cs310-csv-json-sp21

This is another project from a class at JSU this semester (Spring 2021). This project takes in Comma Seperated Value (CSV) data or JavaScript Object Notation (JSON) data and 
then converts them to their opposite. CSV data is the more popular choice as it is used in excel spreadsheets. This data may need to be converted to JSON notation so that it
can be more readily accessible to java programs. On the other hand, if you receive JSON data and need to print it out to a console then the better method is to use CSV, as it
can be understood much better. For csvToJson, the program creates Json Objects and a Json Array to store the csv data in. Once the file is read, the information is then iterated 
through and the data is then added into a String array. This String array is then used to "put" the data into Json Objects. Once all the objects are full, the data is then sent 
through a JsonToString() method and stored inside the "results" value. 
For jsonToCsv, we take the jsonString as our argument. We then create Json objects and a string array to hold the values. We then iterate through the Json objects and store the 
data in the array we previously created. This data is then converted to csv by the csvWriter() method. This data is then turned into string by the toString() method and stored in 
the variable "results".
When the Main() method is called, it calls on Converter.csvToJson and Converter.jsonToCsv. When it calls these methods it prints them to the Screen following a message describing 
which converter method is being printed. 
