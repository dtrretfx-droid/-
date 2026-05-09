<!DOCTYPE html>
<html lang="kk">
<head>
<meta charset="UTF-8">
<title>Кешірім</title>

<style>
body{
    background:pink;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    font-family:Arial;
}

.box{
    text-align:center;
    position:relative;
}

button{
    padding:10px 25px;
    border:none;
    border-radius:8px;
    font-size:18px;
    cursor:pointer;
    margin:10px;
}

#yes{
    background:green;
    color:white;
}

#no{
    background:red;
    color:white;
    position:absolute;
    top:60px;
    left:120px;
}
</style>
</head>

<body>

<div class="box">
    <h1>Жүрекке мені кешірші</h1>
    <p>Кешіресің ба?</p>

    <button id="yes" onclick="yes()">Ия</button>
    <button id="no">Жоқ</button>
</div>

<script>
function yes(){
    alert("Я рахмет жүрегім ❤️");
}

const noBtn = document.getElementById("no");

noBtn.addEventListener("mouseover", () => {
    noBtn.style.top = Math.random()*300 + "px";
    noBtn.style.left = Math.random()*300 + "px";
});
</script>

</body>
</html>
