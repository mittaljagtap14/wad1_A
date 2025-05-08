#wadprac_1_A
create a responsive web page which shows the ecommerce admin dashboard with sidebar and statistic 
in cards using HTML,CSS and Bootstrap.

index.html
style.css
//////
login.html 
//////

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Login</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-light d-flex justify-content-center align-items-center" style="height: 100vh;">

  <div class="card p-4 shadow" style="width: 350px;">
    <h3 class="text-center mb-3">Login</h3>
    <form>
      <div class="mb-3">
        <label for="email" class="form-label">Email address</label>
        <input type="email" class="form-control" id="email" required>
      </div>
      <div class="mb-3">
        <label for="password" class="form-label">Password</label>
        <input type="password" class="form-control" id="password" required>
      </div>
      <button type="submit" class="btn btn-primary w-100">Login</button>
      <p class="mt-3 text-center"><a href="register.html">Don't have an account? Register</a></p>
    </form>
  </div>

</body>
</html>
//////////////////////////////////////////

register.html
/////////
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Register</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-light d-flex justify-content-center align-items-center" style="height: 100vh;">

  <div class="card p-4 shadow" style="width: 400px;">
    <h3 class="text-center mb-3">Register</h3>
    <form>
      <div class="mb-3">
        <label for="name" class="form-label">Full Name</label>
        <input type="text" class="form-control" id="name" required>
      </div>
      <div class="mb-3">
        <label for="regemail" class="form-label">Email address</label>
        <input type="email" class="form-control" id="regemail" required>
      </div>
      <div class="mb-3">
        <label for="regpassword" class="form-label">Password</label>
        <input type="password" class="form-control" id="regpassword" required>
      </div>
      <button type="submit" class="btn btn-success w-100">Register</button>
      <p class="mt-3 text-center"><a href="login.html">Already registered? Login</a></p>
    </form>
  </div>

</body>
</html>
