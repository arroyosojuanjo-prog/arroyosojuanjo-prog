<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Juan Arroyo - Developer</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #0d1117;
      font-family: "Segoe UI", Roboto, Arial, sans-serif;
    }

    .banner {
      width: 100%;
      max-width: 800px;
      height: 180px;
      margin: 30px auto;
      position: relative;
      overflow: hidden;
      border: 1.5px dashed #00ff66;
      border-radius: 12px;
      background:
        linear-gradient(rgba(13,17,23,.9), rgba(13,17,23,.9)),
        repeating-linear-gradient(
          0deg,
          transparent 0px,
          transparent 19px,
          #161b22 20px
        ),
        repeating-linear-gradient(
          90deg,
          transparent 0px,
          transparent 19px,
          #161b22 20px
        );
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }

    .top-line {
      position: absolute;
      top: 40px;
      left: 6%;
      width: 88%;
      height: 2px;
      background: linear-gradient(
        90deg,
        #00ff66,
        #00e5ff,
        #0088ff
      );
      border-radius: 10px;
      box-shadow: 0 0 10px #00ff66;
    }

    .name {
      font-size: clamp(28px, 6vw, 42px);
      font-weight: 900;
      letter-spacing: 4px;
      background: linear-gradient(
        90deg,
        #00ff66,
        #00e5ff,
        #0088ff
      );
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-shadow: 0 0 20px rgba(0,255,102,.25);
      z-index: 2;
    }

    .subtitle {
      margin-top: 8px;
      color: #8b949e;
      font-family: "Fira Code", monospace;
      font-size: 16px;
      letter-spacing: 2px;
    }

    .bottom-line {
      position: absolute;
      bottom: 30px;
      width: 300px;
      max-width: 50%;
      height: 1.5px;
      background: linear-gradient(
        90deg,
        #00ff66,
        #00e5ff,
        #0088ff
      );
      box-shadow: 0 0 8px #00e5ff;
    }
  </style>
</head>

<body>

  <div class="banner">

    <div class="top-line"></div>

    <div class="name">
      JUAN ARROYO
    </div>

    <div class="subtitle">
      &lt; DEVELOPER /&gt;
    </div>

    <div class="bottom-line"></div>

  </div>

</body>
</html>
