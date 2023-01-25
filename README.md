# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Write the code in notepad

### Step 2:
save the code as cover.html

###Step3:
Open the file

###Step4:
Output is displayed


## Code:
cover.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport"
content="width=device-width, initial-scale=1.0">
<style>
.bookpage{
width: 400px;
height: 600px;
background-color: #3d3a3a;
color:white;
margin-left: auto;
margin-right: auto;
padding: 20px;
font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
background-image: url(/static/images/book.png);
background-size: cover;
}
.toptext{
color:white;
}
.tophr{
width:140px;
}
.author{
color: white;
display: inline;
position: relative;
color:lightblue;
top:169px;
font-family:Georgia;
font-size: medium;
}
.booktitle{
font-family: 'Courier New', Courier, monospace;
font-size: larger;
text-align: center;
position: relative;
top: 30px;
}
.id {
width:400px;
position: relative;
top:180px;
}
.publisher{
font-size: medium;
position: relative;
top:132px;
left:330px;
}
.edition{
color:yellow;
font-size: medium;
font-family: Verdana;
position:relative;
top:85px;
}
.subtitle{
font-family:Tahoma;
font-size: large;
position: relative;
top:40px;
}
.photo{
position: relative;
top: 135px;
left: 260px;
width: 100px;
height: 100px;
background-size: cover;
}
</style>
<title>Book Cover Page</title>
</head>
<body>
<div class="bookpage">
<div class="toptext">
EXPERT INSIGHT
</div>
<div class="tophr">
<hr style="color: red;">
</div>
<div class="booktitle">
<h1>Responsive Web Design With HTML5 and CSS</h1></div>
<div class="subtitle">
Develop future-proof responsive websites using the latest HTML5 and CSS
Techniques
</div>
<div class="photo">
<img src="C:\Users\SEC\Downloads\WhatsApp Image 2023-01-25 at 10.22.34 PM.jpeg" width="130" height="145" alt="">
</div>
<div class="id">
<hr style="color: orange;">
</div>
<div class="author">
<p><b>Subhikshaa</b></p>
</div>
<div class="publisher">
Packt>
</div>
<div class="edition">
<b>First Edition</b>
</div>
</div>
</body>
</html>

## Output:
![Screenshot (38)](https://user-images.githubusercontent.com/118787344/214629216-0f380247-a813-48e2-87c1-20eb74851f92.png)



## Result:
The cover page design of the book is displayed successfully
