# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM

<html>

    <head>

        <title>IMAGEMAP</title>

        <LINK REL="ICON" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\global.avif">

            <style>
                header{
                    background-color:moccasin;
                    color:darkred;
                    font-size: 50px;
                    text-align: center;
                    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                }
                body{
                    background-color: black;
                    color: azure;
                }
            </style>

    </head>

    <BODY>
        <header>AMBUR</header><br><br><br>
       <center> <img src="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\Screenshot 2024-11-23 173900.png" usemap="#image-map"></center>
        <map name="image-map">
            <area target="_blank" alt="Rahamaniya" title="Rahamaniya Briyani" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\rahamaniya.html" coords="838,165,1053,227" shape="rect">
            <area target="_blank" alt="NR Briyani" title="NR Briyani" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\nr.html" coords="791,255,978,336" shape="rect">
            <area target="_blank" alt="Poorvika" title="Poorvika" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\poorvika.html" coords="237,472,479,523" shape="rect">
            <area target="_blank" alt="Dr Agarwals" title="Dr Agarwals Eye clinic" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\dr.html" coords="300,339,529,408" shape="rect">
            <area target="_blank" alt="GK pet" title="GK Pet shop" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\GK pet.html" coords="849,522,1064,637" shape="rect">
        </map>

    </BODY>

</html> 

# OUTPUT
![Screenshot 2024-11-25 130637](https://github.com/user-attachments/assets/dded9750-ea43-467a-b798-f30001a66abf)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
