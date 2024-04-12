# CSS Summary

 In this summary I will go over a few key attributes about CSS and some of the things you are able to do with it.
I will be answering the following questions:

* What is CSS?
* What are the three ways to insert CSS into your project?
* Write an example of a CSS rule that would give all <p> elements red text.

After i hope you will have a better understanding of how CSS works.

## What is CSS and it's Purpose

CSS (Cascading Style Sheets) is a design or styling language that helps make websites more appealing.   

The purpose of CSS is to take plain text documents and turn them in to eye catching and inspiring websites. The language applies CSS rules that create the ability to style the document by adding pictures, changing the color and size of the text as well as backgound color. All of this so you're able to see the great websites you see today.

## Three ways to insert CSS into a project

There are three ways to insert Cascading Style sheets into a project. 

* External CSS
* Internal CSS
* Inline CSS

### *External CSS*: 
 Gives the ability to change the look of an entire website by changing one file! To do this you must include a reference to the external style sheet file by adding a link element in the Head section that looks like this: *link rel="stylesheet" href="Style.css"*. And now you're able to style in different manners using the external style sheet.

### *Internal CSS*:  
The Internal Style sheet may be used if one single HTML page has a unique style. The internal style is defined inside the style> element, inside the head section, that looks like this body background color update:


*!DOCTYPE html>  
html  
head>  
<style*  
    body {  
        background-color: linen;  
    }

H1 {  
    color: maroon;  
    margin-left: 40px;  
}

### *Inline CSS*:  
Are used to style a single element. To use you must add the style attribute to the relevant element, like this:


!DOCTYPE html>  
html>  
body>

H1 style="color:blue;text-align:center;">This is a heading</>
p style="color:red;">This is a paragraph.</p>

/body>  
/html>   



### *Paragraph color text rulle example:   

p {  
    color: rgb(197, 9, 9);  
}  

<H1 style="color:red;">The API includes 4 functions: phrase - Returns a String of a set of unformatted coder ipsum "words". Optionally input the number of "words" to include. sentence - Returns a String of a set of coder ipsum "words" in the format of a sentence - with capitalization and period punctionation. Optionally input the number of "words" to include. paragraph - Returns a String of a set of coder ipsum "words" in the format of a paragraph with multiple sentences, including capitalization and period punctionation. 