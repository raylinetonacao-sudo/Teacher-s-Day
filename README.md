<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Happy Teacher's Day, Sir Randy Bello 💙</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --bg: #eaf7ff;
            --bg-secondary: #d8f0ff;
            --card: rgba(255, 255, 255, 0.82);
            --text: #23445c;
            --heading: #1976a8;
            --accent: #5bbce9;
            --accent-dark: #278bbd;
            --white: #ffffff;
            --shadow: rgba(40, 130, 180, 0.2);
        }

        body.dark {
            --bg: #101c2b;
            --bg-secondary: #172a3d;
            --card: rgba(25, 42, 59, 0.9);
            --text: #dcefff;
            --heading: #79cdf5;
            --accent: #4baedc;
            --accent-dark: #8dd9fa;
            --white: #eaf8ff;
            --shadow: rgba(0, 0, 0, 0.45);
        }

        body {
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            min-height: 100vh;
            overflow-x: hidden;
            background:
                radial-gradient(circle at 10% 20%, rgba(91,188,233,.25), transparent 25%),
                radial-gradient(circle at 90% 80%, rgba(255,255,255,.5), transparent 25%),
                linear-gradient(135deg, var(--bg), var(--bg-secondary));
            color: var(--text);
            transition: background 0.7s ease, color 0.5s ease;
        }

        /* -----------------------------
           THEME BUTTON
        ----------------------------- */

        .theme-toggle {
            position: fixed;
            top: 20px;
            right: 20px;
            z-index: 1000;
            width: 52px;
            height: 52px;
            border: none;
            border-radius: 50%;
            background: var(--card);
            color: var(--heading);
            box-shadow: 0 8px 25px var(--shadow);
            cursor: pointer;
            font-size: 1.4rem;
            backdrop-filter: blur(10px);
            transition: transform .3s ease, background .5s ease;
        }

        .theme-toggle:hover {
            transform: rotate(20deg) scale(1.1);
        }

        /* -----------------------------
           BACKGROUND DECORATIONS
        ----------------------------- */

        .background-decoration {
            position: fixed;
            inset: 0;
            pointer-events: none;
            overflow: hidden;
            z-index: 0;
        }

        .bubble {
            position: absolute;
            border-radius: 50%;
            background: rgba(255,255,255,.28);
            animation: floatBubble 8s infinite ease-in-out;
        }

        .bubble:nth-child(1) {
            width: 90px;
            height: 90px;
            left: 8%;
            top: 20%;
        }

        .bubble:nth-child(2) {
            width: 50px;
            height: 50px;
            left: 75%;
            top: 30%;
            animation-delay: 2s;
        }

        .bubble:nth-child(3) {
            width: 120px;
            height: 120px;
            left: 82%;
            top: 75%;
            animation-delay: 4s;
        }

        @keyframes floatBubble {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-30px);
            }
        }

        /* -----------------------------
           BALLOONS
        ----------------------------- */

        .balloon {
            position: fixed;
            width: 55px;
            height: 68px;
            border-radius: 50% 50% 45% 45%;
            z-index: 1;
            opacity: .85;
            animation: balloonFloat 7s ease-in-out infinite;
        }

        .balloon::before {
            content: "";
            position: absolute;
            width: 2px;
            height: 120px;
            background: rgba(80,80,80,.35);
            top: 65px;
            left: 50%;
        }

        .balloon::after {
            content: "";
            position: absolute;
            bottom: -5px;
            left: 22px;
            width: 12px;
            height: 12px;
            background: inherit;
            transform: rotate(45deg);
        }

        .balloon.blue {
            background: #67c8f0;
            left: 4%;
            bottom: 8%;
        }

        .balloon.pink {
            background: #f5a8c7;
            right: 5%;
            top: 18%;
            animation-delay: 1.5s;
        }

        .balloon.yellow {
            background: #f8d77b;
            left: 88%;
            bottom: 15%;
            animation-delay: 3s;
        }

        @keyframes balloonFloat {
            0%, 100% {
                transform: translateY(0) rotate(-3deg);
            }
            50% {
                transform: translateY(-25px) rotate(5deg);
            }
        }

        /* -----------------------------
           FLOWERS
        ----------------------------- */

        .flower {
            position: fixed;
            z-index: 2;
            font-size: 2.5rem;
            animation: flowerFloat 6s ease-in-out infinite;
            user-select: none;
        }

        .flower.one {
            left: 3%;
            top: 10%;
        }

        .flower.two {
            right: 3%;
            bottom: 7%;
            animation-delay: 2s;
        }

        .flower.three {
            right: 7%;
            top: 7%;
            animation-delay: 1s;
        }

        .flower.four {
            left: 8%;
            bottom: 20%;
            animation-delay: 3s;
        }

        @keyframes flowerFloat {
            0%, 100% {
                transform: translateY(0) rotate(-5deg);
            }
            50% {
                transform: translateY(-15px) rotate(8deg);
            }
        }

        /* -----------------------------
           MAIN CONTAINER
        ----------------------------- */

        .container {
            position: relative;
            z-index: 10;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 70px 20px;
        }

        .content {
            width: min(900px, 100%);
            text-align: center;
        }

        .subtitle {
            color: var(--heading);
            font-size: 1rem;
            letter-spacing: 4px;
            text-transform: uppercase;
            margin-bottom: 12px;
            animation: fadeDown 1s ease;
        }

        h1 {
            font-size: clamp(2.4rem, 7vw, 5rem);
            color: var(--heading);
            line-height: 1.05;
            margin-bottom: 15px;
            text-shadow: 0 5px 20px var(--shadow);
            animation: fadeDown 1.2s ease;
        }

        .teacher-name {
            font-size: clamp(1.4rem, 4vw, 2rem);
            font-weight: 600;
            margin-bottom: 35px;
            animation: fadeDown 1.4s ease;
        }

        @keyframes fadeDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* -----------------------------
           ENVELOPE
        ----------------------------- */

        .envelope-wrapper {
            position: relative;
            width: min(680px, 95%);
            height: 430px;
            margin: 20px auto;
            perspective: 1200px;
        }

        .envelope {
            position: absolute;
            inset: 0;
            background: #8fd8f6;
            border-radius: 15px;
            box-shadow: 0 25px 60px var(--shadow);
            overflow: visible;
            cursor: pointer;
            transition: transform .8s ease;
        }

        .envelope:hover {
            transform: translateY(-5px);
        }

        .envelope-body {
            position: absolute;
            inset: 0;
            background: linear-gradient(135deg, #92dff9, #62bfe7);
            border-radius: 15px;
            overflow: hidden;
        }

        .envelope-body::before,
        .envelope-body::after {
            content: "";
            position: absolute;
            width: 70%;
            height: 2px;
            background: rgba(255,255,255,.55);
        }

        .envelope-body::before {
            left: -10%;
            bottom: 28%;
            transform: rotate(32deg);
        }

        .envelope-body::after {
            right: -10%;
            bottom: 28%;
            transform: rotate(-32deg);
        }

        .flap {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 60%;
            background: #a5e3fa;
            clip-path: polygon(0 0, 100% 0, 50% 100%);
            transform-origin: top center;
            transition: transform 1.2s cubic-bezier(.68,-.55,.27,1.55);
            z-index: 5;
            border-radius: 15px 15px 0 0;
        }

        .seal {
            position: absolute;
            z-index: 10;
            left: 50%;
            top: 53%;
            transform: translate(-50%, -50%);
            width: 70px;
            height: 70px;
            border-radius: 50%;
            background: #ffffff;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            box-shadow: 0 8px 20px rgba(0,0,0,.15);
            transition: opacity .5s ease, transform .5s ease;
        }

        /* -----------------------------
           LETTER
        ----------------------------- */

        .letter {
            position: absolute;
            z-index: 3;
            left: 5%;
            top: 5%;
            width: 90%;
            height: 90%;
            background: var(--card);
            backdrop-filter: blur(15px);
            border-radius: 12px;
            padding: 35px;
            overflow-y: auto;
            text-align: left;
            opacity: 0;
            transform: translateY(80px);
            transition:
                transform 1.2s ease,
                opacity .8s ease;
            box-shadow: 0 10px 35px rgba(0,0,0,.1);
        }

        .letter h2 {
            text-align: center;
            color: var(--heading);
            margin-bottom: 22px;
            font-size: 1.8rem;
        }

        .letter p {
            line-height: 1.8;
            font-size: 1.05rem;
            margin-bottom: 18px;
        }

        .signature {
            margin-top: 25px;
            text-align: right;
            font-weight: bold;
            color: var(--heading);
            font-size: 1.15rem;
        }

        /* OPEN STATE */

        .envelope.open .flap {
            transform: rotateX(180deg);
        }

        .envelope.open .letter {
            opacity: 1;
            transform: translateY(-35px);
        }

        .envelope.open .seal {
            opacity: 0;
            transform: translate(-50%, -50%) scale(0);
        }

        .envelope.open {
            margin-top: 40px;
        }

        /* -----------------------------
           BUTTON
        ----------------------------- */

        .open-button {
            border: none;
            padding: 14px 28px;
            margin-top: 30px;
            border-radius: 50px;
            background: linear-gradient(135deg, var(--accent), var(--accent-dark));
            color: white;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            box-shadow: 0 10px 25px var(--shadow);
            transition: transform .3s ease, box-shadow .3s ease;
        }

        .open-button:hover {
            transform: translateY(-4px) scale(1.04);
            box-shadow: 0 15px 30px var(--shadow);
        }

        .open-button:active {
            transform: scale(.97);
        }

        /* -----------------------------
           FOOTER
        ----------------------------- */

        .footer {
            margin-top: 35px;
            color: var(--text);
            opacity: .75;
            font-size: .9rem;
        }

        /* -----------------------------
           HEARTS
        ----------------------------- */

        .heart {
            position: fixed;
            font-size: 20px;
            pointer-events: none;
            animation: heartFloat 4s linear forwards;
            z-index: 50;
        }

        @keyframes heartFloat {
            from {
                opacity: 1;
                transform: translateY(0) scale(1);
            }

            to {
                opacity: 0;
                transform: translateY(-150px) scale(1.8) rotate(20deg);
            }
        }

        /* -----------------------------
           MOBILE
        ----------------------------- */

        @media (max-width: 600px) {

            .container {
                padding: 80px 10px 40px;
            }

            .envelope-wrapper {
                height: 520px;
            }

            .letter {
                padding: 25px 20px;
            }

            .letter p {
                font-size: .95rem;
                line-height: 1.65;
            }

            .balloon {
                transform: scale(.7);
            }

            .flower {
                font-size: 1.8rem;
            }
        }
    </style>
</head>

<body>

    <!-- Theme Switch -->
    <button class="theme-toggle" id="themeToggle" title="Toggle dark mode">
        🌙
    </button>

    <!-- Decorative Background -->
    <div class="background-decoration">
        <div class="bubble"></div>
        <div class="bubble"></div>
        <div class="bubble"></div>
    </div>

    <!-- Balloons -->
    <div class="balloon blue"></div>
    <div class="balloon pink"></div>
    <div class="balloon yellow"></div>

    <!-- Flowers -->
    <div class="flower one">🌸</div>
    <div class="flower two">🌷</div>
    <div class="flower three">🌼</div>
    <div class="flower four">🌺</div>

    <!-- Main Content -->
    <main class="container">

        <section class="content">

            <div class="subtitle">
                A Special Message For
            </div>

            <h1>
                Happy Teacher's Day! 💙
            </h1>

            <div class="teacher-name">
                To Sir Randy Bello 🌷
            </div>

            <!-- Envelope -->
            <div class="envelope-wrapper">

                <div class="envelope" id="envelope">

                    <div class="envelope-body"></div>

                    <!-- Letter -->
                    <article class="letter">

                        <h2>
                            Dear Sir Randy Bello, 💙
                        </h2>

                        <p>
                            Happy Teacher's Day, Sir!
                        </p>

                        <p>
                            Today is a special day to appreciate the teachers
                            who do more than simply teach lessons. Thank you
                            for sharing your knowledge, patience, experience,
                            and passion with us.
                        </p>

                

                        <p>
                            Every line of code we write is a small step toward
                            becoming better developers, and your guidance has
                            made that journey more meaningful.
                        </p>

                        <p>
                            We truly appreciate the time and effort you give
                            to your students. Behind every lesson, activity,
                            correction, and explanation is a teacher who wants
                            us to improve and succeed.
                        </p>

                        <p>
                            May you continue inspiring students to learn,
                            create, and believe in what they can accomplish.
                            Your lessons will remain a part of the skills and
                            memories we carry with us.
                        </p>

                        <p>
                            Thank you for being a great teacher and mentor.
                            We are grateful for everything you do.
                        </p>

                        <p>
                            Wishing you a wonderful Teacher's Day filled with
                            happiness, appreciation, and well-deserved
                            recognition. 🌸🎈
                        </p>

                        <div class="signature">
                            With gratitude and respect,<br>
                            Your Student 💙
                        </div>

                    </article>

                    <!-- Envelope Flap -->
                    <div class="flap"></div>

                    <!-- Seal -->
                    <div class="seal">
                        💙
                    </div>

                </div>

            </div>

            <button class="open-button" id="openButton">
                💌 Open Your Letter
            </button>

            <div class="footer">
                Made with gratitude, appreciation, and a little bit of code. 💻💙
            </div>

        </section>

    </main>

    <script>

        const envelope = document.getElementById("envelope");
        const openButton = document.getElementById("openButton");
        const themeToggle = document.getElementById("themeToggle");

        let isOpen = false;

        /* --------------------------------
           OPEN / CLOSE LETTER
        -------------------------------- */

        function toggleLetter() {

            isOpen = !isOpen;

            envelope.classList.toggle("open", isOpen);

            if (isOpen) {
                openButton.innerHTML = "💙 Close Letter";

                // Create floating hearts
                for (let i = 0; i < 15; i++) {
                    setTimeout(createHeart, i * 120);
                }

            } else {
                openButton.innerHTML = "💌 Open Your Letter";
            }
        }

        envelope.addEventListener("click", toggleLetter);
        openButton.addEventListener("click", toggleLetter);


        /* --------------------------------
           DARK / LIGHT MODE
        -------------------------------- */

        themeToggle.addEventListener("click", () => {

            document.body.classList.toggle("dark");

            if (document.body.classList.contains("dark")) {
                themeToggle.textContent = "☀️";
                themeToggle.title = "Switch to light mode";
            } else {
                themeToggle.textContent = "🌙";
                themeToggle.title = "Switch to dark mode";
            }

        });


        /* --------------------------------
           FLOATING HEART EFFECT
        -------------------------------- */

        function createHeart() {

            const heart = document.createElement("div");

            heart.className = "heart";

            const hearts = ["💙", "💖", "💗", "🌸", "✨"];

            heart.textContent =
                hearts[Math.floor(Math.random() * hearts.length)];

            heart.style.left =
                Math.random() * 100 + "vw";

            heart.style.top =
                60 + Math.random() * 30 + "vh";

            heart.style.fontSize =
                15 + Math.random() * 20 + "px";

            document.body.appendChild(heart);

            setTimeout(() => {
                heart.remove();
            }, 4000);
        }


        /* --------------------------------
           AUTOMATIC FLOATING FLOWERS
        -------------------------------- */

        setInterval(() => {

            const flower = document.createElement("div");

            flower.className = "heart";

            const flowers = [
                "🌸",
                "🌷",
                "🌼",
                "🌺",
                "💠"
            ];

            flower.textContent =
                flowers[Math.floor(Math.random() * flowers.length)];

            flower.style.left =
                Math.random() * 100 + "vw";

            flower.style.top = "100vh";

            flower.style.fontSize =
                18 + Math.random() * 18 + "px";

            document.body.appendChild(flower);

            setTimeout(() => {
                flower.remove();
            }, 4000);

        }, 1300);


        /* --------------------------------
           KEYBOARD ACCESSIBILITY
        -------------------------------- */

        document.addEventListener("keydown", (event) => {

            if (event.key === "Enter" && document.activeElement === openButton) {
                toggleLetter();
            }

            if (event.key.toLowerCase() === "d") {
                document.body.classList.toggle("dark");

                if (document.body.classList.contains("dark")) {
                    themeToggle.textContent = "☀️";
                } else {
                    themeToggle.textContent = "🌙";
                }
            }

        });

    </script>

</body>
</html>
```
