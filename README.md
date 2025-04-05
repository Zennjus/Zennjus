vecho "# Zennjus" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Zennjus/Zennjus.git
git push -u origin main
echo "<!DOCTYPE html><html><head><title>Zennjus Recharge</title></head><body><h1>Welcome to Zennjus Recharge</h1></body></html>" > index.html
git add index.html
git commit -m "Added index.html"
git push origin main
git add index.html  # Add changes to the staging area
git commit -m "Updated index.html"  # Commit the changes
git push origin main  # Push the changes to GitHub
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zennjus Recharge Service</title>
    <link rel="stylesheet" href="style.css">  <!-- Link to external CSS file -->
    <script src="script.js" defer></script>  <!-- Link to external JS file -->
</head>
<body>
    <header>
        <h1>Welcome to Zennjus Recharge</h1>
        <p>Recharge your favorite games quickly and securely!</p>
    </header>

    <section class="game-options">
        <h2>Available Game Recharge Options</h2>
        <div class="game" id="mlbb">
            <h3>MLBB (Mobile Legends)</h3>
            <ul>
                <li>13 + 1 Diamond - 1.07 MYR</li>
                <li>38 + 4 Diamond - 3.10 MYR</li>
                <li>50 + 5 (First Time 50 + 50) - 3.89 MYR</li>
                <li>127 + 13 Diamond - 10.20 MYR</li>
                <li>150 + 15 (First Time 150 + 150) - 12 MYR</li>
            </ul>
            <button onclick="rechargeGame('MLBB')">Recharge Now</button>
        </div>
        
        <div class="game" id="freefire">
            <h3>Free Fire</h3>
            <ul>
                <li>50 Diamonds - 3.00 MYR</li>
                <li>100 Diamonds - 6.00 MYR</li>
                <li>150 Diamonds - 9.00 MYR</li>
            </ul>
            <button onclick="rechargeGame('Free Fire')">Recharge Now</button>
        </div>
    </section>

    <footer>
        <p>Contact us: support@zennjus.com</p>
    </footer>
</body>
</html>
