<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bright Future Tanzania Foundation</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f5f7fa;
        }

        header {
            background: #0a3d62;
            color: white;
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            font-size: 20px;
        }

        nav a {
            color: white;
            margin-left: 20px;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            background: linear-gradient(rgba(10,61,98,0.8), rgba(10,61,98,0.8)), url('https://images.unsplash.com/photo-1588072432836-e10032774350');
            background-size: cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        .hero h2 {
            font-size: 40px;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 20px;
        }

        .btn {
            background: #f39c12;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            margin: 5px;
            display: inline-block;
        }

        .section {
            padding: 50px 20px;
            text-align: center;
        }

        .children {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .card {
            background: white;
            width: 250px;
            margin: 15px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .card img {
            width: 100%;
            border-radius: 10px;
        }

        footer {
            background: #0a3d62;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>

<body>

<header>
    <h1>Bright Future Tanzania Foundation</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Sponsor</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Give a Child a Future Today</h2>
    <p>Sponsor a child’s education and change their life forever.</p>
    <a href="#" class="btn">Sponsor a Child</a>
    <a href="#" class="btn">Learn More</a>
</section>

<section class="section">
    <h2>Children in Need</h2>
    <div class="children">

        <div class="card">
            <img src="https://via.placeholder.com/250" alt="Child">
            <h3>Amina, 10</h3>
            <p>Needs $20/month</p>
            <a href="#" class="btn">Sponsor</a>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/250" alt="Child">
            <h3>John, 12</h3>
            <p>Needs $25/month</p>
            <a href="#" class="btn">Sponsor</a>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/250" alt="Child">
            <h3>Neema, 9</h3>
            <p>Needs $18/month</p>
            <a href="#" class="btn">Sponsor</a>
        </div>

    </div>
</section>

<section class="section">
    <h2>How It Works</h2>
    <p>1. Choose a child</p>
    <p>2. Sponsor monthly or yearly</p>
    <p>3. Receive updates and see impact</p>
</section>

<section class="section">
    <h2>You Can Change a Life Today</h2>
    <a href="#" class="btn">Sponsor Now</a>
</section>

<footer>
    <p>© 2026 Bright Future Tanzania Foundation</p>
</footer>

</body>
</html>
