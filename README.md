<!doctype html>
<html lang="ja">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Signage</title>
  <style>
    html, body {
      margin: 0;
      width: 100%;
      height: 100%;
      background: #000;
      overflow: hidden;
    }
    video {
      width: 100vw;
      height: 100vh;
      object-fit: cover;
    }
  </style>
</head>
<body>
  <video src="./signage.mp4" autoplay muted loop playsinline></video>

  <script>
    // 長時間運用で更新を拾わせたい場合。10分ごとにページ再読み込み。
    setInterval(() => location.reload(), 10 * 60 * 1000);
  </script>
</body>
</html>
