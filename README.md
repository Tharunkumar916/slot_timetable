# Ex03 Time Table
## Date:26.10.2025

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
<html>
    <head>

    </head>
    <body>
        <center><img src="logo.png" width="700px"></center>
        <hr>
        <table border="1" cellpadding="10" align="center" bgcolor="cyan">
            <caption>
                <h2>
                    Slot timetable-THARUN KUMAR V-212224240173
                </h2>
                <tr><th>Day/Time</th><th>Monday</th><th>Tuesday</th><th>Wednesday</th><th>Thursday</th><th>Friday</th><th>Saturday</th></tr>
                <tr><th>8-10</th><th>EH</th><th>free</th><th>MUI</th><th>EH</th><th>CRY</th><th>CRY</th></tr>
                <tr><th>10-12</th><th>JAP</th><th>DS</th><th>WEB</th><th>free</th><th>C</th><th>DS</th></tr>
                <tr><th>12-1</th><td colspan="6" align="center">Lunch</td></tr>
                <tr><th>1-3</th><th>WEB</th><th>MUI</th><th>mm</th><th>JAP</th><th>JAP</th><th>C</th></tr>
                <tr><th>3-5</th><th>OS</th><th>HVPE</th><th>OS</th><th>RA</th><th>free</th><th>free</th></tr>
            </caption>
        </table>
    </body>
</html>
<style>
    h2{
        background-color: yellow;
    }
    body{
        background-color: burlywood;
    }
</style>
```

## OUTPUT
![WhatsApp Image 2025-10-26 at 20 37 58_7702ad65](https://github.com/user-attachments/assets/99504b03-cf88-4794-919a-30111dce7def)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
