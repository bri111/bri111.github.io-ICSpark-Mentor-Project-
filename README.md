# bri111.github.io-ICSpark-Mentor-Project


ICSpark Mentor Project: https://bri111.github.io/red-velvet-cookies/

# Objective
Use CSS Flexbox (Responsive layout structure, parent/child nodes)

# Difficulty
Intermediate

# Prerequisites
To complete this project: students should have the following:
- Basic understanding of HTML structures and attributes
- Basic understanding of CSS (Selectors, properties)

# Concepts
| HTML | Description |
| --- | --- |
| img | image tag |
| p | paragraph tag |
| br | breaks the line of the sentance |
| h1 | heading 1 |
| h2 | heading 2 |
| element | An element is an individual part, or a building block, of a web page |
| attribute | A modifier of an element |
| div | A container element |
| ul | An unordered list element |
| ol | An ordered list element |
| li | A list item element |
| section | A tag that defines a section |

| Relative File Paths	 | Description |
| --- | --- |
| images/picture.jpg	 | In the images images folder, points to the picture.jpg |


| CSS | Description |
| --- | --- |
| background-color | Specifies the background color of an element |
| text-align | Specifies the horizontal alignment of text |
| font-family | Specifies the font family for text |
| letter-spacing | Increases or decreases the space between characters in a text |
| font-size | Specifies the font size of text |
| justify-content | Specifies the alignment between the items inside a flexible container when the items do not use all available space |
| display | Specifies how a certain HTML element should be displayed |
| margin-left | Sets the left margin of an element |
| margin-right | Sets the right margin of an element |
| float | Specifies whether an element should float to the left, right, or not at all |
| padding | A shorthand property for all the padding-* properties |
| margin | Sets all the margin properties in one declaration |
| align-items | Specifies the alignment for items inside a flexible container |

# Your Challenge
Part I 
<br>To Complete Part I, complete these requirements:


<br>Part II
1. Create HTML elements below
 * headers
 * sections labelling them by classes (example: <section class="about">
 * create an about this recipe section
 * (ol) ordered and (ul) unordered lists for ingrediates and instructions
 * add images using img tag

2. Headings: 
This part should appear like this in your HTML file:

```
<head> /** Within the <head> add these two */
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Open+Sans:ital,wdth,wght@0,83.2,524;0,100,300;0,100,400;0,100,700;0,100,800;1,100,800&family=Spartan&display=swap" rel="stylesheet">

  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wdth,wght@0,83.2,524;0,100,300;0,100,400;0,100,700;0,100,800;1,100,800&family=Spartan&display=swap" rel="stylesheet"></head>
<h1>Insert Title</h1>

```

3. Use this recipe:
* https://sallysbakingaddiction.com/red-velvet-chocolate-chip-cookies/
* This is your recipe for the week or you can find a recipe online of your choosing

4. Use these tags in your HTML file
Containers or sectors
* ```section``` with a ```class``` of "about"
  * ```p``` about the reason for your recipe

* ```section``` with a ```class``` of "ingredients"
  * ```h2``` title of the section for ingredients
  * ```ul``` and ```li``` start creating the list of ingredients

* ```section``` with a ```class``` of "steps"
  * ```h2``` title of the section for steps
  * ```ol``` and ```li``` start creating the list of steps

5. Create columns for 3 images

* ```section``` with a ```class``` of "row"
* Within this section there is another section 
  * ```section``` with a ```class``` of "column"
    * ```<img src="https://sallysbakingaddiction.com/wp-content/uploads/2013/12/red-velvet-chocolate-chip-cookies-5.jpg" alt="red velvet chocolate chip cookies 5">``` 
  * ```section``` with a ```class``` of "column"
    * ```<img src="https://sallysbakingaddiction.com/wp-content/uploads/2013/12/red-velvet-chocolate-chip-cookies-3.jpg" alt="red velvet chocolate chip cookies 3">``` 
  * ```section``` with a ```class``` of "column"
    * ```<img src="https://sallysbakingaddiction.com/wp-content/uploads/2013/12/red-velvet-chocolate-chip-cookies-4.jpg" alt="red velvet chocolate chip cookies 4">``` 

<br>Part III
<br>
Use the CSS properties above to design your website in the CSS file
</br>
* Note: the # is where you input a digit/number

1. Start with your body by using body {}
  - ```background-color:``` #color of your choice;
  - ```color:``` #color of your text;
2. heading 1
  - ```text-align:``` center; //center your title
  - ```font-family:``` 'Bebas Neue', cursive; // or font of your choice
  - ```letter-spacing:``` #px;
 - ```font-size:``` #px;
3. .about // Selects all elements set within its class/section attribute
  - ```text-align:``` center;
  - ```display:``` flex;
  - ```justify-content:``` center;
4. padding // padding is used for space between content and borders
  - ```padding-left:``` #px;
  - ```padding-right:``` #px;
  - ```padding-top:``` #px;
  - ```padding-bottom:``` #px;
  - ```font-family:``` 'Open Sans', sans-serif;
5. .column // adds columns to your images
  - ```float:``` left;
  - ```width:``` #%;
  - ```padding:``` #%;
6. .row::after // clearfix (clear floats)
  - ```content:``` "";
  - ```display:``` table;
7. .container // this holds the images given to us
  - ```font-family:``` 'Bebas Neue', cursive;
  - ```max-width:``` #px;
  - ```margin:``` auto;
  - ```height:``` #%;
  - ```display:``` flex;
  - ```align-items:``` center;
  - ```justify-content:``` center;
  

# Citation
Definitions found: https://www.w3schools.com/cssref/index.php
<br>Cookie Recipe found: https://sallysbakingaddiction.com/red-velvet-chocolate-chip-cookies/
  
# Replit Website 
* Fork this website (has images 
<br>https://replit.com/join/bvbaaofyyz-blarbbarb
