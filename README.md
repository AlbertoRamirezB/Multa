
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
        }
        .container {
            position: relative;
            width: 90%;
            max-width: 800px;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .image-container {
            position: relative;
            width: 100%;
        }
        .image-container img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .speech-bubble {
            position: absolute;
            background: #fff;
            border-radius: .7em;
            padding: 5px 7px;
            font-size: 12px;
            color: #6B425D;
            border: 2px solid #6B425D;
            -webkit-transform: translate(-50%, -50%);
            transform: translate(-50%, -50%);
        }
        .speech-bubble.left {
            top: 390px;
            left: 600px;;
        }
        .speech-bubble.right {
            top: 400px;
            right: 450px;
            -webkit-transform: translate(50%, -50%);
            transform: translate(50%, -50%);
        }
        .instagram-icon {
            color: #C13584;
            font-size: 18px;
            vertical-align: middle;
            margin-right: 5px;
        }
        .instagram-link {
            color: #003cff;
            text-decoration: none;
        }
        .square-container {
            margin-top: 5px;
            background-color: #044e2d99;
            color: black;
            border-radius: 4px;
            text-align: left;
            line-height: 1.2em;
            font-size: 15px;
            padding: 7px;
            box-sizing: border-box;
            border: 1px solid #0b4a01;
        }
        @media (max-width: 500px) {
            .speech-bubble.left {
                top: 35%;
                left: 74%;
                -webkit-transform: translate(-50%, -50%);
                transform: translate(-50%, -50%);
            }
            .speech-bubble.right {
                top: 36%;
                right: 60%;
                -webkit-transform: translate(50%, -50%);
                transform: translate(50%, -50%);
            }
            .square-container {
                font-size: 10px;
            }
        }
        @media (max-width: 480px) {
            .speech-bubble.left,
            .speech-bubble.right {
                top: 35%;
                -webkit-transform: translate(0, -50%);
                transform: translate(0, -50%);
            }
             .speech-bubble.left {
                top: 32%;
                left: 65%;
            } 
            .speech-bubble.right {
                right: 45%;
            }
            .square-container {
                font-size: 10px;
            }
        }
    </style>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
</head>
<body>

<div class="container">
    <div class="image-container">
        <img src="foto.jpg" alt="Imagen de ejemplo">
        <div class="speech-bubble left">
            <i class="fab fa-instagram instagram-icon"></i>
            <a href="https://www.instagram.com/alberto.ramirezb_/" class="instagram-link">@alberto.ramirezb_</a>
        </div>
        <div class="speech-bubble right">
            <i class="fab fa-instagram instagram-icon"></i>
            <a href="https://www.instagram.com/davidmartinezzz___/" class="instagram-link">@davidmartinezzz___</a>
        </div>
    </div>
    <div class="square-container">
        Buenas, somos dos notas por la costa brava, y hemos creado esta web para buscar planes y conocer a gente.
    </div>
</div>

</body>
