# Svetlana Ilina
## My Contact Info:
* Location: Tbilisi, Georgia
* Phone: +995 595 017 843
* Email: svetailina1987@gmail.com
* GitHub: [SvetaIlina](https://github.com/SvetaIlina)
### About Me:
I've been studying Frontend for six months. But I realized, that I needed a more structured approach to learning. My goal is to get as much knowledge about front-end development as possible.

I have completed several free courses and I want to continue to develop myself. I really enjoy learning new things.

#### My strengths:
* diligence
* communication skills
* striveing for self-development
* stress resistance
* quick learner
### Skills
* HTML/CSS (SASS/SCSS, BEM)
* JavaScript (Basic)
* Git/GitHub
* Gulp, Webpack
### Code Example
**KATA from CODEWARS:** 
Task is to sort a given string. Each word in the string will contain a single number. This number is the position the word should have in the result.

Note: Numbers can be from 1 to 9. So 1 will be the first word (not 0).

If the input string is empty, return an empty string. The words in the input String will only contain valid consecutive numbers.

Examples
```
"is2 Thi1s T4est 3a"  -->  "Thi1s is2 3a T4est"
"4of Fo1r pe6ople g3ood th5e the2"  -->  "Fo1r the2 g3ood 4of th5e pe6ople"
""  -->  ""
```
Code
```function order(words){
  const arr = words.split(' ')
  let newArr = []
  arr.forEach(el => {
    let index = el.match(/\d+/g)
    newArr[index-1] = el
    
  });

  return (newArr.join(' '));
  
}```