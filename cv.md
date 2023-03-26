# Viktoriya Bobr
### Contact infomation
* Phone: +375 (33) 644-16-56
* Email: bobroshaa@gmail.com
* Telegram:  [@bobroshaa](https://t.me/bobroshaa)
* GitHub: https://github.com/lijo-lijo
* Discord-nickname: Vika Bobr(@lijo-lijo)

***

### About me
I'm third year student of BSUIR. In the 4th semester we have subject called Program Interface Development. By the way, teachers were from EPAM. We make our own website in these classes. And i found it very interesting, because you do something and you instantly see what changed in your project. That's the reason why I'm here. 

I hope my interest in the Frontend, responsibility and the desire to gain new knowledge will help me graduate from this school!

***

### Skills
* HTML, CSS
* JavaScript
* Git
* Algorithms and data structures

***

### Code example
Task ["Replace With Alphabet Position"](https://www.codewars.com/kata/546f922b54af40e1e90001da) from CodeWars: *In this kata you are required to, given a string, replace every letter with its position in the alphabet.If anything in the text isn't a letter, ignore it and don't return it. "a" = 1, "b" = 2, etc.*
```
function alphabetPosition(text) {
  return text.split('').map((item) => {
    if (item.toLowerCase() >= 'a' && item.toLowerCase() <= 'z') {
      return item.toLowerCase().codePointAt(0) - 'a'.codePointAt(0) + 1;
    }
    return '';
  }).filter((item) => item !== '').join(' ');
}
```
