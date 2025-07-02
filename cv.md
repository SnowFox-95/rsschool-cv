# ALEXEY BESPYATYKH
---
##### Contacts
###### e-mail 
    - abespyatykh95@vk.com
###### Discord:
    - Alexey Bespyatykh (@snowfox-95)
---
##### About me:
    - 29 years old
    - I live in Kirov (Kirov region)
    - Mobile operator technical support employee since 2016
    - I love (in my free time) learning different things including IT. Lately I've been attracted to frontend
---
##### Skills
- HTML5
- SCSS 
- JS 
- Markdown
- GIT
- python
- Gulp
---
##### Code examples

```JS
let block = document.querySelector(".main");
let posText = document.querySelector(".posX");

block.addEventListener("mousemove", (e) => {
  posText.textContent = e.clientX;
  block.style.backgroundColor = `hsl(${e.clientX},80%,50%`;
});
```