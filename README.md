# fonts

## jsDelivr Example:

```htm
https://cdn.jsdelivr.net/gh/<your-username>/<repo>/<path-to-file>
```
```htm
https://cdn.jsdelivr.net/gh/your-username/fonts/yourfont/YourFont-Regular.woff2
```

## Taking it further

Create a <mark>fonts.css</mark> in your repo on GitHub:

```css
@font-face {
  font-family: 'Your Font';
  src: url('https://cdn.jsdelivr.net/gh/username/fonts/yourfont/YourFont-Regular.woff2') format('woff2');
  font-weight: 400
  font-style: normal;
} ```
```

Then import it into your project via <mark>@import url(...)</mark>

```css
@import url('https://cdn.jsdelivr.net/gh/username/fonts/fonts.css');
```