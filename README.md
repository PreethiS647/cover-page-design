# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

## Step 1:
Create a new Django project and app.

## Step 2:
Create a static file directory and mention the changes in settings.

## Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

## Step 4:
Write down the code for book cover using HTML and CSS.

## Step 5:
Add images and other contents using CSS record a screenshot of it.
## Code:
<html>

<head>
    
    <style>
        .bookpage{

            width: 400px;
            height: 650px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-color: rgb(0, 0, 0);
            background-size: cover;
            background-image: linear-gradient(to bottom right, pink, yellow);
        }
            
        
        .insight{
            color:bisque;
            background-image: linear-gradient(to bottom right, red, yellow);
        
        }
        
        
        .hrstyle{
            width:100px;
            background-image: linear-gradient(to bottom right, red, yellow);
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(217, 191, 191);
            top:280px;
            
            font-family:Georgia;
            font-size: medium;
            background-image: linear-gradient(to bottom right, red, yellow);
        }
        .booktitle{
            color:aqua;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 25px;
            background-image: linear-gradient(red, yellow);
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            background-image: linear-gradient(to bottom right, red, yellow);
           
        }
        .pub{
            color:cornflowerblue;
            font-size: medium;
            position: relative;
            top:250px;
            left:330px;
            
        }
        .ed{
            color:greenyellow;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:180px;
            background-image: linear-gradient(to bottom right,blue , yellow);
        
        }
        .subtitle{
            color:aquamarine;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 60px;
            background-image: linear-gradient(to bottom right, red, yellow);
        }
        
        .mypic{
            position: relative;
            top: 275px;
            left: 320px;
            width: 70px;
            height: 80px;
            background-size:contain;
            background-image: linear-gradient(to bottom right, red, yellow);
        }
    
.bookpage{
background-image:url(images\ \(2\).jpeg);
}
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        
        <div class="bookpage">
            <div class="insight">
                COMPUTER
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>FUNDAMENTALS of COMPUTERS</h1></div>
            <div class="subtitle">
                 BEGINNERS CRASH COURSE [Day 1 to Day 100]
                 <br>
                 CODING DATA, PYTHON,ALGORITHMS AND HACKING.
                </div>
            
            <div class="mypic">
                <img src="author11.jpeg" width="70" height="80" >
            </div>
            <div class="id">
                <hr style="color:rgb(13, 128, 0)">
            </div>
            <div class="author">
               <p><b>PREETHI S</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>FIRST EDITION</b>
            </div>
        </div>
        </body>
</html>

## Output:
![image](https://github.com/PreethiS647/cover-page-design/assets/147313372/519b026e-086c-4932-89eb-e3095690420f)



## Result:
Thus the program to develop a website to display the cover page design of a book is done.
