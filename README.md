<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vape Shop | Products & Prices</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Vape Shop</h1>
        <p>Your one-stop shop for quality vape products</p>
    </header>

    <main>
        <section class="products">
            <h2>Our Products</h2>
            <div class="product-list">
                <div class="product-card">
                    <img src="https://images.unsplash.com/photo-1525186402429-b4ff38ead5f2?auto=format&fit=crop&w=400&q=80" alt="Vape Pen">
                    <h3>Vape Pen</h3>
                    <p class="price">$25.00</p>
                </div>
                <div class="product-card">
                    <img src="https://images.unsplash.com/photo-1542219550-51e1c1a32ecc?auto=format&fit=crop&w=400&q=80" alt="E-Liquid">
                    <h3>E-Liquid (30ml)</h3>
                    <p class="price">$10.00</p>
                </div>
                <div class="product-card">
                    <img src="https://images.unsplash.com/photo-1518972559570-5ca918f7d0d0?auto=format&fit=crop&w=400&q=80" alt="Pod System">
                    <h3>Pod System</h3>
                    <p class="price">$40.00</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>Contact us: <a href="tel:+1234567890" class="phone-link">+1 234 567 890</a></p>
    </footer>

    <a href="tel:+1234567890" class="call-chat-btn" id="callChatBtn">
        Call/Chat
    </a>

    <script>
        // Optionally, add code for chat integration here (like WhatsApp Web link)
        // Example for WhatsApp: 
        // document.getElementById('callChatBtn').href = "https://wa.me/1234567890";
    </script>
</body>
</html>
