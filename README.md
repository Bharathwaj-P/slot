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
        <title>BHarathwaj</title>
    </head>
    <body>
       <center> <img src="logo.png" width="900"> </center>
       <center><h1>Slot Time Table - Bharathwaj (25018022)</h1> 
       <table border="3" cellspacing="5" cellpadding="10" bgcolor="pink">
        <tr bgcolor="orange">
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>saturday</th>
    </tr>
    <tr>
        <td bgcolor="orange">8-10</td>
        <td colspan="2" align="center">Free</td>
        <td>Web</td>
        <td colspan="2" align="center">Free</td>
        <td>Web</td>   
        
    </tr>
    <tr>
        <td bgcolor="orange">10-12</td>
        <td>Python</td>
        <td>CE</td>
        <td>Web</td>
        <td>CE</td>
        <td colspan="2" align="center">Free</td>
        
    </tr>
    <tr>
        <td bgcolor="orange">12-1</td>
        <td colspan="6" align="center">Lunch</td>
        
    </tr>
    <tr>
        <td bgcolor="orange">1-3</td>
        <td colspan="2" align="center">Python</td>
        <td>Mentor Meet</td>
        <td>Python</td>
        <td colspan="2" align="center">Web</td>
    </tr>
    <tr>
        <td bgcolor="orange">3-5</td>
        <td colspan="3" align="center">CE</td>
        <td>Python</td>
        <td>Free</td>
        <td>CE</td>
    </tr>
</table>
<br>
    <table border="3" cellspacing="5" cellpadding="10">
        <tr>
        <th>S.NO</th>
        <th>Subect Code</th>
        <th colspan="3">Subject Name</th>
    </tr>
    <tr>
        <td>1.</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development (Web)</td>  
        
    </tr>
    <tr>
        <td>2.</td>
        <td>19AI301</td>
        <td>Python Programming</td>
        
    </tr>
    <tr>
        <td>3.</td>
        <td>19EN101</td>
        <td>Communicative Engilsh</td>
    </tr>
</table>
</body>
</html>

```

## OUTPUT

<img width="1920" height="1080" alt="Screenshot 2025-09-24 094419" src="https://github.com/user-attachments/assets/8868fc73-e94b-4363-a907-a2db0f1bf429" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
