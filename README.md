# Ex03 Time Table
## Date:18-03-2024

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
    <head>
        <center>
            <img src="logo.png" height="100" width="550">
        </center>
        <title>Slot Time Table</title>
    </head>
    <body>
        <br>
        <br>
        <table align="center" width="550" cellspacing="2" cellpadding="4" border="4" bgcolor="chocolate">
            <caption><b>SLOT TIME TABLE-Prajin S(212223230151)</b></caption>
            <tr>
            <th bgcolor="gold">Day/Time</th>
            <th bgcolor="gold">Monday</th>
            <th bgcolor="gold">Tuesday</th>
            <th bgcolor="gold">Wednesday</th>
            <th bgcolor="gold">Thursday</th>
            <th bgcolor="gold">Friday</th>
            <th bgcolor="gold">Saturday</th>
            </tr>
            <tr>
                <th bgcolor="gold">8-10</th>
                <td>Free Slot</td>
                <td>BEEE</td>
                <td>Web</td>
                <td>Free Slot</td>
                <td>BEEE</td>
                <td>Prob</td>
            </tr>
            <tr>
                <th bgcolor="gold">10-12</th>
                <td>Robot</td>
                <td>Web</td>
                <td>Creative Skill</td>
                <td>Prob</td>
                <td>C prog</td>
                <td>EMPD</td>
            </tr>
            <tr>
                <th bgcolor="gold">12-1</th>
                <td colspan="6" align="center">Lunch Time</td>
            </tr>
            <tr>
                <th bgcolor="gold">1-3</th>
                <td>Web</td>
                <td>Phy</td>
                <td>Phy & HRM</td>
                <td>EMPD</td>
                <td>HRM</td>
                <td>Free Slot</td>
            </tr>
            <tr>
                <th bgcolor="gold">3-5</th>
                <td>C Prog</td>
                <td>Free Slot</td>
                <td>Free Slot</td>
                <td>Free Slot</td>
                <td>Robot</td>
                <td>Free Slot</td>
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr>
                <th>S. No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI303</td>
                <td>Engineering Mechanics and Product development</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>    
                <td>3.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Appliction Development</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19AI533</td>
                <td>Introduction to Robotics</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EE305</td>
                <td>Basic Electrical,Electronics and Measurement Engineering</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY702</td>
                <td>Creative Skills for Communiction</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>19MA222</td>
                <td>Probability and Queueing Models</td>
            </tr>
            <tr>
                <td>8.</td>
                <td>19MS156</td>
                <td>Human Resource Management and Team Building</td>
            </tr>
            <tr>
                <td>9.</td>
                <td>19PH214</td>
                <td>Physics for Quantum Computing</td>
            </tr>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (2).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
