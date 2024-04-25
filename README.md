# abesit-crc-work
#Sign in page without using css 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login and Signup Form</title>
</head>
<body>
    <div class="container">
        <h2><b><i>Abes Institute of technology , Ghaziabad</i></b></h2>
        <form action="login.php" method="post">
            <input type="text" name="username" placeholder="Username or Email" required>
            <input type="password" name="password" placeholder="Password" required>
            <input type="submit" value="Login">
        </form>
        <div class="signup-link">
            Don't have an account? <a href="signup.php">Sign up</a>
        </div>
    </div>
</body>
</html>


# Signup Page using HTML without using css
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="css/formstyle.css">
</head>
<body>
  <div class="continer">
    <form>
      <label><b>Enter Your Name</b></label>
      <input type="text" placeholder="Name" required>
      <label><b>Enter Your Passsword</b></label>
      <input type="password" placeholder="Passsword" required>
      <fieldset>
        <legend><i>Address</i></legend>
        <label><b>Addresss  Line 1</b></label>
        <input type="text" placeholder="Type here your address 1" required>
        <label><b>Addresss  Line 2</b></label>
        <input type="text" placeholder="Type here your address 2" required>
        <select>
          <option>--Select city--</option>
          <option>Delhi</option>
          <option>Ghaziabad</option>
          <option>BULANDHAHR</option>
          <option>shikandrabad
          </option>
        </select>
        <select>
          <option>--Select state--</option>
          <option>Delhi</option>
          <option>UP</option>
          <option>Uk</option>
          <option>varanshi</option>
          <option>dheradun
          </option>
        </select>
      </fieldset>
      <input type="submit" >
      <input type="reset">
    </form>
    
  </div>

</body>
</html>

# All Source Code Files are available
