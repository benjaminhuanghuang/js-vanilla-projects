# Build 15 JavaScript Projects - Vanilla JavaScript Course
- https://www.youtube.com/watch?v=3PHXvlpOkf4&t=2380s
- https://github.com/john-smilga/javascript-basic-projects



## Color Flipper
```
  const btn = document.getElementById("btn");
  const color = document.querySelector(".color");               // select


  function getRandomNumber() {
    return Math.floor(Math.random() * colors.length);
  }

  document.body.style.backgroundColor = colors[randomNumber];   // change color
  color.textContent = colors[randomNumber];                     // change text
```


## Counter
Add event listener for buttons
```
const btns = document.querySelectorAll(".btn");     // select    

btns.forEach(function (btn) {
  btn.addEventListener("click", function (e) {
    const styles = e.currentTarget.classList;       //  distinguish the buttons
    if (styles.contains("decrease")) {
      ...
    }
  }
})
```


## Reiviews
```
<div class="img-container">
```

```
indow.addEventListener("DOMContentLoaded", function () {
});
```

##
```
const navToggle = document.querySelector(".nav-toggle");
const links = document.querySelector(".links");

navToggle.addEventListener("click", function () {
  links.classList.toggle("show-links");
});
```