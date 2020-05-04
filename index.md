# <center>Cirdel/UniversityEntranceExaminationCountdown</center>
## 2022年全国高等院校考试倒计时
<center>
<html>
<head>
    <div style="text-align:center;margin-top:1000px;">
    <span>距离2022年成人高考还有：</span>
    <span id="t_d"></span>
    <span id="t_h">00时</span>
    <span id="t_m">00分</span>
    <span id="t_s">00秒</span>
</div>
<script type="text/javascript">
    function getRTime(){
        var EndTime= new Date('2022/6/7 00:00:00'); //截止时间
        var NowTime = new Date();
        var t =EndTime.getTime() - NowTime.getTime();
        
        var d=Math.floor(t/1000/60/60/24);
        var h=Math.floor(t/1000/60/60%24);
        var m=Math.floor(t/1000/60%60);
        var s=Math.floor(t/1000%60);
        
        document.getElementById("t_d").innerHTML = d + "d";
        document.getElementById("t_h").innerHTML = h + "h";
        document.getElementById("t_m").innerHTML = m + "m";
        document.getElementById("t_s").innerHTML = s + "s";
    }
    setInterval(getRTime,1000);
</script>
</head>
<body>
<div id="timer"></div>
</body>
</html>
</center>
### <center> Before The University/College entrance examination.</center>

