# Tutorial

## <a>🤸 Tutorial Javascript</a>

Step pertama beri ID pada Div horizontal scroll yang ingin kalian beri tombol untuk meng-slide

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

Step pertama, buat fungsi javascript seperti berikut untuk menangani scroll:

Untuk scroll ke kanan:
```javascript
/** rightscrollbutton */
function scrollToNextCard() {
  var container = document.getElementById('cardcontainer');
  container.scrollLeft += window.innerWidth / 2.1;}
```

Untuk scroll ke kiri:
```javascript
/** leftscrollbutton */
function scrollToPrevCard() {
  var container = document.getElementById('cardcontainer');
  container.scrollLeft -= window.innerWidth / 2.1;}
```
