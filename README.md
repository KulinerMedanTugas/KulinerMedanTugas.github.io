<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kuliner Medan</title>
    <link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap">
    <style>
        body {
            font-family: 'Arial', 'Helvetica', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            background-image: url('gambar1.jpg');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        .menu {
            font-family: 'Times New Roman', Times, serif;
            font-weight: bold;
            height: 70px;
            width: 100%;
            background: black;
            border-radius: 5px;
            font-size: 18px;
            position: fixed;
            top: 0;
            z-index: 1000;
            margin: 0;
            padding: 0;
            left: 0;
        }

        label {
            font-family: 'Pacifico', cursive;
            font-size: 32px;
            color: #fff;
            margin: 10px;
            padding: 5px;
            float: left;
        }

        .menu ul {
            margin: 0;
            padding: 0;
            background: none;
            display: flex;
            justify-content: flex-end;
            align-items: center;
        }

        .menu ul li {
            list-style: none;
            margin-right: 10px;
        }

        .menu ul li a {
            text-decoration: none;
            padding: 15px;
            color: #fff;
            display: block;
        }

        .menu ul li:hover {
            background: #141313;
            box-shadow: inset 0px 0px 5px #000;
        }

        h2 {
            text-align: center;
            margin: 20px 0;
            color: #fff;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }

        p {
            text-align: center;
            margin: 10px 0;
            color: #fff;
            font-family: 'Arial', 'Helvetica', sans-serif;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: black;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        footer {
            color: #fff;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        /* Perubahan gaya untuk tata letak tulisan yang lebih menarik */
        .content-container {
            max-width: 800px;
            margin: 0 auto;
        }
    </style>
</head>

<body>
    <nav class="menu">
        <label>🍔 Kuliner Medan 🌮</label>
        <ul>
            <li><a href="kuliner.html">Home</a></li>
            <li><a href="about.hmtl.html">About</a></li>
            <li><a href="makanan.html">Food Gallery</a></li>
            <li><a href="minuman.html">Drink Gallery</a></li>
            <li><a href="kontak.html">Contact</a></li>
        </ul>
    </nav>
    <div class="content-container">
        <h2>Kuliner Khas Medan yang kaya akan rasa dan tradisi</h2>
        <p>Temukan kelezatan kuliner khas Medan yang tidak hanya menggugah selera, tetapi juga membawa pengalaman tradisional yang mendalam. Nikmati perpaduan unik rasa dan aroma yang hanya dapat ditemukan di kota ini.</p>
    </div>

    <script type="text/javascript" src="js/popper.min.js"></script>
    <script type="text/javascript" src="js/bootstrap.bundle.js"></script>
    <footer>
        © 2023 Kuliner Medan. All rights reserved.
    </footer>
</body>

</html>
