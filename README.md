<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodeLab</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            color: #14213d;
        }

        header {
            background: #13213b;
            color: white;
            min-height: 107px;
            padding: 20px 2.4%;
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 20px;
        }

        .logo {
            font-size: 44px;
            font-weight: bold;
        }

        nav {
            display: flex;
            gap: 36px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 29px;
        }

        button {
            background: #ffb900;
            border: none;
            border-radius: 12px;
            padding: 15px 29px;
            font-size: 22px;
            font-weight: bold;
            cursor: pointer;
        }

        .hero {
            background: #315bea;
            color: white;
            min-height: 465px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 30px 20px;
        }

        .hero h1 {
            font-size: 58px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 28px;
            margin-bottom: 22px;
        }

        .courses {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 28px;
            padding: 43px;
        }

        .card {
            background: #eef2ff;
            border-radius: 19px;
            padding: 36px 10px;
            text-align: center;
        }

        .card h2 {
            font-size: 34px;
        }

        .card p {
            font-size: 28px;
        }

        @media (max-width: 768px) {
            header {
                flex-direction: column;
                text-align: center;
            }

            .logo {
                font-size: 34px;
            }

            nav {
                gap: 18px;
                flex-wrap: wrap;
                justify-content: center;
            }

            nav a {
                font-size: 18px;
            }

            button {
                font-size: 17px;
            }

            .hero {
                min-height: 350px;
            }

            .hero h1 {
                font-size: 36px;
            }

            .hero p {
                font-size: 19px;
            }

            .courses {
                grid-template-columns: repeat(2, 1fr);
                gap: 15px;
                padding: 20px;
            }

            .card h2 {
                font-size: 25px;
            }

            .card p {
                font-size: 17px;
            }
        }

        @media (max-width: 400px) {
            .courses {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>

<body>

    <header>
        <div class="logo">CodeLab</div>

        <nav>
            <a href="#home">Home</a>
            <a href="#courses">Courses</a>
            <a href="#contact">Contact</a>
        </nav>

        <button>Sign up</button>
    </header>

    <section class="hero" id="home">
        <h1>Learn Web Development</h1>
        <p>Start from zero. Build real projects.</p>
        <button>Get started</button>
    </section>

    <section class="courses" id="courses">

        <div class="card">
            <h2>HTML</h2>
            <p>Build the structure</p>
        </div>

        <div class="card">
            <h2>CSS</h2>
            <p>Make it beautiful</p>
        </div>

        <div class="card">
            <h2>JavaScript</h2>
            <p>Make it smart</p>
        </div>

        <div class="card" id="contact">
            <h2>Git</h2>
            <p>Save your work</p>
        </div>

    </section>

</body>
</html>

