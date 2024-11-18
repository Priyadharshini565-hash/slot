# Ex03 Time Table
## Date:18.11.2024

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
'''
<html>
<head>
     <title> SLOT TIMETABLE </title>
</head>
<body>
<img src="/static/logo.png" height="200" width="1000">
<table border="2">
    <h1>PRIYADHARSHINI.R (24900285)</h1>
    <caption>Marksheet</caption>
    <tr bgcolor="red">
        <th>TIME/DAY</th>
        <th>MONDAY</th>
        <th>TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
    </tr>
    <tr bgcolor="yellow">
        <th>8-10</th>
        <td>Free</td>
        <td>Web</td>
        <td>Free</td>
        <td>Free</td>
        <td>Free</td>
        <td>Eng</td>
    </tr>
    <tr bgcolor="yellow">
        <th>1-3</th>
        <td>Maths</td>
        <td>Free</td>
        <td>Eng</td>
        <td>Free</td>
        <td>Career</td>
        <td>C program</td>
    </tr>
    <tr bgcolor="yellow">
        <th>3-5</th>
        <td>Free</td>
        <td>DE</td>
        <td>Chem</td>
        <td>Chem</td>
        <td>Free</td>
        <td>Free</td>
    </tr>
    </table>
</table border>
<table border="2">
    <tr bgcolor="red">
        <th>S.no</th>
        <th>Couse code</th>
        <th>Course name</th>
    </tr>
    <tr bgcolor="yellow">
        <td>1</td>
        <td>19AI414</td>
        <td>FUNDAMENTALS OF WEB APPLICATION</td>
    </tr>
    <tr bgcolor="yellow">
        <td>2</td>
        <td>19MA201</td>
        <td>CALCULUS AND MATRIX ALGEBRA </td>
    </tr>
    <tr bgcolor="yellow">
        <td>3</td>
        <td>19EN101</td>
        <td>COMMUNICATIVE ENGLISH</td>
    </tr>
    <tr bgcolor="yellow">
        <td>4</td>
        <td>19AI304</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
    </tr>
    <tr bgcolor="yellow">
        <td>5</td>
        <td>19EY708</td>
        <td>CAREER DEVELOPMENT SKILLS</td>
    </tr>
    <tr bgcolor="yellow">
        <td>6</td>
        <td>19CY205</td>
        <td>PRINCIPLE OF CHEMISTRY IN ENGINEERING </td>
    </tr>
    <tr bgcolor="yellow">
        <td>7</td>
        <td>19EE404</td>
        <td>DIGITAL ELECTRONICS </td>
    </tr>
</table>
</body>
</html>

'''

## OUTPUT
![alt text](<Screenshot 2024-11-18 125112.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
