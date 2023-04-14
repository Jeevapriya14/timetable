# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag

### STEP 2
Add header row using th tag

### STEP 3
Add your timetable

### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html>
    <head>
       <title>
           Time Table
       </title>
    </head>
    <body>
         <h1>Time Table</h1>
         <table border="5px" align="left">

             

             <tr bgcolor="yellow">
                 <td >
                     Day/time
                 </td>

                 <td>
                     Monday
                 </td>

                 <td>
                     Tuesday
                 </td>
                 <td>

                     Wednesday
                 </td>
                 <td>
                     Thursday
                 </td>
                 <td>
                     Friday
                 </td>
             </tr>
             <tr>
                 <td bgcolor="yellow">
                     8-10
                 </td>
                  <td colspan="3" bgcolor="cyan" align="center">FREE Slot</td>
                 <td colspan="1" bgcolor="cyan" align="center">WEB</td>
               	<td colspan="1" bgcolor="cyan" align="center">CN</td>
             </tr>
             <tr>
                 <td bgcolor="yellow">
                    10-12
                 </td>
                 	<td colspan="1" bgcolor="cyan" align="center">MATHS</td>
                 <td colspan="1" bgcolor="cyan" align="center">T.ENG</td>
                 	<td colspan="1" bgcolor="cyan" align="center">CA</td>
                 <td colspan="1" bgcolor="cyan" align="center">PY</td>
                 	<td colspan="1" bgcolor="cyan" align="center">FRENCH</td>
             </tr>
             <tr>
                 <td bgcolor="yellow">
                     12-1
                 </td>
			
                 <td colspan="5" bgcolor="cyan" align="center">LUNCH</td>
             </tr>
             <tr>
                 <td bgcolor="yellow">
                     1-3
                 </td>
			
                 <td colspan="2" bgcolor="cyan" align="center">FREE SLOT</td>
                 	<td colspan="1" bgcolor="cyan" align="center">CA</td>
                 <td colspan="1" bgcolor="cyan" align="center">CN</td>
                 	<td colspan="1" bgcolor="cyan" align="center">SS</td>
             </tr>
             <tr>
                 <td bgcolor="yellow">
                    3-5
                 </td>
                <td colspan="2" bgcolor="cyan" align="center">FREE SLOT</td>
                 <td colspan="1" bgcolor="cyan" align="center">T.ENG</td>
                <td colspan="1" bgcolor="cyan" align="center">CN</td>
                 <td colspan="1" bgcolor="cyan" align="center">PY</td>
             </tr>
         </table>
    </body>
</html>
```
# OUPUT
![OUTPUT](http://jeevapriyar.student.saveetha.in:8000/static/images/out.png?raw=true)

# HTML VALIDATOR
![HTML VALIDATOR](http://jeevapriyar.student.saveetha.in:8000/static/images/out.png?raw=true)

# RESULT
The program for creating timetable is completedly successfully