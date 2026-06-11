# HTML Basics

In HTML, we denote an element by specifying the name of the element in opening brackets `<>` and closing brackets `</>`. Let’s take the time to highlight the structure of an HTML file and some important elements presented in the boilerplate above.

scrap1
Scrap 1: ## What is Responsive Web Design

**Responsive web design (RWD)** is a development approach that allows for elements to dynamically change its appearance or layout depending on screen size. For example, elements may reorder, grow/shrink in size depending on the size of the screen.

HTML files typically contain things like:

- the text contents of a web page, structured into a hierarchy of page elements
- hyperlinks to other pages
- references to other files like images, CSS files, and JavaScript files
- definitions for interactive controls like buttons and text fields
- metadata to help web browsers understand the contents of the page

### Linking CSS Files

**Line 6**  `<link href="style.css" rel="stylesheet" type="text/css" />`  connects the CSS style sheet to our HTML file.

Let’s break down the syntax used to do this action. Learn more on the [MDN Web Docs about the `link` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link).

- `<link>`: This element specifies relationships between the current document (the HTML file) and an external resource (the CSS file).
- `href`: This attribute specifies the file path, or location, of our external resource. In this particular example, the CSS file is named `style.css` but you can name your stylesheet anything. Take note that the file path is surrounded by double quotes, `""`.
- `rel`: `rel` stands for relationship. This lets the document know how the resource will interact with the current document

, in this case we are linking to a `stylesheet`. Learn more on the MDN Web Docs about link types.
- `type`: Similar to the `rel` attribute, the `type` attribute lets the document know the specific type of file that is being linked.

Scrap 3: ## HTML Boilerplate

**The HTML file is the most important file when building a basic website.** Some online IDEs like [Glitch](https://glitch.com/) or [Replit](https://replit.com/), you may notice that a basic website project comes pre-loaded with at least 3 files with the names `index.html`, `style.css`, and `script.js`. These are typical generic names an HTML, CSS, and JavaScript file, but you can name your files any name you want. It is always best practice to give your files a short descriptive name so that it is easier for others to view your code.

All websites **must have at least one HTML file**, but CSS style and JavaScript script files are **optional**. To learn more about file naming conventions and organization tips, check out [MDN web docs on dealing with files](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Dealing_with_files).

*Note:* Web servers will often default to loading the `index.html` file if multiple HTML files are present, unless otherwise specified.

Scrap 4:  **Let’s take a look at a typical boilerplate, or standard template, for an HTML file.**

```html
<!DOCTYPE html>
<html>
 <head>
   <meta charset="utf-8">
   <meta name="viewport" content="width=device-width">
   <title>Title of Website</title>
   <link href="style.css" rel="stylesheet" type="text/css" />
 </head>
 <body>
   <script src="script.js"></script>
 </body>
</html>
```