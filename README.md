# fonts

## jsDelivr Example:

```htm
https://cdn.jsdelivr.net/gh/ecliptiq/fonts/<path-to-file>
```
```
https://cdn.jsdelivr.net/gh/ecliptiq/fonts/sans-serif/smart/Smart-Regular.woff2
```

## Taking it further

Create a <mark>fonts.css</mark> in your repo on GitHub:

```css
@font-face {
  font-family: 'Smart';
  src: url('https://cdn.jsdelivr.net/gh/ecliptiq/fonts/sans-serif/smart/Smart-Regular.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
```

Then import it into your project via <mark>@import url(...)</mark>

```css
@import url('https://cdn.jsdelivr.net/gh/ecliptiq/fonts/sans-serif/smart/all-weights.css');
```