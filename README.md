# Ex04 Places Around Me
## Date:22.11.2023 

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
```
map.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>panruti</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>SANJAI S (23013614)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
                <area shape="rect" coords="1150,330,1200,350" href="HOME.html" title="MY HOME TOWN">
                <area shape="rect" coords="1050,380,1140,390" href="TEMPLE.html" title="Veerateeswar Temple">
                <area shape="rect" coords="40,85,145,100" href="COLLEGE.html" title="St.Anne's Engineering College">
                <area shape="rect" coords="800,475,835,490" href="OFFICE.html" title="Regional Transport Office">
                <area shape="rect" coords="950,180,990,195" href="RAILWAY.html" title="RAILWAY STATION">
                <area shape="rect" coords="1125,500,1070,550" href="RIVER.html" title="KEDILAM RIVER">
            </map>
        </center>
    </body>
</html>

home.html
<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="red"><b>panruti</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>panruti - My Home Town</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                Panruti is a town, municipality and taluk headquarters of Cuddalore district, Tamil Nadu, India. Panruti is located between Cuddalore and Neyveli. Panruti is famous for jackfruits and cashew nuts. The jackfruit grown here is exported worldwide and is very sweet. It is a business capital of Cuddalore district. Kananchavadi one of the villages in panruti taluk, famous for palm juice. It has been a great commercial area for more than 200 years.[citation needed] The name Panruti came from the Tamil words "Pann" and "Urutti" meaning "composing song and music", as the place is where many saints and great religious singers such as nayanmars and vainavas sung. A 150-year-old government school was built here by the British East India Company and a more-than-1000-year-old temple Veerattaneswarar temple is nearby in Thiruvathigai. As of 2011, the town had a population of 60,323.


            </font>
        </p>
        </body>
        </html>

temple.html
<html>
    <head>
        <title>TEMPLE</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="red"><b>panruti</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Veerateeswarar Temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                Legend holds that this temple is the place where Shiva destroyed three rakshashas and the three cities created by them. Saranarayana Perumal, another name of Vishnu, is the one who gave the arrow to Shiva for killing the demons, whose temple is also located in the town, little easterly.[2] The Shiva Purana details the legend of destruction of the demon Tripuran, who was ruling Tripura. The destruction is detailed as a cosmic event, which most attribute to the destruction of stars, meteors and unexplained material bodies. Tripuran attacked all the celestial deities who sought the help of Shiva to protect them. Shiva after a fiery fight, destroyed Tripuran and attained the name Tripurantaka. Shiva ashed down the city Tripura and dipped his three fingers in the ashes, which signifies the three lines of ash which is worn by all shaivites on their forehead.

As per another variant, the three sons of Taraka obtained boons from Brahma and built an impregnable fortress on earth. On account of their atrocious activities, mother earth prayed to Shiva for rescue. Shiva burnt down the fort and was about to attack the trio, but they begged for mercy. He made two of them as Dvarapalas and one as his damaru, which he sports in his right hand. The whole incident is believed to have taken place in Thiruvathigai on the banks of Kedilam.[3] The original name of the place was called Tripura Dahanam, which went on to become Thiruvathigai.[4] During Tripurasamharam, the killing of Tripurantaka, Shiva forgot to worship Ganesha before setting out for the battle. He realized it and came back to worship Ganesha and went ahead to win the demon. The same legend is associated with Aksheeswaraswamy Temple, Acharapakkam and Thiruvirkolam Sri Tripuranthaka Swami temple

            </font>
        </p>
        </body>
        </html>

college.html
<html>
    <head>
        <title>COLLEGE</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="red"><b>panruti</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>St.Anne's Engineering College</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
               St.Anne's Engineering College(AVPTC) was started on 10.9.1986 by the Annai Engineering  educational and social society during the academic year 1986-87. It is recognized by the board of technical education Chennai -25. and the G.O. M.S No. is 946 dated 9.7.1986. This College is located at Anguchettypalayam 3 k.m. away from panruti town on Chitoor-Cuddalore highways. Frequent bus facilities are available.,St.Anne's Engineering College Panruti, is offering three year Diploma programs approved by the ALL INDIA COUNCIL FOR TECHNICAL EDUCATION (AICTE)
            </font>
        </p>
        </body>
        </html>

office.html
<html>
    <head>
        <title>OFFICE</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>panruti</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>Regional Transport Office</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
               The Regional Transport Office or District Transport Office or Regional Transport Authority (RTO/DTO/RTA) is the organisation of the Indian government responsible for maintaining a database of drivers and a database of vehicles[1] for various states of India. The RTO issues driving licences,[2] organises collection of vehicle excise duty (also known as road tax and road fund licence) and sells personalised registrations.[3]To enforce the provisions of the various acts of motor vehicles, central motor vehicle rules and the State motor vehicle rules as laid down by the government from time to time.To ensure that co-ordinated development of road transport through management of permit.To charge and collect tax as per the provisions of the motor vehicle act.To enforce road safety and bring in new amendments into force with relation to the Indian Motor Vehicle Act 1988.

            </font>
        </p>
        </body>
        </html>

railway.html
<html>
    <head>
        <title>RAILWAY</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="red"><b>panruti</b></font>
        </h1>
        <h3 align="center">
            <font color="black">RAILWAY STATION<b></b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
               Panruti Railway Station is one of the busiest railway stations in Panruti. It serves as a major transportation hub for both passengers and goods, connecting Panruti with the rest of India. The total number of trains that pass through Panruti PRT is 14.The station offers a wide range of facilities for the convenience of passengers, including ticket counters, waiting rooms, food stalls, and restrooms. It also has 2 platforms for the different trains that pass through the station, as well as a separate platform for long-distance trains.The station is well-connected to the rest of the city and the state through a network of buses and taxis. There are also parking facilities available for those who prefer to drive to the station.

            </font>
        </p>
        </body>
        </html>

river.html
<html>
    <head>
        <title>RIVER</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="red"><b>panruti</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>KEDILAM RIVER</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                The Gadilam River (sometimes pronounced Kedilam) flows through the Cuddalore and Villupuram districts of Tamil Nadu.[1]

It has a small water flow, drainage area and sand deposit and is generally flooded during the monsoon season and raises the water table and feed tanks on its basin. Few famous temples like Thiruvathigai Veerataneshwar temple and Thiruvanthipuram Thevanathan perumal temple are located in its banks. It is also mentioned in the Medieval Bhakti literatures like Thevaram. The ruins of Fort St. David is located at the mouth of the river.[2]

The Gadilam River flows through the town of Cuddalore and separates the Old Town from Thirupadiripuliyur.
            </font>
        </p>
        </body>
        </html>                                       
```

## OUTPUT
![1](https://github.com/Sanjaichitra/NearMe/assets/144870518/40e83d96-8f5c-4a39-9a7e-376a191eda04)
![2](https://github.com/Sanjaichitra/NearMe/assets/144870518/1d017f2c-d28f-449b-a313-1ed9032fbff6)
![3](https://github.com/Sanjaichitra/NearMe/assets/144870518/e45357ac-3b3f-4b3f-9101-4a219c045a0a)
![4](https://github.com/Sanjaichitra/NearMe/assets/144870518/7dd43a91-5bfb-4261-8cc4-380fef019a4c)
![5](https://github.com/Sanjaichitra/NearMe/assets/144870518/16ecb7e0-084c-4573-b57e-a16d5b527f14)
![6](https://github.com/Sanjaichitra/NearMe/assets/144870518/bf0ac9ca-c6fc-4700-bb21-bf712a3f7631)
![7](https://github.com/Sanjaichitra/NearMe/assets/144870518/867ef4f0-e08d-4fc7-a2f3-2c49dcc0436b)

## RESULT
The program for implementing image maps using HTML is executed successfully.
