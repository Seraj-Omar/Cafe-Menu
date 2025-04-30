# Cafe-Menu
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Cafe Menu</title>
        <style>
            body{
    padding: 20px;
    font-family: sans-serif;
    background-image: url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg);
}
div{
    border-radius: 5px;
}
h1,h2,p{
    text-align: center;
}
h1,h2{
    font-family: Impact, serif;
}
h1{
    font-size: 40px;
    margin-top: 0;
    margin-bottom: 15px;
}
h2{
    font-size: 30px;
}
hr{
    height: 2px;
    background-color: brown;
    border-color: brown;
}
img{
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin-top: -25px;
}
.menu{
    background-color: burlywood;
    width: 80%;
    max-width: 500px;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
}
.flavor,.dessert {
    text-align: left;
    width: 75%;
}
  
.price {
    text-align: right;
    width: 25%;
}
.item p{
    font-size: 18px;
    display: inline-block;
    margin-top: 5px;
    margin-bottom: 5px;
}
.established {
    font-style: italic;
}
.bottom-line{
    margin-top: 25px;
}
.address{
    margin-bottom: 5px;
}
/* FOOTER */
footer{
    font-size: 14px;
}
a{
    color: black;
}
a:visited{
    color: black;
}
a:hover{
    color: brown;
}
a:active{
    color: brown;
}
        </style>
    </head>
    <body>
        <div class="menu">
            <main>
                <h1>CAMPER CAFE</h1>
                <p class="established">Est. 2020</p>
                <hr>
                <section>
                    <h2>Coffee</h2>
                    <img src="https://cdn.freecodecamp.org/curriculum/css-cafe/coffee.jpg" alt="coffee icon">
                    <article class="item">
                        <p class="flavor">French Vanilla</p><p class="price">3.00</p>
                    </article>
                    <article class="item">
                        <p class="flavor">Caramel Macchiato</p><p class="price">3.75</p>
                    </article>
                    <article class="item">
                        <p class="flavor">Pumpkin Spice</p><p class="price">3.50</p>
                    </article>
                    <article class="item">
                        <p class="flavor">Hazelnut</p><p class="price">4.00</p>
                    </article>
                    <article class="item">
                        <p class="flavor">Mocha</p><p class="price">4.50</p>
                    </article>
                </section>
                <section>
                    <h2>Desserts</h2>
                    <img src="https://cdn.freecodecamp.org/curriculum/css-cafe/pie.jpg" alt="pie icon">
                    <article class="item">
                        <p class="dessert">Donut</p><p class="price">1.50</p>
                    </article>
                    <article class="item">
                        <p class="dessert">Cherry Pie</p><p class="price">2.75</p>
                    </article>
                    <article class="item">
                        <p class="dessert">Cheesecake</p><p class="price">3.00</p>
                    </article>
                    <article class="item">
                        <p class="dessert">Cinnamon Roll</p><p class="price">2.50</p>
                    </article>
                </section>
            </main>
            <hr class="bottom-line">
            <footer>
                <p><a href="https://www.linkedin.com/in/seraj-omar-aa5946312/" target="_blank">Visit My LinkedIn</a></p>
                <p class="address">&copy; Seraj Omar</p>
            </footer>
        </div>
    </body>
</html>
