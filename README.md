<body>

  <div class="wrapper">
    <form action="">
      <h1>Login</h1>
      
      <div class="input-box">
       <input type="text" placeholder="Username" required />
       <i class="bx bxs-user"></i>
      </div>
      
      <div class="input-box">
        <input type="password" placeholder="password" required />
        <i class="bx bxs-lock-alt"></i>
      </div>
      
      <div class="remember-forgot">
        <label> <input type="checkbox" /> Remember me </label><
        <a href="#">Forget Password?</a>
      </div>
      
      <button type="submit" class="button">Login</button>
      
      <div class="register-link">
        <p>Don't have an account? <a href="#"> Register</a></p>
      </div>
    </form>
  </div>
</body>
.wrapper h1 {
  text-align: center;
  font-size: 36px;
 }

.wrapper.input-box {
  position: relative;
  width: 100%;
  height: 50px;
  margin: 30px 0;
 }

.input-box input {
  width: 100%;
  height: 100%;
  background: transparent;
  border: none;
  outline: none;
  border-radius: 50px;
  border-radius: 50px;
  font-size: 16px;
  color: white;
  padding: 20px 45px 20px 20px;
 }
