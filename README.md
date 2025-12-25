<!DOCTYPE html>
<html lang="mr">
<head>
  <meta charset="UTF-8">
  <title>MSBTE Result Redirect</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f6f8;
      text-align: center;
      padding-top: 60px;
    }
    .box {
      background: #fff;
      padding: 30px;
      margin: auto;
      width: 90%;
      max-width: 400px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    button {
      padding: 12px 20px;
      font-size: 16px;
      background: #007bff;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background: #0056b3;
    }
    .note {
      font-size: 13px;
      color: #555;
      margin-top: 15px;
    }
  </style>
</head>
<body>

  <div class="box">
    <h2>MSBTE Result</h2>
    <p>खालील बटनवर क्लिक केल्यावर<br>
       Official MSBTE Result Website उघडेल</p>

    <button onclick="goResult()">Check Result</button>

    <p class="note">
      ⚠️ This is NOT an official website.<br>
      It only redirects to the official MSBTE result portal.
    </p>
  </div>

  <script>
    function goResult() {
      window.open("https://result.msbte.ac.in/", "_blank");
    }
  </script>

</body>
</html>
