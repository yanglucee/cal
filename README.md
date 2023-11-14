<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Animation</title>
    <style>
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        .animated-text {
            font-size: 24px;
            font-family: Arial, sans-serif;
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }
    </style>
</head>
<body>

<div class="animated-text">
    Hello, I'm Yang Lucee
</div>

</body>
</html>
