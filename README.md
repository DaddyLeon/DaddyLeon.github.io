html
Code kopieren
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landscape Image Quiz</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Landscape Image Quiz</h1>
        <div id="quiz">
            <div id="image-container">
                <img src="" alt="Landscape Image" id="landscape-image">
            </div>
            <form id="quiz-form">
                <label for="country-input">Enter the country:</label>
                <input type="text" id="country-input" required>
                <button type="submit">Submit</button>
            </form>
            <button id="shuffle-btn">Shuffle Images</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
