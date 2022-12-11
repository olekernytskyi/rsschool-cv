#Oleksandr Kernytskyi

##Contacts:
*Email: olk3258@gmail.com
*Phone:
  +380664724621 (only **Telegram**)
  +48791910789
*GitHub: [Oleksandr Kernytskyi](https://github.com/olekernytskyi)
*Location: Lublin, Poland
##About Me
I am a simple man with a big willing to became a good coder and a big dreams. Also learned 3d modelling and rendering as a hobby

##Skills
*HTML
*CSS
*JavaScript
*3d modelling
*Git

##Code Example

```
function expandedForm(num) {
  // Your code here
  let result = [];
  let x = 10;
  for (let i = 0; i < num.toString().length; i++) {
    if (num % x !== 0) {
      result.unshift(num % x);
      num = num - (num % x)
    } 
    x = x * 10;
  }
  let finalString = '';
  for (let k = 0; k < result.length; k++) {
  	finalString = finalString + result[k];
    if (k !== result.length - 1) {
    finalString += ' + ';
    }
  }
  return finalString
}
```
##Experience
*[6 kyu - Codewars](https://www.codewars.com/users/olekernytskyi/completed_solutions)

##Education
*National University "Lviv Politechnik" - bachelor degree

##Courses
*W3Schools
*[FructCode:HTML\CSS Advanced](https://fructcode.com/ru/certificates/058e495aa6c2f3aeb49e7b7faa112e4e/ru/)

##Languages
*English - B1
*Ukrainian - Native
*Polish - B2
*Russian - Fluent
