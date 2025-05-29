<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Coming Soon Website Using HTML and CSS3</title>
  <style>
    * {
      padding: 0;
      margin: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    header {
      width: 100%;
      height: 100vh;
      position: relative;
    }

    header::before {
      content: "";
      background: url("img/water.jpg") no-repeat center center/cover;
      position: absolute;
      opacity: 0.3;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
    }

    .countdown-timer {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      height: 100%;
      padding: 2rem;
    }

    .countdown-timer h2 {
      font-size: 4rem;
      margin-bottom: 1rem;
    }

    .countdown-timer .content p {
      font-size: 1.1rem;
      max-width: 600px;
      margin-bottom: 2rem;
    }

    .timer-content {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 2rem 0;
      gap: 2rem;
    }

    .time {
      display: flex;
      flex-direction: column;
      justify-content: space-evenly;
      align-items: center;
      padding: 2rem;
      background-color: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
    }

    .numbers {
      font-size: 3.5rem;
      font-weight: 800;
      padding: 0.5rem;
    }

    .input-data {
      width: 100%;
      max-width: 500px;
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-top: 2rem;
    }

    .input-data h3 {
      font-size: 1.3rem;
      padding-bottom: 1rem;
    }

    .input-fields {
      display: flex;
      flex-direction: column;
      align-items: center;
      width: 100%;
    }

    .input-fields input {
      width: 80%;
      max-width: 400px;
      border: none;
      padding: 1rem 2rem;
      margin-bottom: 1.5rem;
      font-size: 1rem;
      border-radius: 5px;
    }

    .input-fields button {
      background: #21618c;
      color: #fff;
      border: none;
      padding: 1rem 2rem;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 5px;
      transition: background 0.3s ease;
    }

    .input-fields button:hover {
      background: #1b4f6b;
    }
  </style>
</head>
<body>
  <header>
    <div class="countdown-timer">
      <div class="content">
        <h2>Website Coming Soon</h2>
        <p>
          Our website is under construction. We are working on it and will be ready to launch soon.
        </p>
      </div>

      <div class="timer-content">
        <div class="time">
          <span id="days" class="numbers">00</span>
          <span>Days</span>
        </div>
        <div class="time">
          <span id="hours" class="numbers">00</span>
          <span>Hours</span>
        </div>
        <div class="time">
          <span id="minutes" class="numbers">00</span>
          <span>Minutes</span>
        </div>
        <div class="time">
          <span id="seconds" class="numbers">00</span>
          <span>Seconds</span>
        </div>
      </div>

      <div class="input-data">
        <h3>Subscribe Now to Get Updates</h3>
        <form class="input-fields">
          <input type="email" placeholder="Enter your email" required />
          <button type="submit">Subscribe Now</button>
        </form>
      </div>
    </div>
  </header>
</body>
</html>
