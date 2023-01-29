# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
clone the gitup repositary into Theia IDE.
### Step 2:
create a new Django Project

### Step 3:
Writ the HTML code.

### Step 4:
Run the Django server and execute the HTML files.

## Code:
```
map.html

<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Tiruvannamalai-Temple city</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Bakkiya lakshmi M (22008649)</b></b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/tourist.html" title="Sri Ramanashramam">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/bus.html" title="Thenimalai">
<area shape="circle" coords="400,350,50" href="/static/html/park.html" title="Science park">
<area shape="circle" coords="400,200,75" href="/static/html/vk.html" title="Thamarai nager lake">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/college.html" title="Shanmuga Industries Arts & Science College">
</map>
</center>
</body>
</html>



bus.html

<html lang="en">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Thenimalai-Bus Stand</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sri Ramanshramam Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Tiruvannamalai is one of the most venerated places in Tamil Nadu. In ancient times, the term “Annamalai” meant an inaccessible mountain. The word “Thiru” was prefixed to signify its greatness, and coupled with the two terms, it is called Tiruvannamalai.
The Temple Town of Tiruvannamalai is one of the most ancient heritage sites of India and is a centre of the Saiva religion. The Arunachala hill and its environs have been held in great regard by the Tamils for centuries. The temple is grand in conception and architecture and is rich in tradition, history and festivals. The main Deepam festival attracts devotees from far and wide throughout South India. It has historic places besides Tiruvannamalai, Arni, Vandavasi, Devigapuram connected to East India and French companies. In the late Chola period this district was ruled by the Cholan of Sambuvarayar having Padavedu near Arni as HQ. We can now find the fort and note along with a Shiva temple namely Kailasanathar in Arni town.
</b>
</font>
</p>
</body>
</html>

park.html

<html lang="en">
<head>
<title>Science-Park</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Tiruvannamali-Temple City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Science-Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
A very nice park near Thenimalai bus stand. It is located surrounding the Ramanashramam. 
Very superb calm place in Tiruvannamalai. Best for walking. Nice playing place for kids.
Well maintained with jogging track. Source of ground water.
Good place play with children.  In Banyan Tree lot of parrot stay like house. 
Good sound and Air. Lake view park looks awesome.
Very nice place at Tiruvannamalai.
Simple and relax with play area.
</font>
</p>
</body>
</html>

college.html

<html lang="en">
<head>
<title>Shanumuga arts and science college</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Tiruvannamalai - Temple City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Shanumuga arts and science college</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of Shanmuga arts and science college are 
<ul>
<li>To impart proper and qualified training to teachers and give them an attractive salary and incentives so that they are not tempted to quit and look elsewhere for jobs.</li>
<li>To provide financial aids and grants wisely and judiciously.</li>
<li>To Frame of syllabus and curriculum.</li>
<li>To set aims and objectives of education.</li>
</ul>
</font>
</p>
</body>
</html>

tourist.html

<html lang="en">
<head>
<title>Ramanashrama</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Tiruvannamalai - Temple City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Ramanashramam</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
     Sri Ramana Ashram, also known as Sri Ramanasramam, is the ashram which was home to modern sage and Advaita Vedanta master Ramana Maharshi from 1922 until his death in 1950. It is situated at the foot of the Arunachala hill, to the west of Tiruvannamalai, Tamil Nadu, where thousands of seekers flocked to be in his presence. His samadhi shrine continues to attract devotees from all over the world.

</b>
</font>
</p>
</body>
</html>

vk.html

<html lang="en">
<head>
<title> Thamarai nagar Lake</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Tiruvannamalai - Temple City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thamarai nagar Lake</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The uses of Thamarai nagar Lake in Tiruvannamalai District are 
<ol type="1">
<li>Lake is used for rain water harvesting.</li>
<li>It is used for drinking.</li>
<li>Pisculture.</li>
<li>For bathing, washing clothes etc.</li>
</ol>
</font>
</p>
</body>
</html>
```


## Output:
![](out1m.png)
![](bus.png)
![](lake.png)
![](ram.png)
![](ram.png)
![](tem.png)


## HTML Validator
![output](Showing results for http___vigneshkumaran.student.saveetha.in_8000_static_html_map.html - Nu Html Checker — Mozilla Firefox Private Browsing 29-01-2023 18_48_42.png)


## Result:
The Program for implementing image map is executed successfully
