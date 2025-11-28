<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>التكاثر الزهري – Dr. Mai Elhalfawy</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
<style>
html, body{
    margin:0;
    padding:0;
    height:100%;
    width:100%;
    font-family: 'Cairo', sans-serif;
    overflow-x:hidden;
}

body{
    display:flex;
    flex-direction:column;
    justify-content:flex-start;
    align-items:center;
    background: linear-gradient(-45deg, #1f2c3a, #3a506b, #5bc0be, #6fffe9);
    background-size: 400% 400%;
    animation: gradientBG 15s ease infinite;
    color:#fff;
    text-align:center;
    padding-top:80px;
    box-sizing:border-box;
}

@keyframes gradientBG{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

h1{
    font-size:3em;
    margin-bottom:10px;
    text-shadow: 3px 3px 12px #000;
}

#welcome{
    font-size:1.6em;
    margin-bottom:50px;
    text-shadow: 1px 1px 6px #000;
}

/* رابط فيسبوك */
#facebookLink{
    color:#3b5998;
    font-size:1.3em;
    text-decoration:none;
    margin-bottom:40px;
    display:block;
    font-weight:700;
}
#facebookLink:hover{
    text-decoration:underline;
}

/* الأزرار */
button{
    width:300px;
    padding:18px 0;
    margin:12px 0;
    font-size:1.35em;
    font-weight:700;
    color:#fff;
    border:none;
    border-radius:25px;
    cursor:pointer;
    background: linear-gradient(135deg,#ff6b9e,#ffcc00,#6bffb8,#66ccff);
    background-size:400% 400%;
    animation: btnGradient 6s ease infinite;
    box-shadow:0 0 25px rgba(255,255,255,0.5);
    transition: all 0.35s ease;
    text-transform: capitalize;
}
button:hover{
    transform: scale(1.12) rotate(-2deg);
    box-shadow:0 0 50px rgba(255,255,255,0.9);
}
@keyframes btnGradient{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

#author{
    position:absolute;
    bottom:5px;
    font-size:0.55em;
    color:#ddd;
}

a, h1{
    animation: floatText 3s ease-in-out infinite;
}
@keyframes floatText{
    0%,100%{transform:translateY(0);}
    50%{transform:translateY(-8px);}
}

/* لمسة إضافية للأزرار: ضوء متحرك */
button::after {
    content:'';
    position:absolute;
    width:100%;
    height:100%;
    top:0;
    left:0;
    background:rgba(255,255,255,0.1);
    border-radius:25px;
    opacity:0;
    transition:all 0.3s ease;
}
button:hover::after{
    opacity:1;
}
</style>
</head>
<body>

<h1>Dr. Mai Elhalfawy</h1>
<div id="welcome">مرحبًا بك في شرح التكاثر الزهري</div>

<a id="facebookLink" href="https://www.facebook.com/share/1Jx5CUApUd/" target="_blank">زيارة صفحتها على فيسبوك</a>

<button onclick="location.href='pollen.html'">تكوين حبة اللقاح</button>
<button onclick="location.href='ovule.html'">تكوين المشيج المؤنث</button>
<button onclick="location.href='fertilization.html'">مرحلة الأخصاب</button>
<button onclick="location.href='quiz.html'">اختبار قصير</button>

<div id="author">Created by Abdullah</div>

<script src="script.js"></script>
</body>
</html>
