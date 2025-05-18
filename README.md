# Ex.07 Restaurant Website
## Date:18-05-2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
admini
<html>
<head>
    <title>Menu</title>
    <style>
        body {
            width: 100%;    
            background-image: url(bg.png);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            margin:0; 
            overflow-y: scroll;
            
        }
        .top{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgb(224, 224, 152);
            width: 100%;
            
        }
       

        .main {
            
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            justify-content: flex-start;
            position: relative; 
            top: 10px; 
            width: 100%; 
            
        }

        .image {
            width: 200px;
            height: auto; 
        }
        
        .logo {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 2rem;
            color: rgba(25, 19, 85, 0.667); 
            text-align: center;
            margin: 10px 0; 
        }
        .hr{
            width: 100%;
        }
        
        .sub{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 11px;
            margin: auto;
            align-items: center;
            
        }
        .box2{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: aliceblue;
            border: 4px solid rgb(255, 255, 255); 
            padding: 10px;          
            width: 300;
            height: 550px;  
            border-radius: 20px;         
            text-align: justify;
            background-color: rgba(0, 0, 0, 0.522);
            
            
        }
        .box2 a{
            color: aliceblue;
            
        }
        .lowerbox{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            padding: 5%;
            gap: 40px;
        }
        .i{
            height:200;
            width: 300;
        }
        .lowerbox2{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            gap:40px;
        }
        .i1{
            height: 300px;
            width: 300px;
        }
        
        .start{
            color: aliceblue;
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 40px;
            padding: 1px;
            position: absolute;
            top:220
        }
        
        
    </style>
</head>
<body>
    <div class="main">
        <div class="top">
            <img class="image" src="lo.jpg" alt="Restaurant Logo">
            <h2 class="logo">The DS Royal</h2>
            <h3 class="sub">A Premium Restaurant</h3>
            <hr class="hr">
        </div>
        <p class="start">Our Team</p>
        <div class="lowerbox">
            
            <div class="box2"> 
                
                <h2>Arjun Kapoor</h2>
                <p>(Executive Chef)<br></p>
                <img src="images.jpeg" class="i">
                
                <p><br>A culinary maestro, the Executive Chef is the creative genius 
                    behind the menu. With years of experience in world-class kitchens,
                     they craft dishes that tantalize the taste buds and delight the soul.
                      Their dedication to quality ingredients and presentation ensures
                       every plate reflects the restaurant's premium standards.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Darling Subbu</h2>
                <p>(Restaurant Manager)<br></p>
                <img src="subbu.jpg" class="i1">
                
                <p><br>As the driving force behind this premium restaurant, subbu ensures
                     the finest dining experience for guests. </p>
                
            </div>
            <div class="box2"> 
                
                <h2>Ravi Desai</h2>
                <p>(Head Waiter)<br></p>
                <img src="Captain-Waiter.jpg" class="i">
                
                <p><br>The Head Waiter exemplifies service excellence, ensuring every 
                    guest enjoys a seamless and memorable dining experience. With a 
                    deep understanding of hospitality, they lead the service staff, 
                    manage table arrangements, and cater to the individual preferences 
                    of each guest, embodying the warmth of the 
                    restaurant.</p>
                
            </div>
            
            
        </div>
        <div class="lowerbox2">
            <div class="box2"> 
                
                <h2>Anjali Nair</h2>
                <p>(Restaurant Supervisor)<br></p>
                <img src="manager.jpeg" class="i">
                
                <p><br>The Restaurant Supervisor is the backbone of daily operations,
                     ensuring the highest standards of service and ambiance. From
                      coordinating staff schedules to maintaining a welcoming environment,
                       they ensure every detail is perfect, reflecting the restaurant's
                        premium reputation.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Sneha Reddy</h2>
                <p>(HR Manager)<br></p>
                <img src="hr.jpg" class="i">
                
                <p><br>The HR Manager is the people champion, ensuring the team thrives 
                    in a supportive and inspiring environment. They oversee recruitment,
                     training, and staff well-being, cultivating a team that upholds the
                      restaurant's commitment to luxury and excellence.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Priya Mehta</h2>
                <p>(Sous Chef)<br></p>
                <img src="Sous-Chef-job-description_5719402.avif" class="i">
                
                <p><br>Second-in-command in the kitchen, the Sous Chef plays a vital role
                     in maintaining the restaurant's culinary excellence. They assist in
                      menu development, oversee daily food preparation, and ensure the
                       kitchen runs smoothly, making every dining experience exceptional.

                </p>
                
            </div>
       
        
        
    </div>
</body>
</html>
contain
<html>
<head>
    <title>My Restaurant</title>
    <style>
        body {
            width: 100%;    
            background-image: url(bg.png);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            margin:0; 
            overflow-y: scroll;
        }
        .top{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgb(224, 224, 152);
            width: 100%;
            
        }
        .bottom{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgba(216, 216, 197, 0.928);
            width: 100%;
        }

        .main {
            
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            justify-content: flex-start; 
            position: relative; 
            top: 10px; 
            width: 100%;
        }

        .image {
            width: 200px; 
            height: auto;
        }
        
        .logo {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 2rem;
            color: rgba(25, 19, 85, 0.667);
            text-align: center; 
            margin: 10px 0;
        }
        .hr{
            width: 100%;
        }
        
        .sub{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 11px;
            margin: auto;
            align-items: center;
            
        }
        .root{
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: rgba(0, 0, 0, 0.47);
            height: 500;
            width: 800;
            font-size: 20;
        }
        
        
        
        
    </style>
</head>
<body>
    <div class="main">
        <div class="top">
            <img class="image" src="lo.jpg" alt="Restaurant Logo">
            <h2 class="logo">The DS Royal</h2>
            <h3 class="sub">A Premium Restaurant</h3>
            <hr class="hr">
            
        </div>
    
        <br>
        <br>
        <div class="root">
            <font color="white">
            <p>
                Contact Us<br>
                <br>
                The DS Royal<br>
                <ul><li>Address: 123 Gourmet Street, Culinary Town, Chennai 600001</li>
                    <li>Phone: +91-768-567-345</li>
                    <li>Email: contact@thedsroyal.com</li>
                    <li>Website: www.thedsroyal.com</li>
                </ul>
                
                We are here to assist you with reservations, inquiries, and feedback.<br> Feel 
                free to reach out to us during our business hours, and we'll be delighted to 
                serve you.<br> Your satisfaction is our priority!</p>
            </font>
        </div>
        
        
    </div>
</body>
</html>
main 
<html>
<head>
    <title>My Restaurant</title>
    <style>
        body {
            width: 100%;    
            background-image: url(bg.png);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            margin:0; 
            overflow-y: scroll;
        }
        .top{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgb(224, 224, 152);
            width: 100%;
            
        }
        .bottom{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgba(216, 216, 197, 0.928);
            width: 100%;
        }

        .main {
            
            display: flex;
            flex-direction: column; 
            align-items: center; 
            justify-content: flex-start;
            position: relative; 
            top: 10px; 
            width: 100%; 
        }

        .image {
            width: 200px; 
            height: auto;
        }
        .image1{
            height: 100px;
        }
        .logo {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 2rem;
            color: rgba(25, 19, 85, 0.667); 
            text-align: center; 
            margin: 10px 0; 
        }
        .hr{
            width: 100%;
        }
        .hr2{
            width: 100px;
        }
        .sub{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 11px;
            margin: auto;
            align-items: center;
            
        }
        .root{
            display: flex;
            align-items: center;
            justify-content: center;
            
        }
        .rootchild{
            display: flex; 
            flex-direction: row;
            justify-content: center;
            align-items: center; 
            gap: 20px;
        }
        .rootchild a{
            text-decoration:none;
            color: aliceblue;
            font-size: 30px;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            padding: 20px;
            margin:0 15px
            
        }
        .box{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: aliceblue;
            border: 4px solid rgb(255, 255, 255); 
            padding: 10px;          
            width: 900px;
            height: 200px;  
            border-radius: 20px;         
            text-align: center;
            background-image: url(front.jpg);
        }
        .box h2{
            font-size: 50;
        }
        .box h3{
            background-color: rgba(0, 0, 0, 0.308);
            font-family:'Courier New', Courier, monospace;
            
        }
        .box2{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: aliceblue;
            border: 4px solid rgb(255, 255, 255); 
            padding: 10px;      
            width: 300;
            height: 700px;  
            border-radius: 20px;         
            text-align: justify;
            background-color: rgba(0, 0, 0, 0.522);
            
            
        }
        .box2 a{
            color: aliceblue;
            
        }
        .lowerbox{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            padding: 10%;
            gap: 40px;
        }
        .i{
            height:200;
        }
    </style>
</head>
<body>
    <div class="main">
        <div class="top">
            <img class="image" src="lo.jpg" alt="Restaurant Logo">
            <h2 class="logo">The DS Royal </h2>
            <h3 class="sub">A Premium Restaurant</h3>
            <hr class="hr">
            
        </div>
    
        
        <div class="root">
            <div class="rootchild">
                <a href="main.html">HOME </a>
                <a href="menu1.html">MENU </a>
                <a href="admini.html">ADMINISTRATION</a>
                <a href="contact.html">CONTACT US</a>
            </div>
        
        </div>
        <div class="box">  
            <h2>30% off this summer</h2>
            <h3>for orders more than 1000Rs<br>and get exciting spot offers</h3>
            <h2></h2>
        </div>
        <div class="lowerbox">
            <div class="box2"> 
                
                <h2>Our Dish</h2>
                <img src="ChineseFood.webp" class="i">
                
                <p><br>Welcome to The DS Royal, where taste meets elegance!
                     Our dishes are crafted with passion, blending the finest
                      ingredients to create unforgettable flavors. From classic
                       favorites to signature creations, every plate is a masterpiece. 
                       Experience the warmth of premium dining, where every meal tells
                        a story. Taste perfection, only at Liha Otnas!. At DS Royal
                        , we redefine fine dining with a blend of tradition and
                         innovation. Our chefs meticulously prepare each dish to offer 
                         a symphony of flavors that cater to every palate. Whether it's 
                         a family gathering or a romantic evening, enjoy a dining 
                         experience that's as memorable as the meals themselves.<br>
                         <a href="">See Our Menu</a></p>
                
            </div>

            <div class="box2"> 
                
                <h2>Book a Table</h2>
                <img src="tabel.jpg" class="i">
                <br>
                <p><br>Reserve your table at The DS Royal and indulge in a premium dining 
                    experience like no other. Whether you're celebrating a special
                     occasion, enjoying a family dinner, or planning a romantic evening,
                      our warm ambiance and exquisite flavors set the stage for 
                      unforgettable moments. Booking a table ensures you skip the wait 
                      and savor your favorite dishes in comfort. From personalized service 
                      to our signature culinary creations, we prioritize your satisfaction 
                      in every detail. Don't miss out on an exceptional dining 
                      journey secure your reservation at Liha Otnas today and let us make
                       your visit truly extraordinary!<br>
                       <a href="">Book a Table Now!</a></p>
            </div>
            <div class="box2"> 
                
                <h2>Opening Hours</h2>
                <img src="servent.jpg" class="i">
                <p><br>We are here to serve you with exceptional dining experiences every day!

                    <ul><li>Monday to Friday:<ul><li>Opening: 11:00 AM</li>
                        <li>Closing: 10:00 PM</li></li></ul>
                    
                    
                    <li>Saturday and Sunday:<ul><li>Opening: 10:00 AM</li>
                        <li>Closing: 11:00 PM</li></ul></li>
                    
                    </ul>
                    Step into The DS Royal for a delightful blend of flavors and a
                     welcoming ambiance. Whether it's a casual lunch, a family dinner,
                      or a special celebration, our team is ready to make your visit 
                      unforgettable. Reserve your spot today and let us serve you with
                       passion and perfection!</p>
            </div>
        </div>
        <div class="bottom">
            
            <img class="image1" src="lo.jpg" alt="Restaurant Logo">
            <hr class="hr2">
            <h3 class="sub">A Premium Restaurant</h3>
            
            <br>
            <h3 class="sub">Designed And Developed by: D.Bala Subramanyam</h3>
        </div>
    </div>
</body>
</html>
menu1.html
<html>
<head>
    <title>Menu</title>
    <style>
        body {
            width: 100%;    
            background-image: url(bg.png);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            margin:0; 
            overflow-y: scroll;
            
        }
        .top{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgb(224, 224, 152);
            width: 100%;
            
        }
       

        .main {
            
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            justify-content: flex-start; 
            position: relative; 
            top: 10px; 
            width: 100%; 
            
        }

        .image {
            width: 200px; 
            height: auto; 
        }
        
        .logo {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 2rem; 
            color: rgba(25, 19, 85, 0.667); 
            text-align: center;
            margin: 10px 0; 
        }
        .hr{
            width: 100%;
        }
        
        .sub{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 11px;
            margin: auto;
            align-items: center;
            
        }
        .box2{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: aliceblue;
            border: 4px solid rgb(255, 255, 255);
            padding: 10px;         
            width: 300;
            height: 360px;  
            border-radius: 20px;         
            text-align: justify;
            background-color: rgba(0, 0, 0, 0.522);
            
            
        }
        .box2 a{
            color: aliceblue;
            
        }
        .lowerbox{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            padding: 5%;
            gap: 40px;
        }
        .i{
            height:200;
            width: 300;
        }
        .lowerbox2{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            gap:40px;
        }
        .i1{
            height: 300px;
            width: 300px;
        }
        
        .start{
            color: aliceblue;
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 40px;
            padding: 1px;
            position: absolute;
            top:220
        }
        
        
    </style>
</head>
<body>
    <div class="main">
        <div class="top">
            <img class="image" src="lo.jpg" alt="Restaurant Logo">
            <h2 class="logo">The DS Royal</h2>
            <h3 class="sub">A Premium Restaurant</h3>
            <hr class="hr">
        </div>
        <p class="start">The DS Exclusive</p>
        <div class="lowerbox">
            
            <div class="box2"> 
                
                <h2>Royal Butter Chicken</h2>
                
                <img src="food1.avif" class="i">
                
                <p><br> Succulent chicken cooked in creamy tomato sauce with aromatic spices.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Herb-InfusedGrilled Lamb</h2>
               
                <img src="food2.avif" class="i">
                
                <p><br>Tender lamb chops seasoned with Mediterranean herbs.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Seafood Symphony</h2>
               
                <img src="food3.avif" class="i">
                
                <p><br>A medley of shrimp, calamari, and mussels in a tangy sauce.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Golden Prawns</h2>
                
                <img src="food4.webp" class="i">
                
                <p><br>Crispy battered prawns served with a spicy dip.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Stuffed Mushroom Caps</h2>
               
                <img src="food5.webp" class="i">
                
                <p><br>Mushrooms filled with cheese and herbs, baked to perfection.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Tandoori Paneer Tikka</h2>
                
                <img src="food6.jpeg" class="i">
                
                <p><br>Marinated cottage cheese cubes grilled over charcoal.</p>
                
            </div>
            
            
        </div>
        <div class="lowerbox2">
            <div class="box2"> 
                
                <h2>Exotic Veggie Platter</h2>
                
                <img src="food7.jpeg" class="i">
                
                <p><br>Assorted seasonal vegetables in flavorful gravies.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Spicy Pepper Beef</h2>
               
                <img src="food8.jpg" class="i">
                
                <p><br>Wok-tossed beef slices in a fiery black pepper sauce.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Signature Biryani </h2>
                
                <img src="food9.jpeg" class="i">
                
                <p><br>Fragrant basmati rice layered with spiced meat or vegetables.

                </p>

                
            </div>
            <div class="box2"> 
                
                <h2>Saffron Gulab Jamun</h2>
            
                <img src="food10.avif" class="i">
                
                <p><br>Soft, golden dumplings soaked in saffron syrup</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Dark Chocolate Lava Cake</h2>
                
                <img src="food11.jpeg" class="i">
                
                <p><br> Warm, gooey chocolate cake served with vanilla ice cream.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>ALiha's Secret Mocktail</h2>
             
                <img src="food12.webp" class="i">
                
                <p><br>A refreshing blend of exotic fruits and herbs.</p>
                
            </div>
       
        
        
    </div>
</body>
</html>

```
## OUTPUT:

![alt text](<Screenshot 2025-05-18 144100.png>)
![alt text](<Screenshot 2025-05-18 144116.png>)
![alt text](<Screenshot 2025-05-18 144138.png>)
![alt text](<Screenshot 2025-05-18 144151.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
