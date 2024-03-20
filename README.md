# Ex03 Time Table
## Date:20/03/2024

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
         <title>Slot Timetable</title>
    </head>
    <body>
    <center>
    <img src="/static/logo.png" height="100" width"550">
    </center>
    <br>
         <table align="center" width="550" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
         <caption><b>Time Table - Thirumalai.V (23013035)</b></caption>
    <tr align="center">
        <th bgcolor="plum">Day/Time</th>
        <th bgcolor="plum">Monday</th>
        <th bgcolor="plum">Tuesday</th>
        <th bgcolor="plum">Wednesday</th>
        <th bgcolor="plum">Thursday</th>
         <th bgcolor="plum">Friday</th>
    </tr>
    <tr align="center">
        <th bgcolor="plum">8-10</th>
        <td colspan="2">Communicative english</td>
        <td>Web development</td>
        <td>Engineering design and modelling</td>
        <td>Python and Linear programming</td>
    </tr>
    <tr align="center">
        <th bgcolor="plum">10-12</th>
        <td>Free slot</td>
        <td>Pyhton and Linear algebra</td>
        <td>Free slot</td>
        <td>Web development</td>
        <td>Free slot</td>
    </tr>
    <tr>
        <th bgcolor="plum">12-1</th>
        <td colspan="5" align="center">L U N C H</td>
    </tr>
    <tr align="center">
        <th bgcolor="plum">1-3</th>
        <td>Principles of chemistry in engineering</td>
        <td>Engineering design and modelling</td>
        <td>Principles of chemistry in engineering</td>
        <td>Free slot</td>
        <td>Web development</td>
    </tr>
    <tr align="center">
        <th bgcolor="plum">3-5</th>
        <td colspan="2">Free slot</td>
        <td colspan="2">python and linear algebra</td>
            <td>Free slot</td>
    </tr>
    </table>
    </br>
    <table align="center" cellspacing="2" cellpadding="4" border="2">
    <tr align="center">
    <th>S. No.</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
    </tr>
    <tr>
    <td align="center">1.</td>
    <td align="center">19AI301C</td>
    <td>Python and Linear Algebra</td>
    </tr>
    <tr>
    <td align="center">2.</td>
    <td align="center">19AI302</td>
    <td>EDM</td>
    </tr>
    <tr>
    <td align="center">3.</td>
    <td align="center">19AI414</td>
    <td>FWAD</td>
    </tr>
    <tr>
    <td align="center">4.</td>
    <td align="center">19CY205</td>
    <td>Principles of chemistry in Engineering</td>
    </tr>
    <tr>
    <td align="center">5.</td>
    <td align="center">19EN101</td>
    <td>Communicative English</td>
    </tr>
    </table>
    </body>
    </html>
```

## OUTPUT
![Screenshot 2024-03-20 092949](https://github.com/Thirumalai23013035/slot/assets/153185249/17e3d66d-06fd-431d-be72-6716c2a195f1)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
