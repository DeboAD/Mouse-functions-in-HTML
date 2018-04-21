# Mouse-functions-in-HTML
//This page displays an image that displays how many times the image has been clicked, double clicked, mouse has moved over it and mouse has moved out of it

<!DOCTYPE html>
<html>
</head>
<body>
<div onmousemove="myMoveFunction()"
  <p><img src="https://i.kinja-img.com/gawker-media/image/upload/s--one06NIU--/c_scale,fl_progressive,q_80,w_800/dlss3ysrqnd6sjjmxaji.jpg" width="192" height="81" />: <br> <span id="demo">Mouse over and leave me!</span></p>
</div>
<div onmouseout="myOutFunction()"
<p><img src="https://i.kinja-img.com/gawker-media/image/upload/s--one06NIU--/c_scale,fl_progressive,q_80,w_800/dlss3ysrqnd6sjjmxaji.jpg" width="192" height="81" />: <br> <span id="demo3">Mouse over and leave me!</span></p>
</div>

<div onclick="fuctionName()"
<p><img src="https://i.kinja-img.com/gawker-media/image/upload/s--one06NIU--/c_scale,fl_progressive,q_80,w_800/dlss3ysrqnd6sjjmxaji.jpg" width="192" height="81" />:<br> <span id="demo2"> Click me!</span></p>
</div>

<div ondblclick="myFunction()"
<p><img src="https://i.kinja-img.com/gawker-media/image/upload/s--one06NIU--/c_scale,fl_progressive,q_80,w_800/dlss3ysrqnd6sjjmxaji.jpg" width="192" height="81" />:<br> <span id="demo4">Double Click me!</span></p>
</div>

<script>
var x= 0
var y = 0;
var z = 0;
var w = 0;

function myMoveFunction() {
    document.getElementById("demo").innerHTML = z+=1;
}
function myOutFunction() {
    document.getElementById("demo3").innerHTML = y+=1;
}
function fuctionName() {
    document.getElementById("demo2").innerHTML = x+=1;
}
function myFunction() {
    document.getElementById("demo4").innerHTML = w+=1;
}

</script>

</body>
</html>
