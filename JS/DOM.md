# Manipulando a DOM
## Alternar a classe de uma div com <code>toggle()</code>
~~~javascript
const nav = document.querySelector('#header nav')
const toggle = document.querySelectorAll('nav .toggle')

for (const element of toggle) {
    element.addEventListener('click', () => {
        nav.classList.toggle('show')
    })
}
~~~
### **<code>visibility: hidden</code>**
* deixa de mostrar o elemento, ou seja, ele deixa de ser visível na página mas seu espaço continua ocupado, ou seja, o layout da página não é alterado por causa disto.