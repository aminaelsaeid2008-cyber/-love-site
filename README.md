<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>🤍 أحمد & أمينة 🤍</title>

<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Cairo',sans-serif;
}

body{
background:linear-gradient(#000,#1b1b1b);
color:white;
text-align:center;
overflow-x:hidden;
}

#login{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
}

input{
padding:12px;
width:250px;
border-radius:15px;
border:none;
text-align:center;
font-size:18px;
margin:15px;
}

button{
padding:12px 30px;
border:none;
border-radius:30px;
background:#ff4d88;
color:white;
font-size:18px;
cursor:pointer;
}

button:hover{
background:#ff1f68;
}

#website{
display:none;
padding:30px;
}

h1{
font-size:40px;
margin:20px;
color:#ff7aa8;
}

.date{
font-size:25px;
margin-bottom:30px;
}

img{
width:300px;
max-width:90%;
border-radius:20px;
box-shadow:0 0 20px pink;
margin:20px;
}

h2{
font-size:30px;
margin:20px;
color:#ffb6c1;
}

.message{
font-size:23px;
line-height:2;
padding:30px;
}
</style>
</head>

<body>

<div id="login">

<h1>🤍 مرحبًا يا أحمد 🤍</h1>

<p>أدخل كلمة السر لبدء رحلتنا</p>

<input type="password" id="pass" placeholder="كلمة السر">

<button onclick="check()">❤️ دخول</button>

</div>

<div id="website">

<h1>لن أتوقف يومًا عن حبك 🤍</h1>

<div class="date">
25 / 12 / 2025
</div>

<img src="photo.jpg">

<h2>بينا وعد... ولازم نوصله 🤍</h2>

<iframe width="320" height="180"
src="https://www.youtube.com/embed/rRzvYOvfCp0"
frameborder="0"
allowfullscreen>
</iframe>

<h2>سوا سوا❣️</h2>

<div class="message">

وجودك في حياتي يا أحمد هو أجمل حاجة حصلتلي. 🤍<br><br>

مهما مرت الأيام... هفضل أحبك وأختارك كل يوم. ❤️<br><br>

بحبك يا أحمد... وبينا وعد ولازم نوصله. ♾️🤍

</div>

</div>

<script>

function check(){

let password=document.getElementById("pass").value;

if(password=="Love"){

document.getElementById("login").style.display="none";
document.getElementById("website").style.display="block";

}else{

alert("🤍 كلمة السر غير صحيحة");

}

}

</script>

</body>
</html>
