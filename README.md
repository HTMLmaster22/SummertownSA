<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohamed Khaled ID Card</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(to bottom, #1a0000, #660000);
      font-family: Arial, sans-serif;
    }

    .card {
      width: 350px;
      height: 500px;
      background: url('HRmohamed.jpg') center/cover no-repeat;
      position: relative;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
      overflow: hidden;
      border-radius: 0; /* <-- Removed rounded corners */
    }

    .overlay {
      position: absolute;
      bottom: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(to top, rgba(102, 0, 0, 0.7), rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0));
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      padding: 20px;
      color: white;
    }

    .overlay h1 {
      margin: 0;
      font-size: 20px;
      font-weight: bold;
      line-height: 1.2;
    }

    .overlay p {
      margin: 5px 0;
      font-size: 13px;
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="overlay">
      <h1>MOHAMMED<br>KHALED</h1>
      <p>HR</p>
      <div class="info">
        <p style="font-style: italic;">+966 59 697 6671</p>
        <p style="font-style: italic;">mohammed.k@summertown.sa</p>
      </div>
    </div>
  </div>
</body>
</html>
