<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Valentine 💖</title>
<style>
  body {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #ffe6ea;
    font-family: Arial, sans-serif;
  }
  .box {
    text-align: center;
  }
  button {
    padding: 12px 25px;
    font-size: 18px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    margin: 10px;
  }
  #yes {
    background: #ff4d6d;
    color: white;
  }
  #no {
    background: #999;
    color: white;
    position: absolute;
  }
</style>
</head>

<body>
  <div class="box">
    <h1>Will you be my Valentine? 💘</h1>
    <button id="yes" onclick="alert('Yayyyy 😍❤️')">Yes</button>
    <button id="no">No</button>
  </div>

<script>
  const noBtn = document.getElementById("no");

  noBtn.addEventListener("mouseover", () => {
    const x = Math.random() * (window.innerWidth - 100);
    const y = Math.random() * (window.innerHeight - 50);
    noBtn.style.left = x + "px";
    noBtn.style.top = y + "px";
  });
</script>
</body>
</html>
