<html>
<head>
<title></title>

<script type="text/javascript">
flag=1
function f1()
{
    alert("Yehey mandam kasakon hehe”)
}
function f()
{
    if(flag==1)
        {
            Bn.style.top=400
            Bn.style.left=300
            flag=2
        }
    else if(flag==2)
        {
            Bn.style.top=400
            Bn.style.left=50
            flag=3
        }
    else if(flag==3)
        {
            Bn.style.top=370
            Bn.style.left=166
            flag=1
        }
}
</script>

</head>
<body>
<h1>Pwede taka makuga? </h1>
<img src="https://www.google.com.ph/imgres?imgurl=https%3A%2F%2Fmedia.tenor.com%2Fimages%2Fadcc68b77b6c9704b999df0a53c82a65%2Ftenor.gif&imgrefurl=https%3A%2F%2Ftenor.com%2Fview%2F15467849&tbnid=p4hOKrsYUOQDXM&vet=1&w=220&h=259&hl=en-US&source=sh%2Fx%2Fim" height="200" />
<h1 style="#"></h1>
<div id="By" style="position:absolute; left:64px; top:370px; width:210px;
height:210px;">
<input type="button" value=" YES " onClick="f1()" />
</div>
<div ID="Bn" style="position:absolute; left:166px; top:370px; width:210px; height:210px;">
<input type="button" value=" NO " onMouseOver="f()" />
</div>

</body>
</html>
