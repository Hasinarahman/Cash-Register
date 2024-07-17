# Cash Register 🚀

## Project Description 📝

> cash rigester  project created in HTML, CSS and javaScript it can provide the amount for customer.


### HTML:
```html

  <body>
  <h1>Cash Register App</h1>
  <div class="cash">
    <h2>Enter cash from customer:</h2>
    <input id="cash" type="number">
    <button id="purchase-btn">Purchase</button>
    <div id="change-due"></div>
  </div>
  <script src="script.js"></script>


```
### CSS:
```css

body {
  background-color: rgb(61, 16, 2);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 20px;
}



```
### JS:
```javascript

const cash = document.getElementById('cash');
const displayChangeDue = document.getElementById('change-due');
const purchaseBtn = document.getElementById('purchase-btn');

cash.addEventListener('keydown', (e) => {
  if (e.key === 'Enter') {
    purchaseBtn.click();
  }
});



```

## Demo 📸

![cash register](https://github.com/Hasinarahman/Cash-Register/assets/168626170/fb501b80-35bf-4c3d-aef3-0afeb59081c7)


## Deploy link
(https://hasinarahman.github.io/Cash-Register/)

## Technologies Used 🛠️

- HTML
- CSS
- JavaScript

## Features ⭐

- Building Cash Register App

## Author 👩‍💻


- LinkedIn: (linkedin.com/in/hasina-rahmani-4a21a9311)
- Email: (hasinarahmani548@gmail.com)
- GitHub:(https://github.com/Hasinarahman/Cash-Register)

