<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Practica</title>
    <!--ESTILOS-->
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@600&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Oswald&display=swap" rel="stylesheet">
</head>
<body>

    <!--AQUI ESTA MI IMAGEN-->
    <header>
        <img src="CODE.png">
    </header>

    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Categorias</a></li>
            <li><a href="#">Noticias</a></li>
        </ul>
    </nav>

    <div>

        <section>
            <aside>
               <H1>William Afton</H1>  
                <p>
                   Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eos distinctio dolor non magni voluptate enim possimus, omnis natus iure sapiente provident quibusdam ratione recusandae laborum? Molestias, unde veniam optio veritatis ratione sint quas aspernatur porro quo voluptas, facere sapiente! Deleniti sapiente vero, inventore quibusdam itaque nemo saepe illum! Nam beatae placeat quasi temporibus nostrum quas inventore nisi ea velit perspiciatis.
                </p>
            </aside>
        </section>
       </div>

    <!--AQUI EL PRIMER TITULO Y EL TEXTO-->
    <div>
    <H1>Freddy's Fazbear Pizza</H1>

    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur quisquam earum ad maiores laborum! Quia, illo aperiam vel placeat saepe doloremque molestiae eveniet ipsa velit nobis quos a aliquid odit architecto libero mollitia aspernatur rerum maiores autem, rem, ipsam dolore. Nemo facere, in quas incidunt optio eveniet itaque delectus sint voluptates totam quo vero dolorem doloremque eligendi harum natus deserunt eum tempore nisi maxime asperiores, molestias quia corporis! Obcaecati, quia!
    </p>
    </div>   

    <!--AQUI ESTA EL SEGUNDO TITULO Y EL TEXTO-->
    
    <div>
    <H1>La Mordida del 87</H1>

    <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptas ea commodi porro quia, modi soluta ullam officiis. Officia similique, aspernatur soluta dicta iure expedita autem libero. Ipsa unde provident ex consequuntur, obcaecati quia libero magnam, perspiciatis praesentium eos aspernatur omnis neque explicabo quo illum quod recusandae quae hic dolore dolor tempore! Deleniti necessitatibus delectus, culpa tempore pariatur commodi iste saepe quidem aliquid et, tenetur, minima suscipit rem iure quae? Deserunt enim architecto nesciunt blanditiis odio veniam dicta nihil! Quis, et!
    </p>
    </div>
     

     <footer>
        <p>Samil Moret - 10/06/2020</p> 
     </footer>
</body>
</html>

* {
    padding: 0;
    margin: 0;
}

/*AQUI ESTILIZO EL CUERPO DE LA PAGINA*/
body {
    background: rgb(226, 225, 225);
    margin: 10%; 
    position: relative;
    margin-top: 20px;
    height: 500px;
    width: 95%;
    margin-left: 10%
}

h1 {
    font-family: 'Oswald', sans-serif;
    margin-left: 0.5cm;
}

p {
    font-size: 20px;
    padding: 0.5cm;
    font-family: Arial, Helvetica, sans-serif;
}

img {
    width: 2cm;
    
}

li {
    display: inline;
    margin: 0.5cm;
    font-family: 'Oswald', sans-serif;
}

a {
    text-decoration: none;
    color: rgb(255, 254, 254);

}

nav {
    background-color: rgb(7, 145, 209);
    padding: 0.2cm;
    height: 40px;
    font-size: 21px;
    margin-right: 18.6%;
}

div {
    width: 60%;    
    position: relative;
    margin-top: 20px;
    background: white;
    width: 60%
}

aside  {
    background: rgb(255, 124, 2);
    width: 350px;
    border: none;
    margin-left:  102%;
    position: absolute;
}

footer {
    text-align: center;
    padding: 0.5cm;
    background: black;
    color: white;
    position: relative;
    margin-top: 20px;
    margin-right: 18.6%;
}
