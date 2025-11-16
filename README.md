<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Kino Sayt</title>

    <!-- Yandex.RTB Loader (Majburiy) -->
    <script>window.yaContextCb = window.yaContextCb || [];</script>
    <script src="https://yandex.ru/ads/system/context.js" async></script>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #111;
            color: #fff;
            padding: 20px;
        }
        .content {
            text-align: center;
            margin-top: 120px;
        }
    </style>
</head>

<body>

    <!-- Yandex Fullscreen Reklama -->
    <div id="yandex_rtb_fullscreen"></div>
    <script>
        window.yaContextCb.push(() => {
            Ya.Context.AdvManager.render({
                blockId: "R-A-17755051-1",  // Sening Fullscreen ID
                type: "fullscreen",
                platform: "touch",
                containerId: "yandex_rtb_fullscreen"
            });
        });
    </script>

    <!-- Sayt Kontenti -->
    <div class="content">
        <h1>Kino saytingiz ishlayapti 😊</h1>
        <p>Bu sinov versiyasi. Hozircha faqat fullscreen reklama o‘rnatilgan.</p>
    </div>

</body>
</html>
