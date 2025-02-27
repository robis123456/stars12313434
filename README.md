# stars12313434
git clone https://github.com/YOUR-USERNAME/stars-theme.git
cd stars-theme
mkdir layout
touch layout/theme.liquid
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page_title }}</title>
    <style>
        body {
            background: #000;
            color: #fff;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .stars {
            background: url('https://source.unsplash.com/1600x900/?stars,night') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        h1 {
            font-size: 3rem;
        }
    </style>
</head>
<body>
    <div class="stars">
        <h1>Welcome to the Stars Theme</h1>
    </div>
    {{ content_for_layout }}
</body>
</html>
git add .
git commit -m "Initial commit with stars theme"
git push origin main
