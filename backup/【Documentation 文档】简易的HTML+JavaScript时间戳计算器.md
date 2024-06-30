代码如下
```html
<script>
 function calcUnixTimeStamp() {
  var timestamp = document.getElementById('timestamp')
  var time = new Date(timestamp * 1000)
  alert('转换结果：' + time)
 }
</script>
<h1>Unix时间戳转正常时间</h1>
<input id="timestamp" type="text" placeholder="输入时间戳"><input type="button" value="转换" onclick="calcUnixTimeStamp()">
```