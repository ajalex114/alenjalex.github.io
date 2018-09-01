
<script type="text/javascript">

    var timeOut = 1;

    var x = setInterval(function () {
        document.getElementById("timer").innerHTML = timeOut + " seconds";

        if (timeOut == 0) {
            window.location = "/dev";
        }
        timeOut--;
        
        }
        , 1000);
</script>

<center><p><strong><font size=10>Alen Joseph Alex</font></strong></p?>
<p><font size=4 style="color:grey">Software Engineer at Microsoft</font></p>

<p>
<a href=https://www.facebook.com/alenjalex><img src="assets\images\ico\facebook.png" height=30 width=30 alt="facebook"/></a>
&nbsp;
<a href=https://www.github.com/alenjalex><img src="assets\images\ico\github.png" height=30 width=30 alt="facebook"/></a>
&nbsp;
<a href=https://www.stackoverflow.com/users/9758633/alen-alex><img src="assets\images\ico\stackoverflow.png" height=30 width=30 alt="facebook"/></a>
<a href=https://www.linkedin.com/in/alenalex><img src="assets\images\ico\linkedin2.png" height=30 width=30 alt="linkedin"/></a>
&nbsp;
<a href=https://www.twitter.com/alenjalex><img src="assets\images\ico\twitter.png" height=30 width=30 alt="twitter"/></a>
&nbsp;
<a href=mailto:alen.alex@outlook.com><img src="assets\images\email.png" height=30 width=30 alt="email"/></a>
</p>

<br/>
<hr/>
<br/>
<br/>
<br/>

<center>
You can find my tech/dev write-ups [here](/dev).

You will be redirected to my dev page in <b id="timer"> 5 seconds</b>...
</left>