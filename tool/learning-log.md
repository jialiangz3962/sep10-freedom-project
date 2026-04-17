# Tool Learning Log

## Tool: **Bulma**

---

### 3/21/26:
* To learn about Bulma, I mainly used their (official documentations)[https://bulma.io/documentation/].

### First
First, I looked at Bulma's syntax, so I could undertand how the code in Bulma is arranged. Similar to Bootstrap, you apply the syntax to html and css, making it familiar to me and easier to work with.

You can use one of the 6 main colors:
```html
is-primary  <button class="button is-primary">Button</button>
is-link     <button class="button is-link">Button</button>
is-info     <button class="button is-info">Button</button>
is-success  <button class="button is-success">Button</button>
is-warning  <button class="button is-warning">Button</button>
is-danger   <button class="button is-danger">Button</button>

```

Changing the sizes from small, medium, large.
```html
<button class="button is-small">Button</button>
<button class="button is-medium">Button</button>
<button class="button is-large">Button</button>
```
And the state of the code, for example a button being loaded, disabled, or outlined.
```html
<button class="button is-primary is-outlined">Button</button>
<button class="button is-loading">Button</button>
<button class="button" disabled>Button</button>
```

You can also combine these components.
```html
<button class="button is-primary is-small" disabled>Button</button>
```

### Second
I looked at the skeletons in Bulma. The placeholders in Bulma are different from the average html, or that is what I think of it. Using Bulma skeletons, the blocks emit a pulsating background and shows that something is ready to be put in that skeleton which is called skeleton loaders.

I learned from the Bulma documentation that all skeleton loaders share these CSS variables.

```css
:root {
  --bulma-skeleton-background: var(--bulma-border);
  --bulma-skeleton-radius: var(--bulma-radius-small);
  --bulma-skeleton-block-min-height: 4.5em;
  --bulma-skeleton-lines-gap: 0.75em;
  --bulma-skeleton-line-height: 0.75em;
}
```

The thing that I made from bulma using these include a circular skeleton.

```html
 <div class="skeleton-block" style="width: 48px; height: 48px; border-radius: 50%;"></div>
```



### 4/15/26:
* Day 1: Make a rough wireframe of my website using Bulma and look more into combinations of code I can do with Bulma to try and make something unique. Also practice on fully understanding properties of basic code such as positioning.

* Day 2: See what the Bulma typography could do to fit into a website. I can use (bulma documentation)[https://bulma.io/documentation/helpers/typography-helpers/] to assist me in this.

* Day 3: Look at other websites that are similar to my topic and try combining some ideas in order to practice using Bulma in my sandbox. I also want to try utilizing the Bulma skeleton to try and make my planning easier.

### 4/17/26
I can use Bulma grid system and use the grid system and flexboxes in it to create an organized layout for a website. Bulma also allows for flexbox to be nested into grid.

* Grids use `cell` classes and you can put a `fixed grid` to have a fixed number of columns

* The flexbox in Bulma is similar to Bootstrap, but in Bulma, there are many properties and helpers that come with it. You can wrap the flexbox around something, put it in a direction horizontal or vertical, justify content, align items, align self, align content, and grow or shrink the flexbox.

The typography in Bulma has its own responsive code. The alignment contains code that are classes that could bee assigned to divs. It has mobile, tablet, desktop, widescreen, and FULLHD or above.

#### Bulma Typography
* `is-capitalized` Transforms the first letter of every word in the class to uppercase
* `is-lowercase`	Transforms all characters to lowercase
* `is-uppercase`	Transforms all characters to UPPERCASE
* `is-italic`	Transforms all characters to italic
* `is-underlined`	Underlines the text

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
