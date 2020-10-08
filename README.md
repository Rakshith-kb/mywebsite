# mywebsite
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Generate alpha numeric character</title>
    <style>
        #id_down {
            color: green;
            font-weight: bold;
            font-size: 24px;
        }
    </style>
</head>
<body>
    <p id="id_up"></p>
    <button onclick="myFunction()">Click Here</button>
    <p id="id_down"></p>
    <script>
        var up = document.getElementById("id_up");
        var down = document.getElementById("id_down");
        up.innerHTML = "Click here to generate the random numbers";
        function myFunction() {
            down.innerHTML = Math.random().toString(36).slice(4);
        }
    </script>
</body>
</html>
