<!DOCTYPE html>
<html>
<head>
  <title>Contact Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header, nav, section, article, footer {
      padding: 20px;
      margin: 10px;
    }
    nav {
      background-color: #e6ffe6;
    }
    form {
      max-width: 500px;
      margin: auto;
    }
    label {
      display:BOX BLOCK;
      margin-top: 15px;
    }
    input, textarea, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      box-sizing: border-box;
    }
    button {
      margin-top: 20px;
      padding: 10px 20px;
      background-color: PURPLE;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: GREEN;
    }
    footer {
      text-align: center;
      background-color: GREY;
    }
  </style>
</head>
<body>

  <header>
    <h1>Contact Us</h1>
  <section>
    <article>
      
      <form action="#" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Submit</button>
      </form>
    </article>
  </section>

  <footer>
    <p>DAY 2 ABOUT CONTACT , MESSAGE , EMAIL</p>
  </footer>

</body>
</html>
