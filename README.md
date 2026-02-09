
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>OCTOPUS</title>
    <link rel="stylesheet" href="style.css" />
</head>

<body>

    <!-- Moving Background Layer -->
    <div class="bg-overlay"></div>

    <div class="container">

        <h3 class="title">OCTOPUS</h3>
        <p class="tagline">Best Cricket Expert → Tips, Calls & Live Analysis</p>

        <!-- Floating Icons -->
        <div class="floating-icons">
            <img src="icon1.png" />
            <img src="icon2.png" />
            <img src="icon3.png" />
        </div>

        <div class="big-counter" id="big-counter">60</div>
        <div class="sub-brand">Join Fast...</div>

        <div class="stats">
            <p>✔ <strong>81/87 MATCH PASSED</strong> 🏆</p>
            <p>✔ <strong>Oldest CRICKET Tipper Since 2009</strong> 🏆</p>
            <p>✔ <strong>40/42 BBL MATCHES PASSED</strong> 🏆</p>
        </div>

       <!-- CTA with LEAD tracking + delay redirect -->
        <a href="javascript:void(0)"
           class="cta-btn"
           onclick="fbq('track', 'Lead'); setTimeout(function(){ window.location.href='https://t.me/+YRGzL7w3xw5hYTc1'; }, 300);">
            SUBSCRIBE — JOIN TELEGRAM ✈️
        </a>

        <p class="timer-text">FREE JOINING ENDS IN <span id="timer">60s</span></p>

        <p class="footer-text">99% Right Accuracy ke sath best result</p>
    </div>

    <script src="script.js"></script>
</body>

</html>
