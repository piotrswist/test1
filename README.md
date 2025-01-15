# test1
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Moja Strona Internetowa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e0f7e0;
        }
        header {
            background-color: #2e7d32;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #388e3c;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #4caf50;
        }
        main {
            padding: 20px;
        }
        footer {
            background-color: #2e7d32;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Witaj na Mojej Stronie!</h1>
</header>

<nav>
    <a href="#home">Strona Główna</a>
    <a href="#about">O Mnie</a>
    <a href="#contact">Kontakt</a>
    <a href="#solar">Panele Fotowoltaiczne</a>
    <a href="#renewable">Odnawialne Źródła Energii</a>
</nav>

<main>
    <section id="home">
        <h2>Strona Główna</h2>
        <p>Witaj na mojej stronie! To jest przykładowa strona internetowa stworzona za pomocą HTML i CSS.</p>
    </section>

    <section id="about">
        <h2>O Mnie</h2>
        <p>Jestem pasjonatem technologii i tworzę strony internetowe. Na tej stronie znajdziesz informacje na temat moich projektów.</p>
    </section>

    <section id="contact">
        <h2>Kontakt</h2>
        <p>Jeśli chcesz się ze mną skontaktować, wyślij wiadomość na adres email: <a href="mailto:kontakt@example.com">kontakt@example.com</a></p>
    </section>

    <section id="solar">
        <h2>Panele Fotowoltaiczne</h2>
        <p>Panele fotowoltaiczne to urządzenia, które przekształcają energię słoneczną w energię elektryczną. Są one ekologicznym rozwiązaniem, które pomaga zmniejszyć emisję dwutlenku węgla.</p>
        <h3>Opis Paneli</h3>
        <ul>
            <li>Panel A: Wysoka wydajność, cena: 1000 PLN</li>
            <li>Panel B: Średnia wydajność, cena: 800 PLN</li>
            <li>Panel C: Niska wydajność, cena: 600 PLN</li>
        </ul>
        <h3>Korzyści z Paneli Fotowoltaicznych</h3>
        <ul>
            <li>Oszczędność na rachunkach za prąd</li>
            <li>Zmniejszenie emisji CO2</li>
            <li>Wzrost wartości nieruchomości</li>
        </ul>
    </section>

    <section id="renewable">
        <h2>Odnawialne Źródła Energii</h2>
        <p>Odnawialne źródła energii to takie, które są odnawialne w krótkim czasie. Przykłady to energia słoneczna, wiatrowa, wodna i geotermalna.</p>
        <h3>Korzyści z OZE</h3>
        <ul>
            <li>Zmniejszenie emisji CO2</li>
            <li>Oszczędność kosztów energii</li>
            <li>Ochrona środowiska</li>
        </ul>
    </section>
</main>

<footer>
    <p>&copy; 2025 Moja Strona. Wszystkie prawa zastrzeżone.</p>
</footer>

</body>
</html>
