# html tags

Created: November 18, 2023 9:41 AM
Class: Comp456
Reviewed: No

# The `<audio>` tag is used to embed sound content in a document, such as music or other audio streams.

```html
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
```

# The `<datalist>` tag specifies a list of pre-defined options for an <input> element.

```html
<label for="browser">Choose your browser from the list:</label>
<input list="browsers" name="browser" id="browser">

<datalist id="browsers">
  <option value="Edge">
  <option value="Firefox">
  <option value="Chrome">
  <option value="Opera">
  <option value="Safari">
</datalist>
```

# The `<dd>` tag is used to describe a term/name in a description list.

```html
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>
```

# The `<dfn>` tag stands for the "definition element", and it specifies a term that is going to be defined within the content.

```html
<p><dfn>HTML</dfn> is the standard markup language for creating web pages.</p>
```

# The `<div>` tag defines a division or a section in an HTML document.

```html
<div class="myDiv">
  <h2>This is a heading in a div element</h2>
  <p>This is some text in a div element.</p>
</div>
```

# The `<fieldset>` tag is used to group related elements in a form.

```html
/<form action="/action_page.php">
  <fieldset>
    <legend>Personalia:</legend>
    <label for="fname">First name:</label>
    <input type="text" id="fname" name="fname"><br><br>
    <label for="lname">Last name:</label>
    <input type="text" id="lname" name="lname"><br><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br><br>
    <label for="birthday">Birthday:</label>
    <input type="date" id="birthday" name="birthday"><br><br>
    <input type="submit" value="Submit">
  </fieldset>
</form>
```

# The `<iframe>` tag specifies an inline frame.

```html
<iframe src="https://www.w3schools.com" title="W3Schools Free Online Web Tutorials"></iframe>
```

# 

# 

# 

Here are 25 CSS tags with examples:

1. `font-size` - Change the size of text.
    
    ```css
    h1 {
      font-size: 24px;
    }
    
    ```
    

```css
∂mg {
  border: 1px solid black;
}

```

1. `width` - Set the width of an element.
    
    ```css
    .container {
      width: 500px;
    }
    
    ```
    
2. `height` - Set the height of an element.
    
    ```css
    .box {
      height: 200px;
    }
    
    ```
    
3. `display` - Specify the display behavior of an element.
    
    ```css
    span {
      display: inline-block;
    }
    
    ```
    
4. `position` - Set the positioning method of an element.
    
    ```css
    .footer {
      position: fixed;
    }
    
    ```
    
5. `float` - Specify the floating behavior of an element.
    
    ```css
    .image {
      float: left;
    }
    
    ```
    
6. `text-align` - Set the alignment of text within an element.
    
    ```css
    .header {
      text-align: center;
    }
    
    ```
    
7. `font-family` - Set the font family for text.
    
    ```css
    p {
      font-family: "Arial", sans-serif;
    }
    
    ```
    
8. `text-decoration` - Add decoration to text.
    
    ```css
    a {
      text-decoration: underline;
    }
    
    ```
    
9. `list-style` - Set the style of list items.
    
    ```css
    ul {
      list-style: none;
    }
    
    ```
    
10. `opacity` - Set the opacity of an element.
    
    ```css
    .overlay {
      opacity: 0.5;
    }
    
    ```
    
11. `box-shadow` - Add a shadow effect to an element.
    
    ```css
    .box {
      box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
    }
    
    ```
    
12. `text-transform` - Transform text to uppercase, lowercase, or capitalize.
    
    ```css
    .uppercase {
      text-transform: uppercase;
    }
    
    ```
    
13. `transition` - Add transition effects to properties.
    
    ```css
    .button {
      transition: background-color 0.3s ease;
    }
    
    ```
    
14. `border-radius` - Set the radius of element corners.
    
    ```css
    .circle {
      border-radius: 50%;
    }
    
    ```
    
15. `overflow` - Specify whether to clip content or add scrollbars.
    
    ```css
    .container {
      overflow: hidden;
    }
    
    ```
    
16. `text-shadow` - Add a shadow effect to text.
    
    ```css
    h1 {
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    }
    
    ```
    
17. `box-sizing` - Set the sizing behavior of an element.
    
    ```css
    .box {
      box-sizing: border-box;
    }
    
    ```
    
18. `background-image` - Set a background image for an element.
    
    ```css
    .hero {
      background-image: url("image.jpg");
    }
    
    ```
    
19. `cursor` - Set the type of cursor to display when hovering over an element.
    
    ```css
    button {
      cursor: pointer;
    }
    
    ```