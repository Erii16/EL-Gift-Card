<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mir se vini tek EL Gift Card Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            color: white;
            float: left;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .gift-card {
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 15px;
            text-align: center;
            background-color: white;
        }
        .gift-card img {
            width: 100%;
            max-width: 200px;
            height: auto;
            margin-bottom: 10px;
        }
        .gift-card button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 10px;
        }
        .gift-card button:hover {
            background-color: #45a049;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            margin-top: 20px;
        }
        .form-container {
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ddd;
            margin: 20px;
            border-radius: 5px;
            max-width: 400px;
            margin-left: auto;
            margin-right: auto;
        }
        .form-container input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form-container button {
            width: 100%;
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
        .form-container button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mir se vini tek EL Gift Card Shop</h1>
        <p>Gjeni te gjitha llojet e Gift Card!</p>
    </header>
    <nav>
        <a href="#home">Ballina</a>
        <a href="#contact">Kontakti</a>
    </nav>
    <div id="home" class="container">
        <h2>Available Gift Cards</h2>
        <div class="gift-card">
            <img src="https://ibb.co/cxj1gnV/200x100" alt="Fortnite Gift Card 1000V-Bucks">
            <h3>€11.00 Gift Card</h3>
            <p>Gift Card ma e shitura per Fortnite.</p>
            <button onclick="selectGiftCard(50)">Blej Tani</button>
        </div>
        <div class="gift-card">
            <img src="https://ibb.co/tMnGmcj/200x100" alt="Apple Gift Card 15€">
            <h3>€17.00 Gift Card</h3>
            <p>Qmimi me i duhur per Apple Gift Card.</p>
            <button onclick="selectGiftCard(100)">Blej Tani</button>
        </div>
        <div class="gift-card">
            <img src="https://ibb.co/1bYMt8K/200x100" alt="Steam Gift Card 20€">
            <h3>€22.00 Gift Card</h3>
            <p>Qmimi me ekonomik.</p>
            <button onclick="selectGiftCard(200)">Blej Tani</button>
        </div>
    </div>
      <div class="gift-card">
        <img src="https://ibb.co/dummy-image1/200x100" alt="Google Play Gift Card 10€">
        <h3>€12.00 Gift Card</h3>
        <p>Perfect për të blerë aplikacione dhe lojëra.</p>
        <button onclick="selectGiftCard(120)">Blej Tani</button>
    </div>
    <!-- Karta e dytë e re -->
    <div class="gift-card">
        <img src="https://ibb.co/dummy-image2/200x100" alt="Netflix Gift Card 20€">
        <h3>€25.00 Gift Card</h3>
        <p>Për të shijuar shfaqjet dhe filmat tuaj të preferuar.</p>
        <button onclick="selectGiftCard(250)">Blej Tani</button>
    </div>
</div>
<!-- Karta e katërt e re -->
    <div class="gift-card">
        <img src="https://ibb.co/dummy-image4/200x100" alt="PlayStation Gift Card 30€">
        <h3>€35.00 Gift Card</h3>
        <p>Për lojëra dhe aplikacione në PlayStation Store.</p>
        <button onclick="selectGiftCard(350)">Blej Tani</button>
    </div>
    <!-- Karta e pestë e re -->
    <div class="gift-card">
        <img src="https://ibb.co/dummy-image5/200x100" alt="Xbox Gift Card 20€">
        <h3>€22.00 Gift Card</h3>
        <p>Për Xbox Live dhe lojëra për Xbox.</p>
        <button onclick="selectGiftCard(220)">Blej Tani</button>
    </div>
    <!-- Karta e gjashtë e re -->
    <div class="gift-card">
        <img src="https://ibb.co/dummy-image6/200x100" alt="Spotify Gift Card 15€">
        <h3>€18.00 Gift Card</h3>
        <p>Për të shijuar muzikën tuaj të preferuar në Spotify.</p>
        <button onclick="selectGiftCard(180)">Blej Tani</button>
    </div>
</div>
    <!-- Form for User Information -->
    <div id="form-container" class="form-container" style="display:none;">
        <h2>Shkruani Informacionet e juaja</h2>
        <form id="userForm" onsubmit="redirectToPayPal(event)">
            <input type="hidden" id="amount" name="amount">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Emri Juaj" required>
            <label for="email">Email Address:</label>
            <input type="email" id="email" name="email" placeholder="Email juaj" required>
            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" placeholder="Numri telefonit tuaj" required>
            <button type="submit">Vazhdo me pagesen</button>
        </form>
    </div>

    <footer>
        <p>&copy; 2024 EL Gift Card Shop. All rights reserved.</p>
    </footer>

    <script>
        // Store the selected gift card amount and show the form
        function selectGiftCard(amount) {
            document.getElementById("amount").value = amount;
            document.getElementById("form-container").style.display = "block";
            window.scrollTo(0, document.getElementById("form-container").offsetTop);
        }

        // Redirect to PayPal with user information
        function redirectToPayPal(event) {
            event.preventDefault();
            const name = document.getElementById("name").value;
            const email = document.getElementById("email").value;
            const phone = document.getElementById("phone").value;
            const amount = document.getElementById("amount").value;

            const paypalURL = `https://paypal.me/lawdyah?amount=${amount}&country.x=DE&locale.x=en_US&item_name=${amount}+Gift+Card&custom=Name:${encodeURIComponent(name)}|Email:${encodeURIComponent(email)}|Phone:${encodeURIComponent(phone)}`;


            window.location.href = paypalURL;
        }
    </script>
</body>
</html>
    <div id="contact" class="container">
        <h2>Kontakti</h2>
        <p>Për çdo pyetje ose informacion, na kontaktoni nëpërmjet mënyrave të mëposhtme:</p>
        
        <p><strong>Email:</strong> elduo.business@gmail.com</p>
        <p><strong>Numri i Telefonit Kosove:</strong> +383 48 731 333</p>
        <p><strong>Numri i Telefonit Gjermani:</strong> +49 172 6544175</p>
        <h3>Na ndiqni në rrjetet sociale:</h3>
        <ul>
            <li><a href="https://www.tiktok.com/@notificatio893?is_from_webapp=1&sender_device=pc" target="_blank">Tik Tok</a></li>
            <li><a href="https://www.instagram.com/ermond_bujupii/" target="_blank">Instagram</a></li>
        </ul>
    </div>
    <div class="container">
        <h2>Si do t'ju vijë kodi i Gift Card?</h2>
        <p>Pas përfundimit të pagesës, kodi i Gift Card do t'ju dërgohet nëpërmjet email-it tuaj.</p>
        <p>Kodi do të vijë së bashku me një foto të kartës dhe do të jetë digjital. Do ta merrni brenda 24 orëve nga momenti i pagesës.</p>
    </div>
