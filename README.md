<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sign Up</title>
  <link rel="stylesheet" href="myStyle.css">
  <style> 
    body{
  background: url('https://images.wallpapersden.com/image/download/small-memory_am1pa2aUmZqaraWkpJRobWllrWdma2U.jpg');
  background-size: cover;
  font-family: Arial;
}

.wrap{
  max-width: 350px;
  border-radius: 20px;
  margin:auto;
  background:rgba(0,0,0,0.8,);
  box-sizing:border-box;
  padding:40px;
  color:#fff;
  margin-top:100px;
}

h1{
  text-align: center;
}

input[type=text],input[type=password] {
  width: 100%;
  box-sizing: border-box;
  padding: 12px 5px;
  background:rgba(0,0,0,0.1,);
  outline:none;
  border:none;
  border-bottom: 1px dotted #fff;
  color:#fff;
  border-radius:5px;
  margin:5px;
  font-weight:bold;
}
input[type=submit]{
  width:100%;
  box-sizing:border-box;
  padding: 10px 0;
  margin-top:30px;
  outline:none;
  border:none;
  background:#50adde;
  opacity:0.7;
  border-radius:20px;
  font-size: 20px;
  color:#fff;
}

input[type=submit]:hover{
  background:#003366;
  opacity:0.7;

}
</style>
</head>
<body>
  <div class="wrap">
  <h1>Sign Up</h1>

  <form id='SignUpForm'>
    <input type='text' placeholder ='First Name..' required>
    <input type='text' placeholder ='Last Name..' required>
    <input type='text' placeholder ='Email..' required>
    <input type='text' placeholder ='Username..' required>
    <input type='Password' placeholder ='Password..' required>
    <input type='submit' value = 'Submit'> 

  </form>

  </div>
</body>
</html>
