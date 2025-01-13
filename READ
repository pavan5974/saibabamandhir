<!DOCTYPE html>
<html lang="en">
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <style>
    /* Basic Styles */
    body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f0f8ff; /* Light blue background */
      font-family: Arial, sans-serif;
    }

    .login-box {
      width: 90%;
      max-width: 400px;
      padding: 20px;
      background: white;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      border-radius: 10px;
      text-align: center;
    }

    .login-box h1 {
      margin-bottom: 20px;
      font-size: 1.8em;
      color: #333;
    }

    .login-box label {
      display: block;
      margin-bottom: 5px;
      font-size: 1.1em;
      color: #555;
      text-align: left;
    }

    .login-box input {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1em;
    }

    .login-box button {
      width: 100%;
      padding: 10px;
      font-size: 1.1em;
      color: white;
      background-color: #007bff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .login-box button:hover {
      background-color: #0056b3;
    }

    .error {
      color: red;
      font-size: 0.9em;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <!-- Login Box -->
  <div class="login-box">
    <h1>Login</h1>
    <div id="error" class="error"></div>
    <form id="loginForm">
      <label for="username">Username:</label>
      <input type="text" id="username" name="username" required>
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>
      <button type="submit">Login</button>
    </form>
  </div>

  <script>
    // Private username and password
    const PRIVATE_USERNAME = "saibabamandhir";
    const PRIVATE_PASSWORD = "11223344";

    const loginForm = document.getElementById('loginForm');
    const errorDiv = document.getElementById('error');

    loginForm.addEventListener('submit', function (event) {
      event.preventDefault();

      const username = document.getElementById('username').value.trim();
      const password = document.getElementById('password').value.trim();

      if (username === PRIVATE_USERNAME && password === PRIVATE_PASSWORD) {
        // Successful login
        alert("Login successful! Welcome to the Saibaba Mandhir.");
        // Redirect to another page or perform further actions
        window.location.href = "file:///C:/Users/pavansai%20daggu/Downloads/index11.html";
      } else {
        // Invalid credentials
        errorDiv.textContent = "Invalid username or password. Please try again.";
      }
    });
  </script>
</body>
</html>
