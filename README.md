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
    align-items: center;
    height: 100vh;
}
.page{
    width: 400px;
    height: 600px;
    background-image: url(bgimage.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    border: 4px solid blue;
    padding:20px;
    box-sizing:border-box;
    background-clip: padding-box;
    position: relative;
}

.insights{
    font-size: 18px;
   font-weight: bold;
   margin-bottom: 20px;
}
.hr{
    color: lightblue;
    width: 120px;
    right: 200%;
    

}
.title{
font-size: 45px;
     margin: 13px 0 15px 0;
    
   font-weight: bold;
    text-align: center;
}
.subtitle{
    font-size: 18px;
    margin-bottom: 40px;
}
.edit{
    font-size: 18px;
    font-weight: bold;
    margin-top: 200px;
}
.name{
    font-size: 16px;
    font-weight: bold;
    margin-top: 5px;
   
}
.bottom{
    position: absolute;
    bottom: 20px;
    right: 20px;
    font-weight: bold;
}
.pic{
    
    position: absolute;
    bottom: 90px;
    left: 75%;
    width: 100px;
    height: 100px;
    background: url("sifizphoto.jpg") no-repeat center;
    background-size: contain;   

}

```

## OUTPUT:
![alt text](<Screenshot (15).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
