# Ex04 Places Around Me
## Date: 9/12/2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
~~~
map.html
<html>
<head>
<title>My City</title>    
</head> 
<body>
    <h1 align="center">
    <font color="brown"><b>Salem</b></font>
    </h1>
    <h3 align="center">
        <font color="black"<b>Dharshana A S (24009985)</b></font>
        </h3>
        <center>
            <img src="img.png" usemap="#MyCity" height="610" width="'1450">
            <map name="MyCity">
                <img src="Screenshot 2024-11-27 231101.png" usemap="#image-map">

                <map name="image-map">
                    <area target="rect" alt="my home town" title="my home town" href="home.html" coords="904,368,1039,441" shape="rect">
                    <area target="rect" alt="Yercaud" title="Yercaud" href="hillstation.html" coords="1040,147,1142,197" shape="rect">
                    <area target="circle" alt="Kurumbapatty Zoological Park" title="Kurumbapatty Zoological Park" href="zoo.html" coords="987,301,36" shape="circle">
                    <area target="rect" alt="Mookaneri" title="Mookaneri" href="lake.html" coords="1015,336,1045,360" shape="rect">
                    <area target="rect" alt="Belur" title="Belur" href="temple.html" coords="1454,282,1520,331" shape="rect">
                </map>
        </map>
        </center>
</body>   
</html>   
lake.html
<html>
<head>
    <title>Mookaneri</title>
    </head>
    <body bgcolor="olive">
        <h1 align="center">
        <font><h1 align="center">
            <font color ="green"><b>Mookaneri</b></font>
            </h1>
        <h3 align="center">
           <font color ="line"><b>lake</b><hr size="2" color="black">
            <p align="justify"></font>
                <font align = "center"size="5"><p><br>
            Mookaneri Lake is a popular bird watching destination. The floating islands lush growth of trees help in providing shelter for the birds, like a birds’ sanctum, and their food needs are sufficed by waterholes or the lake. The most commonly sighted birds are Egrets and Kingfishers. Over 169 species of birds have been spotted at the lake.
       </h3>
    </body>
</html>
temple.html
<html>
<head>
<title>Thanthondreeswarar kovil</title>    
</head> 
<body bgcolor="brown">
    <h1 align="center">
        <font color="black"><b>Thanthondreeswarar kovil</b></font>
    </h1>
    
    <h3 align="center">
    <font color ="line"><b>Temple</b><hr size="3" color="green">
        <p align="justify"></font>
            <font align="center" size="5"><p><br>
            The temple was built by the Cholas kingdom in the 12th century AD. The main deity is Lord Thanthondreeswarar (Lord Shiva) and the female deity is Goddess Dharmasamvarthini.
            Thanthondreeswarar Temple is located on the banks of Vasishta Nadi (Vasishta River). 
            This temple comes under the Hindu Religious Charitable Endowment Department.
        </p></font>
    </body>
</html>
home.html
<html>
<head>
<title>My Home</title>    
</head> 
<body bgcolor="white">
    <h1 align="center">
        <font color="black"><b>Salem</b></font>
    </h1>
    
    <h3 align="center">
    <font color ="line"><b>My Home</b><hr size="3" color="black">
        <p align="justify"></font>
            <font align="center" size="5"><p><br>
                Salem District was formed on 1772.Salem is Geologist paradise, surrounded by hills and the landscape dotted with hillocks. Salem has a vibrant culture dating back to the ancient Kongu Nadu. As a district, Salem has its significance in various aspects.
                There are many things in Salem that are noteworthy by virtue of its location and social set-up.
    </h3>
</body>
zoo.html
<html>
<head>
<title>My Home</title>    
</head> 
<body bgcolor="yellow">
    <h1 align="center">
        <font color="black"><b>Kurumbapatti</b></font>
    </h1>
    
    <h3 align="center">
    <font color ="line"><b>zoo</b><hr size="3" color="black">
        <p align="justify"></font>
            <font align="center" size="5"><p><br>
            The Kurumbapatti Zoological Park is a second largest zoo in Tamil Nadu next to Arignar Anna Zoological Park, situated in the foothills of the Shervaroyan Hills, 10 km from Salem, Tamil Nadu, India. It was set up in 1981 as a small museum and was later extended to 69 Ha. The zoo houses many species of wildlife, with monkeys as the major attraction, and is in the vicinity of reserve forest, permitting visitors the opportunity to also experience the flora and fauna there. The park has a gentle topography, areas of bamboo and woodland and semi-perennial streams.Facilities include a children's playground area.
           

    </body>
</html>
~~~

## OUTPUT
![alt text](<Screenshot 2024-12-16 134808.png>)
![alt text](<Screenshot 2024-12-16 140524.png>)
![alt text](<Screenshot 2024-12-16 140652.png>)
![alt text](<Screenshot 2024-12-16 141048.png>)
![alt text](<Screenshot 2024-12-16 141331.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
