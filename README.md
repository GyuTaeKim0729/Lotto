# <!DOCTYPE html>
<html>

<head>
    <title>로또</title>
    <meta charset="utf-8">
    <style>
        body {
            margin: 0px 0px 0px 0px;
        }

        div {
            border: 0px;
            text-align: center
        }

        .header {
            padding-top: 50px;
            height: 200px;
            background: orange;
            color: white;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: 140%;
        }

        .button {
            background-color: red;
            /* Green */
            border: none;
            color: white;
            padding: 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
            border-radius: 8px;
        }
    </style>
</head>

<body>
    <div class="header">
        <h1>인생 역전 가자!<br>로또 번호 생성</h1>
    </div>

    <div>
        <button class="button" type="button" onclick="document.getElementById('demo').innerHTML = Date()">
            번호 생성</button>

        <p id="demo"></p>

        <p id="one">1회</p>
        <p id="two">2회</p>
        <p id="three">3회</p>
        <p id="four">4회</p>
        <p id="five">5회</p>
    </div>
    <script>

        document.getElementById("demo").innerHTML = "fuck";
    </script>
</body>

</html>
