# LOGIN-FORM
THIS IS A SIMPLE LOGIN FORM PAGE USING HTML CSS
<!DOCTYPE html>
<head>
<style>
body{
  margin:0;
  font-family: poppins,Arial,Helvetica,sans-serif;
  font-size:16px;
  font-weight:400;
  color:white;
  background:#cacff4;
  }
  
  .wrapper {
  margin: 0 auto;
  widht: 100%;
  max-width: 1140px;
  min-height: 100vh;
  display: flex;
  align items:center;
  justify-content:center;
  flex-direction:column;
  }
  
  .container {
  position:relative;
  width:100%;
  max-widht:600px;
  height=auto;
  display:flex;
  background: #ffffff;
  box-shadow: 0 0 5px #999999;
  }
  .login .col-left,
  .login .col-right {
  padding: 30px;
  display:flex;
  }
  .login .col-left {
  width: 60%;
  clip-path: polygon( 0 0,0% 100%,100% 0);
  background:green;
  }
  @media(max-width: 575px) {
  .login .container {
  flex-direction:column;
  box-shadow: none;
  }
 .login .col-left,
  .login .col-right {
  width: 100%;
  margin: 0;
  clip-path:none;
  }
  .login .col-right {
  padding: 30px;
  }
  }
  .login .login-text {
  position:relative;
  width:100%;
  margin:100%;
  color: #ffffff;
  }
  .login .login-text h2{
  margin: 0 0 20px 0;
  font-size: 30px;
  font-weight:700;
  }
  .login .login-text p{
  margin: 0 0 20px 0;
  font-size: 16px;
  font-weight: 500;
  line-weight: 22px;
  }
  .login .login-text .btn{
  display: inline-block;
  font-family:poppins;
  padding: 7px 20px;
  font-size:16px;
  letter-spacing: 1px;
  text-decoration: none;
  border-radius: 40px;
  color: #ffffff;
  outline: none;
  border: 1px solid #ffffff;
  box-shadow: inset 0 0 0 0 #ffffff;
  transtion: .3s;
  }
  .login .login-text .btn:hover{
  color: #2aa15f;
  box-shadow:inset 150px 0 0 0 #ffffff;
  }
  .login .login-form{
  position:relative;
  width:100%;
  }
  .login .login-form h2{
  margin: 0 0 10px 0;
  text-align:left;
  color:#666666;
  font-size:15px;
  }
  .login .login-form label{
  display: block;
  width: 100%;
  margin-bottom: 2px;
  letter-spacing: .5px;
  }
  .login .login-form label span {
  color:#ff574e;
  padding-left: 2px;
  }
  .login .login-form input {
  display: block;
  width: 100%;
  height: 35px;
  padding: 0 10px;
  outline: none;
  border: 1px solid #cccccc;
  border-radius:30px;
  }
  .login .login-form input:focus;
  border-color:#ff547e;
  }
  .login .login-form button;
  .login .login-form input[type=submit] {
  display: inline-block;
  width:100%;
  margin-top:5px;
  color:#2aa15f;
  font-size:16px;
  letter spacing:1px;
  cursor:pointer;
  background:transparent;
  border: 1px solid #2aa15f;
  border-radius: 30px;
  box-shadow: inset 0 0 0 0 #2aa15f;
  transition:.3s;
  }
  
  .login .login-form  button:hover,
  .login .login-form input[type=submit]:hover {
  
  color:#ffffff;
  box-shadow: inset 250px 0 0 0 #2aa15f;
  }
  </style>
</head>
  
  <link rel="stylesheet" href="style.css">
<body>
  <div class="wrapper login">
    <div class="container">
      <div class="col-left">
        <div class="login.text">
          <h2>Welcome!</h2>
          <p>Create your own account</p>
          <a href=""class="btn">Sign Up</a>
        </div>
      </div>
      <div class="col-right">
        <div class="login-form">
          <h2>Login</h2>
          <form action="">
            <p>
              <label>
                Username/Email Adress<span>*</span></label>
                <input type="text"placeholder="Username or Email" required>
            </p>
            <p>
              <label>password<span>*</span></label>
              <input type="password" placeholder="Password" required>
              </p>
              <p>
                <input type="submit" value="Sign In">
               </p>
               <p>
                 <a href="">Forgot password?</a>
               </p>
          </form>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
