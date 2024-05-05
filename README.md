<!DOCTYPE html> 
<html> 
<head> 
  <title>MurashkinISP321/1 practica module№2 JavaScript Zadanie№1</title> 
  <style> 
    body, html {
      margin: 0;
      padding: 0;
    }
    #Perviy-paragaf{
        padding-top: 50px; 
    }
    .pagination a {
    color: black;
    float: left;
    padding: 8px 16px;
    text-decoration: none;
    transition: background-color 0.3s;
    }
    .pagination a.active {
    background-color: dodgerblue;
    color: white;
    }
    .pagination a:hover:not(.active) {
    background-color: #ddd;
    }
    .breadcrumb-container {
      position: fixed; 
      top: 0;
      left: 25%; 
      width: 100%; 
      background-color: #aae7da; 
      z-index: 1000; 
      padding: 10px 16px; 
    }

    .breadcrumb-container ul {
      padding: 0;
      margin: 0;
      list-style-type: none;
    }

    .breadcrumb-container ul li {
      display: inline; 
      font-size: 18px; 
    }

    .breadcrumb-container ul li + li:before { 
      padding: 8px; 
      color: black; 
      content: "/\00a0"; /* Декоративные слэши между элементами */
    }

    .breadcrumb-container ul li a { 
      color: #0275d8; 
      text-decoration: none; 
    }

    .breadcrumb-container ul li a:hover { 
      color: #01447e; 
      text-decoration: underline; 
    }

    #Header-One { 
      list-style-type: none; 
      margin: 0; 
      padding: 0; 
      width: 25%; 
      background-color: #f1f1f1; 
      position: fixed; 
      height: 100%; 
      overflow: auto; 
    }

    ul {
      list-style-type: none; 
      padding: 0;
    }

    ul#nav {
      padding-top: 50px; /* Отступ для списка, использовать, если список под шапкой */
    }

    .content {
      margin-left: 25%; 
      padding: 1px 16px; 
      height: 1000px;
      padding-top: 70px; /* отступ сверху для содержимого, чтобы не перекрывало навигацию */
    }

    #section1 { color: rgb(54, 119, 24); } 
    #section2 { color: rgb(95, 43, 13); } 

  </style> 
</head> 
<body> 
  <header id="Header-One">
    <h1>Навигация</h1> 
    <nav id="nav"> 
      <ul> 
        <li><a href="#">Главная</a></li> 
        <li><a href="JSpractica_1.html">О Камчатке</a></li> 
        <li><a href="JSpractica_2.html">Услуги</a></li> 
        <li><a href="JSpractica_3.html">Контакты</a></li> 
      </ul> 
    </nav> 
  </header> 
  <div class="breadcrumb-container">
    <ul class="breadcrumb"> 
      <li>Главное</li> 
      <li><a href="JSpractica_1.html">О Камчатке</a></li> 
      <li><a href="JSpractica_2.html">Услуги</a></li> 
      <li><a href="JSpractica_3.html">Контакты</a></li> 
    </ul>
  </div>
    <div style="margin-left: 25%; padding: 1px 16px; height: 1000px">
        
        <section id="section1">
        <article id="article1">
          <h2 id="Perviy-paragaf">Скалы Три Брата</h2>
          <figure id="figure1">
            <img src="https://tripplanet.ru/wp-content/uploads/europe/russia/petropavlovsk-kamchatsky/three-brothers.jpg" alt="Скалы Три Брата" style="width: 400px;">
            <figcaption>Скалы Три Брата</figcaption>
          </figure>
          <p>Три Брата — группа из трех выступающих из воды столбообразных скал (кекуров), расположенных на входе в Авачинскую бухту на Камчатке. </p>
        </article>
        <article id="article2">
          <h2>Авачинская Сопка</h2>
          <figure id="figure2">
            <img src="https://vsegda-pomnim.com/uploads/posts/2022-05/1651425119_5-vsegda-pomnim-com-p-vulkan-avacha-na-kamchatke-foto-5.jpg" alt="Авачинская Сопка" style="width: 400px;">
            <figcaption>Авачинская Сопка</figcaption>
          </figure>
          <p>Вулкан представляет собой молодой конус, возвышающийся над опоясывающим его «воротником» – останками старого конуса, уничтоженного вулканическим взрывом около 11 тысяч лет назад. Высота Авачи – 2749 метров над уровнем моря.
        </p>
        </article>
      </section>
      <section id="section2">
        <article id="article3">
          <h2>Вулканариум</h2>
          <figure id="figure3">
            <img src="https://i8.otzovik.com/2022/10/17/13890337/img/974982_36154225.jpeg" alt="Вулканариум" style="width: 400px;">
            <figcaption>Вулканариум</figcaption>
          </figure>
          <p>Музей состоит из трёх тематических залов и повествует об удивительном Камчатском крае и его вулканизме, 
            а также о происхождении и значении вулканов мира для всей нашей планеты.</p>
        </article>
        <article id="article4">
          <h2>Театр Драмы и Комедии</h2>
          <figure id="figure4">
            <img src="https://thumbs.dreamstime.com/b/%D0%BE%D1%81%D0%B2%D0%B5%D1%89%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BD%D0%BE%D1%87%D0%B8-%D0%B0%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%BD%D0%BE%D0%B0%D0%BA%D1%83%D1%81%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5-%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D1%8F-%D0%B4%D1%80%D0%B0%D0%BC%D1%8B-%D0%BA%D0%B0%D0%BC%D1%87%D0%B0%D1%82%D0%BA%D0%B8-%D0%B8-103649413.jpg" alt="Театр Драмы и Комедии" style="width: 400px;">
            <figcaption>Театр Драмы и Комедии</figcaption>
          </figure>
          <p>Историю театра на Камчатке принято вести от 21 апреля 1933 года, 
            когда труппа профессиональных артистов дала первое представление в Петропавловске
             — спектакль Д. Курдина «Междубурье».
          </p>
        </article>
      </section>
      <footer id="footer"><p>Открытые источники &copy; 2023</p></footer>
      <div class="pagination">
        <a href="#">&laquo;</a>
        <a class="active" href="JSpractica_1.html">1</a>
        <a href="JSpractica_2.html">2</a>
        <a href="JSpractica_3.html">3</a>
        <a href="m2sr1.html">4</a>
        <a href="#">&raquo;</a>
        </div>
    </div>
  </body>
</html>
