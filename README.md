<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>firstPage</title>
    <style>
        body{
            margin: 0;
            padding: 0;
            background-image: url("background.jpg");
            background-attachment: fixed;
            background-position: center;
            background-repeat: no-repeat;
            background-size:cover;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .container1{
            margin:150px;
            padding: 40px;
            height: 400px;
            width: 600px;
            background:rgba(255, 255, 255, 0.1);
            border-radius: 50px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .login{
            width: 320px;
            padding: 40px;
            border-radius: 20px;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(15px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
            text-align: center;
            color: darkblue; 
        }
        .login h2{
            margin: 20px;
            text-align: left;
            color: darkblue;
        }
        .login h4{
            margin: 5px;
            text-align: left;
            color: darkblue;
        }
        .login input{
            width: 300px;
            padding: 10px;
        }
        .login  .forgot{
            margin-top: 5px;
            text-align:left;
            color: darkblue;
        }
        .login button{
            margin-top: 10px;
            margin-bottom: 10px;
            padding: 10px;
            width: 175px;
            background-color:rgb(4, 4, 154);
            text-align: center;
            color: whitesmoke;
        }
         .social {
            display: flex;
            justify-content: space-between;
        }
           .social button {
            width: 30%;
            padding: 0;
            background: #fff;
            color: #333;
            font-size: 14px;
        }
        .social button{
            margin: 10px;
            height: 20px;
            width:150;
            background-color:white;
            text-align: center;
            color: black;


        }
        .register span{
            color:red;

        }
    </style>
</head>
<body>
    <div class="container1">
        <div class="login">
            <h3 ,align="center">Your Logo</h3>
            <h2 ,align="left">Login</h2>
            <h4>Email</h4>
            <input type="email" placeholder="username@gmail.com">
            <h4>Password</h4>
            <input type="password" placeholder="Password">

            <div class="forgot">Forgot Password?</div>

            <button>Sign in</button>

            <div class="divider">or continue with</div>

            <div class="social">
                <button>G</button>
                <button>Git</button>
                <button>F</button>
           </div>

    <div class="register">
      Don’t have an account? <span>Register</span>
    </div>
    </div>  
</body>
</html>
