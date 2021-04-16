# highlight.js theme

`highlight.js`의 테마를 브라우저 테마에따라 다른 모습으로 나타내기위해서 제작

```css
@media (prefers-color-scheme: light) {
  @import "highlight-theme/github.scss";
}
@media (prefers-color-scheme: dark) {
  @import "highlight-theme/dracula.scss";
}
```

Light Theme: github
Dark Theme: dracula

## 사용방법

link 방식

```html
<link rel="stylesheet" type="text/css" href="https://hansanghyeon.github.io/highlight.js-custom/main.css">
```

import 방식

```css
@import url('https://hansanghyeon.github.io/highlight.js-custom/main.css');
```
