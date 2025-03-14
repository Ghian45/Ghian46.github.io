<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook - Log In or Sign Up</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
        }
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100%;
            max-width: 980px;
        }
        .left-section {
            flex: 1;
            padding-right: 50px;
        }
        .left-section h1 {
            color: #1877f2;
            font-size: 48px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        .left-section p {
            font-size: 20px;
        }
        .right-section {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            width: 360px;
            text-align: center;
        }
        input {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }
        .login-btn {
            background: #1877f2;
            color: white;
            border: none;
            padding: 10px;
            width: 100%;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }
        .login-btn:hover {
            background: #165baf;
        }
        .forgot-link {
            display: block;
            margin-top: 10px;
            color: #1877f2;
            text-decoration: none;
            font-size: 14px;
        }
        .signup-btn {
            background: #42b72a;
            color: white;
            padding: 10px;
            width: 100%;
            border: none;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
        .signup-btn:hover {
            background: #369920;
        }
        .bottom-text {
            margin-top: 15px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="left-section">
            <h1>fakebook</h1>
            <p>Fakebook helps you connect and share with the people in your life.</p>
        </div>
        <div class="right-section">
            <input type="text" placeholder="Email or Phone Number">
            <input type="password" placeholder="Password">
            <button class="login-btn">Log In</button>
            <a href="#" class="forgot-link">did u not forgotten the password?</a>
            <hr>
            <button class="signup-btn">Create New Account</button>
            <p class="bottom-text">Create a Page for a celebrity, brand, or business.</p>
        </div>
    </div>
</body>
</html>
