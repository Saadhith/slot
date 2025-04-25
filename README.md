# Ex03 Time Table
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="c:\Users\admin\Desktop\saveetha eng logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - RAMESH KRISHNAN S (24001852)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td colspan="3" align="center">FREE SLOT</td>
<td>PYTH</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>C PROG</td>
<td>FREE SLOT</td>
<td>FWAD</td>
<td>FREE SLOT</td>
<td>PYTH</td>
<td>OS</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td colspan="1" align="center">FREE SLOT</td>
<td>OS</td>
<td>MENTOR</td>
<td>PYTH</td>
<td>C PROG</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td colspan="2" align="center">FREE SLOT</td>
<td>PYTH</td>
<td>FREE SLOT</td>
<td>FWAD</td>
<td>FREE SLOT</td>
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
<td align="center">19AI414</td>
<td>Fundamentals of Web (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTAL OF C</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS405</td>
<td>OPERATING SYSTEM</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS416</td>
<td>Python and Linear Algebra</td>
</tr>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/00d89e13-c8da-4f72-9f37-4c4bf4a62171)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
