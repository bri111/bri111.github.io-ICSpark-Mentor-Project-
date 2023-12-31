# Red Velvet Cookies Recipe


## Objective
Use CSS Flexbox to a website about Red Velvet Cookies Recipe (Responsive layout structure, parent/child nodes). 

## Difficulty
Intermediate

## Prerequisites
To complete this project: students should have the following:
- Basic understanding of HTML structures and attributes
- Basic understanding of CSS (Selectors, properties)

## Concepts
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

## Your Challenge


#Part I: Complete HTML

1. Headings: Copy and Paste the ```<head></head>``` with the code below. 

```
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>replit</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Open+Sans:ital,wdth,wght@0,83.2,524;0,100,300;0,100,400;0,100,700;0,100,800;1,100,800&family=Spartan&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wdth,wght@0,83.2,524;0,100,300;0,100,400;0,100,700;0,100,800;1,100,800&family=Spartan&display=swap" rel="stylesheet">
</head>

```

2. Use this recipe to fill out the content of your website:
   - https://sallysbakingaddiction.com/red-velvet-chocolate-chip-cookies/
   - This is your recipe for the week or you can find a recipe online of your choosing
   - Create a ```<h1></h1>``` for your title
   - Create a ```<p class="author">``` for your name

3. Add an image into your webpage using the ```img``` tag
   - Create a ```<h1></h1>``` for your title
   - Create a ```<p class="author">``` for your name
   - Add  ``` <img src="https://drive.google.com/uc?export=view&id=13qYykjvPWZurnw2W1tMGjo9B-HbVT2G-" alt="girl on top of red velvet cookies" width ="200px">```

4. Create the following sections inside the ```<body>``` tag to describe the recipe

```
<section class="about">
<!----"p1" can be changed into anything you like, you can even say "paragraph1"---->
    <p>A friend of mine loves red velvet cookies and decided to draw a picture of her standing on a stack of red velvet cookies.
<!----break separates sentences from each other---->
      <br> Being inspired by this image, I wondered how does one actually make red velvet cookies.</p>
```

  * ```section``` with a ```class``` of "about"
    *   ```p``` about the reason for your recipe

  * ```section``` with a ```class``` of "ingredients"
    * ```h2``` title of the section for ingredients
    * ```ul``` and ```li``` start creating the list of ingredients

* ```section``` with a ```class``` of "steps"
  * ```h2``` title of the section for steps
  * ```ol``` and ```li``` start creating the list of steps

5. Within this [first, second, third] section, create and img tag and set the src attribute to [link] and alt attribute to [description]

* ```section``` with a ```class``` of "row"
* Within this section there is another section 
  * ```section``` with a ```class``` of "column"
    * ```<img src="https://sallysbakingaddiction.com/wp-content/uploads/2013/12/red-velvet-chocolate-chip-cookies-5.jpg" alt="red velvet chocolate chip cookies 5">``` 
  * ```section``` with a ```class``` of "column"
    * ```<img src="https://sallysbakingaddiction.com/wp-content/uploads/2013/12/red-velvet-chocolate-chip-cookies-3.jpg" alt="red velvet chocolate chip cookies 3">``` 
  * ```section``` with a ```class``` of "column"
    * ```<img src="https://sallysbakingaddiction.com/wp-content/uploads/2013/12/red-velvet-chocolate-chip-cookies-4.jpg" alt="red velvet chocolate chip cookies 4">``` 

<br>Part II: Complete CSS
<br>
Use the CSS properties above to design your website in the CSS file
</br>
* Note: the # is where you input a digit/number

1. Start with your body be selecting the body tag followed by {}
  - ```background-color:``` //Set the background-color to #75201a or a color of your choice;
  - ```color:``` //Set the font-color to a color of your choice;
2. Set [heading 1] to [value] or a value of your choice 
  - ```text-align:``` center; //center your title
  - ```font-family:``` 'Bebas Neue', cursive; // or font of your choice
  - ```letter-spacing:``` #px;
 - ```font-size:``` #px;
3. Set [.about 1] to [value] or a value of your choice  // Selects all elements set within its class/section attribute
  - ```text-align:``` center;
  - ```display:``` flex;
  - ```justify-content:``` center;
4. Set [padding] to [value] or a value of your choice  //padding is used for space between content and borders
  - ```padding-left:``` #px;
  - ```padding-right:``` #px;
  - ```padding-top:``` #px;
  - ```padding-bottom:``` #px;
  - ```font-family:``` 'Open Sans', sans-serif;
5. Set [.column] to [value] or a value of your choice  // adds columns to your images 
  - ```float:``` left;
  - ```width:``` #%;
  - ```padding:``` #%;
6. Set [.row::after] to [value] or a value of your choice // clearfix (clear floats)
  - ```content:``` "";
  - ```display:``` table;
7. Set [.container] to [value] or a value of your choice // this holds the images given to us
  - ```font-family:``` 'Bebas Neue', cursive;
  - ```max-width:``` #px;
  - ```margin:``` auto;
  - ```height:``` #%;
  - ```display:``` flex;
  - ```align-items:``` center;
  - ```justify-content:``` center;
  

## Citation
Definitions found: https://www.w3schools.com/cssref/index.php
<br>Cookie Recipe found: https://sallysbakingaddiction.com/red-velvet-chocolate-chip-cookies/
 

## Project Results:
<img class="ui image" src="img/redvelvet1.png">
<img class="ui image" src="img/redvelvet2.png">
<img class="ui image" src="img/redvelvet3.png">

