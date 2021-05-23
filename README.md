# Large-File-Processing
## Steps to Run

1. Load the csv file in the same directory.
2. Compile the java file - javac code.java
3. Run the Java File - java code.java

## Details of all the tables and their schema
Three columns - name, sku and description

## Points to achieve
- [x] Your code should follow concept of OOPS 
- [x] Support for regular non-blocking parallel ingestion of the given file into a table. Consider thinking about the scale of what should happen if the file is to be processed in 2 mins.
- [ ] Support for updating existing products in the table based on `sku` as the primary key. (Yes, we know about the kind of data in the file. You need to find a workaround for it)
- [x] All product details are to be ingested into a single table
- [ ] An aggregated table on above rows with `name` and `no. of products` as the columns

## What would you improve if given more days
Will optimize the possible code.
