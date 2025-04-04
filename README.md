# Ex03 Time Table
## Date:30/3/2025

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

Name : Deepak S
Reg.No.: 212224230053

```
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIME TABLE</title>
    <style>
        body {
            text-align: center;
            font-family: "Poppins", sans-serif;
            background-color: #f4f7fc;
            color: #2c3e50;
            padding: 20px;
        }

        .logo {
            height: 150px;
            width: auto;
            margin-top: 20px;
        }

        .schedule {
            font-size: 48px;
            color: #34495e;
            font-weight: bold;
            text-transform: uppercase;
            margin-bottom: 20px;
        }

        table {
            border-collapse: collapse;
            width: 85%;
            margin: 20px auto;
            background-color: #37474f;
            color: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.15);
        }

        th, td {
            border: 1px solid #bdc3c7;
            padding: 18px;
            font-weight: semi bold;
            text-align: center;
            font-size: 20px;
        }

        caption {
            font-size: 26px;
            color: white;
            margin-bottom: 10px;
            font-weight: bold;
        }

        th {
            background-color: #2980b9;
            color: white;
        }

        .monday { background-color: #e74c3c; color: white; }
        .tuesday { background-color: #3498db; color: white; }
        .wednesday { background-color: #f1c40f; color: black; }
        .thursday { background-color: #9b59b6; color: white; }
        .friday { background-color: #e67e22; color: white; }
        .saturday { background-color: #2ecc71; color: white; }
        
        .sno {
            background-color: #ffffff;
            color: #2c3e50;
            font-weight: bold;
    </style>
</head>

<body>
    <header> 
        <img src="logo.png" alt="LOGO" class="logo">
    </header>
    
    <h1 class="schedule">Schedule</h1>
    
    <table class="timetable">
        <caption>Timetable</caption>
        <tr>
            <th>DAY/TIME</th>
            <th>8-10</th>
            <th>10-12</th>
            <th>1-3</th>
            <th>3-5</th>
        </tr>
        <tr>
            <th class="monday">MONDAY</th>
            <td>FUND. OF AI</td>
            <td>PHYSICS</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <th class="tuesday">TUESDAY</th>
            <td>-</td>
            <td>WEB APP</td>
            <td>PROBABILITY</td>
            <td>-</td>
        </tr>
        <tr>
            <th class="wednesday">WEDNESDAY</th>
            <td>-</td>
            <td>PHYSICS</td>
            <td>MENTOR MEET</td>
            <td>FUND. OF AI</td>
        </tr>
        <tr>
            <th class="thursday">THURSDAY</th>
            <td>UI UX</td>
            <td>DATA SCIENCE</td>
            <td>-</td>
        </tr>
        <tr>
            <th class="friday">FRIDAY</th>
            <td>-</td>
            <td>UI UX</td>
            <td>-</td>
            <td>PROBABILITY</td>
        </tr>
        <tr>
            <th class="saturday">SATURDAY</th>
            <td>-</td>
            <td>DATA SCIENCE</td>
            <td>WEB APP</td>
            <td>-</td>
        </tr>
    </table>
    
    <h1 class="schedule">Courses</h1>
    
    <table class="courses">
        <caption>Courses</caption>
        <tr>
            <th>S.No</th>
            <th>Course Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Fundamentals of WEB</td>
        </tr>
        <tr>
            <td>2</td>
            <td class="monday">FUND. OF AI</td>
        </tr>
        <tr>
            <td>3</td>
            <td class="tuesday">MATHS</td>
        </tr>
        <tr>
            <td>4</td>
            <td class="wednesday">PHYSICS</td>
        </tr>
        <tr>
            <td>5</td>
            <td class="friday">UI UX</td>
        </tr>
        <tr>
            <td>6</td>
            <td class="saturday">DATA SCIENCE</td>
        </tr>
    </table>
</body>
</html>

```

## OUTPUT

![alt text](<Screenshot 2025-03-30 173233.png>)

![alt text](<Screenshot 2025-03-30 173257.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
