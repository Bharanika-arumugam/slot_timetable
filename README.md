# Ex03 Time Table
## Date:17-10-2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <body bgcolor="#E8F3EC">
        <center><img src="c:\Users\admin\Downloads\image.jpg" width="500"></center>
        <table border="1" cellspacing="0" cellpadding="10" bgcolor="#A7C7E7">
            <h3 align="center"><strong>Slot time table - Bharanika A S (212224040048)</strong></h3>
           <tr bgcolor="#FADADD">
            <th>Date/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
           </tr>
           <tr>
            <th bgcolor="#FADADD">8.00-10.00</th>
            <td colspan="5" align="center">Free slots</td>
            <td>Fundamentals of web application and development</td>
           </tr>
           <tr>
            <th bgcolor="#FADADD">10.00-12.00</th>
            <td>Free</td>
            <td>Algebra and Number theory</td>
            <td>Software engineering</td>
            <td>Advanced C programming</td>
            <td>Computer Networks</td>
            <td>Free slot</td>
           </tr>
           <tr>
            <th bgcolor="#FADADD">12.00-1.00</th>
            <td colspan="6" align="center">LUNCH TIME</td>
           </tr>
           <tr>
            <th bgcolor="#FADADD">1.00-3.00</th>
            <td>HRM</td>
            <td>HRM</td>
            <td>Mentor meet</td>
            <td>Algebra and number theory</td>
            <td>Fundamentals of web development</td>
            <td>Computer Networks</td>
           </tr>
           <tr>
            <th bgcolor="#FADADD">3.00-5.00</th>
            <td>Reasoning ability</td>
            <td>Software engineering</td>
            <td>Advanced C programming</td>
            <td colspan="3" align="center">Free slots</td>
           </tr>

        </table>
        <br>
        <table border="1" cellspacing="0" cellpadding="10" bgcolor="#FADADD" align="center">
            <h3 align="center"><strong>Subject details</strong>
        <tr bgcolor="#E8F3EC">
            <th>S.no</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <th>1.</th>
            <td>19AI414</td>
            <td>Fundamentals of web application</td>
        </tr>
        <tr>
            <th>2.</th>
            <td>19AI305</td>
            <td>Advanced C programming</td>
        </tr>
        <tr>
            <th>3.</th>
            <td>19CS406</td>
            <td>Computer Networks</td>
        </tr>
        <tr>
            <th>4.</th>
            <td>19CS408</td>
            <td>SOftware Engineering</td>
        </tr>
        <tr>
            <th>5.</th>
            <td>19MS156</td>
            <td>HRM</td>

        </tr>
        <tr>
            <th>6.</th>
            <td>19MA212</td>
            <td>Algebra and number theory</td>
        </tr>
        <tr>
            <th>7.</th>    
            <td>19EY709</td>
            <td>Reasoning ability</td>
            </tr>

        </table>
    </body>
</html>
```


## OUTPUT
"C:\Users\admin\Pictures\Screenshots\Screenshot 2025-10-17 235559.png"


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
