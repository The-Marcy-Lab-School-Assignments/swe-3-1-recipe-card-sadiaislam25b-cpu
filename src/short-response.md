# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: HTML Structure

What is the difference between the `<head>` and `<body>` sections of an HTML document? What kind of content goes in each?

**Your Answer:**
The <head> section contains information about the webpage that is not directly visible to users, such as the page title, meta tags, and links to CSS files or fonts. It helps the browser understand how to display and manage the page. The <body> section contains all the visible content of the website, including text, images, links, forms, and other elements users interact with.

## Question 2: Semantic HTML

Why should we use semantic elements like `<header>`, `<main>`, and `<footer>` instead of using `<div>` tags for everything?

**Your Answer:**
Semantic HTML elements like <header>, <main>, and <footer> describe the purpose of the content inside them, making the structure of the page clearer. They improve accessibility by helping screen readers understand the layout and meaning of the content. Semantic elements also make code easier to read and maintain compared to using generic <div> tags everywhere.

## Question 3: CSS Selectors

Given the following HTML:

```html
<ul>
  <li class="vegetable">Carrots</li>
  <li class="vegetable">Broccoli</li>
  <li class="fruit" id="favorite">Mango</li>
</ul>
```

Write THREE different CSS rules:
1. One that makes ALL list items have a `yellow` background
2. One that makes only the vegetables have `green` text color
3. One that makes only the Mango `bold`

**Your Answer:**

```css
/* 1. Make ALL list items have a yellow background */
li {
  background-color: yellow;
}

/* 2. Make only the vegetables have green text */
.vegetable {
  color: green;
}

/* 3. Make only the Mango bold */
#favorite {
  font-weight: bold;
}

```


## Question 4: The Box Model

In your own words, explain the four parts of the CSS box model (content, padding, border, margin). What is the purpose of each part?

**Your Answer:**


## Question 5: Box-Sizing

What problem does `box-sizing: border-box` solve? Why do we include it in a CSS reset at the top of our CSS files?

**Your Answer:**
box-sizing: border-box makes the width and height of an element include its padding and border, so the total size of the element doesn’t grow unexpectedly. Without it, adding padding or a border can make an element larger than intended, which can break layouts. Including it in a CSS reset ensures all elements behave consistently, making it easier to design precise and predictable layouts.

## Question 6: Display Property

What is the difference between `display: block`, `display: inline`, and `display: inline-block`? Give an example of when you might use `inline-block`.

**Your Answer:**

display: block makes an element take up the full width of its container and start on a new line, like a <div> or <p>. display: inline makes an element only take up as much width as its content and stay on the same line, like <span> or <a>. display: inline-block combines both: the element stays on the same line like inline elements but can have width, height, and padding like a block. You might use inline-block for buttons or menu items so they sit side by side but can still be sized and padded consistently.