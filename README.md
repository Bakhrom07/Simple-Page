# Simple-Page
Про новости 
 <html>
<head>
<meta charset="UTF-8">
<title>Название страницы - отображается на вкладке браузера и в поиске</title>
<style type="text/css">
a{
color: #fff;
text-decoration: none;
}
html{
background: #E0E4EF;
min-height: 100%;
font-family: Helvetica;
display: flex;
flex-direction: column;
}
body{
margin: 0;
padding: 0 15px;
display: flex;
flex-direction: column;
flex: auto;
}
h1{
margin-top: 0;
}
h1, p{
color: #006064;
}
img{
border: 0;
}
.header{
width: 100%;
min-width: 460px;
max-width: 960px;
margin: 0 auto 30px;
padding: 30px 0 10px;
display: flex;
flex-wrap: wrap;
justify-content: space-between;
box-sizing: border-box;
}
.logo{
font-size: 1.5rem;
color: #fff;
text-decoration: none;
margin: 5px 0 0 5px;
justify-content: center;
align-items: center;
display: flex;
flex: none;
align-items: center;
background: #839FFF;
width: 130px;
height: 50px;
}
.nav{
margin: -5px 0 0 -5px;
display: flex;
flex-wrap: wrap;
}
.nav-item{
background: #BDC7FF;
width: 130px;
height: 50px;
font-size: 1.5rem;
color: #fff;
text-decoration: none;
display: flex;
margin: 5px 0 0 5px;
justify-content: center;
align-items: center;
}
.sqr{
height: 300px;
width: 300px;
background: #FFDB89;
}

.main{
width: 100%;
min-width: 460px;
max-width: 960px;
margin: auto;
flex: auto;
box-sizing: border-box;
}
.box{
font-size: 1.25rem;
line-height: 1.5;
margin: 0 0 40px -50px;
display: flex;
flex-wrap: wrap;
justify-content: center;
}
.box-base{
margin-left: 50px;
flex: 1 0 430px;
}
.box-side{
margin-left: 50px;
font: none;
}
.box-img{
max-width: 100%;
height: auto;
}
.content{
margin-bottom: 30px;
display: flex;
flex-wrap: wrap;
}
.banners{
flex: 1 1 50px;
}
.banner{
background: #FFDB89;
width: 100%;
min-width: 100px;
min-height: 200px;
font-size: 3rem;
color: #fff;
margin: 0 0 30px 0;
display: flex;
justify-content: center;
align-items: center;
}
.posts{
margin: 0 0 100px 30px;
flex: 1 1 200px;
}
.comments{
margin: 0 0 10px 30px;
flex: 1 1 40px;
}
.comment{
display: flex;
}
.comment-side{
padding-right: 20px;
flex: none;
}
.comment-base{
flex: auto;
}
.comment-avatar{
background: #FFA985;
width: 50px;
height: 50px;
}
.footer{
background: #FF4866;
width: 100%;
max-width: 960px;
min-width: 460px;
color: #fff;
margin: auto;
padding: 15px;
box-sizing: border-box;
}

@media screen and  (max-width: 800px) {
.banners{
margin-left: -30px;
display: flex;
flex-basis: 100%;
}
.banner{
margin-left: 20px;
}
.posts{
margin-left: 0;
}
}
@media screen and  (max-width: 600px) {
.content{
display: block;
}
.banners{
margin: 0;
display: block;
}
.banner{
margin-left: 0;
}
.posts{
margin: 0;
}
}
</style>
</head>
<body>
<header class="header">
<a class="LOGO">
LOGO
</a>
<nav class="nav">
<a href="#posts" class="nav-item">Посты</a>
<a href="#comments" class="nav-item">Комменты</a>
<a href="#footer" class="nav-item">Инфо</a>
</nav>

</header>
<main class="main">
<div class="box">
<div class="box-base">
<h1><p style="text-align: center">
Новости</h1>
<p>Как писать новости? </p>
<img src="https://yt3.ggpht.com/ytc/AMLnZu9r9Rp5AKujraTCL7fx-SFEtmJNAlV_7dZ6Ty_2hw=s900-c-k-c0x00ffffff-no-rj" width="600" height="800" border="10" align="middle" vspace="5" hspace="4" 
>


</div>
<div class="box-side">
<div class="sqr">

</div>
</div>
</div>
<div class="content">
<div class="banners">
<div class="banner">Заголовок-интрига-1</div>
<img src="https://www.gazeta.uz/media/img/2020/08/l8WOc115977650129310_b.jpg">
<div class="banner">Заголовок-интрига-2</div>
<img src="https://www.gazeta.uz/media/img/2022/12/q6b3kP16708346427764_b.jpg">
<div class="banner">Заголовок-интрига</div>
<img src="https://www.gazeta.uz/media/img/2022/12/oLa0zW16707765476889_b.jpg">
</div>
<div class="posts"  id="posts">
<div class="post">
<h1>Пост #1</h1>

</div>
<div class="post">
<h1>Пост #2</h1>

</div>
<div class="post">
<h1>Пост #3</h1>

</div>
</div>
<div class="comments"  id="comments">
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">Комментарий #1</h1>
<p>Бензин Аи-80 может подешеветь до 5500 сумов
10 декабря 2022, 10:54
Почти 300 заправок лишились поставок бензина из-за повышения цен и некачественного топлива
9 декабря 2022, 15:25
Узбекистан активизирует переговоры по импорту газа, энергии, угля и мазута
8 декабря 2022, 09:33
Дефицита бензина Аи-80 нет — «Узбекнефтегаз»
6 декабря 2022, 12:17</p>
</div>
</div>
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">Комментарий #2</h1>
<p>Имидж предприятия, в рамках сегодняшних воззрений, вполне вероятен. Стоит отметить, что имидж версифицирован. Экспертиза выполненного проекта осмысленно программирует из ряда вон выходящий клиентский спрос. </p>
</div>
</div>
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">Комментарий #3</h1>
<p>То есть нынешний декабрь не такой уж аномальный. Обычный </p>
</div>
</div>
</div>
</div>
</main>
<footer class="footer"  id="footer">
<h2><p style="text-align: center">
	© 2008-2022 «Газета.uz»
	Новости для людей.<
</footer>
</body>
</html>
