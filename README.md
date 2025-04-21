# Ex03 Time Table
## Date: 16.11.2024

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
<html >
    <head>
        <title>Timetable </title>
    </head>
    <body >
        <center>
            <img src="/static/logo.png" height = "200" width="1000>">
        </center>
        <table align="Center" border="3">
            <caption><b>My Time Table (Kishore B - 24900596)</b></caption>
            <tr  bgcolor="Purple" cellspacing="10" cellpadding="20">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <th  bgcolor="Purple">8-10</th>
                <td  bgcolor="Violet">Free </td>
                <td  bgcolor="Violet">FWAD</td>
                <td  bgcolor="Violet">Python & Math</td>
                <td  bgcolor="Violet">Free</td>
                <td  bgcolor="Violet">Free</td>
                <td  bgcolor="Violet">English</td>
            </tr>
            <tr>
                <th  bgcolor="Purple">10-12</th>
                <td  bgcolor="Violet">Free</td>
                <td  bgcolor="Violet">Free</td>
                <td  bgcolor="Violet">English</td>
                <td  bgcolor="Violet">Python</td>
                <td  bgcolor="Violet">Soft Skills</td>
                <td  bgcolor="Violet">Python & Math</td>
            </tr>
            <tr>
                <th  bgcolor="Purple">12-1</th>
                <td    bgcolor="Lavender"colspan="6" align="center">LUNCH BREAK</td>
            </tr>

            <tr>
                <th  bgcolor="Purple">1-3</th>
                <td  bgcolor="Violet">Chemistry</td>
                <td  bgcolor="Violet">Python</td>
                <td  bgcolor="Violet">Mentor Meet</td>
                <td  bgcolor="Violet">Chemistry</td>
                <td  bgcolor="Violet">FWAD</td>
                <td  bgcolor="Violet">FWAD</td>
            </tr>
            <tr>
                <th  bgcolor="Purple">3-5</th>
                <td  bgcolor="Lavender" colspan="6" align="center">FREE SLOT</td>

        </table>    

    </body>
</html>
<br>
<hr>
<br>

<html>
    <head>
        <title>courses</title>
    </head>
    <body>
        <table align="Center" border="3" >
        <caption><b>My courses</b></caption>

            <tr bgcolor=" Purple">
                <th>S.NO</th>
                <th>Course Code</th>
                <th>Course Name</th>
            </tr>
            <tr>
                <th bgcolor="Purple">1</th>
                <td bgcolor=" Violet">19A13414</td>
                <td bgcolor=" Violet">Fundamentals of web application development (FWAD)</td>
            </tr>
            <tr>
                <th bgcolor="Purple">2</th>
                <td  bgcolor=" Violet">19AI301C</td>
                <td  bgcolor=" Violet">Python adn Linear Algebra</td>
            </tr>
            <tr>
                <th bgcolor="Purple">3</th>
                <td  bgcolor=" Violet">19EN101</td>
                <td  bgcolor=" Violet">Communicative English</td>
            </tr>
            <tr>
                <th bgcolor="Purple">4</th>
                <td  bgcolor=" Violet">19CY205</td>
                <td  bgcolor=" Violet">Principle of Chemistry in Engineeing </td>
            </tr>
            <tr>
                <th bgcolor="Purple">6</th>
                <td  bgcolor=" Violet">ECA-M-SCOFT</td>
                <td  bgcolor=" Violet">Mentor Meet</td>
            </tr>
            <tr>
                <th bgcolor="Purple">8</th>
                <td  bgcolor=" Violet">19EY708</td>
                <td  bgcolor=" Violet">Carrer development skill(Soft skill)</td>
            </tr>
        </table>
    </body>
</html>  
```

## OUTPUT
![image](https://github.com/user-attachments/assets/c9feaa17-cd42-43b1-a036-a8a4460825b1)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
