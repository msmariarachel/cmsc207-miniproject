<h1>CMSC 207 Mini-Project: Personal Web Profile</h1>

<h2>Overview</h2>

This is a simple personal web profile created as part of my CMSC 207 Web Programming and Development course. The project showcases fundamental web development skills, including HTML, CSS, and JavaScript.

<h2>Features</h2>

**Basic HTML Structure**: A structured webpage with a header, navigation menu, main content, and footer.

**CSS Styling**: Aesthetic improvements, basic animations and transitions using an external CSS file.

**Interactivity with JavaScript**: Clicking the "**Fun Fact About Me**" button displays a random fact.

<h2>Technologies Used</h2>

**HTML**: For structuring the webpage.

**CSS**: For styling,layout, animations and transitions.

**JavaScript**: For adding interactivity.

<h2>How It Works</h2>

The webpage loads with a structured layout containing my personal information.

A "Fun Fact About Me" button is included. When clicked, JavaScript displays a fun fact.

<h2>Code Example</h2>

<h3>HTML</h3> Snippet for "Fun Fact About Me" Button

```html
<button id="funFactBtn" onclick="showFunFact()"><strong>Fun Fact About Me</strong></button>
<p id="funFact"></p>
<script>
function showFunFact() {
      var funFact = "I've watched Friends a million times and it never fails to make me laugh out loud. :)";
      document.getElementById("funFact").textContent = funFact;
}</script>
```

<h2>How to Run</h2>

Open [https://msmariarachel.github.io/cmsc207-miniproject/](https://msmariarachel.github.io/cmsc207-miniproject/) in a web browser.

Click the "Fun Fact About Me" button to see a random fun fact displayed.

<h2>Contact Information</h2>

If you have any questions or suggestions, feel free to reach out:

**Email**: mmsaluna@up.edu.ph

**LinkedIn**: [linkedin.com/in/rachelmsaluna](linkedin.com/in/rachelmsaluna)

**Facebook**: [facebook.com/in/msmariarachel](facebook.com/in/msmariarachel)

**Instagram**: [instagram.com/msmariarachel](instagram.com/msmariarachel)

<h2>References</h2>

[Create with Code: Build Your Own Website](https://fliphtml5.com/ldrjr/jout/)

[W3Schools: HTML Basics](https://www.w3schools.com/html/html_basic.asp)

[CSS Tricks: A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

[CSS-Tricks - A Guide to JavaScript Events](https://css-tricks.com/intro-to-event-listeners/)

<h2>Conclusion</h2>

This mini project is for educational purposes and demonstrates the use of HTML, CSS, and JavaScript to create a simple interactive webpage. It serves as a foundational exercise in web development and front-end scripting.

© 2025 Maria Rachel. CMSC 207 Mini-Project.

