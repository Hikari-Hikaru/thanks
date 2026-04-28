<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>hidden</title>
  <style>
    body {
      background-color: #000;
      color: #fff;
      font-family: 'Courier New', monospace;
      padding: 2em;
      opacity: 1;
    }

    .faint {
      color: #999;
      font-size: 0.9em;
    }

    .secret {
      color: #222;
    }
  </style>
</head>

<body>

<h2>……ここまで読んでくれてありがとう。</h2>

<p>
　でも、もう遅いよね。<br>
　あのとき、わたしは気づいてた。<br>
　誰が、わたしを……。
</p>

<p>
　お願い。もしこれを見つけてくれたなら、<br>
　わたしがなぜ、こんな最後を迎えたのかを知ってほしい。<br>
　そして、<span class="secret">〇〇〇</span>を…。
</p>

<p class="faint">（このページはすぐに閉じるかもしれない）</p>

<script>
  setTimeout(() => {
    document.body.style.transition = "opacity 2s";
    document.body.style.opacity = "0";

    setTimeout(() => {
      window.location.href = "https://hikari-hikaru.github.io/Emma_dailyblog/";
    }, 2000);
  }, 58000);
</script>

</body>
</html>
