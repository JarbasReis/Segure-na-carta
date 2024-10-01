<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jarbas e Samara</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            height: 100vh;
            width: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            font-family: sans-serif;
            background-color: #FFDAB9;
        }
        
        .wrapper {
            height: 200px;
            width: 300px;
            background-color: #FFF5EE;
            position: relative;
            display: flex;
            justify-content: center;
            z-index: 0;
            cursor: pointer;
        }
        
        .lid {
            position: absolute;
            height: 100%;
            width: 100%;
            top: 0;
            left: 0;
            border-right: 150px solid transparent;
            border-bottom: 100px solid transparent;
            border-left: 150px solid transparent;
            transform-origin: top;
            transition: transform 0.25s linear;
        }
        
        .lid.one {
            border-top: 100px solid #FFF5EE;
            transform: rotateX(0deg);
            z-index: 3;
            transition-delay: 0.75s;
        }
        
        .lid.two {
            border-top: 100px solid #FFF5EE;
            transform: rotateX(90deg);
            z-index: 1;
            transition-delay: 0.5s;
        }
        
        .envelope {
            position: absolute;
            height: 100%;
            width: 100%;
            top: 0;
            left: 0;
            border-top: 100px solid transparent;
            border-right: 150px solid #FAF0E6;
            border-bottom: 100px solid #FAF0E6;
            border-left: 150px solid #FFF5EE;
            z-index: 3;
        }
        
        .letter {
            position: absolute;
            top: 0;
            width: 80%;
            height: 80%;
            background-color: white;
            border-radius: 15px;
            z-index: 2;
            transition: 0.5s;
        }
        
        .letter p {
            text-align: center;
            font-size: 30px;
            margin-top: 30px;
            color: #3B4049;
        }
        
        .wrapper:hover .lid.one {
            transform: rotateX(90deg);
            transition-delay: 0s;
        }
        
        .wrapper:hover .lid.two {
            transform: rotateX(180deg);
            transition-delay: 0.25s;
        }
        
        .wrapper:hover .letter {
            transform: translateY(-50px);
            transition-delay: 0.5s;
        }

        .button-link {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #ff69b4;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .button-link:hover {
            background-color: #ff1493;
        }
    </style>
    <script>
        function showImage() {
            window.location.href = 'https://i.ibb.co/7pK27zX/cl314-1.png'; // Link 1
        }

        function openLink2() {
            window.location.href = 'https://maps.app.goo.gl/Y1n793wW8qfiyyuy5'; // Link 2
        }

        function openLink3() {
            window.location.href = 'https://noivos.casar.com/samara-e-jarbas#/presentes'; // Link 3
        }
    </script>
</head>
<body>
    <div class="wrapper" onclick="showImage()">
        <div class="lid one"></div>
        <div class="lid two"></div>
        <div class="envelope"></div>
        <div class="letter">
            <p>Convidamos você!</p>
        </div>
    </div>

    <button class="button-link" onclick="openLink2()">Local no maps</button>
    <button class="button-link" onclick="openLink3()">Lista de presente</button>
</body>
</html>
