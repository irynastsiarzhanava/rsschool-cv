# <div align="center">Iryna Stsiarzhanava - <br>Front-end Developer</div>


## Contact Information
**Email** - <iryna.stsiarzhanava@gmail.com><br>
**Linkedin profile** - <https://www.linkedin.com/in/iryna-stsiarzhanava-36900959><br>
**Phone number** +48-530-432-344<br>
**Adress** - ul. Katowicka 57/B, 31-351, Kraków<br>


# Summary

Hi! I am a front-end developer with 3-years experience of working in real commercial projects. Right now I am on maternity leave (from middle of 2019) and planning coming back to work in 6-8 months. I started RS JS course to refresh my knowledge and be up-to-date with nowadays technologies and best practices.

# Skills

**HTML/CSS**: HTML5, CSS3, responsive design (media queries, grid view) - advanced  
**JavaScript**: ES5- medium, AngularJS - medium, ES6,Angular 4/5, Redux - basic  
**Unit testing**: Karma and Jasmine - basic  
**Frameworks**: JQuery, Bootstrap, SASS/LESS, Compass, Font Awesome - advanced  
**Version control systems**: Git - advanced Development platforms: GitHub, Bitbucket - advanced  
**Bug tracking systems**: Jira, Teamlab, Lighthouse - advanced  
**Operating system**: Linux (Ubuntu) - advanced  
**Browsers**: IE, Chrome, Mozilla, Opera, Safari - advanced  
**Editors**: Sublime Text, Adobe Photoshop/Gimp - advanced  
**Development method experience**: Scrum - medium  
**Languages**: English (upper-intermediate), Russian/Belorussian (native), Polish (upper-intermediate), Italian (elementary)

# Code examples

Function that when given a number (n) returns the n-th number in the Fibonacci Sequence.
```
function nthFibo(n) {
  var i;
  var fib = [];
  
  fib[0] = 0;
  fib[1] = 1;
  for (i = 2; i <= 100; i++) {
    fib[i] = fib[i - 2] + fib[i - 1];  
  }
  return fib[n-1];
}
```