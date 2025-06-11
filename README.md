<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>hidden</title>
  <style>
    body {
      background-color: #000;
      color: #fff;
      font-family: 'Courier New', Courier, monospace;
      padding: 2em;
    }
    .faint {
      color: #999;
      font-size: 0.9em;
    }
    .secret {
      color: #222; /* 一見見えない（暗号） */
    }
  </style>
</head>
<body onload="setTimeout(() => window.close(), 15000)">
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
</body>
</html>
