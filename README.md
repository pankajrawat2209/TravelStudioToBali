# TravelStudioToBali

Below is the source code and preview of website created of booking page for travelling to Bali ( A Historic place in Indonesia with Tropical paradise with beaches , culture and spiritual retreats )

![Website Preview](https://github.com/pankajrawat2209/TravelStudioToBali/blob/main/Screenshot%202025-07-16%20072518.png?raw=true)

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TravelStud.com - Book your Travel to Bali</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      height: 100vh;
      background: linear-gradient(135deg, #f3c6f1, #a1c4fd);
      display: flex;
      align-items: center;
      justify-content: center;
      backdrop-filter: blur(10px);
    }

    .glass-form {
      background: rgba(255, 255, 255, 0.2);
      border-radius: 20px;
      box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border: 1px solid rgba(255, 255, 255, 0.18);
      padding: 30px;
      width: 350px;
    }

    .glass-form h2 {
      text-align: center;
      color: #fff;
      margin-bottom: 20px;
    }

    .form-group {
      margin-bottom: 15px;
      display: flex;
      flex-direction: column;
      color: white;
    }

    label {
      margin-bottom: 5px;
      font-weight: bold;
    }

    input, textarea {
      padding: 10px;
      border: none;
      border-radius: 10px;
      outline: none;
      background-color: rgba(255, 255, 255, 0.7);
    }

    textarea {
      resize: none;
      height: 60px;
    }

    .submit-btn {
      margin-top: 20px;
      width: 100%;
      padding: 12px;
      border: none;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      color: black;
      font-weight: bold;
      border-radius: 10px;
      cursor: pointer;
      transition: 0.3s;
    }

    .submit-btn:hover {
      background: linear-gradient(135deg, #fbc2eb, #a6c1ee);
    }
  </style>
</head>
<body>
  <form class="glass-form" action="">
    <h2>Book Your Bali Vacation</h2>

    <div class="form-group">
      <label for="Name">Name:</label>
      <input name="Name" placeholder="Enter your name" type="text" />
    </div>

    <div class="form-group">
      <label for="age">Age:</label>
      <input name="age" placeholder="Enter your age" type="number" />
    </div>

    <div class="form-group">
      <label for="phoneno">Phone:</label>
      <input name="phoneno" placeholder="Enter your phone no" type="tel" />
    </div>

    <div class="form-group">
      <label for="email">Email:</label>
      <input name="email" placeholder="Enter your email ID" type="email" />
    </div>

    <div class="form-group">
      <label for="address">Address:</label>
      <textarea name="address" id="address" placeholder="Enter your address"></textarea>
    </div>

    <button class="submit-btn" type="submit">Submit</button>
  </form>
</body>
</html>


