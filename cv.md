#Tatiana Frolova

---

##Contact info:

**Phone number:** +905352356371
**E-Mail:** tatianaaleks.frolova@gmail.com
**Location:** Turkey, Istanbul
**GitHub:** frrrolova
**Discord** Tania (@frrrolova)

##About myself:

I love to learn new and challenging tasks. I started to learn frontend development at May 2022. I took a course in frontend development on the Innopolis learning platform. I feel most confident in layout, css/scss, BEM. Now I want to improve my knowlege of JS and React

##Skills:

- HTML5
- CSS (SASS/SCSS, BEM)
- JS (basic knowledge)
- React.JS, Redux (basic knowledge)
- Figma
- Git
- GitHub/GitLab

##Code example:

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

##Studing projects:

https://gitlab.com/t_frrolova/layout-practice/-/tree/develop (html, css/scss)
https://gitlab.com/t_frrolova/module-react/-/tree/develop (react, redux)

##Education:

Innopolis University course of Frontend Development

##Languages:

- English (Pre-Intermediate)
- Russian (native)

![it's me](https://lh3.googleusercontent.com/u/0/drive-viewer/AFDK6gOO2-cXTzyzWnoEpPO1ONeRnZw3vWkjHUmcbzDbarMdjcv82hHqZ9tfngl_K6Z-OnxOrgGPJyXh1jCQmV8ETrq39XS9=w1920-h902)
