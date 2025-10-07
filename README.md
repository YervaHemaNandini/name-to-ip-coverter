<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Domain to IP Converter</title>
    <link rel="stylesheet" href="style.css"> </head>
<body>
    <div class="container">
        <h1>🌐 Domain to IP Converter</h1>
        <form id="converter-form">
            <label for="domainName">Enter Domain Name:</label>
            <input type="text" id="domainName" name="domainName" placeholder="e.g., google.com" required>
            <button type="submit">Get IP Address</button>
        </form>
        <div id="result-area">
            <p><strong>IP Address:</strong> <span id="ip-result">Awaiting input...</span></p>
        </div>
    </div>
    <script src="app.js"></script> </body>
</html>
