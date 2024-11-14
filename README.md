# Ex03 Time Table
## Date: 

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot</title>
</head>
<style>
    body{
        text-align: center;
        background-color: pink;
        font-family: cursive;
        
    }
    table{
        border-color: white;
    }
</style>
<body>
    {%load static%}
    <img src="{%static 'images/logo.jpg'%}" alt="error">
    <h3 align="center">SLOT TIME TABLE - Dheena Darshini-212223240030</h3>
    <table border="3" align="center">
        <thead>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </thead>
        <tbody>
            <tr>
                <th>8-10</th>
                <td>ADV C</td>
                <td>PMC</td>
                <td>PMC</td>
                <td>ML</td>
                <td>WEB</td>
                <td>OS</td>
            </tr>
            <tr>
                <th>10-12</th>
                <td>ML</td>
                <td>FREE</td>
                <td>WEB</td>
                <td>CN</td>
                <td>FREE</td>
                <td>PQM</td>
            </tr>
            <tr>
                <th>12-1</th>
                <td colspan="6" style="text-align: center;">LUNCH</td>
            </tr>
            <tr>
                <th>1-3</th>
                <td>FREE</td>
                <td>FREE</td>
                <td>MENTOR MEET</td>
                <td>QA 1</td>
                <td>FREE</td>
                <td>FREE</td>
            </tr>
            <tr>
                <th>3-5</th>
                <td>CN</td>
                <td>WEB</td>
                <td>PQM</td>
                <td>OS</td>
                <td>FREE</td>
                <td>ADV C</td>
            </tr>   
        </tbody>
    </table>
<br>
<br>
    <table border="1" align="center">
        <thead>
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </thead>
        <tr>
            <th>1.</th>
            <td>19AI305</td>
            <td>Advanced C Programming</td>
        </tr>
        <tr>
            <th>2.</th>
            <td>19AI410</td>
            <td>Introduction to Machine Learning</td>
        </tr>
        <tr>
            <th>3.</th>
            <td>19AI414</td>
            <td>Fundamentals of Web Application</td>
        </tr>
        <tr>
            <th>4.</th>
            <td>19CS405</td>
            <td>Operating System</td>
        </tr>
        <tr>
            <th>5.</th>
            <td>19CS406</td>
            <td>Computer Networks</td>
        </tr>
        <tr>
            <th>6.</th>
            <td>19EE309</td>
            <td>Programming Microcontrollers</td>
        </tr>
        <tr>
            <th>7.</th>
            <td>19EY710</td>
            <td>Quantitative Ability I</td>
        </tr>
        <tr>
            <th>8.</th>
            <td>19MA222</td>
            <td>Probability and Queueing Models</td>
        </tr>
    </table>
</body>
</html>
'''

## OUTPUT
![image](https://github.com/user-attachments/assets/12c3d375-0000-4088-a30b-476006cf5179)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
