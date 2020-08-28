# sDyna
Developed with [Ali Talha Atici](https://github.com/alitatici).

The basic aim of the application is to calculate the base shear force of multi-degree of freedom (MDOF) systems according to selected earthquake data. Response of multi degree of freedom systems to ground motion can be solved by sDyna easily. Mass and stiffness must be entered to calculate amplitudes of the system according to the equation of motion (EOM) for each floor. Besides, sDyna creates a unique and brief report with your inputs in MS Word(.docx) format. You can check the results, mode shapes, and graphs from this report.

### SETUP FILE 

sDyna can be reached with [setup file](https://drive.google.com/file/d/1wOrw0f-yjygQAH-0EQWknsbBQFWn9zWl/view).

### NOTES:

1- When trying to enter data, do not forget to fill all required areas.

2- Floor, Mass, and Stiffness can be saved and opened as an Excel file.  

3- Damping raito is set as 0.05 for reinforced concrete buildings.

4- Newmark Method is used to evaluate dynamic response numerically.

5- Modes' base shear forces have been integrated with SRSS Method(Square Root of Sum of Squares).

6- Earthquake data must be taken from [AFAD](https://tadas.afad.gov.tr)* web page. There is an example earthquke data file to use.

7- It is recommended to add the floor data in order.


### *HOW TO USE AFAD
 
 1- Open the web page.
 
 2- Choose "Guest Login".
 
 3- Click "Events" section and then "Search".
 
 4- Filter earthquakes features and click "Search".
 
 5- Click "Detail" button of an earthquake.
 
 6- Go to "Records" tab and then put a check mark on station code.
 
 7- Scroll down and make sure acceleration from processed data and ASCII file format is selected. 
 
 8- Download data.
 
 ### PREVIEW

![sDyna-Ui-SS](https://user-images.githubusercontent.com/52800054/91605244-d0ffe500-e978-11ea-9495-22ceb1be4731.PNG)

![sDynaReportSS](https://user-images.githubusercontent.com/52800054/91605541-48ce0f80-e979-11ea-9b14-4bcc6ee8f677.PNG)

