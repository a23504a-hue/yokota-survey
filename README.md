
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>卒業論文アンケート</title>
<style>
body {
  font-family: sans-serif;
  text-align: center;
  background: #f5f6fa;
  padding: 40px 20px;
  color: #333;
}
.container {
  background: white;
  max-width: 400px;
  margin: 30px auto;
  padding: 30px 20px;
  border-radius: 15px;
}
a {
  display: block;
  background: #4285f4;
  color: white;
  padding: 16px;
  border-radius: 10px;
  text-decoration: none;
  margin-top: 20px;
  font-weight: bold;
}
</style>
</head>
<body>
<div class="container">
<h2>横田ゼミ<br>卒業論文アンケート</h2>

<p>
ご協力ありがとうございます。<br>
画像を正しく表示するため、<br>
Safariでの回答をおすすめします。
</p>

<a id="answer" href="#">
アンケートを開始する
</a>

<p style="font-size:12px;color:#888;">
画像が表示されない場合は、Safariで開いてください。
</p>
</div>

<script>
const forms = [
"https://forms.gle/UiYsQhNR682c7zXE6",
"https://forms.gle/MvY2jDXbj8oTty1S7"
];

const form = forms[Math.floor(Math.random() * 2)];

document.getElementById("answer").href = form;
</script>
</body>
</html>
