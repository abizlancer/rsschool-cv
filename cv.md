# Abdulaziz Pulatov
====
### Front-end developer
====
## Contact info:
**Telegram:** @abiz03
**Phone:** +998 90 903 11 23
**Email:** abizlancer@gmail.com
**Discord:** Abiz
====
## About me:
I'm a Front-end developer. By this course I want to become a EPAM Software Engineer but my main goal in a year to become a Senior developer.
====
## My skilss:
* Figma
* Git, Github
* Html (preprocessor PUG)
* CSS (preprocessor SCSS, Bootstrap)
* Webpack
* JavaScript
    + Vue Js Vuex VueRouter
    + React (basic)
    + GSAP (GreenSock)
* Php, MySql (basic)
=====
## Code example:
16+18=214 For this kata you will have to forget how to add two numbers. In simple terms, our method does not like the principle of carrying over numbers and just writes down every number it calculates
```javascript
function add(num1, num2) {
  num1 = num1.toString().split('').reverse()
  num2 = num2.toString().split('').reverse()
  let result = []
     
  for(let i = 0; i < (num1.length > num2.length ? num1.length : num2.length); i++) {
    if(num1[i] == undefined) {
      num1[i] = 0
    } else if(num2[i] == undefined) {
      num2[i] = 0
    }
    result[i] = (+num1[i]) + (+num2[i])
  }
  
  return +result.reverse().join('')
}
```
====
## Experience:
I have a little experience as a Front-end developer. I worked in digital marketing compony [Digital360 Agency](https://digital360.uz/). My main task was to convert Figma templates into code using webpack pug scss and js and ext. Now I work as a Freelancer. By the link bellow you can visit my site and see my projects !
[abizlancer](http://abizlancer.42web.io/)