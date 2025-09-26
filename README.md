# KFC-html
site kfc
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css"> 
    <title>KFC</title>
</head>
<body>
    <nav>
        <ul class="menu">
            <li>
                <a href="#">Menu</a>
            </li>
            <li><a href="#">Restauracje</a></li>
            <li><a href="#">Ku(r)pony</a></li>
            <li><a href="#"><button>Nowosci</button></a></li>
        </ul>
    </nav>
    <main>
        <h1>Wiamy w KFC</h1>
        <p>Najlepsze jedzenie na wynos w miescie!</p>
        <input type="text" placeholder="Szukaj w menu...">
    </main>
</body>
</html>





style.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.menu {
    margin-right: 20px;
    list-style: none;    
}

.menu {
    border: 1px solid rgb(0, 225, 47);
    display: flex;
    align-items: center;
    justify-content: center;
}

.menu {
    display: flex;
    border: 1px solid red;
    width: 1024;
}

.menu li a {
    margin-right: 20px;
    list-style: none;
    font-style: 20px;
}

.menu li a {
    text-decoration: none;
    color: black;
}

.menu li button {
    border: none;
    background-color: red;
    padding: 5px 10px;
    color: white;
    cursor: pointer;
    font-size: 20px;
}

.menu li button:hover {
    background-color: darkred;
    text-transform: uppercase;
}

main {
    text-align: center;
}
