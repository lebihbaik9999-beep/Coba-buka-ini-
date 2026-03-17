
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Evita ❤️</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg, #ff9a9e, #fad0c4);
    text-align: center;
    color: #fff;
}

.container {
    padding: 30px;
}

h1 {
    font-size: 2.5em;
    animation: fadeIn 2s ease;
}

p {
    font-size: 1.2em;
    margin: 20px;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 10px;
    margin-top: 20px;
}

.gallery img {
    width: 100%;
    border-radius: 15px;
    transition: 0.3s;
}

.gallery img:hover {
    transform: scale(1.05);
}

button {
    padding: 12px 20px;
    border: none;
    border-radius: 20px;
    background: #ff4d6d;
    color: white;
    font-size: 1em;
    cursor: pointer;
}

button:hover {
    background: #ff1e4d;
}

.hidden {
    display: none;
    margin-top: 20px;
    font-size: 1.3em;
}

@keyframes fadeIn {
    from {opacity: 0;}
    to {opacity: 1;}
}
</style>

</head>
<body>

<div class="container">

<h1>🎉 Happy Birthday 🎉</h1>
<h2>EVITA GRAHA WIDIASTUTI ❤️</h2>

<p>
Hari ini bukan hari biasa... karena dunia lagi ngerayain seseorang yang super cantik, lucu, dan bikin hati nyaman 😆❤️  
</p>

<div class="gallery">
    <img src="AED9F030-958C-4DC3-83BC-D6611975A8AF.jpeg">
    <img src="ECD52E0D-6AFF-4F9C-9A9A-7D9A2A897EC4.jpeg">
    <img src="0750035B-BFD6-48EE-83A5-24086E8C9D37.jpeg">
    <img src="265DB1A7-4D5F-4791-9A2C-A11214263684.jpeg">
</div>

<p>
Semoga di umur yang baru ini:  
✨ Makin bahagia  
✨ Makin cantik (padahal udah banget 😌)  
✨ Rezekinya lancar  
✨ Dan jangan lupa… makin sayang aku 😜
</p>

<button onclick="showMessage()">Klik Aku 🎁</button>

<div id="secret" class="hidden">
    💖 Aku cuma mau bilang...  
    <br><br>
    Dari semua hal indah di dunia, kamu tetap yang paling bikin aku senyum 😊  
    <br><br>
    Happy Birthday yaa Evita 💕  
</div>

</div>

<script>
function showMessage() {
    document.getElementById("secret").style.display = "block";
}
</script>

</body>
</html>ni
