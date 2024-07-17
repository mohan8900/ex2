# ex2
## index.html
```c
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RoopTech Contact</title>
    <style>
    body {
        background-image: url(img.png);
        background-size: cover;
        color: white;
    }
    .header {
        display: flex;
        align-items: center;
        padding: 20px;
    }
    .logo{
        font-size: 35px;
        font-weight: bold;
        padding-left: 60px;
        
    }
     .red {
        color: red;
    }
     .white {
        color: white;
    }
    .nav {
        display: flex;
        align-items: center;
        padding-left: 200px;
        gap: 20px;
    }
    .nav a {
        color: white;
        text-decoration: none;
        font-size: 20px;
    }
    .nav a:hover {
        color: red;
    }
    .search-bar {
        display: flex;
       padding-left: 150px;
    }
    .search-bar input {
        padding: 5px;
        border: none;
        border-radius: 5px 0 0 5px;
        background-color: #585656;
        color: white;
        
    }
    .search-bar button {
        padding: 5px 10px;
        border: none;
        border-radius: 0 5px 5px 0;
        background: red;
        color:white;
        cursor: pointer;
        
    }
    .hero {
        
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        padding: 0 20px;
        
        position: relative;
        top: 80px;
    }
    .hero h1 {
        font-size: 36px;
        margin-bottom: 20px;
    }
    
    .buttons {
        display: flex;
        gap: 20px;
    }
    
    .buttons button {
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        font-size: 16px;
        cursor: pointer;
    }
    
    .login {
        background: red;
        color: white;
    }
    
    .signup {
        background: green;
        color: white;
    }
    
    footer {
        background: red;
        text-align: center;
        font-size: 15px;
        padding: 1px;
        position: fixed;
        width: 100%;
        bottom: 0;
    }
    </style>
</head>
<body>

    <div class="header">
        <div class="logo">
            <span class="red">R</span><span class="white">OOP</span><span class="red">T</span><span class="white">ECH</span>
        </div>
        <div class="nav">
            <a href="index.html">Home</a>
            <a href="product.html">Products</a>
            <a href="people.html">People</a>
            <a href="contact.html">Contact</a>
            <div class="search-bar">
                <input  type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </div>
    </div>
    <main>
        <section class="hero">
            <h1>"Driving progress through precision <br> engineering and <br> boundless creativity."</h1>
            <div class="buttons">
                <button class="login">Log In</button>
                <button class="signup">Sign Up</button>
            </div>
        </section>
    </main>
    <footer>
        <p>DESIGNED AND DEVELOPED MOHANRAJ(212221230064)</p>
    </footer>
</body>
</html>
```
## OUTPUT:
![Screenshot 2024-07-17 105532](https://github.com/user-attachments/assets/c07f34ec-fced-4f38-bc7b-cd9366e05bf5)

## people.html
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RoopTech - People</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-image: url(img.png);
            background-size: cover;
            color: white;
        }
        .header {
            display: flex;
            align-items: center;
            padding: 20px;
        }
        .logo{
            font-size: 35px;
            font-weight: bold;
            padding-left: 60px;
            
        }
         .red {
            color: red;
        }
         .white {
            color: white;
        }
        .nav {
            display: flex;
            align-items: center;
            padding-left: 200px;
            gap: 20px;
        }
        .nav a {
            color: white;
            text-decoration: none;
            font-size: 20px;
        }
        .nav a:hover {
            color: red;
        }
        .search-bar {
            display: flex;
           padding-left: 150px;
        }
        .search-bar input {
            padding: 5px;
            border: none;
            border-radius: 5px 0 0 5px;
            background-color: #585656;
            color: white;
            
        }
        .search-bar button {
            padding: 5px 10px;
            border: none;
            border-radius: 0 5px 5px 0;
            background: red;
            color:white;
            cursor: pointer;
            
        }
        .people {
    display: flex;
    justify-content: space-around;
    padding: 50px 0;
}

.person {
    text-align: center;
}

.person img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
}

footer {
        background: red;
        text-align: center;
        font-size: 15px;
        padding: 1px;
        position: fixed;
        width: 100%;
        bottom: 0;
    }
    </style>
</head>
<body>
    <header>
        <div class="header">
            <div class="logo">
                <span class="red">R</span><span class="white">OOP</span><span class="red">T</span><span class="white">ECH</span>
            </div>
            <div class="nav">
                <a href="index.html">Home</a>
                <a href="product.html">Products</a>
                <a href="people.html">People</a>
                <a href="contact.html">Contact</a>
                <div class="search-bar">
                    <input  type="text" placeholder="Enter to Search">
                    <button>Search</button>
                </div>
            </div>
        </div>
    </header>
    <main>
        <section class="people">
            <div class="person">
                <img src="1.png" alt="Roop Sagar">
                <h3>SHETY</h3>
                <p>CEO</p>
            </div>
            <div class="person">
                <img src="2.png" alt="Ratan Tata">
                <h3>LENA</h3>
                <p>CEO, Co-Founder</p>
            </div>
            <div class="person">
                <img src="3.png" alt="Steve Jobs">
                <h3>JOBS</h3>
                <p>CTO, Co-Founder</p>
            </div>
            <div class="person">
                <img src="4.png" alt="Sundar">
                <h3>SELVI</h3>
                <p>DIRECTOR</p>
            </div>
            <div class="person">
                <img src="5.png" alt="Walt Disney">
                <h3>DISNEY</h3>
                <p>Asst. Director</p>
            </div>
            <div class="person">
                <img src="6.png" alt="Elon Musk">
                <h3>MALINA</h3>
                <p>Dy. Director</p>
            </div>
        </section>
    </main>
    <footer>
        <p>DESIGNED AND DEVELOPED MOHANRAJ(212221230064)</p>
    </footer>
</body>
</html>
```

## OUTPUT:
![Screenshot 2024-07-17 105727](https://github.com/user-attachments/assets/15b3f9d2-c0d0-40a9-a075-a3b2900f3400)

## Product.html
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RoopTech - Products</title>
    <style>
        body {
            background-image: url(img.png);
            background-size: cover;
            color: white;
        }
        .header {
            display: flex;
            align-items: center;
            padding: 20px;
        }
        .logo{
            font-size: 35px;
            font-weight: bold;
            padding-left: 60px;
            
        }
         .red {
            color: red;
        }
         .white {
            color: white;
        }
        .nav {
            display: flex;
            align-items: center;
            padding-left: 200px;
            gap: 20px;
        }
        .nav a {
            color: white;
            text-decoration: none;
            font-size: 20px;
        }
        .nav a:hover {
            color: red;
        }
        .search-bar {
            display: flex;
           padding-left: 150px;
        }
        .search-bar input {
            padding: 5px;
            border: none;
            border-radius: 5px 0 0 5px;
            background-color: #585656;
            color: white;
            
        }
        .search-bar button {
            padding: 5px 10px;
            border: none;
            border-radius: 0 5px 5px 0;
            background: red;
            color:white;
            cursor: pointer;
            
        }
        .products {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    padding: 20px 0;
    width: 80%;
   
    margin: 0 auto;
}

.product {
    background-color: #111;
    padding: 20px;
    border-radius: 10px;
    border: 2px solid #444;
    text-align: center;
}

.product h3 {
    color: #f00;
    margin-bottom: 10px;
}

footer {
        background: red;
        text-align: center;
        font-size: 15px;
        padding: 1px;
        position: fixed;
        width: 100%;
        bottom: 0;
    }
    </style>
</head>
<body>
    <header>
        <div class="header">
            <div class="logo">
                <span class="red">R</span><span class="white">OOP</span><span class="red">T</span><span class="white">ECH</span>
            </div>
            <div class="nav">
                <a href="index.html">Home</a>
                <a href="product.html">Products</a>
                <a href="people.html">People</a>
                <a href="contact.html">Contact</a>
                <div class="search-bar">
                    <input  type="text" placeholder="Enter to Search">
                    <button>Search</button>
                </div>
            </div>
        </div>
    </header>
    <main>
        <section class="products">
            <div class="product">
                <h3>C++</h3>
                <p>Efficiency Redefined: Harnessing the Power of C++ for Next-Level Development</p>
            </div>
            <div class="product">
                <h3>C</h3>
                <p>Crafting Performance: Where Precision Meets C Programming.</p>
            </div>
            <div class="product">
                <h3>JAVASCRIPT</h3>
                <p>Scripting Success: Unleashing the Power of JavaScript.</p>
            </div>
            <div class="product">
                <h3>PHP</h3>
                <p>PHP is a server-side scripting language that is embedded in HTML.</p>
            </div>
            <div class="product">
                <h3>PYTHON</h3>
                <p>Unlocking Innovation: Python Paving the Way to Progress.</p>
            </div>
            <div class="product">
                <h3>SQL</h3>
                <p>SQL is a standard language for accessing and manipulating databases.</p>
            </div>
            <div class="product">
                <h3>SHELL</h3>
                <p>Shell can be accessed by users using a command line interface.</p>
            </div>
            <div class="product">
                <h3>RUBY</h3>
                <p>Ruby: Where Simplicity Meets Power in Programming.</p>
            </div>
            <div class="product">
                <h3>TYPESCRIPT</h3>
                <p>Empower Your Code: Embrace the Future with TypeScript.</p>
            </div>
            <div class="product">
                <h3>F#</h3>
                <p>F# is an Open-source programming language with a lot of features.</p>
            </div>
        </section>
    </main>
    <footer>
        <p>DESIGNED AND DEVELOPED MOHANRAJ(212221230064)</p>
    </footer>
</body>
</html>
```
## OUTPUT
![Screenshot 2024-07-17 105736](https://github.com/user-attachments/assets/aa26cf48-94cf-4185-8a74-84e8b6c6629e)

## contact.html
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RoopTech Contact</title>
    <style>
    body {
        background-image: url(img.png);
        background-size: cover;
        color: white;
    }
    .header {
        display: flex;
        align-items: center;
        padding: 20px;
    }
    .logo{
        font-size: 35px;
        font-weight: bold;
        padding-left: 60px;
        
    }
     .red {
        color: red;
    }
     .white {
        color: white;
    }
    .nav {
        display: flex;
        align-items: center;
        padding-left: 200px;
        gap: 20px;
    }
    .nav a {
        color: white;
        text-decoration: none;
        font-size: 20px;
    }
    .nav a:hover {
        color: red;
    }
    .search-bar {
        display: flex;
       padding-left: 150px;
    }
    .search-bar input {
        padding: 5px;
        border: none;
        border-radius: 5px 0 0 5px;
        background-color: #585656;
        color: white;
        
    }
    .search-bar button {
        padding: 5px 10px;
        border: none;
        border-radius: 0 5px 5px 0;
        background: red;
        color:white;
        cursor: pointer;
        
    }
    .content{
position: absolute;
top: 52%;
left: 30%;
transform: translate(-50%,-50%);
color: #fff;
text-align: center;

}

form {
border: 3px solid white;
padding: -0.2px;
border-radius: 15px;
}

form input[type=text], input[type=email] {
background: none;
padding: 10px 14px;
margin: 8px 0;
color: white;
display: inline-block;
border: 1px solid white;
box-sizing: border-box;
border-radius: 5px;
width: 200px;
}
form input[type=button]{
border-radius: 20px;
color: white;
background-color: red;
padding: 8px 30px 8px 30px;
}
.container {
padding: 10px 20px;
}

.content1{
position: absolute;
top: 52%;
left: 180%;
transform: translate(-50%,-50%);
color: #fff;
text-align: left;
border: 3px solid white;
padding: 20px;
border-radius: 15px;
width: 220px;
}
footer {
        background: red;
        text-align: center;
        font-size: 15px;
        padding: 1px;
        position: fixed;
        width: 100%;
        bottom: 0;
    }
</style>
</head>
<body>
    <header>
    <div class="header">
        <div class="logo">
            <span class="red">R</span><span class="white">OOP</span><span class="red">T</span><span class="white">ECH</span>
        </div>
        <div class="nav">
            <a href="index.html">Home</a>
            <a href="product.html">Products</a>
            <a href="people.html">People</a>
            <a href="contact.html">Contact</a>
            <div class="search-bar">
                <input  type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </div>
    </div>
</header>
    <main>
    <div class="content">
    <form  method="get">
                    
        <div class="container">
            <h1 style="font-weight: bold" >Contact us</h1>
            <input type="text" placeholder="Your Name" name="uname" required><br>
            <input type="email" placeholder="Your Email" name="email" required>
            <div style="padding: 20px 10px;">
               <input type="button" value="Submit">
            
            </div>
        
    </form>
    
    </div>
    <div class="content1">
        <h2 >Contact Information</h2>
        <p><strong class="red">Address:</strong> FCA Building No. 18, ROOP DEVELOP CITY, Phase-I, CHENNAI HR IN 1888546</p>
        <p><strong class="red">Email:</strong> rooptech@gmail.com</p>
        <p><strong class="red">Phone:</strong> 7854216557</p>
    </div>
   </main>
    <footer>
        <p>DESIGNED AND DEVELOPED MOHANRAJ(212221230064)</p>
    </footer>
</body>
</html>
```

## OUTPUT:
![Screenshot 2024-07-17 105744](https://github.com/user-attachments/assets/d34b3937-d67d-4f8c-9485-4d390051fb6d)




