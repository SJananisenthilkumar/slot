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
<html>
	<head>
	<title>SLOT TIMETABLE</title>
	<body>
	<center>
	<img src = "/static/logo.png" height="100" width="540">
	<table border="5" bgcolor="cyan" cell spacing="10" cellpadding="10">
	<caption>SLOT TIME TABLE-JANANI S (23013409)</caption>
	<tr>
	<TR bgcolor="Yellow">
	<th>Day/Time</th>
	<th>Monday</th>
	<th>Tuesday</th>
	<th>Wednesday</th>
	<th>Thursday</th>
	<th>Friday</th>
	</TR>
	<tr>
	<th bgcolor="yellow">8-10</th>
	<td>FREE SLOT</td>
	<td>PROB</td>
	<td>FWAD</td>
	<td>FREE SLOT</td>
	<td>PYTHON</td>
	</tr>
	<tr>
	<th bgcolor="yellow">10-12</th>
	<td>FREE SLOT</td>
	<td>PYTHON</td>
	<td>PHYSICS</td>
	<td>FWAD</td>
	<td>PROB</td>
	</tr>
	<tr>
	<th bgcolor="yellow">1-3</th>
	<td>FREE SLOT</td>
	<td>FREE SLOT</td>
	<td>FREE SLOT</td>
	<td>SOFT SKILLS</td>
	<td>FWAD</td>
	</tr>
	<tr>
	<th bgcolor="yellow">3-5</td>
	<td>FREE SLOT</td>
	<td>FREE SLOT</td>
	<td>PYTHON</td>
	<td>PYTHON</td>
	<td>PHYSICS</td>
	</tr>
	</table>
	<br>
	<table>
	<table border="5" cell spacing="10" cellspading="15">
	<tr>
	<th>S.NO</th>
	<th>SUBJECT CODE</th>
	<th>SUBJECT NAME</th>
	</tr>
	<tr>
	<td >1</td>
	<td>19A1414</td>
	<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
	</tr>
	<tr>
	<td>2</td>
	<td>19MA222</td>
	<td>PROBABILITY AND QUEUEING THEORY(PQ)</td>
	</tr>
	<tr>
	<td>3</td>
	<td>19AI301C</td>
	<td>PYTHON AND LINEAR ALGEBRA(PYTHON)</td>
	</tr>
	<tr>
	<td>4</td>
	<td>19PH214</td>
	<td>PHYSICS AND QUANTUM COMPUTING(PQC)</td>
	</tr>
	<tr>
	<td>5</td>
	<td>19EY701</td>
	<td>SOFT SKILLS(SS)</td>
	</tr>
	</center>
	</body>
	</head>
</html>
	
```
## OUTPUT
![Alt text](<Screenshot (17).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
