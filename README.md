# tableau-10-essential

Notes for myself while I am completing the Tableau 10 essential training through LinkedIn 

Downloading and activating my year of student tableau desktop and tableau prep

### Chapter 1
- Introduction


tableau.com/support/drivers to download drivers allowing connection to different data sources. ie EMR, Redshift, Google Analytics etc
- server was down for maintenance when I tried. 

Tableau workbook (.twb) stores visualization without the data source

Tableau data source (.tds) server address password to access data source is included. 

Tableau bookmark (.tbm) stores connection to worksheet in another Tableau workbook

Tableau data extract (.tde) stores Tableau data as filtered and aggregated - useful if you have 100's of thousand of rows of data and want to isolate a certain number or time series 

Tableau packaged workbook (.twbx) stored data and visualizations to be shared with others working with Tableau or Tableau Reader (for people that don't need to manipulate the data but want to view it)

### Chapter 2 
- Managing Data Sources and Visualization


connecting to a data source - like opening any other file. Unless we need to connect to a database that is hosted somewhere. 


joining related data sources - the process for this has changed since version 10 of the Tableau software when this tutorial was writeen. Now Relationships are the default way of joining data together but we can still double click a table and manually join with another table with our choosing. All related tables stay separate 
- https://help.tableau.com/v2020.3/pro/desktop/en-us/datasource_multitable_normalized.htm has an explanation of the new way things are done from when the tutorial was written. 


joining related fields woth inconsistent names


cleaning up source data 


creating visualization using Show Me 


changing the order of fields in a visualization 


changing the summary operation


splitting text into multiple columns


presenting data using storylines


#### Vocab for review 
Inner join - two files have a field in common and are joined based on this