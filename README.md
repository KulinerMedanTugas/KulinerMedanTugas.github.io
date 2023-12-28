<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kuliner Medan</title>
    <link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap">
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            margin: 0.5px;
            padding: 0.5em;
            background-color: #f4f4f4;
            background-image: url('gambar1.jpg');
            background-size: 100%;
            background-position: left;
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
            font-size: 20pt;
            color: rgb(247, 238, 238);
            margin: 10px;
            padding: 5px;
            float: left;
        }

        .menu ul {
            margin: 0px;
            padding: 5px;
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
            color: #fbfbfb;
            display: block;
        }

        .menu ul li:hover {
            background: #141313;
            box-shadow: inset 0px 0px 5px #000;
        }

        footer {
            color: #fff;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        h2 {
            text-align: center;
            margin: 5px 0;
            color: #fbfbfb;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }
        p {
            text-align: center;
            margin: 5px 0;
            color: #fbfbfb;
            font-family: Arial, Helvetica, sans-serif;
        }
    </style>
</head>

<body>
    <nav class="menu">
        <label>Kuliner Medan</label>
        <ul>
            <li><a href="resotoran.html">Home</a></li>
            <li><a href="about.hmtl.html">About</a></li>
            <li><a href="makanan.html">Food Galery</a></li>
            <li><a href="minuman.html">Drink Galery</a></li>
            <li><a href="kontak.html">Contact</a></li>
        </ul>
    </nav>
    <h2> Eksplore Wisata</h2>
    <h2> Kuliner Medan</h2>
    <p>Kuliner Khas Medan yang kaya akan rasa dan tradisi</p>
    <script type="text/javascript" src="js/popper.min.js"></script>
    <script type="text/javascript" src="js/bootstrap.bundle.js"></script>
    <footer>
        © 2023 Kuliner Medan. All rights reserved.
    </footer>
</body>

</html>
