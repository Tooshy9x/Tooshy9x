# Hi, I'm TOOSHY


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Pentest Training Lab</title>
  <style>
    body {
      font-family: monospace;
      background-color: #101010;
      color: #00ffcc;
      padding: 20px;
    }
    h1 {
      color: #ff00cc;
    }
    a {
      color: #ffcc00;
    }
    .box {
      border: 1px solid #444;
      padding: 10px;
      margin-top: 20px;
      background-color: #1a1a1a;
    }
  </style>
</head>
<body>
  <h1>🔐 Welcome to Pentest Lab</h1>
  <p>This page is designed for penetration testing practice only.</p>

  <div class="box">
    <h2>🧪 Test SQL Injection</h2>
    <form action="vulnerable.php" method="GET">
      <label>Username:</label>
      <input type="text" name="user" />
      <button type="submit">Login</button>
    </form>
  </div>

  <div class="box">
    <h2>💥 Try XSS Attack</h2>
    <form action="xss.php" method="POST">
      <label>Comment:</label>
      <input type="text" name="comment" />
      <button type="submit">Submit</button>
    </form>
  </div>
</body>
</html>
