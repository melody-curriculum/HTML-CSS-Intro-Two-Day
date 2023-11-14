# Introduction to HTML & CSS Workshop 
--
## Installation
- Install [Sublime Text](http://www.sublimetext.com/)
	- Sublime Text is a text-editor for code.  

## What is front-end web development?
- Everything your eyes can see on the page. 
- Composed of HTML, CSS, and JavaScript.
- A front-end developer will take the work of a designer, and code it on the front-end so a back-end developer can build on top of that. 

### What is HTML? 
- Stands for: Hyper Text Markup Language.
- It is the content of the page. 
	- e.g. header or paragraph
- Has its own default styles. 

### What is CSS?
- Stands for: Cascading Style Sheet. 
- It is the stylistic component of the page. 
- Overrides the default styles of HTML. 
	- e.g. change the color or the font-family of your header

### What is JavaScript?
- Helps increase interactivity of the page. 
- Helps with page interactions such as animations 
- Helps with dynamic loading of content. 

## Let's Dive Deeper
### HTML:
#### Tags < >
- Allow you to set up structure of the page. 
- Tell the browser how to format content. 

`<h1>Hello World!</h1>`

#### Basic layout for an HTML file

```
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>My First Webpage</title>
</head>
<body>
	<h1>Hello World!</h1>
</body>
</html>

```
### CSS:
- In order to run external CSS you need to link it to the HTML. This usually goes in the head tag:

`<link rel=“stylesheet” href=“css/style.css” />`

#### Basic layout for a CSS file

```
h1 {
	color: #FF9966;
	text-align: center;
}

```
### What about different ways to organize content?

#### divs:
- Define a division.
- They are equivalent to empty rectangles. 
- They are used to format block elements that can be styled via CSS. 

`<div> </div `

#### spans:
- They are inline elements that are normally displayed without line breaks. 

`<span> </span> `

#### input:
- Inputs allow users to enter data to be saved to a database.
- They come in different forms to facilitate the specific data entry type.

```
<input type="text" class="form-control" />
```

#### select list:
- Select lists allow users to select options from a dropdown menu.

```
<select>
	<option value="USA">United States</option>
</select>
```

#### button:
- Buttons are HTML elements that give users the ability to submit the data entered as well as transition to new pages.

```
<button>My Button</button>
```

### Linking JS with HTML
- JavaScript enables interaction with the page.
- In order to run external JS you need to link it to the HTML. This usually goes before the closing `body` tag:

```
<script src="js/script.js"></script>
```


### HTML Markup Lab
- Open the `html_form` folder and open `index.html`.
- For each comment denoted by `<!-- -->` replace the comment text with the correct HTML as per the instruction to create the form.
- Alter the CSS file to use a Google Fonts font. You will need to use the `font-family` CSS property.
- Bonus: Use CSS to change the background color of the page. Experiment with using images as backgrounds as well.
- Double Bonus: Review the CSS `transition` property documentation and try to create a small animation anywhere on the form. An example may be to highlight a border around a form field when it is clicked.


### Id's versus classes
#### Id's: 
- Are selectors. 
- They are used if you want a single, unique element. 
- By convention, they are used only once. 

HTML:

```
<div id=“header”>
	<h1>Welcome to my website</h1>	
</div>
``` 
CSS: hash/pound sign designate an id

```
#header{
	text-align: center;
	color: red;
}
```


#### Classes:
- Are selectors. 
- Select an element with a specific class attribute.
- Can be used more than once.  

HTML:

```
<div class=“paragraph”>
     Here are my favorite hobbies:
     skateboarding, scuba diving, and
     riding motorcycles.
</div> 

```
CSS: a period designates a class

```
.paragraph {
	color: green;
}

```

## Selector Exercise
- Let's use Codepen.io to practice CSS selectors.
- Create at least one div with an id, and four divs with a class.
- Use CSS to apply styling to the divs based on the id and class selectors.
- Bonus: Try implementing one or more styles using a CSS3 selector (first-child, nth-child, first-of-type, etc).

### Margin, Padding, and the Box Model
- **Margin** clears area outside border, it is transparent. 
- **Padding** clears area around the content, it is transparent. 
- The **CSS box model** is a box that wraps around HTML elements. It consists of: the content, padding, border, and margin. This model allows us to define space around and between elements. 


![image](http://www.w3schools.com/css/box-model.gif)

## CSS Positioning
- There are four main types of positioning that you will see most often - static, relative, absolute, and fixed.
- Static positioning is what all elements have by default.
- Relative and absolute work together - elements can be positioned absolutely relative to their container.
- Fixed position elements are essentially absolute relative to the window no matter where they are in the DOM. A.K.A. the window is always the relative parent.

## Positioning Exercise
- Try to replicate the following mockups using what we've talked about in this class so far.
- Utilize margins, padding, floats, positioning, etc.

1. Stackers!

![Stackers!](../img/stackers.png)

2. The Mirror

![The Mirror](../img/the_mirror.png)

3. The Skinny

![The Skinny](../img/the_skinny.png)

4. The Absolute

![The Absolute](../img/the_absolute.png)


## How can you edit an existing webpage?
- Hit "command+option+j" and this will open the developer tools. 
- This can then be used as a “console” to test new code/change code and see what it looks like. 

## about.me type portfolio site
Click [here](virtual-resume) to find the starter code for a virtual about me page you will be creating. Change the HTML where necessary. Upon completion of the HTML, add your own styles. Add ids and classes to your elements to have even more control over the design and style of the page. In this folder you will see [screenshots](virtual-resume) of an example that has been stylized. 

## Summary
- HTML and CSS work together. How?
- What do you think is happening on the back-end?
