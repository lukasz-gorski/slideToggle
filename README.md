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

### Usage Example

```javascript
import { slideToggle } from '@roghz/slidetoggle';
//import { slideUp, slideDown, slideToggle } from '@roghz/slidetoggle';

const accordionsBlock = document.querySelectorAll('.accordions');
accordionsBlock.forEach(function (accordionBlock, i) {
    const question = accordionBlock.querySelectorAll('.accordions__item--heading');
    question.forEach(el => {
        el.addEventListener('click', (e) => {
            el.classList.toggle('active');
            slideToggle(el.nextElementSibling, 500);
        });
    });
});
```

# **LICENSE**

[MIT](https://en.wikipedia.org/wiki/MIT_License) License