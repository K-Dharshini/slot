# Ex03 Time Table
## Date:

## AIM:
To write a html webpage page to display your slot timetable.

## ALGORITHM:
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

## PROGRAM:
### HTML
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Time table</title>
    <link rel="stylesheet" href="table.css">
</head>
<body>
   <img src="SEC LOGO NEW.png" style="width: 60%;height: 10%;padding-left: 20%;" alt="">
   <h1 style="text-align: center;font-size: 20px;"><b>SLOT TIME TABLE - DHARSHINI K(212223230047)</b></h1>
  
   <table border="2px" class="table">
    <tr class="attributes">
    <th>Time/Day</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
    </tr>
    <tr>
        <td class="attributes"><b>8-10</b></td>
        <td>CA</td>
        <td>OS</td>
        <td>DS</td>
        <td>CRYPTO</td>
        <td>WEB</td>
    </tr>
    <tr>
    <td class="attributes"><b>10-12</b></td>
    <td>FREE</td>
    <td>FREE</td>
    <td>WEB</td>
    <td>QUANT</td>
    <td>TRANSFORMS</td>
    </tr>
    <tr>
        <td class="attributes"><b>12-1</b></td>
        <td colspan="5">LUNCH</td>
    </tr>
    <tr>
        <td class="attributes"><b>1-3</b></td>
        <td>FREE</td>
        <td>FREE</td>
        <td>MENTOR MEET</td>
        <td>CA</td>
        <td>DBMS</td>
    </tr>
    <tr>
        <td class="attributes"><b>3-5</b></td>
        <td>TRANSFORMS</td>
        <td>WEB</td>
        <td>DBMS</td>
        <td>FREE</td>
        <td>DS</td>
    </tr>
   </table>
   <table border="2px">
    <tr>
        <th><b>S.No</b></th>
        <th><b>Subject Code</b></th>
        <th class="table2"><b>Subject Name</b></th>
    </tr>
    <tr>
        <td>1.</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development (WEB)</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>19CS305</td>
        <td>Computer Architecture (CA)</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>19MA219</td>
        <td>Transforms and it's Applications (TRANSFORMS)</td>
    </tr>
    <tr>
        <td>4.</td>
        <td>19CS405</td>
        <td>Operating System (OS)</td>
    </tr>
    <tr>
        <td>5.</td>
        <td>19EY710</td>
        <td>Quantitative Ability - I (QUANT)</td>
    </tr>
    <tr>
        <td>6.</td>
        <td>19CS404</td>
        <td>Database Management and it's Applications (DBMS)</td>
    </tr>
    <tr>
        <td>7.</td>
        <td>19AI408</td>
        <td>Data Structures (DS)</td>
    </tr>
    <tr>
        <td>8.</td>
        <td>19CS415</td>
        <td>Cryptography (CRYPTO)</td>
    </tr>
   </table>
</body>
</html>
~~~

### CSS
~~~
table
{
    text-align: center;
    margin-left: 28%;
    margin-top: 1%;
}

.table
{
    background-color: aqua;
}

.attributes
{
    background-color: yellow;
}

td,th
{
    width: 100px;
    height: 30px;
}

.table2
{
    width:420px;
}
~~~

## OUTPUT:
![image](https://github.com/user-attachments/assets/90f08da5-96de-44a3-8bdb-6b4e2046d57d)

## RESULT:
The program for creating slot timetable using basic HTML tags is executed successfully.
