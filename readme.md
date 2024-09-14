Here is the documentation in Markdown format with an example for each HTML tag:

---

# HTML Documentation

### `<!DOCTYPE html>`
Defines the document type and version of HTML (in this case, HTML5). It helps the browser display the content correctly.

Example:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Example Page</title>
    </head>
</html>
```

### `<html lang="en">`
The root element that encloses all other HTML elements. The `lang="en"` attribute specifies the language of the document.

Example:
```html
<html lang="en">
    <head>
        <title>My Page</title>
    </head>
    <body>
        <p>Hello World!</p>
    </body>
</html>
```

### `<head>`
Contains metadata and links to external resources (e.g., stylesheets or scripts). It doesn't directly affect the visible content on the page.

Example:
```html
<head>
    <title>Page Title</title>
    <meta charset="UTF-8">
    <meta name="description" content="An example HTML page">
</head>
```

### `<title>`
Sets the title of the webpage, which appears in the browser's title bar or tab.

Example:
```html
<title>Washera Academy</title>
```

### `<body>`
Encloses the visible content of the webpage, such as text, images, and links.

Example:
```html
<body>
    <h1>Welcome to Washera Academy</h1>
    <p>This is the main content of the webpage.</p>
</body>
```

### `<header>`
Represents the introductory content or navigation links. It typically contains the site's title and a navigation menu.

Example:
```html
<header>
    <h1>Washera Academy</h1>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
        </ul>
    </nav>
</header>
```

### `<h1>`
A heading element. `<h1>` is the most important heading, typically used for the main title of the webpage.

Example:
```html
<h1>Main Title of the Page</h1>
```

### `<ul>`
Unordered list element. It creates a bullet-point list.

Example:
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

### `<li>`
List item element. It defines each item within an ordered or unordered list.

Example:
```html
<ul>
    <li>First Item</li>
    <li>Second Item</li>
</ul>
```

### `<a href="#">`
Anchor element, which creates a hyperlink. The `href` attribute specifies the URL of the page the link goes to. If the value is `#`, it links to an element within the same page.

Example:
```html
<a href="https://www.example.com">Visit Example</a>
```

### `<p>`
Paragraph element. Used to define blocks of text.

Example:
```html
<p>This is a paragraph of text that describes the content of the webpage.</p>
```

### `<section>`
Groups content into thematic sections.

Example:
```html
<section>
    <h2>About Us</h2>
    <p>We provide excellent services to our customers.</p>
</section>
```

### `<h2>`
A subheading element, typically used for titles within a section.

Example:
```html
<h2>Subsection Title</h2>
```

### `<img src="URL">`
Image element. The `src` attribute specifies the source (URL) of the image to display.

Example:
```html
<img src="https://www.example.com/image.jpg" alt="Description of the image">
```

### `<ol>`
Ordered list element. It creates a numbered list.

Example:
```html
<ol>
    <li>Step 1</li>
    <li>Step 2</li>
</ol>
```

### `<footer>`
Represents the footer section of the webpage. Typically contains copyright notices, links, or other information at the bottom of the page.

Example:
```html
<footer>
    <p>&copy; 2024 Washera Academy</p>
    <a href="#top">Back to top</a>
</footer>
```

### `<a href="#top">`
Creates a link that navigates back to the top of the page using an internal anchor (`id="top"` in the header).

Example:
```html
<a href="#top">Go to top of the page</a>
```

### `<table>`
Creates a table for displaying structured data.

Example:
```html
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>John Doe</td>
        <td>30</td>
    </tr>
</table>
```

### `<form>`
Collects user input and submits it to a server for processing.

Example:
```html
<form action="/submit" method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <input type="submit" value="Submit">
</form>
```

---

