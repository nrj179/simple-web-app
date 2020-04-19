# simple-web-app

        top
        
        margin
left    border      right
        padding
        content
    
        bottom
        
Content -> Everythin goes insidex content box. e.g. Images, txt, video. 
Every web page has these four boxes arount it. Padding, Border, Margin are invisible by default.
Padding is used to generate spaces around content.
Margin is also used to generate space around content but outside border box.

class & Id

Javascript:
JavaScript is a programming language used to make web pages interactive. It is a client side programming language and runs inside browser.

JQuery
jQuery is a Javascript library.

you can download jQuery from jquery.com and add to your html file head section using below code.
<script src="js/jquery-3.5.0.js"></script>

Bootstrap Framework
Bootstrap is the most popular HTML, CSS and JS framework for developing responsive, mobile first projects on the web.
officila website : getbootstrap.com.
    Download from 'compiled css and js' section. A zip file will be downloaded, extract it and at first we need only two files.
    bootstrap.min.css and bootstrap.min.js. and add it using below lines
    <link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
        <script src="js/bootstrap.min.js"></script>
        
    ** Bootstrap's JavaScript requires jQuery. jQuery must be included before Bootstrap's JavaScript.
    

Bootstrap Grid system
it allows up to 12 columns across the page. You can group columns together to get wider system if you dont want to use it individually.
Columns will rearrange automatically depending on the screen size.
Bootstrap Grid is made up of 3 things
    1. Container
    2. Rows
    3. Columns
e.g.
    <div class="container">
        <div class="row">
            <div class="col-*-*">
                // content goes here
            </div>
        </div>
    </div>
    // Column number should be add up to 12 for each row