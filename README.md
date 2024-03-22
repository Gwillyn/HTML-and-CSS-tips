**HTML-and-CSS-tips**  
Check attached branches for small project demonstrations of concepts.

**HTML**




**CSS**  
  
class~="" indicates the class can INCLUDE the set variable 
    
Before every doc, you can set the scroll behavior to smooth with:  
* {    
  scroll-behavior: smooth;  --scroll behavior to smooth--   
  box-sizing: border-box;  --elements include padding and border in their specified width and height--   
}  

position: static <!--default positioning for all elements. If you assign it to an element, you won't be able to move it around with top, right, left, or bottom-->   
position: relative <!--positioned according to the normal flow of the document, but the top, left, bottom, and right values become active-->  
position: absolute <!--element is taken out of the normal flow of the document, and then its position is determined by the properties-->  
position: fixed <!--element fixed to the page no matter where the user scrolls to on the page...-->  
position: sticky <!--hybrid of relative and fixed... stick to a specific position within its containing element or viewport, based on the scroll position-->  
  
transform: translate(), rotate(), scale(), skew(), and matrix() <!--modify the shape, position, and size of an element without changing the layout or affecting the surrounding elements-->  
  
  

    z-index is a property you can use to define the order of overlapping HTML elements. Any element with a higher z-index will always be positioned over an element with a lower z-index  
  
        
![diagram-3](https://github.com/Gwillyn/HTML-and-CSS-tips/assets/163878088/2aed9225-ebc8-419f-bfe4-87bf85b9d660)  
        This diagram represents the spacing of elements. (margin, border, padding, height, content, width).  
  
nav {  
  width: 50%;  
  max-width: 300px;  
  height: 50px;  
}  
  
nav > ul {  
  display: flex;  
  justify-content: space-evenly;  
}  

nav > ul > li {  
  color: #dfdfe2;  
  margin: 0 0.2rem;  
  padding: 0.2rem;  
  display: block;  
}  

nav > ul > li:hover {  
  background-color: #dfdfe2;  
  color: #1b1b32;  
  cursor: pointer;  
}    
  
This code demonstrates the ability to change the interactive elements, for example, anchor links to be more interactive.  
hence the white background and color change.  
<img width="290" alt="image" src="https://github.com/Gwillyn/HTML-and-CSS-tips/assets/163878088/14e84493-bd70-42a6-a6a7-3d48088be32b">    
   
  
@media at-rule, also known as a media query, is used to conditionally apply CSS. Media queries are commonly used to apply CSS based on the viewport width using the max-width and min-width properties:  
  
@media (max-width: 960px) {
  .card {
    padding: 2rem;
  }
}  
**This padding is applied to the .card class when the viewport is 960px wide and below**  
a media query that targets a display width between 500px and 1000px would be:  
@media (min-width: 500px) and (max-width: 1000px){}  

