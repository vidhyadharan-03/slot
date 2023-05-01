# Ex03 Time Table

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

## CODE
```
<html lang="en">
<head>
<title>MY TIMETABLE</TITLE>
</head>
<Body>
<H1 ALIGN="CENTER">MY TIME TABLE FOR EVEN SEM</h1>

<table border="4" CELLPADDING="7" CELL SPACING="6" >
<CAPTION><b> VIDHYADHARAN TIME TABLE (212222110053)</CAPTION>
     <tr BGCOLOR="YELLOW">
         <td><B>TIME</TD>
         <td><B>MONDAY</TD>
         <td><B>TUESDAY</TD>
         <td><B>WEDNESDAY</TD>
         <td><b>Thursday</td>
         <td><b>Friday</td>
     </TR>
      
     <TR bgcolor="LIME">
          <td>8-10</TD>
          <td>FREE TIME</TD>
          <td>TRANSFORMS</TD>
          <td>FREE</TD>
          <td>Web-technology</td>
          <td>Web-technology</td>
      </TR>
  
      <TR bgcolor="LIME">
          <TD>10-12</TD>
          <td>FREE TIME</TD>
          <td>PROGRAMMING CONTROLLERS</TD>
          <td>EDM</TD>
          <td>Free</td>
          <td>Free</td>
         </TR>

     <TR bgcolor="LIME">
           <td>1-3</TD>
           <td>STATISTICS</TD>
           <td>EDM</TD>
           <td>WEB APPLICATION</TD>
           <td>Free</td>
           <td>Programming
               Microcontroller</td>
     </TR>

     <TR bgcolor="LIME">
           <td>3-5</TD>
           <td>FUND C</TD>
           <td>STATISTICS</TD>
           <td>TRANSFORMS</TD>
           <td>c-programming</td>
           <td>Free</td>
      </TR>

    </TABLE>
<br>
<br>
<br>
<br>



   <table border="4" cellpadding="6" cellspacing="7">
   <tr>
   <td>S.No.</td>
   <td>Subject code</td>
   <td>Subject name</td>
   </tr>
   <tr>
   <td>1.</td>
   <td>19AI414</td>
   <td>Fundamental of Web Application and Development</td>
   </tr>
   <tr>
   <td>2.</td>
   <td>19MA211</td>
   <td>Statistics and Numerical Methods</td>
   </tr>
   <tr>
   <td>3.</td>
   <td>19AI304</td>
   <td>Fundamental of C Programming</td>
   </tr>
   <tr>
   <td>4.</td>
   <td>19MA219</td>
   <td>Transforms and its Applications</td>
   </tr>
   <tr>
   <td>5.</td>
   <td>19EE309</td>
   <td>Programming Microcontrollers</td>
   </tr>
   <tr>
   <td>5.</td>
   <td>19AI302</TD>
   <td>Engineering Design and Modelling</td>
   </tr>
   </table>
   
   

</body>
</html>
```


## OUTPUT

![output](http://vidhyadharanr.student.saveetha.in:8000/static/images/output.png?raw=true)
## HTML VALIDATOR
![output](http://vidhyadharanr.student.saveetha.in:8000/static/images/valid.png?raw=true)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
