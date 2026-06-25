<!DOCTYPE html>
<html lang="fa">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>I Love You ❤️</title>

<style>
body{
    margin:0;
    display:flex;
    justify-content:center;
    align-items:center;
    min-height:100vh;
    background:linear-gradient(135deg,#ffd6e8,#fff5f9);
    font-family:tahoma,sans-serif;
    overflow:hidden;
}

.box{
    text-align:center;
    background:white;
    padding:30px;
    border-radius:20px;
    box-shadow:0 0 20px rgba(0,0,0,.15);
    z-index:2;
}

h1{
    color:#e91e63;
    font-size:55px;
}

iframe{
    width:320px;
    height:180px;
    border:none;
    border-radius:15px;
    margin-top:20px;
}

.heart{
    position:absolute;
    color:#ff4d88;
    animation:float 6s linear infinite;
}

@keyframes float{
    from{
        transform:translateY(100vh);
        opacity:1;
    }
    to{
        transform:translateY(-120vh);
        opacity:0;
    }
}
</style>
</head>

<body>

<div class="box">

<h1>❤️ I Love You ❤️</h1>

<p>🎵 نفس - داریوش و گوگوش</p>

<iframe
src="https://www.youtube.com/embed/Wsjyqqo8ClY"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
allowfullscreen>
</iframe>

</div>

<script>
for(let i=0;i<40;i++){
 let h=document.createElement("div");
 h.className="heart";
 h.innerHTML="❤️";
 h.style.left=Math.random()*100+"vw";
 h.style.fontSize=(18+Math.random()*25)+"px";
 h.style.animationDuration=(3+Math.random()*5)+"s";
 document.body.appendChild(h);
}
</script>

</body>
</html>
