# Project 0
===========
Web Programming with Python and JavaScript


Requirements
============

Design a personal webpage about yourself, one of your interests, or any other topic of your choice. The subject matter, look and feel, and design of the site are entirely up to you, subject to the following 

* Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
* Your website must include at least 
    one list (ordered or unordered), 
    at least one table, and 
    at least one image.
* Your website must have at least one stylesheet file.
* Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
* Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.

* You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.

* Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.

* In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.
===============================================================

            <ul> 
                <li>Design a personal webpage about yourself, one of your interests, or any other topic of your choice.</li>

                <li>Your website must contain at least four different .html pages</li>

                <li>it should be possible to get from any page on your website to any other page by following one or more hyperlinks.</li>

                <li> Your website must include at least</li>
                    <ul> 
                        <li>one list (ordered or unordered),</li>
                        <li>at least one table, and</li>
                        <li>at least one image.</li>
                    </ul>
                </li>
                
                <li>Your website must have at least one stylesheet file</li>
                     <ul> 
                        <li>at least five different CSS properties, and</li>
                        <li>at least five different types of CSS selectors.</li>
                        <li>at least one image.</li>
                    </ul>               
                <li>Your stylesheet(s) must use
                
                </li>
                
                <li>You must use the #id selector at least once.</li>
                
                <li>You must use the .class selector at least once.</li> 
                
                <li>Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.</li> 
                
                <li>You must use Bootstrap 4 on your website, taking advantage of
                    <ul> 
                        <li>at least one Bootstrap component, and</li>
                        <li>at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.</li>
                    </ul>                
                </li> 
                
                <li>You must have an SCSS stylesheets with
                    <ul> 
                        <li>at least one SCSS variable,</li>
                        <li>at least one example of SCSS nesting, and</li>
                        <li>at least one use of SCSS inheritance.</li>
                    </ul>                
                </li>
                 
                <li>In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.</li>                 
            </ul> 

===============================================================
<!DOCTYPE html>
<html>
    <head>
        <title>Project 0</title>
        
        <!-- include Bootstrap -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">        
        <link   rel="stylesheet"  href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <!-- Menu -->
        <nav class="navbar navbar-expand-lg navbar-light ">
            <p class="navbar-text">Menu:</p>
            <ul class="nav navbar-nav">
                <li><a href="index.html">Home</a></li>
                <li><a href="list.html">Requirements</a></li>
                <li><a href="table.html">Colors</a></li>
                <li><a href="image.html">Image</a></li>
            </ul>      
        </nav>   

        <!-- Content -->
        <div class="container"> 
            <div class="row"> 
                <h1>Requirements</h1>
            </div>        
            <div class="row">
                
            <ul> 
                <li>Red</li>
                <li>Yellow</li>
                <li>Blue</li>
                <li>Green</li>
                <li>Orange</li>
                <li>Purple</li>
                <li>Black</li>
                <li>more colors
                    <ul> 
                        <li>Red</li>
                        <li>Yellow</li>
                        <li>Blue</li>
                        <li>Green</li>
                        <li>Orange</li>
                        <li>Purple</li>
                        <li>Black</li>           
                    </ul>
                </li>                                             
            </ul>            
                
            </div>
           
        </div>            
            
    </body>
</html>













===============================================================
<!DOCTYPE html>
<html>
    <head>
        <title>My Webpage</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <!-- Menu -->
        <div class="menu">
            <a href="index.html">Home</a>
            <a href="list.html">List</a>
            <a href="table.html">Table</a>
            <a href="image.html">Image</a>
        </div>

        <h1>List</h1>

        <div id="list">
        <h2>Colors</h2>
        <ul> 
            <li>Red</li>
            <li>Yellow</li>
            <li>Blue</li>
            <li>Green</li>
            <li>Orange</li>
            <li>Purple</li>
            <li>Black</li>
            <li>White</li>                                             
        </ul>
    </div>
    </body>
</html>











