# Develop By: Naveen Kumar.T
# Reg No: 212223220067
# Ex03 Time Table
## Date:06:03:2024

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

## PROGRAM:
```
<!DOCTYPE html>
<html>
<head>
<title>SLOT TIME TABLE (EVEN SEM)
</title>
</head>
<img src="/static/logo.png" height="100" width="540"
<body >
    <br>
    <b>SLOT TIME TABLE - NAVEEN KUMAR.T (212223220067)</b>
</body>
<body>
<table border="5" width="570">
<tr>
<th bgcolor="WHITE">Day/Time</th>
<th bgcolor="WHITE">Monday</th>
<th bgcolor="WHITE">Tuesday</th>
<th bgcolor="WHITE">Wednesday</th>
<th bgcolor="WHITE">Thursday</th>
<th bgcolor="WHITE">Friday</th>
</tr>
<tr>
<th bgcolor="NAVY">8-10</th>
<th bgcolor="PINK">INTRO OF ML</th>
<th bgcolor="PINK">FREE SLOT</th>
<th bgcolor="PINK">FWAD</th>
<th bgcolor="SILVER">FREE SLOT</th>
<th bgcolor="SILVER">PRINCIPAL OF CHEMISTRY</th>
</tr>
<tr>
<th bgcolor="NAVY">10-12</th>
<th bgcolor="PINK">COMMUNICATIVE ENGLISH</th>
<th bgcolor="olive">FWAD</th>
<th bgcolor="SILVER">COMMUNICATIVE ENGLISH </th>
<th bgcolor="PINK">FREE SLOT</th>
<th bgcolor="cyan">FREE SLOT</th>
</tr>
<tr>
<th bgcolor="NAVY">12-1</th>
<th colspan="5" align="center" bgcolor="CREAM">LUNCH</th>
</tr>
<tr>
<th bgcolor="NAVY">1-3</th>
<td bgcolor="olive">FWAD</th>
<th bgcolor="TEAL">INTRO OF ML</th>
<th bgcolor="SILVER">COMPUTER NETWORK</th>
<th bgcolor="SILVER">COMMUNICATIVE ENGLISH</th>
<th bgcolor="PINK"> Computer Network</th>
</tr>
<tr>
<th bgcolor="NAVY">3-5</th>
<th bgcolor="TEAL">FREE SLOT</th>
<th bgcolor="PINK">FREE SLOT</th>
<th bgcolor="olive">FWAD</th>
<th bgcolor="PINK">PY</th>
<th bgcolor="SILVER">FREE SLOT</th>
</tr>
</table>
<br>
<table border="5" width="570">
<tr>
<td>S.NO.</td>
<td>Subject Code</td>
<td>Subject Name</td>
</tr>
<tr>
<td>1.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Developement (FWAD)</td>
</tr>
<tr>
<td>2.</td>
<td>19EN101</td>
<td>Communicative English </td>
</tr>
<tr>
<td>3.</td>
<td>19AI301</td>
<td>Python Programming</td>
</tr>
<tr>
<td>4.</td>
<td>19CY205</td>
<td>Principles of Chemistry in Engineering </td>
</tr>
<tr>
<td>5.</td>
<td>19CS406</td>
<td>Computer Network</td>
</tr>
<tr>
<td>6.</td>
<td>19AI410</td>
<td>intro Of ML</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT:![alt text](<V1/Screenshot (75).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
