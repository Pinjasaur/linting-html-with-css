- Ire Aderinokun's concept: https://bitsofco.de/linting-html-using-css/
- Demo page: https://chriscoyier.github.io/linting-html-with-css/

### Bookmarklet

```js
javascript:(function() {
  var link = document.createElement("link");
  link.rel = "stylesheet";
  link.href = "https://cdn.rawgit.com/chriscoyier/linting-html-with-css/master/lint.css";
  document.getElementsByTagName("head")[0].appendChild(link);
})();
```

### Ideas:

- Browser extension to inject the CSS
