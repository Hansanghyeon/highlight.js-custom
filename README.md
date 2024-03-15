# highlight.js

- `highlight.js`의 테마를 미리생성해서 간편하게 가져다 사용할수있다 
- 브라우저 테마에따라 다른 모습으로 나타낸다
  - Light Theme: github
  - Dark Theme: github-dark-dimmed

참고자료
- REF - https://github.com/highlightjs/highlight.js/tree/main/src/styles
- REF - https://highlightjs.org/examples

## 사용방법

### prefers-color-scheme으로 적용

link 방식

```html
<link rel="stylesheet" type="text/css" href="https://hansanghyeon.github.io/highlight.js-custom/main.css">
```

import 방식

```css
@import url('https://hansanghyeon.github.io/highlight.js-custom/main.css');
```

### `.dark` 클래스로 적용

link 방식

```html
<link rel="stylesheet" type="text/css" href="https://hansanghyeon.github.io/highlight.js-custom/class.css">
```

import 방식

```css
@import url('https://hansanghyeon.github.io/highlight.js-custom/class.css');
```