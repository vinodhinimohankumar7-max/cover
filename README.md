# Ex.05 Book Cover Page Design
## Date:15.12.2025

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
        <title>cover</title>
        <link href="mohan.css" rel="stylesheet">
    </head>
    <body>
        <div class="container">
            <h2>About the Book</h2>
            <hr size="3"; color="red">
            <p align="justify">
                <font size="4">
                This book <span class="highlight">"Artificial intelligence"</span>
                provides information about in a field of computer science focused on creating machines that mimic human cognitive functions like learning, reasoning, problem-solving, and language understanding, enabling them to perform tasks requiring intelligence, such as analyzing data, recognizing speech, and making decisions. AI systems learn from vast amounts of data, identify patterns, and use logic to make predictions or take actions, improving accuracy over time. 
            </font>
            </p>
        <div class="quote">
            <font size="4"; color="green">
            "The future of AI is not about replacing humans,but augmenting human capabilities."
            </font>
        </div>
        <div class="author-box">
            <img src="author.jpg" alt="Author"class="author-img">
        
        <div>
            <h3>M.K.Vinodhini</h3>
            <p>
                M.K.Vinodhini is a student studying in saveetha engineering college b.tech AIDS department, one who is enthusiastic and friendly.
            </p>
        </div>
        </div>
        <br></br>
        <div class="footer">
            <span><strong>SEC Publishers</strong>-Printed in India</span>
            <span class="price">Price:Rs.500</span>
        </div>

    </body>
</html>
```
```
mohan.css

body
{
    background: white;
    background-size: contain;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.container {
    height:700px;
    width: 500px;
    margin: 40px auto;
    background-image:url(lite.jpg);
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 0 15px rgba(0,0,0,0.1);
}

.highlight {
    background: yellow;
    padding: 2px 5px;
}

.quote {
    background: #eaf3ff;
    border-left: 4px solid #5a8dee;
    padding: 15px;
    font-style: italic;
    margin: 20px 0;
}

.author-box {
    display: flex;
    gap: 15px;
    background: #f7faff;
    padding: 15px;
    border-radius: 8px;
}

.author-img {
    width: 70px;
    height: 80px;
    border-radius: 5px;
}

.footer {
    margin-top: 25px;
    background: #003c8f;
    padding: 15px;
    color: white;
    border-radius: 8px;
    display: flex;
    justify-content: space-between;
}

.price {
    font-weight: bold;
    color: #ffeb3b;
}
```


## OUTPUT:
![alt text](<yamu/Screenshot (38).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
