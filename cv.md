# Tatiana Frolova

---

## Contact info:

- **Phone number:** +381652722056
- **E-Mail:** tatianaaleks.frolova@gmail.com
- **E-Mail:** Serbia, Novi Sad
- **GitHub:** frrrolova
- **Discord** Tania (@frrrolova)

## About myself:

I'm Junior-Frontend developer with learning experience of 1 year. I love to learn new and challenging tasks. I Realized myself, as well as under the guidance of more experienced developers, several small sites and web-applications. I learn quickly - I can learn new technologies in a short time. I am punctual, diligent, take on tasks with enthusiasm and strive to bring them to the end.  I like clean code and adhere to the principles of KISS, DRY. I can accept constructive criticism, as I consider it a great opportunity for professional growth.

## Skills:

- HTML5
- CSS (SASS/SCSS)
- JS, TS
- React
- Webpack
- Git
- BEM
- OOP

## Code example:

```javascript
/* Sum all the numbers of a given array ( cq. list ), except the highest and the lowest element ( by value, not by index! ).
The highest or lowest element respectively is a single element at each edge, even if there are more than one with the same value.*/

function sumArray(array) {
  if (!array) {
    return 0;
  }

  function compareNum(a, b) {
    return a - b;
  }

  array.sort(compareNum);

  return array.reduce(function (acc, currentValue, index) {
    if (index == 0 || index == array.length - 1) {
      return acc + 0;
    }

    return acc + currentValue;
  }, 0);
}
```

## Studing projects:

- https://rolling-scopes-school.github.io/frrrolova-JSFE2023Q1/minesweeper/index.html
- https://frrrolova.github.io/virtual-keyboard/
- https://rolling-scopes-school.github.io/frrrolova-JSFE2023Q1/rss-css-selectors/index.html

## Education:

- St. Petersburg Pediatric Medical University
- Innopolis University course of Frontend Development
- RSSchool JS Frontend course

## Languages:

- English (B1-B2)
- Russian (native)

![it's me](https://lh3.googleusercontent.com/u/0/drive-viewer/AFDK6gOO2-cXTzyzWnoEpPO1ONeRnZw3vWkjHUmcbzDbarMdjcv82hHqZ9tfngl_K6Z-OnxOrgGPJyXh1jCQmV8ETrq39XS9=w1920-h902)
