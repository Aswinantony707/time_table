# Ex03 Time Table
# Date:01.04.2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>24010127</title>
    <link rel="icon" href="static/sec-logo-01as.png">
    <style>
        table {
            width: 60%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        th, td {
            border: 2px solid black;
            text-align: center;
        }
        th {
            background-color:rgba(87, 186, 181, 0);
            height: 40px;
        }
        td {
            background-color: rgba(87, 186, 181, 0);
        }

    </style>
</head>
<body align="center">
    <center>
    <div style="display: flex;justify-content:right;" >
    <img src="/static/sec-logo-01as.png" alt="TimeTable" width="600" height="100px">
</div>

    <h2 style="text-align: center;"><marquee>🕔🗒TIMETABLE - ASWIN ANTONY.S[24001423]🗒🕔</marquee></h1>
    <table >
        <tr>
            <th>Days</th>
            <th>8AM to 10AM</th>
            <th>10Am to 12pm</th>
            <th>12PM to 1PM</th>
            <th>1PM to 3PM</th>
            <th>3PM to 5PM</th>
        </tr>
        <tr>
            <th>MONDAY</th>
            <TD>-</TD>
            <TD>19AI301</TD>
            <TD rowspan="6"><span>LUNCH</span></TD>
            <TD>19AI302</TD>
            <TD>-</TD>
        </tr>
        <TR>
            <TH>TUESDAY</TH>
            <TD>19AI410</TD>
            <TD>-</TD>
            <TD>19AI414</TD>
            <TD>-</TD>
        </TR>
        <TR>
            <TH>WEDNESDAY</TH>
            <TD>19AI410</TD>
            <TD>19PH814</TD>
            <TD>ECA-M</TD>
            <TD>-</TD>
        </TR>
        <TR>
            <TH>THURSDAY</TH>
            <TD>-</TD>
            <TD>19AI302</TD>
            <TD>19CS406</TD>
            <TD>19MA222</TD>
        </TR>
        <TR>
            <TH>FRIDAY</TH>
            <TD>-</TD>
            <TD>19PH814</TD>
            <TD>19AI414</TD>
            <TD>-</TD>
        </TR>
        <TR>
            <TH>SATURDAY</TH>
            <TD>-</TD>
            <TD>19CS406</TD>
            <TD>19AI301</TD>
            <TD>19MA222</TD>
        </TR>
</table>
<table style="height: 50px;">
    <tr>
        <th>SUBJECT CODE</th>
        <th>NAME OF THE SUBJECT</th>
    </tr>
    <tr>
        <td>19AI301</td>
        <td>Python programming</td>
    </tr>
    <tr>
        <td>19AI302</td>
        <td>Engineering Design and Modelling</td>
    </tr>
    <tr>
        <td>19AI410</td>
        <td>Introdution to Machine Learning</td>
    </tr>
    <tr>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development </td>
    </tr>
    <tr>
        <td>19PH814</td>
        <td>Physics for Quantum Comuting</td>
    </tr>
    <tr>
        <td>ECA-M</td>
        <td>Mentor Meet</td>
    </tr>
    <tr>
        <td>19CS406</td>
        <td>Computing Networks</td>
    </tr>
    <tr>
        <td>19MA222</td>
        <td>Probability and Queueing Models</td>
    </tr>
</table>
</center>
    </body>
</html> 
```
# OUTPUT
![alt text](<newpro/app/static/Screenshot 2025-04-01 125011.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
