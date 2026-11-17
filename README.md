<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Chromine</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@1,600&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; }
    body { margin: 0; background: #080808; }
    .nameplate {
      position: relative;
      isolation: isolate;
      width: 289px;
      max-width: 100%;
      min-height: 97px;
      padding: 21px 20px 10px;
      overflow: hidden;
      background: #080808;
      color: #e6e3dd;
    }
    .nameplate::before {
      content: "";
      position: absolute;
      inset: 0;
      z-index: -1;
      opacity: .27;
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='150' height='150'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.85' numOctaves='3' stitchTiles='stitch'/%3E%3CfeColorMatrix type='saturate' values='0'/%3E%3C/filter%3E%3Cpath fill='%23808080' filter='url(%23n)' d='M0 0h150v150H0z'/%3E%3C/svg%3E");
    }
    .nameplate h1 {
      margin: 0;
      font-family: "Cormorant Garamond", "Times New Roman", serif;
      font-size: 46px;
      font-style: italic;
      font-weight: 600;
      line-height: 1.12;
      letter-spacing: -.025em;
    }
    .nameplate::after {
      content: "";
      display: block;
      height: 2px;
      margin-top: 11px;
      background: #d1d0ca;
    }
    ::selection { background: #e6e3dd; color: #080808; }
  </style>
</head>
<body>
  <div class="nameplate">
    <h1>Chromine</h1>
  </div>
</body>
</html>
𝐶ℎ𝑟𝑜𝑚𝑖𝑛𝑒 is a semi-auto minecraft server set-up/controler helper.
