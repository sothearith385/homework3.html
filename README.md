<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Login Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .form-container {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      width: 300px;
      text-align: center;
    }

    .form-container h2 {
      margin-bottom: 20px;
    }

    .tabs {
      display: flex;
      margin-bottom: 20px;
    }

    .tabs button {
      flex: 1;
      padding: 10px;
      border: none;
      background: linear-gradient(to right, #8e2de2, #f452c1);
      color: white;
      cursor: pointer;
    }

    .tabs button.signup {
      background: #f1f1f1;
      color: #333;
    }

    input[type="email"], input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .forgot {
      color: #e91e63;
      font-size: 0.85em;
      text-align: left;
      margin-bottom: 15px;
    }

    .login-btn {
      width: 100%;
      padding: 10px;
      background: linear-gradient(to right, #8e2de2, #f452c1);
      border: none;
      color: white;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
    }

    .signup-link {
      margin-top: 15px;
      font-size: 0.9em;
    }

    .signup-link a {
      color: #e91e63;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <h2>Login Form</h2>
    <div class="tabs">
      <button>Login</button>
      <button class="signup">Signup</button>
    </div>
    <form>
      <input type="email" placeholder="Email Address" required>
      <input type="password" placeholder="Password" required>
      <div class="forgot">Forgot password?</div>
      <button type="submit" class="login-btn">Login</button>
    </form>
    <div class="signup-link">
      Not a member? <a href="#">Signup now</a>
    </div>
  </div>
</body>
</html>
