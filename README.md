<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ruby Gardens</title>
    <link rel="stylesheet" type="text/css" title="Ruby Gardens stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css?family=EB+Garamond:500|Roboto" rel="stylesheet">
</head>
<body>
    <div class="header">
        <div class="inner-box">
            <img src="logo.png" />
            <h1>Gardening services for Newmarket, ON and beyond</h1>
        </div>
    </div>
    <div class="footer">
        <div class="inner-box">
            <p>Our website is currently under construction.</p>
            <p>Please contact info@rubygardens.ca if you have questions or concerns.</p>
        </div>
    </div>
    <script src="main.js" type="text/javascript"></script>
</body>
</html>


* {
    box-sizing: border-box;
}

body, html {
    height: 100%;
}

body {
    color: #4B4F53;
    text-align: center;
    margin: 0;
}

body > div {
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
}

.inner-box {
    margin: 2.5rem 0;
    width: 100%;
}

.header {
    background-color: #F1F3F4;
    height: 84%;
}

img {
    width: 50%;
    border: 1px solid #dfe1e5;
    border-radius: 3px;
}

h1 {
    font-family: 'EB Garamond', serif;
    font-weight: 500;
    color: #202124
}

.footer {
    height: 16%;
}

p {
    font-family: 'Roboto', sans-serif;
    margin: .5rem;
}
