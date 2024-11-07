# Terrastack_Assignment
This assignment is based on QGIS, PostgreSQL, geometry and maps.
The problem statement is -
# Assignment: Getting Familiar with GIS

This problem involves getting familiar with the tools we usually use and performing some basic queries and operations using them.

The `sawangi.shp` file contains the ownership plots of Sawangi village in the Amravati district.  
**Shape file can be located here:** [Sawangi Shape File](https://drive.google.com/file/d/1OeR0WB-6TAQQzAI5tcQIt0JVxc59asWH/view?usp=share_link)

### Tasks

1. **Load the `sawangi.shp` shapefile into QGIS and add the screenshot in your report.**  
2. **Insert the shapefile into your Postgres database** (`dbname=sawangi_test`) and report the datatype of each column.
3. **Write the answer to each of the following questions along with the SQL query in your report:**
   - **Number of polygons with an area greater than 5 Ha.**
   - **Delete polygons with the value of the `pin` column as NULL and report the number of rows deleted.**
   - **Total perimeter of the Sawangi village.**

   **Note:** The SRID for `sawangi.shp` is **32643**. Feel free to use this information anywhere as required.

### Assignment Guidelines

- You must submit a single PDF file titled `{your_name}.pdf` on the Google Form.
- The PDF report should include the images, queries, and results for the assignment.

