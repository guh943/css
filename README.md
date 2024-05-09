#HTML<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body><header>
    Meu site
</header>
<nav>
    <a href="#">home</a>
    <a href="#">sobre</a>
    <a href="#">contato</a>
    <a href="#">item4</a>
    <a href="#">item5</a>
</nav>
<div class="container">
    <aside>
        <h2>Menu lateral</h2>

        <ul>
            <li><a href="#">item 1</a></li>
            <li><a href="#">item 2</a></li>
            <li><a href="#">item 3</a></li>
     </ul>
    
    </aside>
    <article>
<h2>conteudo principal</h2>
<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Magni reiciendis accusamus doloribus illo fuga eos sequi iusto ipsam, praesentium facere labore ratione accusantium. Eum eveniet odio aliquid blanditiis, quia quis.</p>
</article>
</div>
    <footer><p>2024 Meu site. Todos os direitos reservados</p></footer>

</body>
</html>







# css
@charset "UTF-8";
body{
    margin: 0;
    font-family: Arial,sans-serif;
}
header,nav,main,footer{
    padding: 20px;
    background-color: rgb(74, 66, 47);
    color: white;
}
header{
    text-align: center;
}
nav{
    display: flex;
    justify-content: space-around;
}
nav a{
    color: white;
}
.container{
    display: grid;
    grid-template-columns: 1fr 3fr;
    gap: 20px;
    margin: 20px;
}
