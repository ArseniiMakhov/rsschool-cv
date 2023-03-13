# ***Arsenii Makhov***
## My contacts:
---
**Phone:** +375-33-377-66-56
**E-mail:** arseniimakhov@gmail.com
**Git-Hub:** https://github.com/ArseniiMakhov
**Telegram:** @Arsen_Sanbl4
**Linkedin:** https://www.linkedin.com/in/arsenii-makhov-884287265/
## About me:
---
I am 23 years old. I really need in activities where I can develop during my life. That is why I`m here. My goal is to gain knowledge in the field of front-end development.

### My strengths:
* Quick learner
* Active
* Team playing
* Leader

### Skills:
* HTML
* CSS
* JavaScript
* Git/GitHub
* SASS/SCSS
* React(in process...)

## Code examle: 
```
function binarySearch(value, list) {
    let first = 0;    //left endpoint
    let last = list.length - 1;   //right endpoint
    let position = -1;
    let found = false;
    let middle;
 
    while (found === false && first <= last) {
        middle = Math.floor((first + last)/2);
        if (list[middle] == value) {
            found = true;
            position = middle;
        } else if (list[middle] > value) {  //if in lower half
            last = middle - 1;
        } else {  //in in upper half
            first = middle + 1;
        }
    }
    return position;
}
```
## Education:
---
* Polotsk State University
    * Сhemical production machines and apparatuses
* It-academy
    * Basic HTML/CSS/JS
* Rsschool
    * Stage#1 (in process...)
## Languages:
---
* **Russian** - native speaker
* **English** - A2-B1