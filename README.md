# Ex03 Time Table
## Date:12.03.2024

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
<title> My Time Table </title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
<table border="2" cellspacing="5" cellpading="5">
<caption>SLOT TIMETABLE - NIKESH KUMAR(212223040132)</caption>
<tr>
<th bgcolor="red">Day/Time</th>
<th bgcolor="red">Monday</th>
<th bgcolor="red">Tuesday</th>
<th bgcolor="red">Wednesday</th>
<th bgcolor="red">Thursday</th>
<th bgcolor="red">Friday</th>
</tr>
<tr>
<td bgcolor="red">8-10</td>
<td bgcolor="lightblue">BEEE</td>
<td bgcolor="lightblue">C</td>
<td bgcolor="lightblue">chemistry</td>
<td bgcolor="lightblue">free</td>
<td bgcolor="lightblue">FWAD</td>
</tr>
<tr>
<td bgcolor="red">10-12</td>
<td bgcolor="lightblue">free</td>
<td bgcolor="lightblue">free</td>
<td bgcolor="lightblue">CN</td>
<td bgcolor="lightblue">C</td>
<td bgcolor="lightblue">Creative Skills</td>
</tr>
<tr>
<td bgcolor="red">12-1</td>
<td colspan="5" bgcolor="yellow">----------------LUNCH TIME----------------</td>
</tr>
<tr>
<td bgcolor="red">1-3</td>
<td bgcolor="lightblue">maths</td>
<td bgcolor="lightblue">FWAD</td>
<td bgcolor="lightblue">free</td>
<td bgcolor="lightblue">FWAD</td>
<td bgcolor="lightblue">chemistry</td>
</tr>
<tr>
<td bgcolor="red">3-5</td>
<td colspan="3" bgcolor="lightblue">free</td>
<td bgcolor="lightblue">OS</td>
<td bgcolor="lightblue">maths</td>
</tr>
</table>
<table border="2" cellspacing="5" cellpading="5">
<tr>
<th>S.NO</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr>
<td>1.</td>
<td>19AI305</td>
<td>Advanced C Programming(C)</td>
</tr>
<tr>
<td>2.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Developement(FWAD)</td>
</tr>
<tr>
<td>3.</td>
<td>19CS405</td>
<td>Computer Networks(CN)</td>
</tr>
<tr>
<td>4.</td>
<td>19CS406</td>
<td>Operating System(OS)</td>
<tr>
<td>5.</td>
<td>19CY205</td>
<td>Principles of Chemistry in Engineering(chemistry)</td>
</tr>
<tr>
<td>6.</td>
<td>19EE305</td>
<td>Basic Electrical Electronics and Measurement Engineering(BEEE)</td>
</tr>
<tr>
<td>7.</td>
<td>19EY702</td>
<td>Creative Skills for Communication(creative skills)</td>
</tr>
<tr>
<td>8.</td>
<td>19MA206</td>
<td>Logics and Combinatorics(maths)</td>
</tr>
</table>
</center>
</body>
</html>

```

## OUTPUT
![alt text](<WEB EX3.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
