<!DOCTYPE html>
<html>
<head>
    <title>BEEN Mining</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body { text-align: center; font-family: sans-serif; background: #1a1a1a; color: white; padding-top: 50px; }
        .balance-box { font-size: 24px; margin-bottom: 20px; color: #f39c12; }
        .btn { background: #f39c12; border: none; padding: 20px 40px; color: white; font-size: 20px; border-radius: 50px; cursor: pointer; box-shadow: 0 4px #d35400; }
        .btn:active { box-shadow: 0 2px #d35400; transform: translateY(2px); }
    </style>
</head>
<body>
    <h1>Brian BEEN Mining 🐝</h1>
    <div class="balance-box">Số dư: <span id="balance">0</span> BEEN</div>
    <button class="btn" onclick="claim()">NHẬN 100.000 BEEN 🎁</button>

    <script>
        function claim() {
            document.getElementById('balance').innerText = '100.000';
            alert('Chúc mừng! Bạn đã nhận được 100.000 BEEN đầu tiên!');
        }
    </script>
</body>
</html>
