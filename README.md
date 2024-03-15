
General
Page structure
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SheCodes</title>
</head>
<body>
  
</body>
</html>
More info


HTML
Comment
<!-- this is a comment -->
This code will be ignored. Comments are generally a bad idea, your code should be explicit enough as it is.

More info


HTML
Text Tags
Headings
<h1>
  SheCodes
</h1>
<h2>
  SheCodes
</h2>
<h3>
  SheCodes
</h3>
<h4>
  SheCodes
</h4>
<h5>
  SheCodes
</h5>
<h6>
  SheCodes
</h6>
Note: Only h1, h2, h3, h4, h5, and h6 exist, you should only have one h1 on your page.

More info


HTML
Paragraph
<p>
  SheCodes teaches busy women how to code.
</p>
More info


HTML
Unordered Lists
<ul>
  <li>
    SheCodes Basics
  </li>
  <li>
    SheCodes Plus
  </li>
  <li>
    SheCodes Responsive
  </li>
  <li>
    SheCodes React
  </li>
</ul>
Note: <ul> can only have <li> as direct descendants.

More info


HTML
Ordered List
<ol>
  <li>
    SheCodes Basics
  </li>
  <li>
    SheCodes Plus
  </li>
  <li>
    SheCodes Responsive
  </li>
  <li>
    SheCodes React
  </li>
</ol>
Adds numbers in front of each list item.

Note: We rarely use this one as it's hard to style.

More info


HTML
Nested lists
<ul>
  <li>SheCodes Basics</li>
  <li>SheCodes Plus</li>
  <li>
    <strong>SheCodes Pro</strong>
    <br />
    <ul>
      <li>SheCodes Basics</li>
      <li>SheCodes Plus</li>
      <li>SheCodes Responsive</li>
      <li>SheCodes React</li>
    </ul>
  </li>
</ul>
More info


HTML
Link
<a href="https://www.shecodes.io/">SheCodes</a>
<a href="https://www.shecodes.io/" target="_blank">SheCodes</a>
<a href="https://www.shecodes.io/" target="_blank" title="SheCodes Website">SheCodes</a>
Adds a link to the page.

Note: target="_blank" opens the link in a new window.

More info


HTML
Mailto link
<a href="mailto:team@shecodes.io">Send us an email</a>
More info


HTML
Anchor link
<a href="#important">
  Jump to the heading below
</a>

<div id="important">
  This is a note
</div>
Link to a section on the same page

More info


HTML
Separators
Line Break
SheCodes offers coding workshops <br />
to busy women <br />
Sign up today
Note: Inline element

More info


HTML
Horizontal Rule
SheCodes offers coding workshops
<hr />
to busy women
<hr />
Sign up today
Note: Inline element

More info


HTML
Attributes
Classes
<a href="https://www.shecodes.io/" class="website-url">SheCodes</a>
<div class="header important">SheCodes Workshops</div>
Classes are generally used to select elements from CSS. Name your classes using clear English words. If you want a class name to include multiple words, separate each word with a hyphen - . If you want to use multiple class names, use a space in between. Class names should be lower cased.

More info


HTML
Ids
<a href="https://www.shecodes.io/" id="website-link">SheCodes</a>
Ids are generally used to select elements from JavaScript and can only be used once. Name your ids using clear English words. If you want an id name to include multiple words, separate each word with a hyphen -. If you want to use multiple id names, use a space in between. Id names should be lowercased.

More info


HTML
Containers
Div
<div>SheCodes</div>
<div class="coding-workshop">SheCodes</div>
Generally used to add a class around some content and target that class from CSS. It doesn't add any styling on its own.

Note: Block element

More info


HTML
Span
<span>SheCodes</span>
<span class="best-workshop">SheCodes</span>
Generally used to add a class around some content (especially text and images) and target that class from CSS. It doesn't add any styling on its own.

Note: Inline element

More info


HTML
Header
<header class="page-header">
    <h1>SheCodes Workshops</h1>
</header>
It typically groups the introduction of the page or the navigation. It doesn't add any styling on its own.

Note: Block element

More info


HTML
Footer
 <footer>
        <p>© SheCodes</p>
    </footer>
It typically groups information about the author of the section, copyright data, or links to related documents. It doesn't add any styling on its own.

Note: Block element

More info


HTML
Section
<section class="workshop-information">
    <h2>SheCodes Pro</h2>
    <p>SheCodes Pro includes everything you need to become a professional developer...</p>
</section>
It typically groups information on a page. It's very similar to <div> but less commonly used. It doesn't add any styling on its own.

Note: Block element

More info


HTML
Media Tags
Image
<img src="https://s3.amazonaws.com/shecodesio-production/uploads/files/000/083/182/original/cat.png?1685030491" />
<img src="https://s3.amazonaws.com/shecodesio-production/uploads/files/000/083/182/original/cat.png?1685030491" alt="Image description" />
<img src="https://s3.amazonaws.com/shecodesio-production/uploads/files/000/083/182/original/cat.png?1685030491" alt="Image description" width="400" />
Adds an image to the page.

Note: This is a self-closing tag.

More info


HTML
Video
<video src="https://video-url"></video>
<video src="https://video-url" controls></video>
Adds a video to the page.

More info


HTML
Audio
<audio controls src="https://url-to-audio-file.mp3"></audio>
Adds audio to the page.

More info


HTML
Form Tags
Form
<form action="/submit">
    <label for="name">Enter your name: </label>
    <input type="text" placeholder="Your name" name="name" id="name" required />
    <label for="email">Enter your email: </label>
    <input type="email" placeholder="Your email" name="email" id="email" required />
    <input type="submit" value="Subscribe!" />
</form>
Adds a form to the page. The action depends on where you want the form data to be sent to (usually provided by a backend developer)

More info


HTML
Inputs
<label for="name">Name (4 to 8 characters):</label>
<input type="text" id="name" />
Creates a form text input.

Note: Self-closing tag

More info


HTML
Button
<button class="signup-button">
  Sign up now
</button>
Adds a button to the page.

Note: Inline element

More info


HTML
Radio inputs
<label>What pets do you have?</label>
<input type="radio" name="pet" id="cats" value="cats" checked />
<label for="cats">Cats</label>
<input type="radio" name="pet" id="dogs" value="dogs" />
<label for="dogs">Dogs</label>
<input type="radio" name="pet" id="frogs" value="frogs" />
<label for="frogs">Frogs</label>
More info


HTML
Checkbox inputs
<label>What pets do you have?</label>
      <div>
        <input type="checkbox" name="pets" id="cats" value="cats" />
        <label for="cats">Cats</label>
      </div>
      <div>
        <input type="checkbox" name="pets" id="dogs" value="dogs" />
        <label for="dogs">Dogs</label>
      </div>
      <div>
        <input type="checkbox" name="pets" id="frogs" value="frogs" />
        <label for="frogs">Frogs</label>
      </div>
More info


HTML
Select element
 <label for="countries">Which country would you like to travel to?</label>
    <select id="countries">
      <option value="">Select a country</option>
      <option value="france">France</option>
      <option value="italy">Italy</option>
      <option value="usa">USA</option>
      <option value="brazil">Brazil</option>
      <option value="japan">Japan</option>
    </select>
More info


HTML
Styling tags
Strong
<strong>SheCodes Workshops</strong>
Makes the content bold.

Note: Inline element

More info


HTML
Small
<small>SheCodes Workshops</small>
Makes the text within it one font size smaller.

Note: Inline element

More info


HTML
Em
<em>SheCodes Workshops</em>
Makes the text italic.

Note: Inline element

More info


HTML
CSS in HTML
Internal CSS
<head>
  <style>
    body {
      background: #f8f5ff;
    }

    h1 {
      color: purple;
      text-align: center;
    }
  </style>
</head>
Add a style element inside your <head> to include CSS in your HTML file. You should ideally have a maximum of 1 style element on your page. You don't need a style element if you're using external CSS.

More info


HTML
External CSS
<head>
    <link rel="stylesheet" href="style.css" />
</head>
Link to an external CSS file, add multiple link tags to link to multiple CSS files.

Note: Link is a self-closing tag

More info


HTML
JavaScript in HTML
Internal JavaScript
<body>
  <h1>
    SheCodes
  </h1>
  <script>
    alert("Hello SheCodes");
  </script>
</body>
Add your script tag to the bottom of your body. Anything inside script is JavaScript.

More info


HTML
External JavaScript
<body>
  <h1>
    SheCodes
  </h1>
  <script src="app.js"></script>
</body>
Link to your external JavaScript file at the bottom of your body. The script element doesn't include any content but needs to be closed. It is not a self-closing tag.

More info


HTML
SEO
Title element
<title>The title of your website - Brand</title>
Determine the document's title that will be shown in a browser’s title bar or a page's tab More info

More info


HTML
Meta description

<head>  
  <meta name="description"  content="This is an example of a meta description. This will often show up in search results." />
</head>
More info


HTML
Table
Table structure
   <table>
      <thead>
        <tr>
          <th>First name</th>
          <th>Last name</th>
          <th>Nationality</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Matt</td>
          <td>Delac</td>
          <td>French</td>
        </tr>
        <tr>
          <td>Amanda</td>
          <td>Smith</td>
          <td>American</td>
        </tr>
      </tbody>
    </table>




Selectors
Element selector
a {
  color: red;
}

h1 {
  text-align: center;
}
More info


CSS
Class selector

/* All elements with class="spacious" */
.spacious {
  margin: 20px;
}

/* All <li> elements with class="spacious" */
li.spacious {
  margin: 20px;
}

/* All <li> elements with a class list that includes both "spacious" and "elegant" */
/* For example, class="elegant retro spacious" */
li.spacious.elegant {
  margin: 20px;
}

/* All <li> elements OR All elements with class="spacious" */
li, .spacious {
  margin: 20px;
}
More info


CSS
ID selector
#demo {
  border: red 2px solid;
}
Note: You should rarely/never use that one

More info


CSS
Pseudo-classes selector
/* Any button over which the user's pointer is hovering */
button:hover {
  color: blue;
}

/* Applied when the user has already visited the link */
a:visited {
  color: red;
}
More info


CSS
Colors
Color property
p {
  color: #00ff00;
}
More info


CSS
Background
.header {
  background: green;
}
You can also use an image as a background.

More info


CSS
Native colors
h1 {
  color: blueviolet;
}
Note: We generally only use black or white. Other colors such as red, blue, green are only good for testing purposes. You should use Hexadecimal values instead.

More info


CSS
Hexadecimal colors
h1 {
  color: #885df1;
}
Use a color picker to find the color you need.

Note: #000000 is black, #ffffff is white. #ffffff is the same as #fff, #FFFFFF or #fff or white.

More info


CSS
RGB colors

/* without transparency */
p {
  color: rgb(135, 93, 241);
}

/* with transparency */
h1 {
  color: rgba(135, 93, 241, 0.5);
}
The RGB color model defines a given color according to its red, green, and blue components. An optional alpha component represents the color's transparency. The first 3 values should be between 0 and 255 and the fourth between 0 and 1. 0 being completely transparent.

More info


CSS
Gradient
.footer {
  background: linear-gradient(#e66465, #9198e5);
}
Multi-position color stop: A gradient tilted 45 degrees, with a red bottom-left half and a blue top-right half, with a hard line where the gradient changes from red to blue linear-gradient(45deg, red 0 50%, blue 50% 100%);

More info


CSS
CSS Background Size
body {
  background-size: cover;
}

img { 
  background-size: 50%;
}
More info


CSS
CSS Background Image
body {
        background-image: url("https://i.notretemps.com/1400x787/smart/2022/06/13/albi.jpeg");
        background-repeat: no-repeat;
        background-size: cover;
        background-color: black;
}
More info


CSS
Box
Border
.header {
  border: 1px solid #885df1;
}
First value is the thickness, second one the style (none | hidden | dotted | dashed | solid | double | groove | ridge | inset | outset), and third one is the color.

More info


CSS
Margin
/* Margin around the element */
.box-1 {
  margin: 10px;
}

/* Margin left only */
.box-2 {
  margin-left: 10px;
}

/* 10px margin on top and bottom, 5px on the sides */
.box-3 {
  margin: 10px 5px;
}

/* 20px margin top, 15px margin right, 10px margin bottom and 5px margin left */
.box-4 {
  margin: 20px 15px 10px 5px;
}
Space outside an element.

More info


CSS
Padding
/* padding around the element */
.box-1 {
  padding: 10px;
}

/* padding left only */
.box-2 {
  padding-left: 10px;
}

/* 10px padding on top and bottom, 5px on the sides */
.box-3 {
  padding: 10px 5px;
}

/* 20px padding top, 15px padding right, 10px padding bottom and 5px padding left */
.box-4 {
  padding: 20px 15px 10px 5px;
}
Space inside an element.

More info


CSS
Width
.box-1 {
  width: 100%;
}

.box-2 {
  max-width: 100px;
}

.box-3 {
  min-width: 200px;
}
More info


CSS
Height
.box-1 {
  height: 100%;
}

.box-2 {
  max-height: 100px;
}

.box-3 {
  min-height: 200px;
}
More info


CSS
Radius
/* Light rounded corner all around the element */
.box-1 {
  border-radius: 20px;
}


/* Rounded corner top left and right only */
.box-2 {
  border-radius: 50% 50% 0 0;
}
The border-radius CSS property rounds the corners of an element's outer border edge.

More info


CSS
Box shadow
.box {
  box-shadow: 10px 5px 5px red;
}
the third value is the blur radius and the last value is the shadow color.

More info


CSS
Transform
/* Function values */
transform: rotate(0.5);
transform: rotateX(10deg);
transform: rotateY(10deg);
transform: rotateZ(10deg);
transform: translate(12px, 50%);
transform: translate3d(12px, 50%, 3em);
transform: translateX(2em);
transform: translateY(3in);
transform: translateZ(2px);
transform: scale(2, 0.5);
transform: skew(30deg, 20deg);;

/* Multiple function values */
transform: translateX(10px) rotate(10deg) translateY(5px);
transform: perspective(500px) translate(10px, 0, 20px) rotateY(3deg);
More info


CSS
Text
Text align
h1 {
  text-align: center;
}
text-align: left | right | center | justify | initial | inherit;

More info


CSS
Text decoration
h1 {
  text-decoration: underline;
}
none: no line is drawn, and any existing decoration is removed. underline: draws a 1px line across the text at its baseline. line-through: draws a 1px line across the text at its “middle” point. overline: draws a 1px line across the text, directly above its “top” point. inherit: inherits the decoration of the parent.

More info


CSS
Text transform
h1 {
  text-transform: uppercase;
}
Note: text-transform: none | capitalize | uppercase | lowercase | initial | inherit;

More info


CSS
Line height
h1 {
  line-height: 28px;
}

p {
  font-size: 14px;
  line-height: 1.5;
}
Note: We generally use a multiplier such as 1.5 which making the line height 1.5 times higher than the font size

More info


CSS
Font style
h1 {
  font-style: italic;
}
Note: font-style: normal | italic | oblique | initial | inherit;

More info


CSS
Font weight
h1 {
  font-weight: normal;
}

p {
  font-weight: 700;
}

a {
  font-weight: 100;
}
Note: font-weight: normal | bold | bolder | lighter | number | initial | inherit; It can also be a value between 100 | 200 | 300 | 400 | 500 | 600 | 700 | 800 | 900 where 100 is thin and 900 is extra bold

More info


CSS
Font size
body {
  font-size: 18px;
}
More info


CSS
Font family
body {
  font-family: Georgia, serif;
}
More info


CSS
List
List style
/* Remove the list bullets point and default spacing */
ul {
  list-style: none;
  padding: 0;
  margin: 0;
}


/* Horizontal list */
li.students {
  display: inline;
}
More info


CSS
Layout
Display
img {
  display: block;
}

.heading {
  display: inline;
}
Note: Each element is by default inline or block element. A block element creates an invisible line before and after. An inline element doesn't.

More info


CSS
Position
.heading {
  position: relative;
  top: -10px;
  left: 20px;
}
Note: Position can be static | relative | fixed | absolute | sticky. By default, elements are static.

More info


CSS
Center element
img {
  display: block;
  margin: 0 auto;
}

CSS
Flexbox
.container {
   display: flex;
   flex-direction: row | row-reverse | column | column-reverse; /* optional */
   justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right; /* optional */
   flex-direction: row | column; /* optional */
}
Align elements within the container horizontally

More info


CSS
Responsive image
img {
  max-width: 100%;
  height: auto;
}
More info


CSS
Grids
.image-gallery {
  display: grid;
  grid-template-columns: 1fr 2fr;
  grid-template-rows: repeat(2, 2fr 1fr);
  gap: 20px;
}

.image-gallery img {
  width: 100%;
}
More info


CSS
Mouse
Cursor
button:hover {
  cursor: pointer;
}
auto | default | none | context-menu | help | pointer | progress | wait | cell | crosshair | text | vertical-text | alias | copy | move | no-drop | not-allowed | e-resize | n-resize | ne-resize | nw-resize | s-resize | se-resize | sw-resize | w-resize | ew-resize | ns-resize | nesw-resize | nwse-resize | col-resize | row-resize | all-scroll | zoom-in | zoom-out | grab | grabbing

Note: Pointer is the most common one.

More info


CSS
Advanced CSS
CSS Variables
:root {
  --main-branding-color: #885df1;
}

h1 {
  color: var(--main-branding-color);
}
Note: Useful to store font families, colors or sizes.

More info


CSS
Media queries
@media (max-width: 900px) {
  h1 {
    font-size: 18px;
    text-align: center;
  }

  .footer {
    display: none;
  }
}

@media (min-width: 900px) {
  h1 {
    color: red;
  }
}
Media queries are useful when you want to apply CSS to specific resolution breakpoints to make your website more responsive.

More info


CSS
Animations
Transitions
a {
  transition: all 200ms ease;
  opacity: 1;
  color: blue;
}

a:hover {
  opacity: 0.7;
  color: red;
}
