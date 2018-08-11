
<script type="text/javascript">

    var timeOut = 4;

    var x = setInterval(function () {
        document.getElementById("timer").innerHTML = timeOut + " seconds";

        if (timeOut == 0) {
            window.location = "/dev";
        }
        timeOut--;
        
        }
        , 1000);
</script>

# Welcome to **ajalex.com**

_Hi_, I'm **Alen Alex**.  


You can find my tech/dev write-ups [here](/dev).

You will be redirected to my dev page in <b id="timer"> 5 seconds</b>...