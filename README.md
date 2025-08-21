<!DOCTYPE html>
<html>
    <head>
        <style>
            .button-class{
                height: 100px;
                width: 200px;
                background-color: lightblue;
                color: lightpink;
                font-size: 20px;
                font-family: Arial;
                font-weight: bold;
                border: none;
                cursor: pointer;
                transition: opacity 0.15s;
            }
            .button-class:hover{
                opacity: 0.8;
            }
            .button-class:after{
                opacity: 0.5;
            }
        </style>
    </head>
    <body>
        <button class="button-class">Follow</button>
    </body>
</html>
