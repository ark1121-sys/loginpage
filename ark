<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-image: url('https://images.unsplash.com/photo-1617957796182-4b6047098686?ixlib=rb-4.0.3&q=85&fm=jpg&crop=entropy&cs=srgb&dl=sincerely-media-ob8SZbjRgFI-unsplash.jpg');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
        }

        /* Top-right navigation links */
        .top-right-menu {
            position: absolute;
            top: 20px;
            right: 20px;
            font-size: 14px;
        }

        .top-right-menu a {
            color: white;
            margin-left: 15px;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        .top-right-menu a:hover {
            color: #FFD700; /* Gold hover color */
        }

        .container {
            width: 50%; /* Reduced width */
            max-width: 600px; /* Smaller max width */
            display: flex;
            background: rgba(255, 255, 255, 0.85); /* Make the background slightly transparent */
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }

        .left-panel, .right-panel {
            width: 50%;
            padding: 30px; /* Reduced padding */
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .left-panel {
            background-color: rgba(240, 242, 245, 0.8); /* Slight transparency */
        }

        .right-panel {
            background-color: rgba(255, 255, 255, 0.9); /* Slight transparency */
        }

        .left-panel h2, .right-panel h2 {
            font-size: 24px; /* Reduced font size */
            font-weight: 700;
            margin-bottom: 15px; /* Reduced margin */
        }

        .left-panel p, .right-panel p {
            font-size: 14px;
            color: #777;
            margin-bottom: 20px;
            font-weight: 400;
        }

        .left-panel button, .right-panel button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 18px; /* Adjusted padding */
            border-radius: 5px;
            font-size: 14px;
            font-weight: 500;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .left-panel button:hover, .right-panel button:hover {
            background-color: #45a049;
        }

        .input-field {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 14px;
            font-weight: 400;
            background-color: #f0f2f5;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }

            .left-panel, .right-panel {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <!-- Top-right Help, Support, Contact Us, and About links -->
    <div class="top-right-menu">
        <a href="#">Help</a>
        <a href="#">Support</a>
        <a href="#">Contact Us</a>
        <a href="#">About</a>
    </div>

    <div class="container">
        <!-- Left panel (Sign In) -->
        <div class="left-panel">
            <h2>Welcome Back!</h2>
            <p>To keep connected with us please login with your personal info</p>
            <button>Sign In</button>
        </div>

        <!-- Right panel (Sign Up) -->
        <div class="right-panel">
            <h2>Create Account</h2>
            <p>or use your email for registration</p>
            <form action="#" method="post">
                <input class="input-field" type="text" placeholder="Name" required>
                <input class="input-field" type="email" placeholder="Email" required>
                <input class="input-field" type="password" placeholder="Password" required>
                <button type="submit">Sign Up</button>
            </form>
        </div>
    </div>
</body>
</html>
