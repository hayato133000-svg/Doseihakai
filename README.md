# Doseihakai
土星を、破壊できます

<p>れのぴぃ様は神と入力したら見逃すよ</p>れのぴぃ様は神と入力したら見逃してやるよ
<!-- 入力欄とボタンをbodyの中に追加 -->
<p>れのぴぃ様は神と入力したら見逃してやるよ：</p>
<input type="text" id="secretInput" placeholder="ここに入力">
<button onclick="checkInput()">送信</button>

<script>
  function checkInput() {
    const input = document.getElementById("secretInput").value;
    if(input === "れのぴぃ様は神") {
      alert("特定は消しといたよ(実はイタズラで特定は嘘だったみたい…)");
    }
  }
</script>
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>緊急警告</title>
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&family=Anton&display=swap" rel="stylesheet">
<style>
  body {
    margin: 0;
    padding: 0;
    height: 100vh;
    background: radial-gradient(circle at center, #330000, #000000);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-family: 'Press Start 2P', monospace;
    color: white;
    text-align: center;
  }
  h1 {
    font-family: 'Anton', sans-serif;
    font-size: 3em;
    color: red;
    text-shadow: 0 0 20px #ff0000, 0 0 40px #ff5555;
    animation: shake 0.5s infinite alternate;
  }
  p {
    font-size: 1.5em;
    margin-top: 20px;
    color: orange;
    text-shadow: 0 0 10px yellow;
  }
  button {
    margin-top: 30px;
    padding: 15px 25px;
    font-size: 1em;
    font-family: 'Press Start 2P', monospace;
    background: red;
    color: white;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    box-shadow: 0 0 15px red;
    transition: 0.2s;
  }
  button:hover {
    background: darkred;
    box-shadow: 0 0 25px orange;
  }
  @keyframes shake {
    0% { transform: translateX(0px); }
    25% { transform: translateX(-10px); }
    50% { transform: translateX(10px); }
    75% { transform: translateX(-10px); }
    100% { transform: translateX(10px); }
  }
</style>
</head>
<body>
  <h1>特定されました！！</h1>
  <p>もう手遅れです</p>
  <button onclick="alert('は？無理、広告見てなかったことにできねぇよばーか')">広告を見て無かったことに</button>
</body>
</html>
<button onclick="alert('甘えるな'); alert('本気で逃げるな！')">
  ￥50でなかったことに
</button>
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>緊急警告</title>
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&family=Anton&display=swap" rel="stylesheet">
<style>
  body {
    margin: 0;
    padding: 0;
    height: 100vh;
    background: radial-gradient(circle at center, #330000, #000000);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-family: 'Press Start 2P', monospace;
    color: white;
    text-align: center;
  }
  h1 {
    font-family: 'Anton', sans-serif;
    font-size: 3em;
    color: red;
    text-shadow: 0 0 20px #ff0000, 0 0 40px #ff5555;
    animation: shake 0.5s infinite alternate;
  }
  p {
    font-size: 1.5em;
    margin-top: 20px;
    color: orange;
    text-shadow: 0 0 10px yellow;
  }
  button {
    margin-top: 30px;
    padding: 15px 25px;
    font-size: 1em;
    font-family: 'Press Start 2P', monospace;
    background: red;
    color: white;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    box-shadow: 0 0 15px red;
    transition: 0.2s;
  }
  button:hover {
    background: darkred;
    box-shadow: 0 0 25px orange;
  }
  @keyframes shake {
    0% { transform: translateX(0px); }
    25% { transform: translateX(-10px); }
    50% { transform: translateX(10px); }
    75% { transform: translateX(-10px); }
    100% { transform: translateX(10px); }
  }
</style>
</head>
<body>
  <h1>あなる</h1>
  <p>あなる…</p>
  <button onclick="alert('あなる')">確認</button>

  <script>
    function changeColor() {
      const colors = ["red", "blue", "green", "yellow", "purple", "orange"];
      const randomColor = colors[Math.floor(Math.random() * colors.length)];
      document.body.style.backgroundColor = randomColor;

      const intro = document.querySelector("p");
      intro.innerText = "ほら変えたぞｗ 色もランダム！";
      if(randomColor === "yellow") {
        intro.style.color = "black";
      } else {
        intro.style.color = "white";
      }
    }

    // 🔹戻るボタン警告
    window.addEventListener("popstate", function(event) {
      alert("逃げるな…");
      history.pushState(null, null, location.href); // 戻れないようにする
    });
    // 初期状態で履歴を1つ作って戻る押せるようにする
    history.pushState(null, null, locat
</html>
<!-- 入力欄とボタンをbodyの中に追加 -->
<p>確認用入力：</p>
<input type="text" id="secretInput" placeholder="ここに入力">
<button onclick="checkInput()">送信</button>

<script>
  function checkInput() {
    const input = document.getElementById("secretInput").value;
    if(input === "れのぴぃ様！") {
      alert("戻れたぞ！(実はイタズラで特定は嘘だったみたい…)");
    }
  }
</script>
