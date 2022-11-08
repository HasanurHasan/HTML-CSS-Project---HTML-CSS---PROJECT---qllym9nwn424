# html-css-js-project-boilerplate
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Verify Account - Ui</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="container">
      <h2>Verify Your Account</h2>
      <p>
        We emailed you the six digit code to demo@gmail.com <br />
        Enter the code below to confirm your email address.
      </p>
      <div class="code-container">
        <input type="number" placeholder="0" min="0" max="9" class="code" />
        <input type="number" placeholder="0" min="0" max="9" class="code" />
        <input type="number" placeholder="0" min="0" max="9" class="code" />
        <input type="number" placeholder="0" min="0" max="9" class="code" />
        <input type="number" placeholder="0" min="0" max="9" class="code" />
        <input type="number" placeholder="0" min="0" max="9" class="code" />
      </div>
      <small class="info">
        This is design only. We did'nt actually send you an email as we don't
        have your email, right ?
      </small>
    </div>

    <script src="script.js"></script>
  </body>
</html>
