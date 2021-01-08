# Web Design for a Manufacturing Company
## AIM: 
To design a static website for a chip manufacturing company.

## DESIGN STEPS:
### Step 1: 
Requirement collection.
### Step 2:
Creating the layout using HTML and CSS.
### Step 3:
Updating the sample content.
### Step 4:
Choose the appropriate style and color scheme.
### Step 5:
Validate the layout in various browsers.
### Step 6:
Validate the HTML code.
### Step 6:
Publish the website in the given URL.

## PROGRAM:

### base.html
```
{% load static %}
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Silicon Private Limited</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}">
    <link rel = "icon" href ="{% static 'img/titleicon.png' %}" type = "image/x-icon"> 
              
</head>

<body>
    <div class="container">
    <div class="banner">
        Silicon Private Limited.
    </div>
    <div class="menu">
        <div class="menuitem"><a href="/home">Home</a></div> 
        <div class="menuitem"><a href="/products">Products</a></div> 
        <div class="menuitem"><a href="/people">People</a></div>
        <div class="menuitem"><a href="/contact">contact</a></div> 
    </div><div class="content">
    {% block content %}    
    {% endblock  %}
    </div>
    <div class="footer">
        Copyright © balaji private limited
    </div>
    </div>
</body>

</html>
```

### home.html
```
{% extends "website/base.html" %}

{% block content %}
    <div class="homecontent">    
    <h1>About Us</h1>
    <img src="/static/img/v1.jpeg" alt="Building">
    <div class="contenttext">
    Silicon Pvt Ltd, provides a broad range of semiconductor and infrastructure software applications. Some of Silicon's core technologies and products include:
    <ul>
        <li>Memory Chips</li>
        <li>SATA HDD</li>
        <li>SATA SSD </li>
        <li>Broadband Modems</li>
        <li>Wifi Devices</li>
        <li>Switching Devices</li>
        <li>Optical Sensors</li>
    </ul> 
    </div>
    </div>
{% endblock  %}
```
### products.html
```
{% extends "website/base.html" %}

{% block content %}
    <div class="productcontent">    
    <h1>Our Premium Products</h1>
    <div class="productitems">
        <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/c1.jpg" alt="product image">
            </div>
            <div class="itemname">4GB DDRA4 laptop memory</div>
            <div class="itemprice">Price: Rs.2000.00 </div>
        </div>
        <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/c2.jpg"  alt="product image">
            </div>
            <div class="itemname">1TB Laptop HDD</div>
            <div class="itemprice">Price: Rs.5000.00 </div>
        </div>
        <div class="productitem">
            <div class="itemimage">
            <img src="/static/img/c3.jpeg"  alt="product image">
            </div>
            <div class="itemname">Gaming laptop with Joystick</div>
            <div class="itemprice">Price: Rs.25000</div>
        </div>
        <div class="productitem">
            <div class="itemimage">
            <img src="/static/img/c4.jpeg"  alt="product image">
            </div>
            <div class="itemname">Macbook air</div>
            <div class="itemprice">price: Rs.50000</div>
        </div>
         <div class="productitem">
            <div class="itemimage">
            <img src="/static/img/c5.jpeg"  alt="product image">
            </div>
            <div class="itemname">Xiaomi Notebook 14</div>
            <div class="itemprice">price: Rs.70000</div>
        </div>
        <div class="productitem">
            <div class="itemimage">
            <img src="/static/img/c6.jpeg"  alt="product image">
            </div>
            <div class="itemname">Laptop with 16 gb ram</div>
            <div class="itemprice">price: Rs.30000</div>
        </div>
        <div class="productitem">
            <div class="itemimage">
            <img src="/static/img/c7.jpeg"  alt="product image">
            </div>
            <div class="itemname">Laptop with HD display</div>
            <div class="itemprice">price: Rs.50000</div>
        </div>
        <div class="productitem">
            <div class="itemimage">
            <img src="/static/img/c8.jpeg"  alt="product image">
            </div>
            <div class="itemname">Laptop with A14 bionic chip</div>
            <div class="itemprice">price: Rs.50000</div>
        </div>
        <div class="productitem">
            <div class="itemimage">
            <img src="/static/img/c9.jpeg"  alt="product image">
            </div>
            <div class="itemname">Laptop with durability</div>
            <div class="itemprice">price: Rs.20000</div>
        </div>
         <div class="productitem">
            <div class="itemimage">
            <img src="/static/img/c10.jpeg"  alt="product image">
            </div>
            <div class="itemname">Best gaming laptop</div>
            <div class="itemprice">price: Rs.12000</div>
        </div>
         <div class="productitem">
            <div class="itemimage">
            <img src="/static/img/c11.jpeg"  alt="product image">
            </div>
            <div class="itemname">Laptop With Intel Core Processor</div>
            <div class="itemprice">price: Rs.50000</div>
        </div>
         <div class="productitem">
            <div class="itemimage">
            <img src="/static/img/c12.jpeg"  alt="product image">
            </div>
            <div class="itemname">Laptop with  A14 bionic chip and IOS</div>
            <div class="itemprice">price: Rs.50000</div>
    </div>
    </div>
{% endblock  %}
```
## OUTPUT:
![output](./static/img/o1.jpg)

![output](./static/img/o2.jpg)

![output](./static/img/o3.jpg)

![output](./static/img/o4.jpg)

![output](./static/img/o5.jpg)

![output](./static/img/o6.jpg)

## CODE VALIDATION REPORT:
![output](./static/img/r1.jpg)

![output](./static/img/r2.jpg)
## RESULT:
Thus a website is designed for the chip manufacturing company and is hosted in the URL http://balaji.student.saveetha.in:8000/. HTML code is validated.