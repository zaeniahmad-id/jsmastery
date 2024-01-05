# Tutorial Singkat

## <a>🤸 Tutorial Slide Button</a>

**Buat Function Javascript.**
<br>
Step pertama, buat fungsi javascript seperti berikut untuk menangani scroll:


Tombol untuk scroll ke kanan:
```javascript
// main.js
/** rightscrollbutton */
function scrollToNextCard() {
  var container = document.getElementById('id-kontainer-horizontal');
  container.scrollLeft += window.innerWidth / 2.1;}
```

Tombol untuk scroll ke kiri:
```javascript
// main.js
/** leftscrollbutton */
function scrollToPrevCard() {
  var container = document.getElementById('id-container-horizontal');
  container.scrollLeft -= window.innerWidth / 2.1;}
```
<br>
<br>
<br>

**Konfigurasi HTML.**
<br>
Panggil fungsi di atas kedalam tombol yang ada di div elemen horizontal scroll:
```html
<div class="container">
  <span class="tombol-kiri" onclick="scrollToPrevCard()"></span>
  <span class="tombol-kanan" onclick="scrollToNextCard()"></span>
</div>
```

Buat id horizontal scroll div, lalu integrasikan dengan kode js di atas:
```html
<div class="horizontal-scroll id="id-kontainer-horizontal">
  <div class="card">
    <img>
    <p>
  </div>
</div>
```
