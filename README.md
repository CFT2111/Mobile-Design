# Responsive Web Design

* Download *xyz.html*.
* Open it in a text editor and a web browser
* In the browser, view the page in responsive mode

## Using the viewport meta tag
+ Add a viewport meta tag in the head of the document and save the document
```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```
+ Open up a new tab and view the HTML page. 
    * Note the effect of the viewport tag. The page contents should be scaled to fit the browser window better. 
    * Try viewing two versions of the same page side by side, one with the viewport tag and one without to see the effect. 

## Using Media Queries
+ Create two separate CSS files. 
+ Each CSS file should contain a single simple rule e.g. changing the background colour of the page. Make sure the rule is different in each page. 
+ Name the two files *style1.css* and *style2.css*. In the HTML document add two link elements:
```html
<link rel="stylesheet" type="text/css" href="style2.css" media="screen and (max-width: 480px)" >
<link rel="stylesheet" type="text/css" href="style1.css" media="screen and (min-width: 481px)" >
```
+ Test the page in a browser. The browser should switch between different the different CSS files depending on the browser width. 

## Design the site
Start thinking about the design of the site and how it might differ for different sized displays. 
+ First think about mobile. 
    + Make the hyperlinks easy to select if the user is using a finger. Make your tap targets at least 50px by 50px. 
    + You shouldn't have to do too much to the layout - a single column works best on mobile. 
+ Next think about the design for a large screen display.
    * Make the navigation options into a navigation bar i.e. align them horizontally in the header. 
    * Can you make a two-columned design. The *section* and *aside* elements should form the two columns. Set the header and footer to the full width of the browser. 
    