# Ex.07 Restaurant Website
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant </title>
    <style>
        body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #151614;
    
    padding: 15px;
    text-align: center;

}

.home{
    font-size: 50px;
    color:aquamarine;
    font-family: Georgia, 'Times New Roman', Times, serif;
    padding:20px;
      
}
.home span{
    color: red;
}



nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

nav ul li {
    margin-right: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

#home {
    background-image: url(coffee\ -\ Copy.jpg);
    background-size: cover  ;
    background-position: center;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
}

#home img {
    width: 100%;
    height: 100vh;
    object-fit: cover;
    opacity: 0.5;
}



    </style>
</head>
<body>



    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="dish.html">Menu</a></li>
                <li><a href="chzt.html">process</a></li>
                <li><a href="resweb.html">contect</a></li>
            </ul>
        </nav>
    </header>



    <section id="home">
        <div class="home">
            <h1 class="title-1">Good <span>coffee</span> will always <br>Find the audience</h1>
            <p>We provide a variety of uniques and best coffee</p>
            <button type="button">Shop Now</button>
        </div>   
    </section>



    <center>
<body>
    <img src="menu.webp">
</body>
</center>
</html>
<style>
        body{
            background-color: antiquewhite;
        }
        form{
            padding: 250px;
            font-size: 30px;
            color:palevioletred ;
            border-color: black;
           

         
        }
        input type{
            color: black;
            size: 80px;
            
        }
    </style>
</head>

<body>
    
    <form>
        <center>
        <label>Enter Your Name</label>
        <input type="text"id="name"><br>
        <label>Order of Menu</label>
        <input type="text"id="menu"><br>
        <label>Table Number</label>
        <input type="number"id="num"><br>
        <button type="button">success in Order</button>
        </center>
    </form>

    <script>
        function show()
        {
            var Enter Your Name=document.getElementById("name").value
            var Order of Menu=document.getElementById("menu").value
            var Table Number=document.getElementById("num").value
        }

    </script>
    
</body>
</html>
<style>
        h1{
            font-size: 30px;
            padding: 100px;
            color:black;
            font-family:Georgia, 'Times New Roman', Times, serif;
            font-style: italic;
        }
        h3{
            font-size: 40px;
            color: aqua;
        }
        h1 span{
            font-size: 50px;
            color: red;
        }
        h4{
            color: black;
            font-size: 50px;

        }
    </style>
</head>
<center>
<body>
    <h1>The <span>coffee</span> Shop</h1>
    <h3>111 , sarasvathi street , kanchipuram</h3>
    
    <h4>Email : saveetha @@@gmain .com</h4>
    <h4>contect No: 5555557777777</h4>

    
    
</body>
</center>
</html>
```

## OUTPUT:
Home page
![image](https://github.com/user-attachments/assets/9edd9a4d-ca1f-4650-b9ab-831517fbdc65)
menu page
![image](https://github.com/user-attachments/assets/453145be-b5ca-4992-96ab-d114f36b0fc0)
process page

![image](https://github.com/user-attachments/assets/e90a32e3-10d7-476b-a806-014872d3fb85)


contect page
![image](https://github.com/user-attachments/assets/c6cee4f0-d959-42e6-a707-b999a563a999)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
