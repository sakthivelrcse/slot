# Ex03 Time Table
## Date:22-03-2024

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
        <title>
            MY SLOT
        </title>
        <link rel="stylesheet" href="mo.css">
    </head>
    <body class="table">
        <center>
            <img src="logo.png" width="700px", height="100px"><br><br>
            <h2 class="name" style="color: rgba(21, 90, 38, 0.902);"> TIME TABLE SAKTHIVEL (212221040141)</h2>
            <table border="6" class="table1" style="width: 800; height: 250;">
                <tr class="dt">
                    <th class="mkmk">Day/Time</th>
                    <th class="mkmk">Monday</th>
                    <th class="mkmk">Tuesday</th>
                    <th class="mkmk">Wednesday</th>
                    <th class="mkmk">Thuresday</th>
                    <th class="mkmk">Friday</th>
                </tr>
                <tr>
                    <td class="dt">8-10</td>
                    <td>FREE SLOT</td>
                    <td class="fs">GRID AND CLOUD COMPUTING</td>
                    <td>GRID AND CLOUD COMPUTING</td>
                    <td class="fs">FREE SLOT</td>
                    <td>FUNDAMENTAL OF WEB APPLICATION</td>
                </tr>
                <tr>
                    <td class="dt">10-12</td>
                    <td class="fs">OPERATING SYSTEM</td>
                    <td>FUNDAMENTAL OF WEB APPLICATION</td>
                    <td>FREE SLOT</td>
                    <td>COMPILER DESIGN</td>
                    <td>FREE SLOT</td>
                </tr>
                <tr>
                    <td class="dt">12-01</td>
                    <td colspan="5" style="text-align: center; color: rgb(181, 38, 13)">LUNCH BREAK</td>
                </tr>
                <tr>
                    <td class="dt">01-03</td>
                    <td>COMMUNICATION ENGLISH</td>
                    <td>FREE SLOT</td>
                    <td class="fs">OPERATING SYSTEM</td>
                    <td>FREE SLOT</td>
                    <td>COMPILER DESIGN</td>
                </tr>
                <tr>
                    <td class="dt">03-05</td>
                    <td class="fs">FREE SLOT</td>
                    <td class="fs">PROBLEM SOLVING AND PYTHON</td>
                    <td>FUNDAMENTAL OF WEB APPLICATION</td>
                    <td class="fs">SOFT SKILLS</td>
                    <td class="fs">FREE SLOT</td>
                </tr>
            </table>
            <br> <br> 
            <table border="6" class="table2" style="width: 800; height: 250;">
                <tr>
                    <th>S. No.</th>
                    <th>Subject Code</th>
                    <th>Subject Name</th>
                </tr>
                <tr>
                    <td>1.</td>
                    <td>19AI414</td>
                    <td><b>FUNDAMENTAL OF WEB APPLICATION</b></td>
                </tr>
                <tr>
                    <td>2.</td>
                    <td>19CS301</td>
                    <td><b>PROBLEM SOLVING PYTHON</b></td>
                </tr>
                <tr>
                    <td>3.</td>
                    <td>19CS405</td>
                    <td><b>OPERATING SYSTEM</b></td>
                </tr>
                <tr>
                    <td>4.</td>
                    <td>19CS409</td>
                    <td><b>COMPILER DESIGN</b></td>
                </tr>
                <tr>
                    <td>5.</td>
                    <td>19EN101</td>
                    <td><b>COMMUNICATIVE ENGLISH</b></td>
                </tr>
                <tr>
                    <td>6.</td>
                    <td>19EY701</td>
                    <td><b>SOFT SKILLS</b></td>
                </tr>
                <tr>
                    <td>7.</td>
                    <td>19IT406</td>
                    <td><b>GRID AND CLOUD COMPUTING</b></td>
                </tr>
            </table>
        </center>
    </body>
</html>
```

## OUTPUT

![TIME TABLE SAKTHIVEL R (212221040141)](https://github.com/sakthivelrcse/slot/assets/116993934/71a3107e-7b19-4a14-a388-c1c7251e87cd)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
