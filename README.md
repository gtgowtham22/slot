# Ex03 Time Table
## Date:12/11/2024

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
    <img src="logo.png">
    <body>
        <table border="1" cellspacing="15" cellpadding="2">
            <caption>Timetable</caption>
            <tr bgcolor="cyan">
                <th>DAY</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>

            </tr>
            <tr>
                <td>8-10</td>
                <td>FREE SLOT</td>
                <td>ENGINEERING DESIGN AND MODELLING</td>
                <td>ENGINEERING DESIGN AND MODELLING</td>
                <td>COMMUNICATIVE ENGLISH</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
                <td>FREE SLOT</td>
            </tr>
            <tr>
                <td>10-12</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
                <td>DIGITAL ELECTRONICS</td>
                <td>FREE SLOT</td>
                <td>DIGITAL ELECTRONICS</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
                <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
            </tr>
            <tr>
                <td>12-1</td>
                <td align = center colspan="6">LUNCH</td>
            </tr>
            <tr>
                <td>1-3</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT/td>
                <td>FREE SLOT</td>
                <td>CAREER DEVELOPMENT</td>
                <td>DIGITAL ELECTRONICS</td>
                <td>FREE SLOT
                </tr>

               
                <html>
    <body>
        <table border="1" cellspacing="15" cellpadding="2">
            <caption><br></caption>
            <tr bgcolor="cyan">
                <th>S.No</th>
                <th>course code</th>
                <th>course name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19CY205</td>
                <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EE404</td>
                <td>DIGITAL ELECTRONICS</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19AI302</td>
                <td>ENGINEERING DESIGN AND MODELLING</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <td>6</td>
                <td>19EY708</td>
                <td>CAREER DEVELOPMENT SKILLS</td>
            </tr>
        </table>
    </body>
</html>
                
        </table>
    </body>
</html>

```
## OUTPUT
![alt text](<slot mudichithu.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
