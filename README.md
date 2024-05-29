# Learning-HTML
Here are some practice websites I will build while learning HTML.

## Notes: 

### 1. MAIN ELEMENT
The main element is used to represent the main content of the body of an HTML document. Content inside the main document should be unique and should not be repeated in other parts of the document.
The main element is an element that needs both an opening tag and a closing tag.

### 2. SECTION ELEMENT
The section element helps seperate images from future content. This element helps with Search Engine Optimization and accessibility. 

### 3. IMG ELEMENT
The img element has a self-closing tag. For example, you do not need to put <img> <\img>.
The src attribute in the element img specifies the images URL (where the image is located). 
All img elements should have an alt attribute. The alt attribute's text is used for screen readers to improve accessiblity and is displayed if the image fails to load.

### 4. LINKS
You can turn a text into a link.

You can link another page with the anchor element (a). The anchor element is NOT a self-closing tag.
A links text must be placed between the opening and closing tags of the anchor element (a).
To open links an a new tab, you can use the target attribute to the anchor (a) element. The target attribute specifies where to open the linked document. 

### 5. FIGURE ELEMENT
The figure element represents self-contained content and will allow you to associate an image with a caption.
The figcaption element is used to add a caption to describe the image within the figure element.

### 6. INPUT                              
There are also many kinds of inputs you can create using the type attribute. 
You can easily create a password field, reset button, or a control to let users select a file from there computer.
You can create a text field to get text input from a user by adding the type attribute with the value text to the input element.
input type="text"

In order for the form's data to be accessed by the location specified in the action attribute, you must give the text field a name attribute and assign it a value to the data being submitted. 
input type="text" name="name"
