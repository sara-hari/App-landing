# App-landing
Application install
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Get Your App Now!</title>
<style>
    body {
        margin: 0;
        padding: 0;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background: linear-gradient(135deg, #6a11cb, #2575fc);
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        color: #fff;
    }
    .card {
        background: #fff;
        color: #333;
        border-radius: 15px;
        padding: 25px;
        max-width: 350px;
        width: 90%;
        text-align: center;
        box-shadow: 0 8px 20px rgba(0,0,0,0.2);
        animation: fadeIn 1s ease-in-out;
    }
    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }
    .card img {
        width: 120px;
        margin-bottom: 20px;
    }
    h1 {
        font-size: 22px;
        margin-bottom: 12px;
    }
    p {
        font-size: 14px;
        color: #555;
        margin-bottom: 20px;
    }
    .btn {
        display: inline-block;
        padding: 14px 30px;
        background: #28a745;
        color: #fff;
        font-weight: bold;
        text-decoration: none;
        border-radius: 8px;
        transition: 0.3s;
    }
    .btn:hover {
        background: #1e7e34;
    }
    @media (max-width: 400px) {
        .card { padding: 20px; }
        h1 { font-size: 20px; }
    }
</style>
</head>
<body>
    <div class="card">
        <img src="https://via.placeholder.com/120" alt="App Logo">
        <h1>Download the App Today!</h1>
        <p>Experience exclusive features and enjoy seamless performance. Quick download and easy setup!</p>
        <a class="btn" href="YOUR_OGADS_LINK_HERE" target="_blank">Download Now</a>
    </div>
</body>
</html>
