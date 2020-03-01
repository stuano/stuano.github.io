<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>米粒</title>
<style>
body{
  margin:0; 
  padding:0; 
  overflow-y:hidden
}
</style>
<script src="http://libs.baidu.com/jquery/1.9.0/jquery.js"></script>
<script type="text/javascript"> 
window.onerror=function(){return true;} 
$(function(){ 
  headerH = 0;  
  var h=$(window).height();
  $("#iframe").height((h-headerH)+"px"); 
});
</script>
</head>
<body>
<iframe id="iframe" frameborder="0" src="//player.bilibili.com/player.html?aid=85803886&cid=146658337&page=1&high_quality=1" style="width:100%;"></iframe>
</body>
</html>
