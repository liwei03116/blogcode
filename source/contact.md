---
title: Contact Information
layout: page
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    form {
      max-width: 600px;
      margin: 0 auto;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    label {
      display: block;
      margin-bottom: 8px;
    }
    input,
    textarea {
      width: 100%;
      padding: 8px;
      margin-bottom: 16px;
      box-sizing: border-box;
    }
    button {
      background-color: #4caf50;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

  </style>
</head>
<body>

  <p>You can reach me at my email address: liwei03116@yahoo.com</p>

  <form action="https://formspree.io/f/xdorrjyb" method="POST">
    <label for="_replyto">Your Email:</label>
    <input type="email" name="_replyto" required>

<label for="message">Message:</label>
<textarea name="message" rows="4" required></textarea>

<button type="submit">Send</button>

  </form>

</body>
</html>
