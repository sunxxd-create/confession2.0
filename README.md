<!DOCTYPE html>
<html>
<head>
    <title>Funny Confession</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #ff9a9e, #fad0c4);
            text-align: center;
            padding: 50px;
        }
        .box {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0px 4px 10px rgba(0,0,0,0.2);
            display: inline-block;
            animation: fadeIn 2s ease-in-out;
        }
        h1 {
            color: #e63946;
            animation: bounce 2s infinite;
        }
        p {
            font-size: 18px;
            animation: fadeInUp 2s ease-in-out;
        }
        .btn {
            display: block;
            margin: 15px auto;
            padding: 10px 20px;
            background: #e63946;
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            animation: glow 2s infinite alternate;
        }
        .btn:hover {
            background: #d62828;
            transform: scale(1.1);
        }

        /* Animations */
        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes glow {
            from { box-shadow: 0 0 5px #e63946; }
            to { box-shadow: 0 0 20px #ff6f61; }
        }
    </style>
</head>
<body>
    <div class="box">
        <h1>💻 Funny Confession 💖</h1>
        <p>Dear Crush,</p>
        <p>You’re the missing semicolon in my life.<br>
        Without you, my code won’t compile!</p>
        <p>So… will you accept my love?</p>

        <button class="btn" onclick="alert('Yay! Our love compiled successfully with 0 errors! 🎉')">Yes, let’s compile together!</button>
        <button class="btn" onclick="alert('Ouch… That’s a runtime error in my heart 💔')">No, go debug yourself.</button>
        <button class="btn" onclick="alert('Okay… I’ll stay in an infinite loop waiting ⏳')">Maybe… let me think.</button>
    </div>
</body>
</html>

