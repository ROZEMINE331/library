<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TRPG & Scenario Log</title>
    <style>
        /* --- ここをいじれば全体の雰囲気が変わります --- */
        :root {
            --bg-color: #1a1a1a;       /* 背景色（チョコっぽい黒） */
            --accent-color: #d2691e;   /* アクセント（チョコブラウン） */
            --text-color: #f5f5f5;     /* 文字色 */
            --card-bg: #2a2a2a;        /* カードの背景 */
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: "Helvetica Neue", Arial, "Hiragino Kaku Gothic ProN", "Hiragino Sans", sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        header {
            padding: 4rem 2rem;
            text-align: center;
            background: linear-gradient(transparent, var(--card-bg));
        }

        main {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem;
        }

        h2 {
            border-left: 5px solid var(--accent-color);
            padding-left: 1rem;
            margin-top: 3rem;
        }

        /* カードレイアウト */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-top: 1rem;
        }

        .card {
            background: var(--card-bg);
            padding: 1.5rem;
            border-radius: 8px;
            transition: transform 0.3s;
            border: 1px solid #444;
        }

        .card:hover {
            transform: translateY(-5px);
            border-color: var(--accent-color);
        }

        .card h3 { margin-top: 0; color: var(--accent-color); }
        .tag { font-size: 0.8rem; background: #444; padding: 2px 8px; border-radius: 4px; }

        footer { text-align: center; padding: 3rem; opacity: 0.6; font-size: 0.8rem; }
    </style>
</head>
<body>

<header>
    <h1>TRPG & Scenario Log</h1>
    <p>通過した物語と、共に歩んだ記録</p>
</header>

<main>
    <section id="scenarios">
        <h2>Passage Scenarios</h2>
        <div class="grid">
            <div class="card">
                <span class="tag">CoC</span>
                <h3>シナリオ名A</h3>
                <p>KP: 〇〇様 / END: A</p>
            </div>
            <div class="card">
                <span class="tag">マダミス</span>
                <h3>作品名B</h3>
                <p>担当: キャラクター名</p>
            </div>
        </div>
    </section>

    <section id="characters">
        <h2>Characters</h2>
        <div class="grid">
            <div class="card">
                <h3>PC名：〇〇</h3>
                <p>システム：クトゥルフ神話TRPG</p>
                <p>一言メモ：ここにキャラの性格とか</p>
            </div>
        </div>
    </section>
</main>

<footer>
    &copy; 2026 Your Name - Built with Minimal Effort
</footer>

</body>
</html>
