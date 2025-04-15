"👋 Welcome to the world of websites!

## Learning Outcomes
By the end of this lesson, you will be able to:

- Define what frontend development is
- Explain how HTML, CSS, and JavaScript work together
- Build a simple interactive “Hello, World!” webpage

##  See the magic first!
Here’s a fun webpage that reacts when you click it 👇
<iframe height=""600"" scrolling=""no"" title=""Example Editable Embed"" src=""https://codepen.io/team/codepen/embed/preview/PNaGbb?default-tab=html%2Cresult&editable=true"" frameborder=""no"" loading=""lazy"" allowtransparency=""true"" allowfullscreen=""true"">
  See the Pen <a href=""https://codepen.io/team/codepen/pen/PNaGbb"">
  Example Editable Embed</a> by CodePen (<a href=""https://codepen.io/team/codepen"">@codepen</a>)
  on <a href=""https://codepen.io"">CodePen</a>.
</iframe>
> What makes this page interactive and what  do you think is responsible for the colors and movement?

```
Think about a website you like using — maybe YouTube or Instagram.
- What do you notice about the design?
- What happens when you click a button?
- Ever wondered how it works behind the scenes?
```
🎯 **These are all frontend experiences!**


In this lesson, you’ll meet the three superheroes of frontend:
- **HTML**  — the structure that brings the webpage
- **CSS**  — the style that builds the colour for the webpage
- **JavaScript**  — the motion




---

##   Meet the Trio

**Imagine a webpage is like a person.**

| Web Tech    |    Role             |    Analogy              |
|--------------------|----------------------|--------------------------|
| HTML          | Structure       | The skeleton      |
| CSS             | Presentation | The clothes        |
| JavaScript | Behavior        | The actions        |


Got it! Here's a working example using [JSFiddle](https://jsfiddle.net/) that you can safely embed and is publicly accessible:

---

Let’s try this out together.

<iframe height=""600"" scrolling=""no"" title=""Untitled"" src=""https://codepen.io/Dharini94/embed/preview/dPPbGgz?default-tab=html%2Cresult&editable=true"" frameborder=""no"" loading=""lazy"" allowtransparency=""true"" allowfullscreen=""true"">
  See the Pen <a href=""https://codepen.io/Dharini94/pen/dPPbGgz"">
  Untitled</a> by Dharini S (<a href=""https://codepen.io/Dharini94"">@Dharini94</a>)
  on <a href=""https://codepen.io"">CodePen</a>.
</iframe>
**Here’s what’s happening in this example:**

##  HTML — The **Structure** of the Page

```html
<h1>Hello world!</h1>

<p>This is a demo app that shows how to Fiddle with Firefox OS using JSFiddle! Please fork me and make wonderful things</p>
```

- `<h1>Hello world!</h1>`  
  👉 This is a **heading** — the largest kind. It introduces the page.
  
- `<p>...</p>`  
  👉 This is a **paragraph**. It gives a bit of text to explain what the page is about.

Together, this is the **skeleton** of the page — no style or behavior yet.

---

## CSS — The **Style** of the Page

```css
h1 {
    color: #f00;
}
```

- This tells the browser:  
   *“Make all `<h1>` headings red (#f00 = red in hex color code)”*
**Result: The “Hello world!” text appears in bright red!**

---

## JavaScript — The **Behavior** of the Page

```js
alert(document.getElementsByTagName('h1')[0].innerHTML);
```


It shows an **alert box** with the content inside the `<h1>` tag.


```
- `document.getElementsByTagName('h1')` → Looks for all `<h1>` tags on the page
- `[0]` → Grabs the first (and only) `<h1>` tag
- `.innerHTML` → Gets the text inside it: `""Hello world!""`
- `alert(...)` → Shows that text in a popup box
```
**Result: When the page loads, you get a popup saying: Hello world!**

## Why this matters

This example shows how:
- HTML **puts content on the page**
- CSS **makes it look nice**
- JavaScript **makes it interactive**

Even though this interaction is small, it’s your **first step into programming behavior** in the browser!

---

## What you just learned

| Technology | Role | What It Did |
|------------|------|-------------|
| HTML | Structure | Created a heading and a paragraph |
| CSS | Style | Turned the heading red |
| JavaScript | Behavior | Popped up a message showing the heading’s text |

Here are [revision notes](https://docs.google.com/document/d/19XhXaAJ_-YesSsRLYPIfqv-VO2lVjPCcFbIam56x_QA/edit?usp=sharing) on this lesson."