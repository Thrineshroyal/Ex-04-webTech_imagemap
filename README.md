# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
Step 1
Create a new django project and app.

Step 2:
Add a new imagemap html file in templates and neede images in static folder and define it in settings.

Step 3:
Type ur image map code in the html with coordinates and target file to redirect on click.

Step 4:
Define your components pages and create content in such a way that it gives information about place which is being clicked.

Step 5:
Include pictures and contents for your subpages and map them using urls and views.
# Code:
Developed by: T.Thrinesh Royal
Ref no:23004810


MAP.HTML:
index.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>Madanapalli Image Map</title>
    </head>
    <body>
       
        <img src = "C:\Users\admin\Pictures\Screenshots\Screenshot 2023-11-21 210047.png" height="750" width="1800" align="center" usemap="#imgmap">
        <map name="imgmap">
           <area target="" alt="Basinikonda" title="Basinikonda" href="basinikonda.html coords="413,514,389,462,399,406,425,387,449,370,482,367,529,372,565,416,565,476,528,523,470,540" shape="poly">
           <area target="" alt="MMC park" title="MMC park href="park.html" coords="611,709,545,745,492,797,669,773,498,805,562,882,622,888,664,872,695,862,707,836,718,802,715,755,686,711,647,709,624,716" shape="poly">
           <area target="" alt="NVR convention hall"  href="hall.html" coords="1025,286,1020,304,1000,315,992,341,1008,357,1039,374,1065,374,1085,370,1119,349,1126,312,1093,289,1054,286" shape="poly">
           <area target="" alt="Boyakonda Temple" title="boyakonda Temple" href="temple.html" coords="1056,157,1021,170,1012,207,1016,229,1026,251,1041,256,1065,260,1088,255,1108,251,1109,224,1106,198,1106,185,1087,162" shape="poly">
           <area target="" alt="Madanapalli tomoto market" title="madanapalli tomato market" href="market.html" coords="811,192,839,190,881,188,898,171,899,128,873,107,829,104,806,109,790,120,775,135,774,157,780,177,793,185" shape="poly">
        </map>
    </body>
    </html>
```
basinikonda.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>Madanapalli</title>
    </head>
    <body>
        <h1 align='center'>Basinikonda</h1>
        <img src =![Screenshot 2023-11-21 210557](https://github.com/Thrineshroyal/Ex-04-webTech_imagemap/assets/145741928/07f9bd18-d046-48e3-aceb-eee8caa85edd) height="500" width="700" align="center" >
        <p>
      Basnikonda is referred to in Annual Report of Epigraphy no. 342 of 1912. The tamil inscription documents the conversion of  Siravalli (a village) into an ERIVIRAPATTINAM (a merchant town with armed guards). This resolution was passed by merchant guilds and merchants of that time including Nadu, Nagara, Nana Desi and Ayiraththainnurruvar. The inscription reads that they met at Siravalli in Mugai-nadu, a sub-division of Purani-Marayapadi of Jayangonda-sola Mandalam and resolved to convert the village Siravalli into a Nanadesiya-Dasamadi-Erivirapattana and to grant certain privileges to the residents of that village.

        </p>
    </body>

</html>
```
MMC park.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>MMC PARK</title>
    </head>
    <body>
        <h1 align='center'>MMC PARK</h1>
         <img src ="C:\Users\admin\Pictures\Screenshots\Screenshot 2023-11-21 211026.png" align="center" height="500" width="700"  >
        <p>MMC Park is a park located in Madanapalle, Andhra Pradesh. The average rating of this place is 4.20 out of 5 stars based on 447 reviews. The street address of this place is GGV7+6J5, Nemali Nagar, Madanapalle, Andhra Pradesh 517325, India. It is about 1.26 kilometers away from the Madana Palle railway station.
        </p>    
    </body>

</html>
```
hall.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>"NVR convention mall"</title>
    </head>
    <body>
        <h1 align='center'>"NVR convention mall"</h1>
        <img src ="C:\Users\admin\Pictures\Screenshots\Screenshot 2023-11-21 211752.png" height="500" width="700" align="center" >
        <p>
     With a modern and a great construction this convention hall provides a complete costumer satisfaction though the price details can't be specified currently. The overall facilities are mind blowing and unlike it's location where the surroundings are not well developed and it being located on the sub urban area, this is just a unique and special place a person can find in the locality.
        </p>
     
    </body>

</html>
```
temple.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>"Boyakonda Temple"</title>
    </head>
    <body>
        <h1 align='center'>"Boyakonda Temple"</h1>
        <img src ="C:\Users\admin\Pictures\Screenshots\Screenshot 2023-11-21 212404.png"="center" height="500" width="700"  >
        <p>
      What is the history of Gangamma Temple
Temple history

A popular Goddess in India, Gangamma is a Nada Devathe (Local deity) in Bangalore. The annual Gangamma jathre (Religious fair and festival) is held in various places across India and the event in Bangalore has been held in and around Malleshwara area since 1928.
        </p>
    </body>

</html>
```
market.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>"Madanapalli tomato market"</title>
    </head>
    <body>
        <h1 align='center'>"Madanapalli tomato market</h1>
        <img src ="C:\Users\admin\Pictures\Screenshots\Screenshot 2023-11-21 213006.png" height="500" width="700"  >
        <p>
     At the crack of dawn, if there is life in Madanapalle it is at the tomato market. It buzzes with life: farmers bringing their harvested crop from the farms to the market, and tomato dealers occupied in weighing the tomatoes and transacting the payments, and the lorries (trucks) carrying the tomatoes as far as to Mumbai by the Arabian Sea to Chennai by Bay of Bengal and as closer cities and towns like Bengaluru and Hyderabad and Vijayawada. By the time the sun is up and before forenoon it will be a calm place.  

The tomato market in Madanapalle is one the biggest tomato markets in India, and in Asia, and also in the world. It gathers tomatoes cultivated by small-scale and marginal farmers in the surrounding villages of Madanapalle, and also from Chittoor and Kadapa districts of Andhra Pradesh. The market is spread in about twenty acres of land and it is located in the centre of the city. It is the largest tomato market in Andhra Pradesh.

According to downtoearth.org.in, Chittoor district in India is the largest cultivator of tomatoes. The tomato yard in Madanapalle in Chittoor district holds about 1000 tonnes of tomatoes.
        </p>
    </body>

</html>
```
# output : 
index.hmtl : 
![image](https://github.com/Thrineshroyal/Ex-04-webTech_imagemap/assets/145741928/6bc42ede-d6c5-4e17-aed8-beabcc1f6217)

basinikonda.html :
![image](https://github.com/Thrineshroyal/Ex-04-webTech_imagemap/assets/145741928/f28c63c5-6a8a-4afc-8b16-dd6ee5022a85)

MMC.html
![image](https://github.com/Thrineshroyal/Ex-04-webTech_imagemap/assets/145741928/0af9e4d6-24f2-4c05-90d4-90c69e91299e)

hall.html;
![image](https://github.com/Thrineshroyal/Ex-04-webTech_imagemap/assets/145741928/1fe5c8f5-0cf5-404b-bbc4-c77b7de056c7)

temple.html:
![image](https://github.com/Thrineshroyal/Ex-04-webTech_imagemap/assets/145741928/b4721406-d71f-4ad6-a797-6b2a02d3569b)

market.html:
![image](https://github.com/Thrineshroyal/Ex-04-webTech_imagemap/assets/145741928/57ab36cf-d4a4-49e0-9496-c9ef68719cd2)

# Result:
The program for implementing image map is executed successfully.
