<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beautiful Log Viewer</title>
    <style>
        /* Add your custom styles here */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            padding: 20px;
        }
        
        .log-container {
            background-color: #fff;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            max-width: 800px;
            margin: 0 auto;
        }

        pre {
            white-space: pre-wrap;
            word-wrap: break-word;
        }
    </style>
</head>
<body>
    <div class="log-container">
        <h1>Beautiful Log Viewer</h1>
        <p>This is a simple log viewer for your server. It provides an easy-to-read interface for viewing log files.</p>
        <h2>Installation</h2>
        <ol>
            <li>Download the log viewer file and place it in your server directory.</li>
            <li>Open your <code>server.cfg</code> file and add the following line at the end: <br><code>ensure log</code></li>
            <li>Restart your server or refresh from the console. You can use the <code>logout</code> command.</li>
        </ol>
        <h2>Usage</h2>
        <p>Once the server is up and running, visit the log viewer URL in your web browser. You should now see a beautiful interface for viewing your log files.</p>
        <p>Enjoy! If you encounter any issues or have suggestions for improvements, feel free to open an issue or create a pull request.</p>
        <h2>License</h2>
        <p>This project is licensed under the <a href="LICENSE">MIT License</a>. Feel free to use, modify, and distribute it as you like.</p>
    </div>
</body>
</html>
****
