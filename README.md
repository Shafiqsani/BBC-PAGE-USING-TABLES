
# LAB-3: BBC PAGE USING TABLES

## Introduction:
Students have learned advanced HTML concepts of designing web pages using tables and styles. In this lab, student will practically design a web page using these advanced HTML concepts. 

## Lab Objectives:
The objective of this lab is to help students in designing the layout of a web page using tables and styles.  Students will apply different HTML tags and styling concepts they have learned in the lectures to design the layout of a web page.

## Tools:
Dreamweaver, notepad, browser.
## Helping Material:
* Lecture slides.
* W3Schools: https://www.w3schools.com/html/default.asp 
* https://www.w3schools.com/html/html_tables.asp 
* Nesting tables examples: https://www.lehigh.edu/~inwww/seminar/intermediate/tables/table-nest.html  

 


### Lab Task 1:
 
BBC is one of the famous public broadcasting companies. BBC broadcast news in several ways e.g. television, radio, electronic (via internet) etc. They can be accessed over the internet through their web site: www.bbc.com. The layout of this website can be designed using HTML tables. A screenshot of the website is shown below:

#### Your Task:
Design a web page which has similar layout as shown in the above screenshots. Your layout must be based on tables (no divs). You are encouraged to use either internal CSS (using style attribute). You are also encouraged to use different HTML tags we learned so far. 
Hints
1.	Feel free to browse BBC’s website and look into its page source to see how the layout is designed.
2.	You can change the color scheme as per your choice. 
3.	BBC’s website has a menu (More) and a search bar. You can skip both in your layout.
4.	You are encouraged to use most of the HTML tags you have learned so far or even new tags, which you can learn from W3Schools.
5.	Make good use of HTML colors, fonts, font-family, font-sizes and other styles for the look and feel of the web page.
6.	Make sure to test your website with different resolutions by changing the resolution of your screen.
7.	High resolution images of both screenshots can be seen by using zoom in features of MS Word.

#### CODE:
```
<!DOCTYPE html>
<html>
<head>
<title>BBC</title>
<style>
table {
  width:100%;
}
table, th, td {
  border = "0" align="center"
}
th, td {
  padding-right: 20px;
  padding-left: 20px;
  text-align: left;
}

#t01 tr {
  background-color: black;
  color: white;
}
</style>
</head>
<body>

<table border = "0" align="center" >
  <tr style = "background-color: black;
  color: white;">
    <td style="font-size:250%;padding-left: 50px;color:red">BBC</td>
    <td>Home</td>
    <td>News</td>
    <td>Sports</td>
    <td>Travel</td>
    <td>Culture</td>
    <td>Reel</td>
    <td>Worklife</td>
    <td>Future</td>
  </tr>

  <tr align = "center">
    <td colspan="9">
      <table border = "0" align="center">
        <td style="font-size:150%;padding-top: 20px;font-family:verdana;"><b>  Welcome to BBC.com</b></td>
        <td style="font-size:130%;padding-top: 20px;padding-left: 500px">Thursday, 11 March</td>
      </table>
    </td>
  </tr>
</table>

<table border="0" align = "center">
  <tr>
    <td rowspan="2"; height="300px" width="300px" style="background-image
    :url(https://ichef.bbci.co.uk/news/976/cpsprodpb/03E6/production/_117589900_hi066255977.jpg)
    ; background-size:cover"><h2 style="color:white;font-family:arial">Vaccine safety experts to review AstraZeneca jab</h2></td>

    <td height="100px" width="100px" style="background-image
    :url(https://ichef.bbci.co.uk/news/976/cpsprodpb/3F46/production/_117589161_gettyimages-1228918581.jpg)
    ; background-size:cover"><h3 style="color:white;font-family:arial">China's tech giants fall under regulator's pressure</h3></td>
    <td  height="100px" width="100px" style="background-image
    :url(https://ichef.bbci.co.uk/news/976/cpsprodpb/3640/production/_117588831_gettyimages-951833242.jpg)
    ; background-size:cover"><h3 style="color:white;font-family:arial">North Korea: Kim Jong-un's sister warns US not to 'cause a stink'</h3></td>
  </tr>
  <tr>
    <td height="100px" width="100px" style="background-image
    :url(https://ychef.files.bbci.co.uk/1600x900/p099rt65.webp)
    ; background-size:cover"><h3 style="color:white;font-family:arial">Why noise pollution is bad for your heart</h3></td>
    <td height="100px" width="50px" style="background-image
    :url(https://ychef.files.bbci.co.uk/1600x640/p099bkjt.jpg)
    ; background-size:cover"><h3 style="color:white;font-family:arial">The Jamaican fruit that could kill you</h3></td>
  </tr>
</table>
<table border="0" align = "center">
  <tr>
    <th style="font-size:150%;padding-top: 40px;padding-bottom: 20px;padding-left: 20px;color:red"><b>|| News</b></th>
  </tr>
  <tr>
    <td><img src="https://ichef.bbci.co.uk/news/976/cpsprodpb/C1DD/production/_117592694_7539d7d9-2475-41d8-a301-aa4027e52427.jpg"
       style="width:320px;height:220px;"><h2>Prince Philip: Duke of Edinburgh leaves hospital after a month</h2>
       <p>The 99-year-old Duke of Edinburgh returns to Windsor Castle following a successful heart procedure.</p>
     </td>
   <td><img src="https://ichef.bbci.co.uk/news/976/cpsprodpb/11B47/production/_117591527_germanpic.jpg"
      style="width:320px;height:220px;"><h2>Coronavirus: Alarm at German AstraZeneca pause as cases spike</h2>
    <p>German leaders have postponed a summit on extending the vaccine rollout as they await confirmation.</p>
    </td>
    <td><img src="https://ichef.bbci.co.uk/news/976/cpsprodpb/C0F6/production/_117589394_gettyimages-1231369198.jpg"
       style="width:320px;height:220px;"><h2>Mozambique insurgency: Militants beheading children, <br>  aid agency reports</h2>
       <p>Aid agency Save the Children says militants are beheading children as young as 11 in Mozambique's northern province.</p>
     </td>
     <td><img src="https://ichef.bbci.co.uk/news/976/cpsprodpb/E941/production/_112531795_gettyimages-452255528.jpg"
        style="width:320px;height:220px;"><h2>Facebook to pay News Corp  for content in Australia. Facebook v Australia</h2>
        <p>Facebook has agreed to pay Rupert Murdoch's News Corp Australia for journalism from its local mastheads. Facebook v Australia: Two sides to the story</p>
      </td>
  </tr>
</table>
<table border="0" align = "center">
  <tr>
    <th style="font-size:150%;padding-top: 40px;padding-bottom: 20px;padding-left: 20px;color:red"><b>|| News</b></th>
  </tr>
  <tr>
    <td><img src="https://ichef.bbci.co.uk/onesport/cps/800/cpsprodpb/78C7/production/_117591903_mediaitem117591901.jpg"
       style="width:400px;height:300px;"><h2>Stander to retire at end of season</h2>
       <p>Ireland and Munster back row CJ Stander announces that he will retire from rugby at the end of this season.</p>
     </td>
   <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZ0t3-csSiRytyjWfFRn6f8TNbInMnsTa2nA&usqp=CAU"
      style="width:400px;height:300px;"><h2>Messi equals Xavi's Barcelona record</h2>
    <p>Lionel Messi scores twice and makes another on the day he equals Xavi's record for most Barcelona appearances.</p>
    </td>
    <td><img src="https://ichef.bbci.co.uk/onesport/cps/800/cpsprodpb/7426/production/_113343792_usman1.jpg"
       style="width:400px;height:300px;"><h2>Usman-Masvidal full-capacity event</h2>
       <p>The UFC is set to host its first full-capacity event in 13 months, its president Dana White says.</p>
     </td>
  </tr>
</table>
<table border="0" align = "center">
  <tr>
    <th style="font-size:150%;padding-top: 40px;padding-bottom: 20px;padding-left: 20px;color:red"><b>|| Feature Video</b></th>
  </tr>
  <tr>
    <td><iframe width="1280" height="720" src="https://www.youtube.com/embed/tgbNymZ7vqY?autoplay=1">
</iframe></td>
  </tr>
</table>

<table border = "0" align="center" style = "background-color: grey;
color: white;">
  <tr>
    <th colspan="7" style="font-size:150%"><b>Explore the BBC</b></th>
  </tr>
  <tr style="padding-top: 50px;padding-bottom: 20px;padding-left: 20px">
    <td >Home</td>
    <td>News</td>
    <td>Sports</td>
    <td>Weather</td>
    <td>iPlayer</td>
    <td>Sounds</td>
    <td>CBBC</td>
  </tr>
  <tr >
    <td>CBeebies</td>
    <td>Food</td>
    <td>BiteSize</td>
    <td>Arts</td>
    <td>Taster</td>
    <td>Local</td>
    <td>Three</td>
  </tr>
  <tr>
    <td colspan="7"><hr color = black></td>
  </tr>
  <tr>
    <td colspan="7"><p>Copyright © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking.</p></td>
  </tr>

</table>

</body>
</html>
```
![alt text](https://i.ibb.co/61sBGCC/3.png)
