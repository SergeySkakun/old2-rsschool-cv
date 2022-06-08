# Skakun Sergey

### Contacts:

- **Telegram:** delerium_116
- **Email:** thexfiles116@gmail.com

---

### Briefly About Myself:

_For as long as I can remember, I have always loved computers. What they allow a person to do today is magic. The Internet has become a book of knowledge for a person. It's hard to resist the temptation to find out how it all works._

_I want to work as a front-end programmer and help connect people through the Internet._

---

### Skills:

- HTML5
- CSS3
- JS
- React
- Git
- npm
- Webpack
- Figma

---

### Code Example:

[Snail Sort](https://www.codewars.com/kata/521c2db8ddc89b9b7a0000c1/javascript)

```javascript
snail = function (array) {
  let result = [];

  while (array.length > 1) {
    let temp = [];
    let length = array.length;
    result = result.concat(array.shift());

    for (let i = array[0].length - 1; i >= 0; i--) {
      let newLine = [];
      for (let l = 0; l < length; l++) {
        newLine.push(array[l][i]);
      }
      temp.push(newLine);
    }

    array = temp;
  }

  result = result.concat(array.shift());
  return result;
};
```

---

### Education:

- GrSU -> 2009-2014 -> Программное обеспечение информационных технологий

---

### Languages:

- Russian (Native)
- English (Pre Intermediate)

---
