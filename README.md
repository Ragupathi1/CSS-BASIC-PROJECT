### HTML AND CSS PAGE TO RE-CREATE THE IMAGE

### AIM:
To re-create a HTML and CSS page based on the given image.

### HTML CODE
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - RoopTech</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>ROOPTECH</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">People</a></li>
                <li><a href="#" class="active">Contact</a></li>
            </ul>
        </nav>
        <div class="search-container">
            <input type="text" placeholder="Enter to Search">
            <button>Search</button>
        </div>
    </header>
    <main>
        <div class="container">
            <div class="contact-form">
                <h2>Contact Us</h2>
                <form>
                    <input type="text" name="name" placeholder="Your Name" required>
                    <input type="email" name="email" placeholder="Your Email" required>
                    <button type="submit">Submit</button>
                </form>
            </div>
            <div class="contact-info">
                <h2>Contact Information</h2>
                <address>
                    3RD Floor, Tower 12, FCA Building<br>
                    No.18, ROOP DEVELOP CITY Phase-I<br>
                    SECUNDERABAD HR IN 1888546
                </address>
                <p>Email: <a href="mailto:rooptech.official@gmail.com">rooptech.official@gmail.com</a></p>
                <p>Phone: 1234567890</p>
            </div>
        </div>
    </main>
    <footer>
        <p>DESIGNED AND DEVELOPED BY RAGU (212221040135)</p>
    </footer>
</body>
</html>

~~~
### CSS CODE
~~~
body {
    font-family: Arial, sans-serif;
    background:  url('backround image.jpg') no-repeat center center fixed;
    background-size: cover;
    color: rgb(12, 11, 11);
}

header {
    text-align: center;
    padding: 20px 0;
    background: #101010;
}

header h1 {
    color: rgb(65, 32, 183);
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

nav ul li a.active {
    color: rgb(15, 156, 216);
}

.search-container {
    text-align: center;
    margin-top: 10px;
}

.search-container input {
    padding: 10px;
    border: 1px solid #fff;
    border-radius: 5px;
}

.search-container button {
    padding: 10px;
    background: rgb(43, 85, 224);
    border: none;
    color: #fff;
    cursor: pointer;
    border-radius: 5px;
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: calc(100vh - 150px);
}

.contact-form, .contact-info {
    border: 2px solid #fff;
    padding: 20px;
    margin: 10px;
}

.contact-form {
    flex: 1;
    max-width: 300px;
    text-align: center;
}

.contact-form input, .contact-form button {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #27b0bc;
    border-radius: 5px;
}

.contact-form button {
    background: rgb(13, 107, 196);
    color: #fff;
    border: none;
    cursor: pointer;
}

.contact-info {
    flex: 1;
    max-width: 400px;
}

.contact-info address, .contact-info p {
    margin: 0 0 10px;
}

.contact-info p a {
    color: rgb(112, 12, 234);
    text-decoration: none;
}

footer {
    text-align: center;
    padding: 10px;
    background: rgb(13, 83, 224);
    color: #000;
}


~~~
### OUTPUT

![image](https://github.com/Ragupathi1/CSS-BASIC-PROJECT/assets/143526042/c3754890-df44-4840-856e-a27fa4564f1f)


### RESULT:
Thus the program has been completed successfully.
