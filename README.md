<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be Mine Eya?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        .container {
            margin-top: 50px;
        }
        img {
            width: 150px;
            margin-bottom: 20px;
        }
        h1 {
            font-size: 24px;
            color: #333;
            margin-bottom: 30px;
        }
        .button-container button {
            font-size: 16px;
            margin: 10px;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .button-container .yes {
            background-color: #28a745;
            color: white;
        }
        .button-container .no {
            background-color: #dc3545;
            color: white;
        }
        .footer {
            margin-top: 30px;
            font-size: 14px;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://i.imgur.com/PlOEzqg.png" alt="Cute Bear">
        <h1>Will you be mine Eya?</h1>
        <div class="button-container">
            <button class="yes" onclick="showResponse('Yes')">Yes</button>
            <button class="no" onclick="showResponse('No')">No</button>
        </div>
        <div class="footer">Take a screenshot</div>
    </div>

    <script>
        function showResponse(answer) {
            alert(`You
 clicked: ${answer}`);
        }
    </script>
</body>
</html>
