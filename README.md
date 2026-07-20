<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>Your Company Name — Coming Soon</title>

    <meta
        name="description"
        content="A new independent game and technology company is under development."
    >

    <style>
        :root {
            color-scheme: dark;
            font-family:
                Inter,
                system-ui,
                -apple-system,
                BlinkMacSystemFont,
                "Segoe UI",
                sans-serif;
        }

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            min-height: 100vh;
            display: grid;
            place-items: center;
            background:
                radial-gradient(circle at top, #26334b 0%, #10141d 45%, #080a0f 100%);
            color: #f4f6fa;
        }

        main {
            width: min(760px, calc(100% - 40px));
            padding: 64px 24px;
            text-align: center;
        }

        .eyebrow {
            margin: 0 0 18px;
            color: #b8c4da;
            font-size: 0.85rem;
            font-weight: 700;
            letter-spacing: 0.18em;
            text-transform: uppercase;
        }

        h1 {
            margin: 0;
            font-size: clamp(2.5rem, 9vw, 5.5rem);
            line-height: 0.95;
            letter-spacing: -0.05em;
        }

        .statement {
            max-width: 620px;
            margin: 28px auto 0;
            color: #cbd3e0;
            font-size: clamp(1.05rem, 2.5vw, 1.3rem);
            line-height: 1.7;
        }

        .status {
            display: inline-block;
            margin-top: 34px;
            padding: 10px 16px;
            border: 1px solid rgba(255, 255, 255, 0.22);
            border-radius: 999px;
            background: rgba(255, 255, 255, 0.06);
            color: #e8edf6;
            font-size: 0.95rem;
        }

        footer {
            margin-top: 64px;
            color: #8f9aad;
            font-size: 0.85rem;
        }
    </style>
</head>

<body>
    <main>
        <p class="eyebrow">Independent games and technology</p>

        <h1>Your Company Name</h1>

        <p class="statement">
            We are building a new kind of game platform centered on
            permanent ownership, affordable hardware, physical media,
            local multiplayer, privacy, and independent development.
        </p>

        <p class="status">Currently in development</p>

        <footer>
            &copy; 2026 Your Company Name. All rights reserved.
        </footer>
    </main>
</body>
</html>