# project 
project name- Daily habits

Discription -Daily habits are the routines or practices that a person regularly engages in, often without much thought, as part of their daily life. These habits can contribute to physical, mental, or emotional well-being.

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Habits Tracker</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .container {
            padding: 20px;
        }
        .habit-list {
            list-style-type: none;
            padding: 0;
        }
        .habit-item {
            background-color: white;
            padding: 15px;
            margin: 10px 0;
            border-radius: 5px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            display: flex;
            align-items: center;
        }
        .habit-item input[type="checkbox"] {
            margin-right: 15px;
        }
        .habit-item span {
            font-size: 18px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Daily Habits Tracker</h1>
        <p>Track your habits every day for a healthier lifestyle!</p>
    </header>

    <div class="container">
        <h2>My Daily Habits</h2>
        <ul class="habit-list">
            <li class="habit-item">
                <input type="checkbox" id="habit1">
                <span>Drink water in the morning</span>
            </li>
            <li class="habit-item">
                <input type="checkbox" id="habit2">
                <span>Morning exercise</span>
            </li>
            <li class="habit-item">
                <input type="checkbox" id="habit3">
                <span>Eat a healthy breakfast</span>
            </li>
            <li class="habit-item">
                <input type="checkbox" id="habit4">
                <span>Read for 30 minutes</span>
            </li>
            <li class="habit-item">
                <input type="checkbox" id="habit5">
                <span>Spend time with family</span>
            </li>
            <li class="habit-item">
                <input type="checkbox" id="habit6">
                <span>Reflect on the day (journaling)</span>
            </li>
        </ul>
    </div>

    <footer>
        <p>&copy; 2025 Daily Habits Tracker. All Rights Reserved.</p>
    </footer>
</body>
</html>
