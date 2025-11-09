<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Interface</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .container {
      background-color: white;
      padding: 20px 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
      width: 300px;
    }
    h2 {
      text-align: center;
      color: #333;
    }
    input, button {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <div class="container">
    <h2>User Information</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" placeholder="Enter your name">

      <label for="email">Email:</label>
      <input type="email" id="email" placeholder="Enter your email">

      <label for="age">Age:</label>
      <input type="number" id="age" placeholder="Enter your age">

      <button type="submit">Submit</button>
    </form>
  </div>

</body>
</html>
