<!DOCTYPE html>
<html lang="en">
<header> 
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Galeri Foto</title>
    <style>

      body{
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        background: black;
        color: #eee;
      }

        header nav {
            display: flex;
            gap: .5rem;
            align-items: center;
        }
        header nav a {
            text-decoration: none;
            color: inherit;
            font-size: .9rem;
            text-transform: capitalize;
            border-radius: 100vw;
            padding: .5rem 1rem;
            transition: .3s ease;
        }
        header nav a:hover ,.active{
            background:rgb(172, 0, 134);
        }
        img{
            max-width: 1100px;
            height: auto;
        }

        .konten{
            margin:auto;
            padding-top: 5%;
            box-sizing :border-box;
            text-align: center;
        }
        
        .header1 img{
            width: 150px;
            height: 150px;
            border-radius: 100%;
            box-shadow: 0 6px 11px rgb(0, 172, 106);
            object-fit: cover;
        }

        .gallery {
          margin: 50px 0;
          display: grid;
          grid-template-columns: 1fr 1fr 1fr;
          grid-gap: 20px;
          scroll-behavior: auto;

        }
        
        .gallery img{
          width: 100%;
          height: 280px;
          object-fit: cover;
          border: 1px solid #eee;
          box-shadow: 1px 6px 9px rgb(0, 172, 106);
          border-radius: 25px;
          box-sizing: border-box;
          scroll-behavior: auto;
        }
        .gallery:hover{
          transform: translateY(-5px);
          box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
    </style>
    <nav>
      <a href="Portofolio.html" class="active"> Home </a>
      <a href="about.html"> Biodata </a>
      <a href="pendidikan.html"> Skill & Pendidikan </a>
      <a href="usaha.html"> Usaha </a>
      <a href="contact.html"> Contact</a>
    </nav>
  </header>
  <div class="konten">
    <div class="header1">
      <img src="/foto/IMG_8256.JPG" alt="header1">
      <h1> Gallery Valdo</h1>
      <p> This is Data Bases My Album full History</p>
    </div>
    <div class="gallery">
      <img src="/foto/IMG-20230112-WA0013.jpg"/> 
      <img src="/foto/IMG-20221206-WA0012(1).jpg"/> 
      <img src="/foto/IMG20211217100401.jpg"/> 
      <img src="/foto/IMG20220208165619.jpg"/> 
      <img src="/foto/IMG20220504132216.jpg"/>
      <img src="/foto/IMG_20230701_112509_736.jpg"/>
      <img src="/foto/temajok.jpg"/>
      <img src="/foto/2023-01-15-080556777.jpg"/>
      <img src="/foto/Picsart_23-01-16_01-34-41-573.jpg"/>
      <img src="/foto/2023-07-14-095332484.jpg"/>
      <img src="/foto/fotooo.jpg"/>
      <img src="/foto/IMG-2023.jpg"/>
      <img src="/foto/IMG-2022.jpg"/>
      <img src="/foto/biruuu.jpg"/>
      <img src="/foto/2023-04-26-061902960.jpg"/>
      <img src="/foto/IMG_8511.JPG"/>
      <img src="/foto/valdo.jpg"/>
      <img src="/foto/IMG_7763.JPG"/>
      <img src="/foto/IMG_20230620_103637_onFire(Abhi).jpg"/>
      <img src="/foto/Picsart_23-07-25_18-17-07-022.jpg"/>
      <img src="/foto/DSC00828.JPG"
    </div>
  </div>
</body>
</html>
