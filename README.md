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
        }
        .container {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .username {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .username a {
            text-decoration: none;
            color: #0073e6;
        }
        .speech-bubble {
            position: relative;
            background: #fff;
            border-radius: .7em;
            padding: 10px 15px;
            display: inline-block;
            font-family: Arial, sans-serif;
            font-size: 15px;
            color: #6B425D;
            border: 2px solid #6B425D;
        }
        .speech-bubble:after {
            content: '';
            position: absolute;
            bottom: -20px;
            left: 20px;
            width: 0;
            height: 0;
            border: 10px solid transparent;
            border-top-color: #fff;
            border-bottom: 0;
            border-left: 0;
            margin-left: -10px;
        }
        .speech-bubble:before {
            content: '';
            position: absolute;
            bottom: -22px;
            left: 18px;
            width: 0;
            height: 0;
            border: 11px solid transparent;
            border-top-color: #6B425D;
            border-bottom: 0;
            border-left: 0;
            margin-left: -11px;
        }
        .speech-bubble2 {
            position: relative;
            background: #fff;
            border-radius: .7em;
            padding: 10px 20px;
            display: inline-block;
            font-family: Arial, sans-serif;
            font-size: 15px;
            color: #6B425D;
            border: 2px solid #6B425D;
            margin-left: 40px;
        }
        .speech-bubble2:after {
            content: '';
            position: absolute;
            bottom: -20px;
            right: 20px;
            width: 0;
            height: 0;
            border: 10px solid transparent;
            border-top-color: #fff;
            border-bottom: 0;
            border-right: 0;
            margin-right: -10px;
        }
        .speech-bubble2:before {
            content: '';
            position: absolute;
            bottom: -22px;
            right: 18px;
            width: 0;
            height: 0;
            border: 11px solid transparent;
            border-top-color: #6B425D;
            border-bottom: 0;
            border-right: 0;
            margin-right: -11px;
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
            position: absolute;
            bottom: -30px;
            right: 0;
            width: 350px;
            height: 280px;
            background-color: #e6e6e641;
            color: black;
            border-radius: 4px;
            text-align: left;
            line-height: 1.2em;
            font-size: 15px;
            padding: 5px;
            box-sizing: border-box;
            border: 5px solid transparent;
            border-color:#6B425D;
        }
        /* Media Queries para dispositivos móviles */
        @media (max-width: 768px) {
            .speech-bubble {
                top: 30%; 
                left: 70%; 
                transform: translate(-50%, -50%);
            } 
            .speech-bubble2 {
                top: 35%; 
                left: 30%;
                transform: translate(-50%, -50%);
            }  
            .square-container {
                top: 70%; 
                left: 50%;
                width: 80%;
                height: auto;
                padding: 10px;
                font-size: 14px;
            }
            img {
                width: 100%;
                height: auto;
            }
        }
        @media (max-width: 480px) {
            .speech-bubble {
                top: 25%; 
                left: 65%; 
                transform: translate(-50%, -50%);
                font-size: 14px;
                padding: 8px 12px;
            }    
            .speech-bubble2 {
                top: 30%; 
                left: 25%;
                transform: translate(-50%, -50%);
                font-size: 14px;
                padding: 8px 12px;
            }
            .square-container {
                top: 65%; 
                left: 50%;
                width: 90%;
                padding: 8px;
                font-size: 12px;
            }
        }
    </style>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">

</head>
<body>
    <div style="position: relative; text-align: center; color: white;">
    <img src="foto.jpg" alt="" style="width:90%;">
    <div class="speech-bubble" style="position: absolute; top: 36%; left: 77%; transform: translate(-50%, -50%);">
        <i class="fab fa-instagram instagram-icon"></i><a href="https://www.instagram.com/alberto.ramirezb_/" class="instagram-link">@alberto.ramirezb_</a>
    </div>
    <div class="speech-bubble2" style="position: absolute; top: 37%; left: 38%; transform: translate(-50%, -50%);">
        <i class="fab fa-instagram instagram-icon"></i><a href="https://www.instagram.com/davidmartinezzz___/" class="instagram-link">@davidmartinezzz___</a>
    </div>
    <div class="square-container" style="position: absolute; top: 75%; left: 60%;">
        Buenas, somos dos notas por la costa brava, y hemos creado esta web para buscar planes y conocer a gente 
    </div>
</body>

