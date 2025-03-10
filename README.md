# Ex03 Time Table
## Date: 15-03-2024

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
        <title>My Time Table</title>
    </head>
    <body>
        <img src="logo.png" height="200" width="1200">
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="lightpink">
<caption><b>My Time Table - MOPURI ANKITHA (212223040117)</b></caption>
<tr align="center">
<th bgcolor="silver">Day/Time</th>
<th bgcolor="silver">Monday</th>
<th bgcolor="silver">Tuesday</th>
<th bgcolor="silver">Wednesday</th>
<th bgcolor="silver">Thursday</th>
<th bgcolor="silver">Friday</th>
<th bgcolor="silver">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="silver">8-10</th>
<td colspan="0" align="center">Basic Financial Accounting</td>
<td>Free Slot</td>
<td>Probability and Queueing Models</td>
<td>Free Slot</td>
<td>FWAD</td>
<td>Free Slot</td>
</tr>
<tr align="center">
<th bgcolor="silver">10-12</th>
<td>Software Engineering</td>
<td>Computer Networks</td>
<td>BEEE</td>
<td>Computer Networks</td>
<td>Python</td>
<td>Free Slot</td>
</tr>
<tr>
<th bgcolor="silver">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="silver">1-3</th>
<td colspan="0" align="center">BEEE</td>
<td>FWAD</td>
<td>Free Slot</td>
<td>FWAD</td>
<td>Free Slot</td>
<td>Creative Skills</td>
</tr>
<tr align="center">
<th bgcolor="silver">3-5</th>
<td colspan="0" align="center">Probability and Queueing Models</td>
<td>Free Slot</td>
<td>Software Engineering</td>
<td>Python</td>
<td>Basic Financial Accounting</td>
<td>Free Slot</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI301</td>
<td>Python Programming</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development(FWAD)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS406</td>
<td>Computer Networks</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS408</td>
<td>Software Engineering</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA222</td>
<td>Probability and Queueing Models</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EE305</td>
<td>Basic Electrical,Electronics and Measurement Engineering(BEEE)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MS154</td>
<td>Basic Financial Accounting</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY702</td>
<td>Creative Skills for Communication</td>
</tr>
</table>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (202).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
