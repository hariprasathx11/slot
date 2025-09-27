# Ex03 Time Table
## Date:05.09.2025

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
        <title>slot timetable</title>
    </head>
    <body>
        <center><img src="logo.png"align="center" height="80" width="1000" ></center>
        
        <h1 align="center">slot timetable-(25017723)</h1>
        <table align="center" border="4" cellspacing="4" celpadding="4">
            <tr bgcolor="orange">
                <td>day/time</td>
                <td>monday</td>
                <td>tuesday</td>
                <td>wednesday</td>
                <td>thursday</td>
                <td>friday</td>
                <td>saturday</td>
            </tr>
            <tr>
                <td bgcolor="yellow">8-10</td>
                <td>comm eng</td>
                <td bgcolor="grey">free slot</td>
                <td>fwad</td>
                <td>comm eng</td>
                <td>python</td>
                <td>fwad</td>
            </tr>
            <tr>
                <td bgcolor="yellow">10-12</td>
                <td bgcolor="grey">free slot</td>
                <td>python</td>
                <td>fwad</td>
                <td bgcolor="grey">free slot</td>
                <td>python</td>
                <td>python</td>

            </tr>
            <tr>
                <td bgcolor="yellow">1-3</td>
                <td>comm eng</td>
                <td>comm eng</td>
                <td>mentormeet</td>
                <td>comm eng</td>
                <td>fwad</td>
                <td>fwad</td>
            </tr>
            <tr>
                <td bgcolor="yellow">3-5</td>
                <td bgcolor="grey">free slot</td>
                <td bgcolor="grey">free slot</td>
                <td>python</td>
                <td bgcolor="grey">free slot</td>
                <td>comm eng</td>
                <td bgcolor="grey">free slot</td>
            </tr>
            <table align="center" border="2">
            <tr bgcolor="yellow">
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>WEB APPLICATIONS</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI304</td>
                <td>PYTHON PRORGRAMMING</td>
            </tr>
        </table>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (12).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
