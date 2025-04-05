<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Blog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .blog-posts {
            margin: 20px 0;
        }
        .post {
            background: #fff;
            margin-bottom: 20px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .post h2 {
            margin-top: 0;
        }
        .post p {
            line-height: 1.6;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>My Simple Blog</h1>
        </div>
    </header>
    <div class="container">
        <div class="blog-posts">
            <div class="post">
                <h2>Blog Post Title</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque ut eros eget erat fermentum pharetra. Nulla facilisi. Vivamus ut eros vel velit varius scelerisque.</p>
            </div>
            <div class="post">
                <h2>Another Blog Post</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque ut eros eget erat fermentum pharetra. Nulla facilisi. Vivamus ut eros vel velit varius scelerisque.</p>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 Simple Blog. All rights reserved.</p>
    </footer>
</body>
</html>
