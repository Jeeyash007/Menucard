<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Presidential's Cafeteria</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #f0f4f8, #dbe9f4);
      font-family: 'Poppins', sans-serif;
      color: #2c3e50;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      background-color: #fff;
      padding: 30px 50px;
      border-radius: 15px;
      box-shadow: 0 12px 24px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease-in-out;
    }

    .container:hover {
      transform: scale(1.01);
    }

    h1 {
      text-align: center;
      color: #2980b9;
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    hr {
      border: none;
      height: 2px;
      background-color: #bdc3c7;
      margin: 25px 0;
    }

    .section {
      margin-bottom: 35px;
    }

    .section p {
      line-height: 1.6;
      font-size: 1.05rem;
    }

    h2, h3, h4 {
      color: #34495e;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      background: #ecf0f1;
      margin: 8px 0;
      padding: 12px 20px;
      border-left: 6px solid #3498db;
      border-radius: 5px;
      transition: background-color 0.2s ease;
    }

    li:hover {
      background-color: #dff6ff;
    }

    .benefits p {
      margin: 6px 0;
    }

    .benefits b {
      color: #27ae60;
    }

    .contact-info {
      background-color: #f5fff7;
      padding: 20px 30px;
      border-left: 6px solid #2ecc71;
      border-radius: 8px;
    }

    .contact-info p {
      font-size: 1rem;
    }

    /* Responsive */
    @media (max-width: 600px) {
      .container {
        padding: 20px;
      }

      h1 {
        font-size: 2rem;
      }

      li {
        font-size: 0.95rem;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Welcome to Presidential's Cafeteria</h1>
    <hr>

    <div class="section">
      <p>Our canteen offers delicious and affordable meals to students and staff.<br>
         Open from <b>7 AM to 7 PM</b> every weekday.</p>
    </div>

    <div class="section">
      <h2>Today's Menu</h2>
      <ul>
        <li>Chicken Momo - Rs. 80</li>
        <li>Chicken Chowmein - Rs. 120</li>
        <li>Tea - Rs. 20</li>
        <li>Sandwich - Rs. 90</li>
        <li>Chicken Burger - Rs. 230</li>
        <li>French Fries - Rs. 70</li>
        <li>Cold Drinks - Rs. 50</li>
        <li>Plain Rice with Curry - Rs. 100</li>
        <li>Egg Roll - Rs. 60</li>
        <li>Milk Coffee - Rs. 50</li>
      </ul>
    </div>

    <div class="section benefits">
      <h3>Why Choose Our Canteen?</h3>
      <p><b>Fresh Food:</b> Cooked daily with hygiene.</p>
      <p><b>Budget-Friendly:</b> Designed for students and staffs.</p>
      <p><b>Wi-Fi Zone:</b> Stay connected while you eat.</p>
    </div>

    <hr>

    <div class="section contact-info">
      <h4>Contact Us</h4>
      <p>Email: canteen@presedentialschool.edu.np<br>
         Phone: 01-5555555</p>
    </div>
  </div>

</body>
</html>
