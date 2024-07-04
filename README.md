# Quiz: Build an HTML Fragment

## Instructions
We have created a model of an animal trading card using concatenation in `card.js`  Your job is to create a second version of the same card that uses template literal syntax. 
>You can ignore the code at the bottom of the `card.js` file. You'll learn how to create the code that appends the HTML strings to the web page when you learn how to create content with JavaScript

When you run the server and view the web page (see instructions below), you should see two identical animal trading cards side-by-side on the page.

![Two identical Animal Trading Cards side-by-side](./images/Cheetah.png)

### Need a hint?

- Make sure to start your template literal with a <code>`</code> instead of a <code>'</code>. 
- You will want to make sure that when you are referring to variable names, you use `${animal.variableName}` instead of just `animal.variableName`.
- Remember that template literals do not need to use `+` for concatenation, so you can remove all of the additional `+` and <code>'</code> characters.
- If you get *really* stuck, you can see the solution on the next page in the lesson.

---

## Loading the Web Page
To get the page running you'll need to start the Node server by typing an npm command in the terminal:
```
npm run start
```

To see the web page, you'll need to click the ***VIEW THE WEB PAGE*** button at the bottom of the screen.

That will open a new browser tab that contains the replica web page.  The page will update as you make changes.

## Tips for Using the Workspace

1. Expand the workspace to full screen. That will give you more room to work.
2. If the type in the workspace is too small, use your browser's zoom control to magnify the screen.

---

> [npm](https://nodejs.org/en/knowledge/getting-started/npm/what-is-npm/) is a command-line utility and online repository for open-source Node projects. We're using npm to install and run a server that will deliver our HTML and JavaScript code to our browser.
# cards
