<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SZN.no - Domener til salgs</title>
    <style>
        /* Reset basic styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #F4F4F4;
            color: #333;
        }

        /* Header */
        header {
            background-color: #FF6A00; /* GoDaddy's orange color */
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 36px;
        }

        header h1 {
            font-weight: bold;
        }

        header p {
            font-size: 18px;
            margin-top: 10px;
        }

        /* Main section */
        main {
            padding: 50px 20px;
            max-width: 1200px;
            margin: 0 auto;
            text-align: center;
        }

        h2 {
            font-size: 28px;
            margin-bottom: 40px;
            color: #FF6A00;
        }

        .domain-list {
            display: flex;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
        }

        /* Domain item styling */
        .domain-item {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            width: 250px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s ease, box-shadow 0.3s ease;
        }

        .domain-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        .domain-name {
            font-size: 22px;
            font-weight: bold;
            color: #333;
            margin-bottom: 10px;
        }

        .buy-button {
            background-color: #FF6A00;
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            text-transform: uppercase;
            transition: background-color 0.3s ease;
        }

        .buy-button:hover {
            background-color: #E55A00;
        }

        /* Sell Domain Button */
        .sell-button {
            background-color: #333;
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            text-transform: uppercase;
            margin-top: 30px;
            transition: background-color 0.3s ease;
        }

        .sell-button:hover {
            background-color: #444;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        footer p {
            font-size: 14px;
        }
    </style>
</head>
<body>

<header>
    <h1>SZN.no</h1>
    <p>Din kilde for premium domener til salgs</p>
</header>

<main>
    <h2>Tilgjengelige domener til salgs</h2>
    <div class="domain-list">
        <!-- Domain 1: frakting.no -->
        <div class="domain-item">
            <p class="domain-name">frakting.no</p>
            <button class="buy-button" onclick="window.location.href='mailto:kontakt@szn.no?subject=Interessert i frakting.no&body=Jeg ønsker å kjøpe frakting.no.'">Kjøp Nå</button>
        </div>
        <!-- Domain 2: databruk.no -->
        <div class="domain-item">
            <p class="domain-name">databruk.no</p>
            <button class="buy-button" onclick="window.location.href='mailto:kontakt@szn.no?subject=Interessert i databruk.no&body=Jeg ønsker å kjøpe databruk.no.'">Kjøp Nå</button>
        </div>
        <!-- Domain 3: sikkerhetsnett.no -->
        <div class="domain-item">
            <p class="domain-name">sikkerhetsnett.no</p>
            <button class="buy-button" onclick="window.location.href='mailto:kontakt@szn.no?subject=Interessert i sikkerhetsnett.no&body=Jeg ønsker å kjøpe sikkerhetsnett.no.'">Kjøp Nå</button>
        </div>
    </div>

    <!-- Sell Domain Section -->
    <button class="sell-button" onclick="window.location.href='mailto:kontakt@szn.no?subject=Jeg ønsker å selge et domene&body=Hei, jeg ønsker å selge mitt domene. Vennligst kontakt meg for videre informasjon.'">Selg ditt domene</button>
</main>

<footer>
    <p>&copy; 2024 SZN.no | Alle rettigheter reservert</p>
</footer>

</body>
</html>

