<!--模拟顶帖-->
<html>
<head>
<script>
window.onload=function(){
var x=0;
var oSpan=document.getElementById('num');
var oBtn=document.getElementById('btn');
oSpan.innerHTML = x;
oBtn.onclick=function()
{
     x++;
     oSpan.innerHTML = x;
}
}
</script>
</head>
<body>
<input id='btn' type="button" value="点击" />
已点次数：
<span id='num'></span>
</body>
</html>
