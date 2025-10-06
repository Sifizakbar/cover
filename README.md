# Ex.06 Book Front Cover Page Design
## Date:03.10.2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
cover.html

<html>
    <head>
        <title>MyBook
        </title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="page">
            
            <div class="insights">
                SEC Insights
            </div>
            <div class="hr">
                <hr>
            </div>
            <div class="title">
                DJANGO FRAMEWORK
            </div>
            <div class="subtitle">
              Deep Dive into DJANGO FRAMEWORK <br>from basics to advanced<br>
              Top Seller of 2025
            </div>
            <div class="edit">
             THIRD EDITION
             </div>
             <br><hr>
              <div class="name">
                SIFIZ A
                </div>
                <div class="bottom">
                    SEC
                </div>
            <div class="pic">
            </div> 
        </div>
    </body>
</html>

style.css

body{
    display: flex;
    justify-content: center;
    height: 100vh;
    align-items: center;
}
.page{
    width: 400px;
    height: 600px;
    background-image: url(bgimage.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    border: 5px solid blue;
    padding:25px;
    box-sizing:border-box;
    background-clip: padding-box;
    position: relative;
}

.hr{
    color: lightblue;
    width: 125px;
    right: 200%;
}

.insights{
    font-size: 15px;
   font-weight: bolder;
   margin-bottom: 25px;
}
.edit{
    font-size: 20px;
    font-weight: bold;
    margin-top: 210px;
}
.title{
font-size: 50px;
     margin: 14px 0 14px 0;
   font-weight: bold;
    text-align: center;
}
.subtitle{
    font-size: 20px;
    margin-bottom: 45px;
}
.pic{
    
    position: absolute;
    background: url("sifizphoto.jpg") no-repeat center;
    bottom: 110px;
    left: 65%;
    width: 130px;
    height: 120px;
    background-size: contain;   

}
.name{
    font-size: 15px;
    font-weight: bold;
    margin-top: 10px;
   
}
.bottom{
    position: absolute;
    bottom: 55px;
    right: 22px;
    font-weight: bold;
}


```

## OUTPUT:
![alt text](<Screenshot (23).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
