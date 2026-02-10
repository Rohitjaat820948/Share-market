# Share-market
Start up of begginers 
<div style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #333; max-width: 800px; margin: auto; border: 1px solid #ddd; padding: 20px; border-radius: 10px;">

    <h1 style="color: #1a73e8; text-align: center;">Share Market News Today: Nifty 25,900 ke Paar! 🚀</h1>
    <p style="text-align: center; color: #666;"><strong>Date:</strong> 10 February 2026</p>

    <hr style="border: 0; border-top: 1px solid #eee;">

    <h2 style="color: #2e7d32;">✅ Aaj Ka Market Update (10 Feb)</h2>
    <p>Indian Stock Market aaj lagatar teesre din tezi ke saath band hua. <strong>India-US Trade Deal</strong> ki wajah se investors mein kafi utsah dikha.</p>
    
    <table style="width: 100%; border-collapse: collapse; margin: 20px 0; background: #f9f9f9;">
        <tr style="background: #1a73e8; color: white;">
            <th style="padding: 10px; border: 1px solid #ddd;">Index</th>
            <th style="padding: 10px; border: 1px solid #ddd;">Closing Level</th>
            <th style="padding: 10px; border: 1px solid #ddd;">Change (%)</th>
        </tr>
        <tr>
            <td style="padding: 10px; border: 1px solid #ddd;"><b>Nifty 50</b></td>
            <td style="padding: 10px; border: 1px solid #ddd;">25,935.15</td>
            <td style="padding: 10px; border: 1px solid #ddd; color: green;">+0.26%</td>
        </tr>
        <tr>
            <td style="padding: 10px; border: 1px solid #ddd;"><b>Sensex</b></td>
            <td style="padding: 10px; border: 1px solid #ddd;">84,273.92</td>
            <td style="padding: 10px; border: 1px solid #ddd; color: green;">+0.25%</td>
        </tr>
    </table>

    <p><strong>Top Gainers:</strong> Eternal (+5.1%), Tata Steel, Mahindra & Mahindra.<br>
    <strong>Top Losers:</strong> HCL Tech, Bajaj Finance, Dr. Reddy's.</p>

    <h2 style="color: #d84315;">🔮 Kal Ke Liye Prediction (11 Feb)</h2>
    <p>Kal market mein <strong>Nifty ke liye 26,000</strong> ek bada resistance level hoga. Agar Nifty ise todta hai, toh 26,150 tak ja sakta hai.</p>
    <ul>
        <li><b>Support:</b> 25,800 - 25,750</li>
        <li><b>Resistance:</b> 26,000 - 26,100</li>
        <li><b>Strategy:</b> Buy on dips (Giraat par kharidein).</li>
    </ul>

    <div style="background: #fff8e1; border: 2px dashed #ff8f00; padding: 15px; text-align: center; margin-top: 30px;">
        <h3 style="margin-top: 0;">🔥 FREE Demat Account Offer!</h3>
        <p>Aaj hi trading shuru karein aur payein <b>FREE Opening + Cashback</b>.</p>
        <a href="APKA_REFERRAL_LINK_YAHAN_DALO" style="background: #ff8f00; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; font-weight: bold; display: inline-block;">Click Here to Open Account</a>
    </div>

</div>
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Startup of Beginners | Live Stock Analysis</title>
    <style>
        :root { --primary: #2ecc71; --dark: #2c3e50; --light: #ecf0f1; }
        body { font-family: 'Poppins', sans-serif; background: var(--light); margin: 0; color: #333; }
        header { background: var(--dark); color: white; padding: 2rem; text-align: center; border-bottom: 5px solid var(--primary); }
        .container { max-width: 800px; margin: 20px auto; padding: 20px; }
        .search-section { background: white; padding: 30px; border-radius: 15px; box-shadow: 0 10px 25px rgba(0,0,0,0.1); text-align: center; }
        input { width: 70%; padding: 12px; border: 2px solid #ddd; border-radius: 25px; outline: none; font-size: 16px; }
        button { padding: 12px 25px; background: var(--primary); color: white; border: none; border-radius: 25px; cursor: pointer; font-weight: bold; transition: 0.3s; }
        button:hover { background: #27ae60; transform: scale(1.05); }
        #loader { display: none; margin-top: 20px; color: var(--dark); font-weight: bold; }
        .result-card { display: none; margin-top: 30px; background: white; padding: 25px; border-radius: 15px; border-left: 8px solid var(--primary); animation: fadeIn 0.5s; }
        .price-tag { font-size: 32px; color: var(--dark); font-weight: 800; margin: 10px 0; }
        .stats { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-top: 15px; }
        .stat-box { background: #f9f9f9; padding: 10px; border-radius: 8px; font-size: 14px; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }
    </style>
</head>
<body>

<header>
    <h1>🚀 Startup of Beginners</h1>
    <p>Stock Market Analysis for Smart Beginners</p>
</header>

<div class="container">
    <div class="search-section">
        <h3>Analyze Any Global Stock</h3>
        <input type="text" id="symbol" placeholder="Stock Symbol daalein (e.g. AAPL, TSLA, IBM)...">
        <button onclick="fetchStockData()">Analyze</button>
        <div id="loader">Data fetch ho raha hai... Kripya rukein...</div>
    </div>

    <div id="resultCard" class="result-card">
        <h2 id="displaySymbol" style="margin:0; color: var(--dark);">---</h2>
        <div class="price-tag">$<span id="displayPrice">0.00</span></div>
        <div class="stats">
            <div class="stat-box"><strong>Open:</strong> <span id="openPrice">--</span></div>
            <div class="stat-box"><strong>High:</strong> <span id="highPrice">--</span></div>
            <div class="stat-box"><strong>Low:</strong> <span id="lowPrice">--</span></div>
            <div class="stat-box"><strong>Prev Close:</strong> <span id="prevClose">--</span></div>
        </div>
        <div style="margin-top:20px; padding:15px; background:#e8f8f0; border-radius:10px;">
            <strong>Startup Analysis:</strong> 
            <p id="analysisTip" style="font-size: 15px; color: #2c3e50;"></p>
        </div>
    </div>
</div>

<script>
    async function fetchStockData() {
        const symbol = document.getElementById('symbol').value.toUpperCase();
        const loader = document.getElementById('loader');
        const resultCard = document.getElementById('resultCard');
        
        if(!symbol) { alert("Please enter a symbol!"); return; }

        loader.style.display = 'block';
        resultCard.style.display = 'none';

        // Note: Demo API Key "demo" use kar raha hoon. 
        // Aap alphavantage.co se apni free key le sakte hain.
        const apiKey = 'demo'; 
        const url = `https://www.alphavantage.co/query?function=GLOBAL_QUOTE&symbol=${symbol}&apikey=${apiKey}`;

        try {
            const response = await fetch(url);
            const data = await response.json();
            const stock = data["Global Quote"];

            if(stock && stock["05. price"]) {
                document.getElementById('displaySymbol').innerText = stock["01. symbol"];
                document.getElementById('displayPrice').innerText = parseFloat(stock["05. price"]).toFixed(2);
                document.getElementById('openPrice').innerText = stock["02. open"];
                document.getElementById('highPrice').innerText = stock["03. high"];
                document.getElementById('lowPrice').innerText = stock["04. low"];
                document.getElementById('prevClose').innerText = stock["08. previous close"];
                
                // Simple Analysis Logic
                const change = parseFloat(stock["09. change"]);
                document.getElementById('analysisTip').innerText = change >= 0 
                    ? "Ye stock aaj bullish (uproar) hai. Long term ke liye iska trend positive dikh raha hai."
                    : "Stock mein thodi girawat hai. Beginner hain toh thoda wait karke 'dip' par kharidna sahi ho sakta hai.";

                resultCard.style.display = 'block';
            } else {
                alert("Stock nahi mila ya API limit khatam ho gayi (Free API 5 requests/min deti hai).");
            }
        } catch (error) {
            alert("Kuch galat hua. Check your internet.");
        } finally {
            loader.style.display = 'none';
        }
    }
</script>

</body>
</html>
