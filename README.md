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
<!DOCTYPE html>
<head>
    <title>SEC SLOT TIMETABLE</title>
</head>
<center>
<img src="/static/logo.png" width='600'align="center">
</center>
<body>
    <table BORDER='3' width='600'bgcolor='white' cellspacing='3' align="center">
        <CAPTION align="above">SLOT TIMETABLE- SREEADHITHSANTHOSH A (212222223003)</CAPTION>
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
            <th align="center" bgcolor="green">8-10</th>
            <td align="center" bgcolor="yellow" colspan="2">Digital Electronics</td>
            <td align="center" bgcolor="yellow">Fundamentals of Web Development</td>
            <td align="center" bgcolor="yellow">Free slot</td>
            <td align="center" bgcolor="yellow">Algebra and number theory</td>
            <td align="center" bgcolor="yellow">Principles of Chemistry</td>
        </tr>

        <tr>
            <th align="center" bgcolor="green">10-12</th>
            <td align="center" bgcolor="pink">Creative Skills</td>
            <td align="center" bgcolor="pink">Fundamentals of Web Development</td>
            <td align="center" bgcolor="pink">Free slot</td>
            <td align="center" bgcolor="pink">Python Programming</td>
            <td align="center" bgcolor="pink">Digital Electronics</td>
            <td align="center" bgcolor="pink">Free slot</td>
        </tr>

        <tr>
            <th align="center" bgcolor="green">12-1</th>
            <td align="center" bgcolor="rose" colspan="6">LUNCH</td>
        </tr>

        <tr>
            <th align="center" bgcolor="green">1-3</th>
            <td align="center" bgcolor="lightpink">Fundamentals of Web Development</td>
            <td align="center" bgcolor="lightpink">Principles of Chemistry</td>
            <td align="center" bgcolor="lightpink">Python Programming</td>
            <td align="center" bgcolor="lightpink">Algebra and number theory</td>
            <td align="center" bgcolor="lightpink">Operating System</td>
            <td align="center" bgcolor="lightpink">Free slot</td>
        </tr>


        <tr>
            <th align="center" bgcolor="green">3-5</th>
            <td align="center" bgcolor="purple">Operating System</td>
            <td align="center" bgcolor="purple">Free Slot</td>
            <td align="center" bgcolor="purple">Digital Electronics</td>
            <td align="center" bgcolor="purple">Computer Networks</td>
            <td align="center" bgcolor="purple" >Free slot</td>
            <td align="center" bgcolor="purple" >Computer Networks</td>
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
            <td align="center">19AI301</td>
            <td align="center">Python Programming</td>
        </tr>

        <tr>
            <td align="center">3</td>
            <td align="center">19EY702</td>
            <td align="center">Creative Skills</td>
        </tr>

        <tr>
            <td align="center">4</td>
            <td align="center">19AI521</td>
            <td align="center">Computer Networks</td>
        </tr>

        <tr>
            <td align="center">5</td>
            <td align="center">19CY205</td>
            <td align="center">Principles of Chemistry</td>
        </tr>

        <tr>
            <td align="center">6</td>
            <td align="center">19MA212</td>
            <td align="center">Algebra and number theory</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19EE404</td>
            <td align="center">Digital Electronics</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19CS405</td>
            <td align="center">Operating System</td>
        </tr>
    </body>
    </html>
```

## OUTPUT

![WhatsApp Image 2024-03-29 at 11 59 17 PM](https://github.com/sakthivelrcse/slot/assets/116993934/0ea4cce9-5c1c-4865-8fcd-f6d151f9d41a)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
