# **Elvira Kiamova**

*********

## **Contacts**

* **Address:** Russia, Ufa
* **E-mail:** ela.kiyamova@yandex.ru
* **Phone:** +7 937 361 19 88

*********

## **About Me**

The purpose of my training is to get a good knowledge base on programming for further use in work. A constant desire for something new and challenging led me to this school. 

*********

## **Skills**

* HTML
* CSS
* JavaScript (base)
* Git
* Figma(for web development)
* Editors: Sublime, VSCode

*********

## **Code examples**

The function takes a string, extracts the digits from 0 to 9 contained in it and returns them as a positive integer.

```
function returnsNumber(str) {
  let string = '';
  if (typeof str === 'number') {
    string = parseInt(Math.abs(str).toString().replace('.', ''), 10);
  }
  for(let i = 0; i <= str.length - 1; i++) {
    const pars = Number.isNaN(parseInt(str[i], 10));
    if (pars === false) {
      string += str[i];
    }
  }
  if (string === '') {
    return NaN;
  }
  return +string;
}

returnsNumber('2023 год'); // 2023
returnsNumber('ECMAScript 2022'); // 2022
returnsNumber('1 кефир, 0.5 батона'); // 105
returnsNumber('агент 007'); // 7
returnsNumber('а я томат'); // NaN
returnsNumber(2023); // 2023
returnsNumber(-1); // 1
returnsNumber(1.5); // 15
```

*********
## **Education**

* **University:** Samara State University of Railway Transport, specialty "engineer"

*********

## **English**

Beginner
