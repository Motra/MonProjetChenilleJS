# MonProjetChenilleJS

<!DOCTYPE html>
<!--
To change this license header, choose License Headers in Project Properties.
To change this template file, choose Tools | Templates
and open the template in the editor.
-->
<html>
    <head>
        <title>TODO supply a title</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width">
        <style>
            body {
                text-align: center;
                font-family: Verdana, Geneva, sans-serif;
            }
            canvas { 
                border:1px solid;
                background-color: greenyellow;
            }
            wrapper {
                width: 800px;
                margin:auto;
            }
        </style>
        <script src="./Chenille.js"></script>
    </head>
    <body onload="init()">
        <p>La chenille</p>
        <div>
            <button id="startBtn">Start</button>
            <button id="stopBtn" disabled>Stop</button>
            <br><br>
        </div>
        <canvas  id="myCanvas" width="800" height ="600">
            coucou, j'apparais c'est qu'il est temps pour vous de changer de navigateur.
        </canvas>
    </body>

</html>
