<html>
<body style="background-color:black; color:red; font-family:monospace; text-align:center;">
<h1>CRITICAL ERROR</h1>
<p>System Failure Detected. Phone will shut down in 10 seconds.</p>
<p>Code: 0xFF9K - REBOOT REQUIRED</p>
<h2 id="countdown">10</h2>
<script>
let time = 10;
let countdown = setInterval(function() {
    time--;
    document.getElementById("countdown").innerHTML = time;
    if (time <= 0) {
        clearInterval(countdown);
        document.body.innerHTML = "<h1 style='color:white;'>FUCK YOU ADRIAN</h1><h2 style='color:white;'>Your phone is fine dude</h2>";
    }
}, 1000);
</script>
</body>
</html>
