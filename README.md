<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Love You Oside</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            background: url('https://www.example.com/romantic-background.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #6d4b88;
            margin: 0;
            padding: 0;
            position: relative;
        }
        header {
            background-color: #ff4d4d;
            color: white;
            padding: 40px;
            text-align: center;
            border-bottom: 4px solid #e60000;
        }
        h1 {
            font-size: 3em;
            letter-spacing: 2px;
        }
        nav {
            text-align: center;
            background-color: #e60000;
            padding: 15px 0;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            margin: 0 20px;
            font-size: 1.2em;
            font-weight: bold;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        nav a:hover {
            background-color: #ff6666;
        }
        section {
            padding: 40px;
            margin: 20px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            border: 1px solid #ff9999;
        }
        h2 {
            font-size: 2em;
            color: #ff4d4d;
            text-align: center;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2em;
            line-height: 1.6;
            text-align: center;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #e60000;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
            font-size: 1.1em;
        }
        footer p {
            margin: 0;
        }
        marquee {
            font-size: 1.5em;
            color: #ff4d4d;
            background-color: #fff;
            padding: 10px 0;
            margin: 20px 0;
        }
        .heart {
            position: absolute;
            bottom: -10vh;
            left: 50%;
            width: 20px;
            height: 20px;
            background-color: #ff4d4d;
            clip-path: polygon(50% 0%, 100% 30%, 80% 100%, 20% 100%, 0 30%);
            animation: float-hearts 5s infinite ease-in-out;
            opacity: 0.7;
        }

        @keyframes float-hearts {
            0% { transform: translateY(100vh) scale(0.5); opacity: 1; }
            100% { transform: translateY(-10vh) scale(1.2); opacity: 0; }
        }

        .romantic-images {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 30px 0;
        }

        .romantic-images img {
            width: 300px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        audio {
            display: none;
        }

        .love-letter {
            font-size: 1.3em;
            line-height: 1.8;
            color: #6d4b88;
            text-align: center;
        }

        hr {
            border: none;
            height: 50px;
            background: url('https://cdn.pixabay.com/photo/2015/04/10/13/05/heart-716625_960_720.png') center no-repeat;
            background-size: contain;
        }

        /* Starry Night Footer */
        .starry-night {
            background: url('https://www.example.com/starry-night.jpg') repeat-x;
            height: 200px;
            width: 100%;
            position: absolute;
            bottom: 0;
            z-index: -1;
        }

        /* Love Quiz */
        .quiz-section {
            padding: 30px;
            margin: 20px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        .quiz-section h2 {
            color: #e60000;
            text-align: center;
            font-size: 2em;
        }

        .quiz-section label {
            font-size: 1.2em;
            display: block;
            margin: 10px 0;
        }

        .quiz-section input[type="radio"] {
            margin-right: 10px;
        }

        .quiz-section button {
            background-color: #ff4d4d;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .quiz-section button:hover {
            background-color: #e60000;
        }
    </style>
</head>
<body>
    <header>
        <h1>I Love You Oside</h1>
    </header>
    <marquee>Yours truly, Monteli Blessen</marquee>
    <nav>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
        <a href="#letter">Love Letter</a>
        <a href="#quiz">Love Quiz</a>
    </nav>
    <section id="about">
        <h2>About Us</h2>
        <p>In a relationship for 1 month and forever in love. This bond is made to last, and every day is a celebration of our love.</p>
    </section>
    <section id="letter">
        <h2>Love Letter</h2>
        <p class="love-letter">
            My beloved soulmate Oside,<br>
            Every moment apart feels like an eternity, and every thought of you fills my heart with warmth. 
            You are the light in my life, the beat in my heart, and the reason I smile every single day. 
            I promise to cherish you forever and make every day we share a beautiful memory.<br>
            Yours always,<br>
            Monteli
        </p>
        <div class="romantic-images">
            <img src="https://www.rd.com/wp-content/uploads/2021/01/GettyImages-912379960.jpg" alt="Beautiful bouquet of flowers">
            <img src="https://cdn.pixabay.com/photo/2017/02/01/22/02/valentines-day-2035265_1280.jpg" alt="Romantic heart and roses">
        </div>
    </section>
    <section id="quiz" class="quiz-section">
        <h2>How much do you love me?</h2>
        <form>
            <label for="a_lot">
                <input type="radio" id="a_lot" name="love" value="a_lot">
                A lot
            </label>
            <label for="more_than_words">
                <input type="radio" id="more_than_words" name="love" value="more_than_words">
                More than words can say
            </label>
            <label for="infinite">
                <input type="radio" id="infinite" name="love" value="infinite">
                Infinitely
            </label><br><br>
            <button type="submit">Submit</button>
        </form>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p><strong>Phone:</strong> 0797768149</p>
        <p><strong>Instagram:</strong> dreamy._meiser._</p>
        <p><strong>Facebook:</strong> Monteli Blessen</p>
    </section>
    <footer>
        <p>Forever Yours, Monteli Blessen</p>
    </footer>
    <div class="starry-night"></div>
    
    <!-- Background music -->
    <audio autoplay loop>
        <source src="https://www.example.com/love-song.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <!-- Heart Animations -->
    <div class="heart"></div>
    <div class="heart" style="animation-delay: 1s; left: 40%;"></div>
    <div class="heart" style="animation-delay: 2s; left: 60%;"></div>
</body>
</html>
