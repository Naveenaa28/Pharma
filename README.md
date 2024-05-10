# Project Responsive Web Design using Bootstrap
## Date:10/5/24
## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<html>
  <head>
    <title>services</title>
    
    <style>
                body{
                background: linear-gradient(rgb(0, 0, 0) , rgb(31, 5, 110) );
                }
                
            ul{
                float: right;
                list-style-type: none;
                margin-top: 20px;
                min-height: 10%;
                margin-right: 60px;
                font-size: 17px;
            }
            ul li{
                display: inline-block;
            }
            ul li a{
                text-decoration: double;
                color: #ffffff;
                padding: 5px 50px;
                border: 1px solid transparent;
                transition: 0.5 ease;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                font-size: larger;
            }

            ul li a:hover{
                background-color: black;
                color: #fff;
            }
            .search{
                width: 330px;
                float:right;
                margin-right: 20px;
            }
            .srch{
                font-family: 'Times New Roman';
                width: 200px;
                height: 40px;
                background: transparent;
                border: 1px solid #fff;
                margin-top: 13px;
                color: black;
                border-right: none;
                font-size: 16px;
                float: left;
                padding: 10px;
                border-bottom-left-radius: 5px;
                border-top-left-radius: 5px;
            }
            .btn{
                width: 100px;
                height: 40px;
                background: #fff;
                border: 2px solid#ffffff;
                margin-top: 13px;
                color:black;
                font-size: 15px;
                border-bottom-right-radius: 5px;
                
            }
            .btn:focus{
                outline: none;
            }
            .srch:focus{
                outline: none;
            }
footer {
    background-color: #faf7f7;
    color: #040303;
    text-align: center;
    }
footer p{
  padding: 0px;
}  
.im{
margin: 35px;
margin-left: 200px;
}
.h1{
    font-size: medium;
    font-family: Arial, Helvetica, sans-serif;
    color: #fff;
    padding: 30px;
    margin-right: 20%;
}
    </style>
  </head>
<body>
  <header>
    <div class="main">
        <ul>
            <li><a href="index.html">HOME</a></li>
            <li><a href="people.html">PEOPLE</a></li>
            <li><a href="products.html">PRODUCTS</a></li>
            <li><a href="contact.html">CONTACT</a></li>
        </ul>
    </div>
    <div class="search" >
        <input class="srch" type="search" name="" placeholder="type to search">
        <a href="#"><button class="btn">Search</button></a>
    </div>
   <div class="h1">
    <h1> SERVICES GOING ON BY ACCENTURES>!</h1>
    </div>
    <div class="im">
<img src="Accenture-Services-768x524.png" alt="" width="1000px" height="450px">
</div>
  <footer>
    <p>Designed And Developed By: NAVEENAA V.R&copy;2024</p>
</footer>
</body>
</html>
```
## OUTPUT:
![image](https://github.com/selvasachein/Pharma/assets/131433133/c31100fe-12c5-483b-93d9-e67022bb7e10)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
