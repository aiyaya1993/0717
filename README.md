# 0717
getElementById()的使用
<!DOCTYPE html>
<html>
  <head>未命名</head>
  <title>Test</title>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <script type="text/javascript">
  window.onload=function(){
    var ofath=document.getElementById("fath");
	ofath.style.backgroundColor="red";
}
  </script>

  <body>
    <div id="fath" class="fath" style="background-color:#ccc;width:60px;height:60px;"></div>
  </body>
  </html>
