# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

## PROGRAM :
### Home Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple Inc.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">KDtech Ltd.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/bg1.png" alt="Building" />
          <div class="contenttext">
            KDTech Solutions is a global IT company and professional services firm founded in 2003 and based in Irving, Texas.

We are committed to your success. From design to custom application development, KDTech Solutions works closely with you to help your company increase productivity, improve business processes, and expand business assets.

The KDTech Way is to be Responsive, Respectful, Resourceful, and Reliable.


          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Apple Inc. Developed by Kadin Samson L.
      </div>
    </div>
  </body>
</html>
```
### Product Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple Inc.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icecream1.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">KDtech Ltd.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ac.png" alt="product image">
                  </div>
                  <div class="itemname">Auto Cad</div>
                  <div class="itemprice">Price: Rs.20000/Month/- </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ap.png"  alt="product image">
                  </div>
                  <div class="itemname">Adobe Photoshop Premier</div>
                  <div class="itemprice">Price: Rs.15000/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/co.png"  alt="product image">
                </div>
                <div class="itemname">Capture One</div>
                <div class="itemprice">Price: Rs.1200/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/f.l.jpg"  alt="product image">
                </div>
                <div class="itemname">F Lux </div>
                <div class="itemprice">Price: Rs.3999/- </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/f360.jpg"  alt="product image">
              </div>
              <div class="itemname">Fusion 360</div>
              <div class="itemprice">Price: Rs.3000/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/obs.png"  alt="product image">
            </div>
            <div class="itemname">OBS Studio</div>
            <div class="itemprice">Price: Rs.2000/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/pcc"  alt="product image">
            </div>
            <div class="itemname">Piriform CCleaner</div>
            <div class="itemprice">Price: Rs.2,500/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/rc.png"  alt="product image">
            </div>
            <div class="itemname">Razer Cortex</div>
            <div class="itemprice">Price: Rs.10900/- </div>
          </div>   <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/ts.jpg"  alt="product image">
            </div>
            <div class="itemname">Team Speak</div>
            <div class="itemprice">Price:520/- </div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/to.png"  alt="product image">
          </div>
          <div class="itemname">Toago</div>
          <div class="itemprice">Price: Rs.3000/- </div>
      </div>  <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/vp.png"  alt="product image">
        </div>
        <div class="itemname">Vayupay</div>
        <div class="itemprice">Price: Rs.6999/- </div>
    </div>  <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/al.png"  alt="product image">
      </div>
      <div class="itemname">Adobe Lightgroom</div>
      <div class="itemprice">Price: Rs.2000/- </div>
  </div>
      
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Apple Inc. Developed by Kadin Samson L.
      </div>
    </div>
  </body>
</html>
```
### People Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple Inc.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner">KDtech Ltd.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/haaland.jpg" alt="product image">
                </div>
                <div class="itemname">Haaland</div>
                <div class="itemprice">Managing Director</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/spi.jpg"  alt="product image">
                </div>
                <div class="itemname">Sunder Pichai</div>
                <div class="itemprice">Office manager</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/bg.jpg"  alt="product image">
              </div>
              <div class="itemname">BillGates</div>
              <div class="itemprice">Assistant HR</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/jb.jpg"  alt="product image">
              </div>
              <div class="itemname">Jeff Bezos</div>
              <div class="itemprice">Marketing Manager</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/em.jpg"  alt="product image">
            </div>
            <div class="itemname">ElonMusk</div>
            <div class="itemprice">Professional Staff</div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/amb.webp"  alt="product image">
          </div>
          <div class="itemname">Ambani

          </div>
          <div class="itemprice">Operation Manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Apple Inc. Developed by Kadin Samson L.
    </div>
  </div>
</body>
</html>
```
### ContactUs Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple Inc.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">KDtech Ltd.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1><br><br>
          <h1>Address:</h1><br><br>
          <div class="contenttext">
            Saveetha Engineering College,
            Kanchipuram High way<br>
            Kanchipuram 600 068,India<br>
            Customer Care:1800 129 2183<br>
            E-mail:kdtechltd@gmail.com
          </div><br>
        
          <h1>E-Mail:</h1><br><br>
          <div class="contenttext">
              Sales:kdtechltd@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Apple Inc. Developed by Kadin Samson L.
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:
### Home Page:
![gitlogo](kd1.png)
### Product Page:
![gitlogo](kd2.png)
### People Page:
![gitlogo](kd3.png)
### ContactUs Page:
![gitlogo](kd4.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
