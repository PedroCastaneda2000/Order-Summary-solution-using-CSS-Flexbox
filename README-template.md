# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

In the Order Summary challenge, I was tasked to mirror the design of an example Ecommerce order summary page.

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![images/screenshot.jpg]

### Links

- Solution URL: [https://github.com/pgc0004/Order-Summary-solution-using-CSS-Flexbox-.git]
- Live Site URL: [order-summary-solution-using-css-flexbox.netlify.app]

## My process

1. Began with the HTML layout of the main background and the card's container. Then continued with the card's contents such as the main image, main text, the main plan, and the main buttons after centering the card's container with CSS Flexbox. The card's container was made responsive using the max-width property.

2. Next designed the layout of the CSS with a Mobile First Approach. Began with global paramenters and variables. Then continued to style the card's contents using responsive sizing such as rem and percentage %.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox
- Mobile-first workflow

### What I learned

Proud of using Unorder Lists to design and style the Annual Plan (main plan) portion of the challenge.

```html
<!-- @@@@@ Main Plan @@@@@ -->
<ul class="plan-container">
  <div class="plan-image">
    <li>
      <img
        id="plan-image"
        src="images/icon-music.svg"
        alt=""
        aria-hidden="true"
      />
    </li>
  </div>
  <div class="plan-text">
    <li>
      <h2>Annual Plan</h2>
    </li>
    <li>
      <p>$59.99/year</p>
    </li>
  </div>
  <div class="change">
    <li>
      <a id="change" href="/" alt="links another page to change order"
        >Change</a
      >
    </li>
  </div>
  s
</ul>
<!-- @@@@@ /Main Plan @@@@@ -->s
```

Proud of using variables to implement the colors and backgrounds to the challenge.

```css
:root {
  /* Text Colors */
  --text-darkblue: hsl(223, 47%, 23%);
  --text-desaturatedblue: hsl(224, 23%, 55%);

  --text-palepurple: hsl(247, 68%, 64%);

  /* Background Colors */
  --bg-paleblue: hsl(225, 100%, 94%);
  --bg-verypaleblue: hsl(225, 100%, 98%);
  --bg-brightblue: hsl(245, 75%, 52%);

  --bg-grayishblue: hsl(225, 100%, 96.5%);
  --bg-palepurple: hsl(247, 68%, 64%);

  /* Images */
  --bg-cover: url(images/pattern-background-desktop.svg);
}
```

### Continued development

ss
In the future, I would like to better understand the CSS Background property in regards to images, the use of CSS variables when styling a project, and designing responsive website.
