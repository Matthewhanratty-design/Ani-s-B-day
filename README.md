# Ani-s-B-day
index.html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Happy Birthday Ani!</title>

  <!-- Nice serif display font (used for both heading and poem) -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg: #f216d1;
      --text: #ffffff;
      --card-bg: rgba(255,255,255,0.06);
    }

    html,body{
      height:100%;
      margin:0;
      font-family: "Playfair Display", Georgia, serif;
      background: var(--bg);
      color: var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }

    /* Center everything */
    .wrap{
      min-height:100%;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:48px 24px;
      box-sizing:border-box;
    }

    .card{
      max-width:860px;
      width:100%;
      text-align:center;
      padding:48px 36px;
      border-radius:18px;
      background: linear-gradient(180deg, rgba(255,255,255,0.06), rgba(255,255,255,0.03));
      box-shadow: 0 10px 30px rgba(0,0,0,0.18);
      backdrop-filter: blur(6px);
    }

    h1{
      margin:0 0 20px 0;
      font-weight:700;
      letter-spacing:0.6px;
      font-size: clamp(32px, 6vw, 64px);
      line-height:1;
      text-shadow: 0 2px 6px rgba(0,0,0,0.25);
    }

    .poem{
      margin:0 auto;
      font-weight:400;
      font-size: clamp(16px, 2.6vw, 20px);
      line-height:1.55;
      max-width:760px;
      white-space: pre-wrap; /* preserves line breaks from source text */
    }

    .signature{
      margin-top:26px;
      font-size:18px;
      opacity:0.95;
    }

    /* small screens tweak */
    @media (max-width:420px){
      .card{ padding:28px 18px; border-radius:14px; }
      h1{ font-size:28px; }
      .poem{ font-size:15px; }
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card" role="main" aria-labelledby="happy-title">
      <h1 id="happy-title">Happy Birthday</h1>

      <div class="poem" aria-label="Birthday Rhyme">
Aus in Oz, you never fail to get an applause.
 It's all because girlie has very little flaws.

Always whipping out your card games with absolutely no shame. Lost in her cross words, nothing seems absurd.

Running around Melbourne with no direction,  always needing correction. Upon reflection, you're truly perfection.

Your personality is now a normality and the spark in our reality.

So let's raise a glass, for our favourite lass.
May your happiness grow as the years pass.

Happy Birthday Ani!

Matt xx
      </div>

      <div class="signature" aria-hidden="true">— With love</div>
    </div>
  </div>
</body>
</html>
