# Ex03 Time Table
## Date:
14.03.2024

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
    <img src="logo.png" height="200" width="1200" >
    
    <h2>My Timetable</h2>
    <table border="5">
        <tr>
            <th style="background-color: lightblue;">Time</th>
            <th style="background-color: lightblue;">Monday</th>
            <th style="background-color: lightblue;">Tuesday</th>
            <th style="background-color: lightblue;">Wednesday</th>
            <th style="background-color: lightblue;">Thursday</th>
            <th style="background-color: lightblue;">Friday</th>
            <th style="background-color: lightblue;">Saturday</th>
        </tr>
       
        <tr>
            <td>8:00 - 10:00</td>
            <td>Physics</td>
            <td>Ethical HACking</td>
            <td>BEE</td>
            <td>Physics</td>
            <td>WEB</td>
            <td>Maths</td>
        </tr>
        <tr>
            <td>10:00 - 12:00</td>
            <td>Software</td>
            <td>Python</td>
            <td>Software</td>
            <td>Maths</td>
            <td>CREATIVE SKILL</td>
            <td>FREE</td>
        </tr>
        <tr>
            <th></th>
            <th></th>
            <th style="background-color: lightgreen;">LUNCH</th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
        <tr>
            <td>1:00 - 3:00</td>
            <td>BEE</td>
            <td>WEB</td>
            <td>Python</td>
            <td>Web</td>
            <td>FREE</td>
            <td>Ethical Hacking</td>
        </tr>
        <tr>
            <td>3:00 - 5:00</td>
            <td>FREE</td>
            <td>FREE</td>
            <td>FREE</td>
            <td>FREE</td>
            <td>FREE</td>
            <td>FREE</td>
        </tr>
    </table>
    

    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI41</td>
            <td>Fundamentals of Web Application Development(FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI414</td>
            <td>python</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19PH214</td>
            <td>quantum Physics</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19cs408</td>
            <td>software engineering</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19MA222</td>
            <td>probability and quing model</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY702</td>
            <td>creative skill</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19EE305</td>
            <td>BEEE</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>19cs417</td>
            <td>ethical hacking</td>
        </tr>
    </table>    
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot (66).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
