<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LIST PANEL BY ARTA</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #222;
            color: #fff;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #333;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .panel {
            margin-bottom: 20px;
            padding: 10px;
            border: 1px solid #555;
            border-radius: 5px;
            background-color: #444;
        }

        .panel h2 {
            margin-bottom: 10px;
        }

        .panel p {
            margin-bottom: 15px;
        }

        .button {
            padding: 8px 16px;
            background-color: #007bff;
            color: #fff;
            text-decoration: none;
            border: none;
            border-radius: 5px;
            font-size: 14px;
            transition: background-color 0.3s ease;
            cursor: pointer;
            margin-right: 10px;
        }

        .button:hover {
            background-color: #0056b3;
        }

        .checkout-button {
            background-color: #28a745;
        }

        .checkout-button:hover {
            background-color: #218838;
        }

        .payment-button {
            background-color: #ffc107;
        }

        .payment-button:hover {
            background-color: #e0a800;
        }

        .popup {
            display: none;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.8);
            border-radius: 10px;
            z-index: 999;
        }

        .popup-content {
            text-align: center;
        }

        .close-button {
            position: absolute;
            top: 10px;
            right: 10px;
            padding: 5px 10px;
            background-color: #f00;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        @media screen and (max-width: 600px) {
            .container {
                padding: 10px;
            }
            .button {
                padding: 6px 12px;
                font-size: 12px;
            }
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="panel">
            <h2>Ram 2GB CPU 40%</h2>
            <p>HARGA 1K PERMANEN HANYA DAPET FREE SC</p>
            <a href="https://wa.me/6287760185040?text=Order Ram 2GB CPU 40%" class="button">Order</a>
            <button class="button">Keranjang</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>

        <div class="panel">
            <h2>Ram 3GB CPU 60%</h2>
            <p>HARGA 2K PERMANEN HANYA DAPET FREE SC</p>
            <a href="https://wa.me/6287760185040?text=Order Ram 3GB CPU 60%" class="button">Order</a>
            <button class="button">Keranjang</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>

        <div class="panel">
            <h2>Ram 4GB CPU 90%</h2>
            <p>HARGA 3K PERMANEN HANYA DAPET FREE SC</p>
            <a href="https://wa.me/6287760185040?text=Order Ram 4GB CPU 90%" class="button">Order</a>
            <button class="button">Keranjang</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>

        <div class="panel">
            <h2>Ram 5GB CPU 120%</h2>
            <p>HARGA 4K PERMANEN HANYA DAPET FREE SC</p>
            <a href="https://wa.me/6287760185040?text=Order Ram 5GB CPU 120%" class="button">Order</a>
            <button class="button">Keranjang</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>

        <div class="panel">
            <h2>Ram 6GB CPU 150%</h2>
            <p>5K/Permanen dapet free sc + di pasang in</p>
            <a href="https://wa.me/6287760185040?text=Order Ram 6GB CPU 150%" class="button">Order</a>
            <button class="button">Keranjang</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>

        <div class="panel">
            <h2>Ram 7GB CPU 180%</h2>
            <p>6K/Permanen dapet free sc + di pasang in</p>
            <a href="https://wa.me/6287760185040?text=Order Ram 7GB CPU 180%" class="button">Order</a>
            <button class="button">Keranjang</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>

        <div class="panel">
            <h2>Ram 8GB CPU 210%</h2>
            <p>7K/Permanen dapet free sc + di pasang in</p>
            <a href="https://wa.me/6287760185040?text=Order Ram 8GB CPU 210%" class="button">Order</a>
            <button class="button">Keranjang</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>

        <div class="panel">
            <h2>Ram 9GB CPU 240%</h2>
            <p>8K/Permanen dapet free sc + di pasang in</p>
            <a href="https://wa.me/6287760185040?text=Order Ram 9GB CPU 240%" class="button">Order</a>
            <button class="button">Keranjang</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>

        <div class="panel">
            <h2>Ram 10GB CPU 310%</h2>
            <p>9K/Permanen dapet free sc + di pasang in</p>
            <a href="https://wa.me/6287760185040?text=Order Ram 10GB CPU 310%" class="button">Order</a>
            <button class="button">Keranjang</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>

        <div class="panel">
            <h2>Ram & CPU UNLI</h2>
            <p>10K/Permanen dapet free sc + di pasang in</p>
            <a href="https://wa.me/6287760185040?text=Order Ram & CPU UNLI" class="button">Order</a>
            <button class="button">Keranjang</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>

        <div class="panel">
            <h2>Bot Pushkontak V8</h2>
            <p>5K Free Pasang</p>
            <a href="https://wa.me/6287760185040?text=Order Bot Pushkontak V8" class="button">Order</a>
            <button class="button">Keranjang</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>
                <div class="SC BOT WA">
            <h2>SC BOT WA VIPP</h2>
            <p>FITUR BISA BUAT NOKOS BUAT PANEL DAN DLL</p>
            <a href="https://wa.me/6287760185040?text=Order Ram & CPU UNLI" class="button">Order</a>
            <button class="button">HARGA SC 20K</button>
            <button class="button payment-button" onclick="showPopup()">Metode Pembayaran</button>
        </div>
    </div>

    <div class="popup" id="popup">
        <div class="popup-content">
            <button class="close-button" onclick="hidePopup()">X</button>
            <h2>Metode Pembayaran</h2>
            <p>Nomor Dana: 087760185040</p>
            <img src="https://telegra.ph/file/64dd6922fcf554f252598.png" alt="QRIS" width="150">
        </div>
    </div>

    <script>
        function showPopup() {
            document.getElementById("popup").style.display = "block";
        }

        function hidePopup() {
            document.getElementById("popup").style.display = "none";
        }
    </script>
</body>

</html>
