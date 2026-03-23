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



### X/X/XX:
* Text


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
