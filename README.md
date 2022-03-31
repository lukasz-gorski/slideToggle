# **slideToggle()**

> Small script for VanillaJS slideToggle.

# **USAGE**

Install package by npm

```npm
npm i @roghz/slidetoggle
```

Install package by yarn

```yarn
yarn add @roghz/slidetoggle
```

### Bundler

```javascript
import { slideUp, slideDown, slideToggle } from '@roghz/slidetoggle';

const btn = document.querySelector('button.btn');
btn.addEventListener('click', () => {
  slideToggle('div.toggle-div', 500);
});
```

# **LICENSE**

[MIT](https://en.wikipedia.org/wiki/MIT_License) License