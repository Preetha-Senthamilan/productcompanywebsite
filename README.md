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
'''
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Silver Linings</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="/static/images/temp.png" type="images/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Silver Linings</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">home</a></div>
        <div class="menuitem"><a href="/static/products.html">products</a></div>
        <div class="menuitem"><a>people</a></div>
        <div class="menuitem"><a>Contact</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <div class="contenttext">
            At Sliver Linings, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new products are at a new level, making your
            start to automation, or your switch to silver linings simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Silver Linings, Developed by Preetha.S
      </div>
    </div>
  </body>
</html>

products.html

 <!DOCTYPE html>
<html lang="en">
  <head>
    <title>Silver Linings</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="/static/images/temp.png" type="images/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Delicacies We Offer :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/b1.png" alt="product image">
                  </div>
                  <div class="itemname">Macbook 12</div>
                  <div class="itemprice">Price: 1,95,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/b2.png"  alt="product image">
                  </div>
                  <div class="itemname">Asus ProArt 11</div>
                  <div class="itemprice">Price: Rs.1,11,000.00</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/b3.png"  alt="product image">
                  </div>
                  <div class="itemname">Apple pro 14</div>
                  <div class="itemprice">Price: Rs.1,75,000.00</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/b4.png"  alt="product image">
                  </div>
                  <div class="itemname">Mac Book 15</div>
                  <div class="itemprice">Price: Rs.1,50,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/b5.png"  alt="product image">
                  </div>
                  <div class="itemname">Mac book rose gold 12</div>
                  <div class="itemprice">Price: Rs.2,50,000.00</div>
              </div>
          </div>
          </div>  
          </div>
      <div class="footer">
        Copyright &#169; 2021 Silver Linings , Developed by Preetha.S
      </div>
    </div>
  </body>
</html>
      
      people.html
        <!DOCTYPE html>
<html lang="en">
  <head>
    <title>Silver Linings</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="/static/images/temp.png" type="images/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Board Of Directors :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/P1.png" alt="People">
                  </div>
                  <div class="itemname">Mr.Damon Salvatore</div>
                  <div class="itemprice">Founder </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/P2.png" alt="People">
                  </div>
                  <div class="itemname">Ms.Elena</div>
                  <div class="itemprice">Co-Founder </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/P3.png" alt="People">
                  </div>
                  <div class="itemname">Mr. klaus Mikaelson</div>
                  <div class="itemprice">Managing Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/P4.png" alt="People">
                  </div>
                  <div class="itemname">Ms.Caroline Forpes</div>
                  <div class="itemprice"> Joint-Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/P5.png" alt="People">
                  </div>
                  <div class="itemname">Mr.Stefan Savatore</div>
                  <div class="itemprice"> CEO </div>
              </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/P6.png" alt="People">
                  </div>
                  <div class="itemname">Mr.Elijah Mikaelson</div>
                  <div class="itemprice"> Chief Technical Officer </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; Silver Linings, Created by Preetha
      </div>
    </div>
  </body>
</html>

layout.css
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: pink;
  color:white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px black;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/images/temp.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px ;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #59ccdbf1;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: pink;
}

.menuitem a {
  text-decoration: none;
  color: #000000;
}

.content {
  display: block;
  width: 100%;
  background-color: black;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}
.homecontent h2{
  text-align: left;
}
.contenttext {
  text-align: justify;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  color:white;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
  color: white;
}
.productitem .itemprice {
  display: block;
  color: white;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #59ccdbf1;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: black;
}
contact.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Silver Linings</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="/static/images/temp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1>
          <h1>Address:</h1>
          <div class="contenttext">
            Saveetha Nagar, Sriperumbadur Taluk, Kanchipuram - Chennai Rd, Chennai, Tamil Nadu- 602105
          </div>
          <h1>Phone:</h1>
          <div class="contenttext">
              Ms.Swetha(HR):6382159898<br/>
              Mr.Abishek(Assistant HR):6383945689
          </div>
          <h1>E-Mail:</h1>
          <div class="contenttext">
              Sales:sales@silverlinings.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Silver Linings, Developed by Preetha.S
      </div>
    </div>
  </body>
</html>
'''



## OUTPUT:
![OUTPUT](./home1.png)
![OUTPUT](./product.png)
![OUTPUT](./people.png)
![OUTPUT](./contact.png)


### HTML VALIDATOR:

![HTML VALIDATOR](./valid1.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
