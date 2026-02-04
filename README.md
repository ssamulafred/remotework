Motionless and static pages

whenenver its good i will do
Workers have a high need to be supported by the company Promotions tend to be slower than usual Workers need to become generalists The Ouchi theory cannot apply to American business
Workers have a high need to be supported by the company Promotions tend to be slower than usual Workers need to become generalists The Ouchi theory cannot apply to American business
The elimination of unnecessary tasks Expectations of greater levels of pay Increased productivity Reduced turnover
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Login Page</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(to right, #0f172a, #1e293b);
    }

    .login-container {
      width: 380px;
      padding: 40px;
      background: rgba(255, 255, 255, 0.05);
      border-radius: 18px;
      backdrop-filter: blur(15px);
      box-shadow: 0 0 30px rgba(56, 189, 248, 0.25);
      text-align: center;
    }

    .login-container h2 {
      font-size: 30px;
      color: #38bdf8;
      margin-bottom: 10px;
    }

    .login-container p {
      color: rgba(255, 255, 255, 0.7);
      margin-bottom: 30px;
      font-size: 14px;
    }

    .input-box {
      margin-bottom: 20px;
      text-align: left;
    }

    .input-box label {
      display: block;
      margin-bottom: 6px;
      font-size: 14px;
      color: white;
      opacity: 0.8;
    }

    .input-box input {
      width: 100%;
      padding: 12px;
      border: none;
      outline: none;
      border-radius: 10px;
      background: rgba(255, 255, 255, 0.1);
      color: white;
      font-size: 15px;
    }

    .input-box input:focus {
      border: 1px solid #38bdf8;
    }

    .login-btn {
      width: 100%;
      padding: 14px;
      border: none;
      border-radius: 10px;
      background: #38bdf8;
      color: black;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
      transition: 0.3s;
      margin-top: 10px;
    }

    .login-btn:hover {
      background: white;
      transform: scale(1.03);
    }

    .extra-links {
      margin-top: 20px;
      font-size: 14px;
      color: rgba(255, 255, 255, 0.7);
    }

    .extra-links a {
      color: #38bdf8;
      text-decoration: none;
      font-weight: 500;
    }

    .extra-links a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>

  <div class="login-container">
    <h2>Welcome Back</h2>
    <p>Login to continue to your account</p>

    <form>
      <!-- Email -->
      <div class="input-box">
        <label>Email Address</label>
        <input type="email" placeholder="Enter your email" required />
      </div>

      <!-- Password -->
      <div class="input-box">
        <label>Password</label>
        <input type="password" placeholder="Enter your password" required />
      </div>

      <!-- Button -->
      <button class="login-btn" type="submit">Login</button>

      <!-- Links -->
      <div class="extra-links">
        <p>
          Don’t have an account?
          <a href="#">Sign Up</a>
        </p>
        <p>
          <a href="#">Forgot Password?</a>
        </p>
      </div>
    </form>
  </div>

</body>
</html>

