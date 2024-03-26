# Ex03 Time Table
## Date:
24/03/2024
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
<head>
    <title>SEC SLOT TIMETABLE</title>
</head>
<center>
<img src="image.png" width='600'align="center">
</center>
<body>
    <table BORDER='3' width='600'bgcolor='white' cellspacing='3' align="center">
        <CAPTION align="above">SLOT TIMETABLE- GOKUL SACHIN K (212223220025)</CAPTION>
        <tr>
            <th align="center" bgcolor="blue">Day/Time</th>
            <th align="center" bgcolor="blue">Monday</th>
            <th align="center" bgcolor="blue">Tuesday</th>
            <th align="center" bgcolor="blue">Wednesday</th>
            <th align="center" bgcolor="blue">Thursday</th>
            <th align="center" bgcolor="blue">Friday</th>
            <th align="center" bgcolor="blue">Saturday</th>
        </tr>

        <tr>
            <th align="center" bgcolor="darkgreen">8-10</th>
            <td align="center" bgcolor="darkgreen" colspan="2">FREE SLOT</td>
            <td align="center" bgcolor="darkgreen">FWAD</td>
            <td align="center" bgcolor="darkgreen">FREE SLOT</td>
            <td align="center" bgcolor="darkgreen">EXPERT SYSTEMS</td>
            <td align="center" bgcolor="darkgreen">PROBABILITY AND QUEUEING MODELS</td>
        </tr>

        <tr>
            <th align="center" bgcolor="blue">10-12</th>
            <td align="center" bgcolor="purple">FREE SLOT</td>
            <td align="center" bgcolor="purple">FWAD</td>
            <td align="center" bgcolor="purple">FREE SLOT</td>
            <td align="center" bgcolor="purple">PROBABILITY AND QUEUEING MODELS</td>
            <td align="center" bgcolor="purple">FUNDAMENTALS OF C PROGRAMMING</td>
            <td align="center" bgcolor="purple">FREE SLOT</td>
        </tr>

        <tr>
            <th align="center" bgcolor="blue">12-1</th>
            <td align="center" bgcolor="darkgreen" colspan="6">LUNCH</td>
        </tr>

        <tr>
            <th align="center" bgcolor="orange">1-3</th>
            <td align="center" bgcolor="orange">FWAD</td>
            <td align="center" bgcolor="orange">PHYSICS FOR QUANTUM COMPUTING</td>
            <td align="center" bgcolor="orange">HRM</td>
            <td align="center" bgcolor="orange">EDM</td>
            <td align="center" bgcolor="orange">HRM</td>
            <td align="center" bgcolor="orange">FREE SLOT</td>
        </tr>


        <tr>
            <th align="center" bgcolor="orange">3-5</th>
            <td align="center" bgcolor="orange">FUNDAMENTALS OF C PROGRAMMING</td>
            <td align="center" bgcolor="orange">EDM</td>
            <td align="center" bgcolor="orange">FREE SLOT</td>
            <td align="center" bgcolor="orange">CREATIVE SKILLS FOR COMMUNICATION</td>
            <td align="center" bgcolor="orange" >FREE SLOT</td>
            <td align="center" bgcolor="orange" >HRM</td>
        </tr>
    </table>

    <table border="3" width="600" cellspacing="3" cellpaddling="3" align="center">

        <tr>
            <th align="center">S.NO</th>
            <th align="center">SUBJECT CODE</th>
            <th align="center">subject name</th>
        </tr>

        <tr>
            <td align="center">1</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamental of Web Application Development(FWAD)</td>
        </tr>

        <tr>
            <td align="center">2</td>
            <td align="center">19AI302</td>
            <td align="center">Engineering designing and modelling</td>
        </tr>

        <tr>
            <td align="center">3</td>
            <td align="center">19AI304</td>
            <td align="center">Fundamentals of C programming</td>
        </tr>

        <tr>
            <td align="center">4</td>
            <td align="center">19AI521</td>
            <td align="center">Expert systems</td>
        </tr>

        <tr>
            <td align="center">5</td>
            <td align="center">19EY702</td>
            <td align="center">Creative skills for communication</td>
        </tr>

        <tr>
            <td align="center">6</td>
            <td align="center">19MA222</td>
            <td align="center">Probability and Queueing models</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19MS156</td>
            <td align="center">Human resource management and team building</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19PH214</td>
            <td align="center">Physics for quantum computing</td>
        </tr>
    </body>
    </html>
```

## OUTPUT
![image](https://github.com/vksachin2018/slot/assets/149366019/48591805-b761-4f9d-9ac8-b1cd5fd71369)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
