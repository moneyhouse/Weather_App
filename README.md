# Weather_App
<!--index.html-->
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Weather App</title>
    <link rel="stylesheet" href="style.css">
    

</head>
<body>
  <div class="weather-container">
    <h1>Weather Checker</h1>
     <input type="text" id="cityInput" placeholder="Enter city name" aria-label="City name">
    
    
    <button id="getWeatherBtn">Get Weather</button>
    
    <p id="weatherOutput"></p>
  </div>
    <!-- Link to the external JavaScript file -->
    <script src="web.js"></script>
</body>
</html>



/*style.css*/

/* Reset default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

/* Sleek full-screen gradient background */
body {
    height: 100vh;
    background: linear-gradient(145deg, #1f1c2c, #928dab); /* deep purple to soft lavender */
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
    color: #ffffff;
}

/* Glowing glassmorphism container */
.weather-container {
    background: rgba(255, 255, 255, 0.05);
    border-radius: 20px;
    padding: 40px;
    width: 100%;
    max-width: 420px;
    text-align: center;
    box-shadow:
        0 0 30px rgba(255, 255, 255, 0.1),
        0 0 60px rgba(255, 255, 255, 0.05);
    backdrop-filter: blur(20px);
    -webkit-backdrop-filter: blur(20px);
    border: 1px solid rgba(255, 255, 255, 0.1);
    animation: pulseGlow 3s infinite alternate ease-in-out;
}

/* Subtle glow animation */
@keyframes pulseGlow {
    from {
        box-shadow: 0 0 30px rgba(255, 255, 255, 0.1);
    }
    to {
        box-shadow: 0 0 60px rgba(255, 255, 255, 0.25);
    }
}

/* Bold heading */
.weather-container h1 {
    font-size: 2.2rem;
    font-weight: 700;
    margin-bottom: 20px;
}

/* Input styling */
input[type="text"] {
    width: 100%;
    padding: 12px;
    border: none;
    border-radius: 10px;
    margin-bottom: 20px;
    font-size: 16px;
    outline: none;
    background: rgba(255, 255, 255, 0.2);
    color: white;
}

/* Glowing button */
button {
    padding: 12px 24px;
    background: #6a5acd;
    color: #ffffff;
    font-weight: bold;
    border: none;
    border-radius: 12px;
    font-size: 16px;
    cursor: pointer;
    transition: all 0.3s ease;
    box-shadow: 0 0 15px #6a5acd;
}

button:hover {
    background: #7b68ee;
    transform: translateY(-2px);
    box-shadow:0 0 20px #7b6;
}


<!--web.js-->

 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Weather App</title>
    <link rel="stylesheet" href="style.css">
    

</head>
<body>
  <div class="weather-container">
    <h1>Weather Checker</h1>
     <input type="text" id="cityInput" placeholder="Enter city name" aria-label="City name">
    
    
    <button id="getWeatherBtn">Get Weather</button>
    
    <p id="weatherOutput"></p>
  </div>
    <!-- Link to the external JavaScript file -->
    <script src="web.js"></script>
</body>
</html>
