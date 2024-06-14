<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width" />
    <title>Aza's coffee shop</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <nav>
        <div class="container">
          <ul class="nav-links">
            <li><a href="#">Нүүр хуудас</a></li>
            <li><a href="#locations">Салбарууд</a></li>
            <li><a href="#comments">Сэтгэгдэлүүд</a></li>
            <li><a href="#contact">Холбоо барих</a></li>
          </ul>
        </div>
      </nav>
      <div class="hero">
        <div class="container">
          <h1>Халуун зуны урамшуулал</h1>
          <a href="#home" class="btn">Нүүр хуудас</a>
        </div>
      </div>
    </header>

    <section id="specialties">
      <div class="container">
        <div class="specialties-grid">
          <div class="specialty-item">
            <img
              src="images/mocha.png"
              alt="Americano"
              height="150"
              width="150"
            />
            <h3>Americano</h3>
            <p>Американо кофе</p>
            <p class="price">5000 ₮</p>
          </div>
          <div class="specialty-item">
            <img src="images/mocha.png" alt="Latte" height="150" width="150" />
            <h3>Latte</h3>
            <p>latte кофе</p>
            <p class="price">8000 ₮</p>
          </div>
          <div class="specialty-item">
            <img src="images/mocha.png" alt="Tea" height="150" width="150" />
            <h3>Цай</h3>
            <p>Цай</p>
            <p class="price">4000 ₮</p>
          </div>
          <div class="specialty-item">
            <img src="images/mocha.png" alt="Tea" height="150" width="150" />
            <h3>Ундаа</h3>
            <p>Ундаа</p>
            <p class="price">4000 ₮</p>
          </div>
        </div>
      </div>
    </section>

    <section id="locations">
      <div class="container">
        <ul>
          <li>Улаанбаатар, Гэндэнгийн гудамж</li>
          <li>Завхан, Улиастай</li>
          <li>Дархан</li>
        </ul>
      </div>
    </section>

    <section id="user-comments">
      <div class="container">
        <h2>Хэрэглэгчийн Сэтгэгдэлүүд</h2>
        <div class="user-comment">
          <p>Гоё кофе</p>
          <p class="username">Бат</p>
        </div>

        <div class="user-comment">
          <p>Гоё кофе</p>
          <p class="username">Гэрэл</p>
        </div>
      </div>
    </section>

    <footer id="contact">
      <ul>
        <li>Email: luckymunkh@gmail.com</li>
        <li>Утас: (+976) 95539884</li>
      </ul>
    </footer>
  </body>
</html>