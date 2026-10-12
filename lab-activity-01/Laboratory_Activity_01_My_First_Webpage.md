# Laboratory Activity 01: My First Webpage 💻

**Time:** 45–60 minutes  
**Type:** Individual activity  
**Tools:** VS Code and a web browser

## I. Objectives

At the end of this activity, students should be able to:

1. Create a simple webpage using HTML.
2. Change text colors and background colors using CSS.
3. Make a button work using JavaScript.

## II. Instructions

Create your first webpage about yourself. Follow the steps below one at a time. No prior programming experience is required.

## III. Step 1: Create your files

Open VS Code and create a folder named `MyFirstWebpage`.

Inside the folder, create these three files:

- `index.html` — webpage content
- `style.css` — webpage design
- `script.js` — button functionality

## IV. Step 2: Write the HTML code

Open `index.html` and type this code:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Webpage</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1>Hello, World!</h1>

    <h2>My name is Juan</h2>

    <p>I am a first-year student.</p>

    <p>My hobby is playing online games.</p>

    <button onclick="showMessage()">Click Me</button>

    <p id="message"></p>

    <script src="script.js"></script>
</body>
</html>
```

**Remember:** Replace `Juan` with your own name and change the hobby to your own hobby.

## V. Step 3: Add CSS

Open `style.css` and type this code:

```css
body {
    background-color: lightblue;
    font-family: Arial;
    text-align: center;
}

h1 {
    color: blue;
}

p {
    color: black;
}

button {
    background-color: green;
    color: white;
    padding: 10px;
}
```

This code changes the background color, text alignment, heading color, and button appearance.

## VI. Step 4: Add JavaScript

Open `script.js` and type this code:

```javascript
function showMessage() {
    document.getElementById("message").textContent =
        "Welcome to my first webpage!";
}
```

This JavaScript code displays a message when the user clicks the button.

## VII. Step 5: Run your webpage

1. Save all three files by pressing `Ctrl + S`.
2. Open your project folder.
3. Double-click `index.html` to open it in your browser.
4. Click the **Click Me** button.
5. Check whether the welcome message appears.

> You do not need Node.js for this activity.

## VIII. Student Tasks

Complete these simple tasks after running your webpage.

### Activity Checklist

- [ ] Change the name to your own name. — **5 pts**
- [ ] Change the hobby to your favorite hobby. — **5 pts**
- [ ] Change the background color in CSS. — **5 pts**
- [ ] Change the heading color in CSS. — **5 pts**
- [ ] Change the message displayed by the button. — **10 pts**

**Total: 30 points**

## IX. Guide Questions

Answer in one or two sentences each.

1. What is HTML used for?
2. What is CSS used for?
3. What is JavaScript used for?
4. What happens when you click the button?

## X. Grading

| Criteria | Points |
|---|---:|
| HTML content | 25 |
| CSS design | 25 |
| JavaScript button | 25 |
| Completed tasks | 15 |
| Guide questions | 10 |
| **Total** | **100** |

## Submission

Submit your three files:

- `index.html`
- `style.css`
- `script.js`

Also submit a screenshot of your finished webpage.

> **Teacher's Tip:** Let students type and run each file before moving to the next step. Explain that HTML creates the content, CSS makes it look better, and JavaScript makes it interactive.
