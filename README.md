# Ex03 Time Table
## Date:20.09.2025

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
< !DOCTYPE html >
< html lang="en">
              < head>
     < meta charset="UTF-8">
    < title>College Timetable</ title>
     < style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5faff;
            text-align: center;
        }
        h1 {
            color: #004080;
            margin-bottom: 10px;
        }
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 20px auto;
            background-color: #f9f9f9;
        }
        th, td {
            border: 2px solid #000;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #ffd700;
            color: #000;
        }
        .subject-table {
            width: 70%;
            margin: 30px auto;
        }
        .subject-table th {
            background-color: #cce5ff;
            color: #000;
        }
    </ style>
</ head>
< body> 
< CENTER>
< img src="\static\logo.png" height="100" width="540" alt="">
< /CENTER>
     < br>
    
    <h2>Slot Time Table - ABHISHEK S (25008757)</h2>

    <table>
        <tr>
            <th>Day/Time</th> 
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <th>8-10</th>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>PHY</td>
            <td>CHE</td>
            <td></td>
        </tr>
        <tr>
            <th>10-12</th>
            <td>GER</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>PHY</td>
        </tr>
        <tr>
            <th>12-1</th>
            <td colspan="5">LUNCH</td>
        </tr>
        <tr>
            <th>1-3</th>
            <td>FREE SLOT</td>
            <td>MAT</td>
            <td>MAT</td>
            <td>SS</td>
            <td></td>
        </tr>
        <tr>
            <th>3-5</th>
            <td>FREE SLOT</td>
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
            <td></td>
        </tr>
    </table>

    <h2>Subject Details</h2>
    <table class="subject-table">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EN612</td>
            <td>German Basic (GER)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19PH206</td>
            <td>Physics for Information Technology (PHY)</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra (MAT)</td>
        </tr>
     <tr>
          <td>6</td>
       <td>19EY701</td>
      <td>Soft Skills (SS)</td>
                </tr>
               </table>
                  </body>
                       </html>


 '''


## OUTPUT
![alt text](<Screenshot (7).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
