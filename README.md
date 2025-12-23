# Ex.05 Book Cover Page Design
## Date:22-12-2025

## AIM:
To design a book back cover page using HTML and CSS.

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
        <title>Coverpage</title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <body>
        <div class="box1">
            <h1>Cyber has Security</h1>
            <hr>
            <p>Cyber has Security Cyber Security is the practice of protecting computers, networks, systems, and data from digital attacks, theft, damage, or unauthorized access. It helps keep information safe from hackers, viruses, malware, and cybercriminals.</p>
        <br><br>
            <div class="box2">
                "Cybersecurity is not just about protecting systems and networks; it is about protecting people, trust, and the future of the digital world."
        </div>
            <br><br><br>
        <div class="box3">
            <img src="Mot.jpeg">
            <div class="info">
                <h3>Mothissh</h3>
                <font>"Mothissh is an aspiring cyber security student. She is passionate about understanding how digital systems work and how they can be protected from cyber threats. Through learning about cyber security, she aims to develop strong skills in safeguarding data, networks, and online privacy, and hopes to contribute to a safer digital future."</font>
            </div>
        </div><br><br>
            <div class="box4">
                <h4>SEC Publisher</h4>
                <h4>Printed in Barbieworld</h4>
                <div class="amount">
                    <h5>Price: &#8377 1000</h5></div>
                </div>
            </div>
    </body>
</html>

styles.css

.box1
{
    height: 100%;
    width: 45%;
    border: solid 3px;
    margin-left: 365px;
    padding-bottom: 100px;
    margin: auto;
    border-radius: 15px;
    background:linear-gradient(rgb(226, 12, 47),rgb(80, 91, 91))
}
.box2
{   
    border-left: solid 2px;
    width: 500px;
    padding: 20px;
    margin: auto;
    background-color: rgb(221, 22, 92);
    display: flex;
    text-align: center;
}
.box3
{
    width: 500px;
    margin: auto;
    border: solid 2px;color: rgb(255, 255, 255);
    background-color: rgb(205, 17, 39);
    display: flex;
    text-align: center;
}
.info
{
    display: flex;
    flex-direction: column;
}
h1{
    margin: auto;
    padding-left: 10%;
    padding-top: 5%;
}
img{
    height: 190px;
    width: 130px;
}
.box4
{
    padding: 15px;
    width: 400px;
    margin: auto;
    background-color:rgb(255, 0, 251);
    border: solid 3px;
    border-radius: 5px;
}
.amount
{
    display: flex;
    flex-direction: row-reverse;
}
h5
{
    font-size: 15px;
}
hr{
    color: whitesmoke;
    border: solid 3px;
}
h2
{
    margin-left: 15px;
}
p{
    margin: auto;
    text-align: center;
    width: 600px;
}

```

## OUTPUT:
![alt text](<Screenshot 2025-12-22 162829.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
