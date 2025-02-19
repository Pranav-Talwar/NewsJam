<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NewsJam - React News App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }
        h1, h2 {
            color: #333;
        }
        p {
            color: #555;
        }
        ul {
            list-style-type: square;
            padding-left: 20px;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        code {
            background: #eee;
            padding: 3px 6px;
            border-radius: 4px;
            font-family: monospace;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>NewsJam - React News App</h1>
        <p><strong>NewsJam</strong> is a simple news application built with React. It pulls the latest articles from the NewsAPI, categorizing them into sections like Business, Entertainment, Health, Science, Sports, and Technology. The app features a clean and responsive design, making it easy to navigate on any device, from mobile to desktop.</p>

        <h2>Key Features:</h2>
        <ul>
            <li><strong>Multiple News Categories:</strong> Access breaking news across different categories including Business, Entertainment, Health, Science, Sports, and Technology.</li>
            <li><strong>Pagination:</strong> Easily flip through articles with the "Previous" and "Next" buttons.</li>
            <li><strong>Responsive Design:</strong> Optimized for both mobile and desktop viewing, providing a smooth experience on any screen size.</li>
            <li><strong>Loading State:</strong> A loading spinner appears while the app fetches news, so you're always aware of the app's status.</li>
            <li><strong>Dynamic Routing:</strong> Seamless navigation through different news sections with React Router.</li>
        </ul>

        <h2>Disclaimer:</h2>
        <p>To use this app, you’ll need a valid API key from <a href="https://newsapi.org/" target="_blank">NewsAPI</a>. You can grab one by signing up on their website. Once you have your key, just replace the <code>YOUR_API_KEY</code> placeholder in <code>App.js</code> with your actual API key.</p>
    </div>
</body>
</html>
