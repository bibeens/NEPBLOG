<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .post {
            border-bottom: 1px solid #ddd;
            padding: 20px 0;
        }
        .post:last-child {
            border-bottom: none;
        }
        .post h2 {
            color: #333;
        }
        .post a {
            text-decoration: none;
            color: #007BFF;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Blog</h1>
    </header>
    <div class="container">
        <div class="post">
            <h2>First Blog Post</h2>
            <p>This is a short introduction to my first blog post.</p>
            <a href="#">Read More</a>
        </div>
        <div class="post">
            <h2>Second Blog Post</h2>
            <p>Another exciting blog post for you to read!</p>
            <a href="#">Read More</a>
        </div>
    </div>
</body>
</html>
