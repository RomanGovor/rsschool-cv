# Govor Roman
## Contact info
- Email: *[roma-govor2013@ya.ru](roma-govor2013@ya.ru)*
- VK: *[Me](https://vk.com/impish_benjamin)*
- Whatsapp : *+375 29 371-24-00*
## Summary
I want to be a ***great***, very ***good*** and very ***proficient*** Fullstack JS developer and start to work as a remote developer, I want to learn **ReactJS** and **Node.js**, **Python**, and **Java** for the Back-End.

At the moment I am developing skills **Front-End Development**.
## Skils
- ◾◾◾◽◽ C/C++
- ◾◽◽◽◽ Java
- ◾◽◽◽◽ Assembly
- ◾◽◽◽◽ JS, HTML, CSS

Have work experience in ***Visual Studio***, ***Visual Studio Code***, ***IntelliJ IDEA***, ***WebStorm***.<br>
I also have a little experience with [**Git**](https://github.com/RomanGovor).

## Code examples
```javascript
    getResource('http://localhost:3000/menu')
        .then(data => createCard(data));

    function createCard(data) {
        data.forEach(({img, altimg, title, descr, price}) => {
            const element = document.createElement('div');

            element.classList.add("menu__item");

            element.innerHTML = `
                <img src=${img} alt=${altimg}>
                <h3 class="menu__item-subtitle">${title}</h3>
                <div class="menu__item-descr">${descr}</div>
                <div class="menu__item-divider"></div>
                <div class="menu__item-price">
                    <div class="menu__item-cost">Цена:</div>
                    <div class="menu__item-total"><span>${price}</span> грн/день</div>
                </div>
            `;
            document.querySelector(".menu .container").append(element);
        });
    }

    axios.get(' http://localhost:3000/menu').then(data => {
        data.data.forEach(({img, altimg, title, descr, price}) => {
                     new MenuCard(img, altimg, title, descr, price, '.menu .container').render();
                 });
    });
```
## Education and experience
At the moment I am a *3rd* year student of the **Belarusian State University of Informatics and Radioelectronics**, Faculty of **Computer Systems and Networks**.

I am currently taking courses on the [*Udemy*](https://www.udemy.com/) platform on **Front-End development**. 
I have experience in writing systems programming (working with WinApi, the Registry). I wrote my own **HTTP server**.

## English
A2(Pre-intermediate)
