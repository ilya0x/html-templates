# <img src="./images/html5-30.png" alt="Flask"> HTML

- basic template with inline notes for use with any project.
- complete template with examples of most useful HTML elements and inline notes

> All HTML files used in Flask and Django frameworks are included in their
> template folders:
>
> - <img src="./images/flask-full-30.png" alt="Flask">
> - <img src="./images/django-full-30.png" alt="Django">

<br>

## <img src="./images/template-20.png" alt="Flask"> Templates

<b>[Basic](generic/index-basic.html)</b> - ready for use in any project requiring
simple HTML needs. Includes inline notes and TODOs.

> This template is also included as a Snippet in <a
> href="https://github.com/ilya0x/snippets-for-html-sass-python-mojo/blob/main/html.json">
> HTML Snippets</a> without all of the inline notes

<b>[Complete w/ Notes](generic/index-complete.html)</b> - includes examples of most
useful HTML elements.

<br>

## <img src="./images/vscode-20.png" alt="Flask"> Visual Studio Code Extensions

<b>[HTML
Boilerplate](https://marketplace.visualstudio.com/items?itemName=sidthesloth.html5-boilerplate)
</b> - A basic HTML5 boilerplate snippet generator.

<b>[HTML End Tag
Labels](https://marketplace.visualstudio.com/items?itemName=anteprimorac.html-end-tag-labels)
</b> - Labels HTML end tags

<b>[HTML CSS
Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
</b> - CSS Intellisense for HTML: HTML `id` and `class` attribute completion

<b>[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
</b> - Launch a development local Server with live reload feature for static &
dynamic pages

<br>

## 📝Notes

> These notes are updated on regular basis

<br>

### `<meta ...>` tags

<br>

```html
<meta charset="utf-8">
```

Declares to user's browser the character set used for the website.
<br>
<br>

```html
<meta http-equiv="">
```

> rarely used thing, but pretty cool when needed

Example:<br>

```html
<meta http-equiv="refresh" content="5">
```

Will refresh the page every 5 seconds.

> This is on HTML level, so will work if Javascript is disabled.

<br>

#### SEO `<meta>` tags

`<meta>` tags specific to search engine optimization:

<br>

### Media Tags

`<video>`

`<audio>`

`<img>`

<br>

`<canvas>`

<br>

### Logical vs Physical Tags

#### The Bold Tag: `<b>` vs `<strong>`

- When you use `<b>` tag it will only make the desired wore or paragraph bold.
- When you use `<strong>` tag it will not only make the word bold but also will
  be the strongest word which will be recognized by SEO search engine and thus
  it will make your website rank in Google etc.

#### The Italics Tag: `<i>` vs `<em>`

<br>

### `<pre>` tag

<br>

### HTML Entities

- start with `&` and end with `;`
- used inline with text to convey literal use of a character
- Examples:<br>
  `&nbsp;` is a non-breaking space<br>
  `&lt` and `&gt` are < and ><br>
  `&copy;` inserts the copyright symbol<br>
<br>

### `<form>` Inputs

Here are some of the most used and my favorite HTML5 `<form>` `<input type="">` inputs.

> These help you avoid JavaScript as many of these were only available through
> use of JS prior to HTML5.

<br>

`<input type="text">` creates a textbox for user to enter text.<br>
Has a lot of different attributed that can be included to customize the textbox
behavior. Most used: <br>
`<input type="text" placeholder="Enter Custom Placeholder Text Here">`

<br>

`<input type="password">`
<br>

`<input type="checkbox">` creates a togglable checkbox, like ones used in user agreements.

<br>

`<input type="radio">` requires at least two linked radio buttons to work:

Grouping radio buttons by `name="group-by-name"` makes them mutually exclusive.

```html
<input type="radio" name="group-by-name" value="value1">Label One
<input type="radio" name="group-by-name" value="value2">Label Two
```

<br>

`<input type="number">`  allows only numbers to be entered into the textbox and
adds increment/decrement arrow buttons to the box.

<br>

`<input type="file">` gives you a "Choose file" button with text "No file
chosen" that when pushed will open the file explorer of user's system and allow
them to pick a file.

<br>

`<input type="email" required>` will require the input to have @ sign and will
give a browser side error to the user to "Please include a '@' in the email
address. '...' is missing as '@'."

<br>

`<input type="color">` creates a color picker for user to select a color. This
will work differently on different browsers and will default to a `tyle="text"`
if not supported.

<br>

`<input type="search">` is just like `<input type="text">` but with a cross
button at the end that clears the input.

<br>

`<input type="range" min="1" max="100">` creates a slider with a range from 1
to 100. Can specify additional values like `step="10"` that will increment the
slider by 10 steps.

<br>

`<input type="date">` creates a date picker. `<input type="datetime-local">`
creates a date and time picker.

<br>

### iFrame

- One of the uses of iFrames is to embed YouTube videos.

`<iframe src="https://address-of-site-to-display">` creates a frame with the
specified website, sizing it to the iframe size.

> Many websites do not allow this to happen, refusing to display in a frame with
> 'X-Frame-Options' set to 'sameorigin'.

<br>

### Accessibility
