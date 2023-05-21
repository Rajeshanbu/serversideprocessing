# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:
Create new project and app in django

### Step 2:
Type the code in view and urls file



### Step 3:
create the html file



### Step 4:
create the url 



### Step 5:
the website is the URL. http://rajesh.student.saveetha.in:8000/volume

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
<title>
www.volume.html
</title>
</head>
<style>
*{
box-sizing: border-box;
}
body{
background-color;
color: black;
  }
  .container{
width: 1080px;
height: 350px;
margin-top: 100px;
margin-left: auto;
margin-right: auto;
border-radius: 25px;
border: 10px solid black;
}
h1{
color: rgb(0, 0, 0);
text-align: center;
}
.calculate{
padding-top: 10px;
padding-bottom: 10px;
padding-left: 10px;
padding-right:10px;
text-align: center;
font-size: 20px;
padding-top: 7px;
font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
</style>
<body>
<div class="container">
<h1>TO CALCULATE VOLUME</h1>
<form method="POST">
{% csrf_token %}
<div class="calculate">
Height:<input type="text" name="height" value={{h}}></input><br/>
</div>
<div class="calculate">
Length:<input type="text" name="length" value={{l}}></input><br/>
</div>
<div class="calculate">
Width:<input type="text" name="width" value={{w}}></input><br/>
</div>
<div class="calculate">
<input type="submit" value="Calculate Volume"></input><br/>
</div>
<div class="calculate">
Volume:<input type="text" name="volume" value={{volume}}></input>
</div>
</form>
</div>
</body>
</html>
```

## OUTPUT:

### Home Page:
![image](https://github.com/Rajeshanbu/serversideprocessing/assets/118924713/a78166f7-c185-4fb1-921b-4340dc3dc490)


## Result:
Thus the experiment was executed successfully.

