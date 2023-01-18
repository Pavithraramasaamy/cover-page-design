cover-page-design

AIM:

To develop a website to display the cover page design of a book


Design Steps:


Step 1:

Create a new Django project and app.


Step 2:


Create a static file directory and mention the changes in settings.


Step 3:

Make a new folder templates inside your app and create a html and map them using views and url.


Step 4:

Write down the code for book cover using HTML and CSS.

Step 5:

Add images and other contents using CSS record a screenshot of it.

Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
          width: 400px;
          height: 600px;

          color:blueviolet;
          margin-left: auto;
          margin-right: auto;
          padding: 20px;
          font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
          background-image:url(/static/images/images.jpeg);
          background-size: cover;

        }

        .insight{
            color:white;


        }

        .hrstyle{
            width: 30px;

        }
        .author{
            color:yellowgreen;
            display: inline;
            position: relative;
            color: red;
            top: 190px;


            font-family: Georgia;
            font-size: medium;

        }

        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: large;
            text-align: inherit;
            position: relative;
            top: 30px;

        }
        .id{
            width: 400px;
            position: relative;
            top: 180px;


        }
        .pub{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }
        .ed{
            color:pink;
            font-size: large;
            font-family: Verdana;
            position: relative;
            top: 65px;

        }
        .subtitle{
            font-family: Tahoma;
            font-size: medium;
            position: relative;
            top: 10px;

        }
        .mypic{
            position: relative;
            top: 220px;
            left: 320px;
            width: 100px;
            height: 100px;
            background-size: cover;

        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:white;">
            </div>
            <div class="booktitle">
                <h1> Responsive Web Design with HTML5 and CSS </h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest  HTML5 and CSS techniques
            </div>
            <div class="mypic">
                <img src="/static/images/my.jpeg" width=" 65" height="70"alt="">
            </div>
            <div class="id">
                <hr style="color:blue;">
            </div>
            <div class="author">
                <p><b>Pavithra</b></p>
            </div>
            <div class="pub">
                Packt>
            </div>
            <div class="ed">
                <b>Third Edition</b>
            </div>


        </div>
    </body>
</html>
```


## OUTPUT:

![](./output.png)

## HTML Validator:

![](./valid1.png)


## RESULT:

The program for designing book cover page using HTML and CSS is executed successfully
