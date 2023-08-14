# Mr_MMM_go

html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Docment</title>
</head>

<body>
    <header>
        <p>Mr_MMM_go - <strong class="element"></strong></p>
    </header>
    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
    <script>
        var typed = new Typed('.element', {
            strings: ["Хороший человек", "Он хороший программист"],
            typeSpeed: 30,
            loop: 'true',
        });
    </script>
</body>

</html>

css

*{
    padding: 0;
    margin: 0;
}

header{
    width: 100%;
    height: 100vh;
    background: url('image/main-section-bg.jpg') no-repeat center center / cover;
    display: flex;
    justify-content: center;
    align-items: center;
}
header .card {
    text-align: center;
}
.card h1{
    color: white;
    font-size: 70px;
    text-shadow:  0 0 60px black;
    margin-bottom: 10px;
}
.card a{
    font-size: 30px;
    background-color: yellow;
    padding: 10px 20px;
    border-radius: 10px;
    text-decoration: none;
}
