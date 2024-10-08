# Ex03 Time Table
## Date:8/10/24

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
<html></html>
<head>
<title>Slot Timetable</title>
<style>
	.free-slot{
		background-color:bisque;
	}
</style>
</head>
<body>
	<center>
	<img src="LOGO.png" height="100" width="540">
	</center>
	<br>
	<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="aqua">
	<caption><b>SLOT TIMETABLE - SANJAY V (212223230188)</b></caption>
	<tr align="center">
		<th bgcolor="Lavender">Day/Time</th>
		<th bgcolor="Lavender">Monday</th>
		<th bgcolor="Lavender">Tuesday</th>
		<th bgcolor="Lavender">Wednesday</th>
		<th bgcolor="Lavender">Thursday</th>
		<th bgcolor="Lavender">Friday</th>
    	<th bgcolor="Lavender">Saturday</th>
	</tr>
	<tr align="center">
		<th bgcolor="LightGreen">8-10</th>
		    <td class = 'free-slot'>Free</td>
			<td class = 'free-slot'>Free</td> 
			<td>TOC</td>
			<td class = 'free-slot'>Free</td>
			<td>Cyber law</td>
    		<td>Fundamentals of Web Application</td>
	</tr>
	<tr align="center">
			<th bgcolor="LightGreen">10-12</th>
			<td class = 'free-slot'>Free</td>
			<td>Fund of AI</td>
			<td>Operating System</td>
			<td>Fundamentals of Web Application</td>
			<td>fund of Ai</td>
			<td class = 'free-slot'>Free</td>
	</tr>
	<tr>
		<th bgcolor="LightGreen">12-1</th>
			<td colspan="5" align="center">L U N C H  T I M E</td>
	</tr>
	<tr align="center">
		<th bgcolor="LightGreen">1-3</th>
		<td class = 'free-slot'>Free</td>
		<td class = 'free-slot'>Free</td>
		<td>Mentor Meet</td>
		<td>TOC</td>
		<td class = 'free-slot'>Free</td>
    	<td>Operating System</td>
	</tr>
		<tr align="center">
			<th bgcolor="LightGreen">3-5</th>
			<td>Fundamentals of Web Application</td>
			<td class = 'free-slot'>Free</td>
			<td>Theory of comptation</td>
			<td class = 'free-slot'>Free</td>
			<td>Operating System</td>
			<td>cyber law</td>
			
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
			<td align="center">19AI414</td>
			<td>Fundamentals of web application</td>
		</tr>
		<tr>
			<td align="center">2.</td>
			<td align="center">19CS408</td>
			<td>Cyber Law</td>
		</tr>
		<tr>
			<td align="center">3.</td>
			<td align="center">19CS405</td>
				<td>Operating system</td>
		</tr>
		<tr>
			<td align="center">4.</td>
			<td align="center">19MA211</td>
			<td>Theory of Computation</td>
		</tr>
		<tr>
			<td align="center">5.</td>
			<td align="center">ECA-M</td>
			<td>Mentor Meet</td>
		</tr>
		<tr></tr>
			<td align="center">6.</td>
			<td align="center">19AI409</td>
			<td>Fund of Ai</td>
		</tr>
		<tr></tr>
			<td align="center">7.</td>
			<td align="center">19MC801</td>
			<td>Professional Ethics</td>
		</tr>
		<tr></tr>
			<td align="center">8.</td>
			<td align="center">19MC802</td>
			<td>Environmental Science</td>
		</tr>
		<tr></tr>
			<td align="center">9.</td>
			<td align="center">19AI409</td>
			<td>Constitution of India</td>
		</tr>
		</table>
	</body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/8625148c-bc7c-4616-88af-7c79061fcf6b)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
