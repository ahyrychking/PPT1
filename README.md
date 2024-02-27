<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Registration</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
<h1 id="title">Registration Form</h1>
<div class="user-info">
<label for="fullName" id="fullName">Full Name</label>
<div class="inputfullName">
<input type="text" name="firstName" placeholder="First Name" required>
<input type="text" name="middleName" placeholder="Middle Name" required>
<input type="text" name="lastName" placeholder="Last Name" required>
</div>
<div class="gender-buttons">
<label for="gender">Gender</label>
<div>
<input type="radio" name="gender" id="male">
<label for="male">♂ Male</label>
</div>
<div>
<input type="radio" name="gender" id="female">
<label for="female"> ♀ Female</label>
</div>
<div>
<input type="radio" name="gender" id="other">
<label for="other">Other</label>
</div>
</div>
<div class="inputBox">
<label for="age">Age</label>
<input type="number" name="age" placeholder="Enter your age" required>
</div>
<div class="inputBox">
<label for="Birthday">Birthdate</label>
<input type="date" name="Birthday" placeholder="Birthdate" required>
</div>
<div class="inputBox">
<label for="Address">Address</label>
<input type = "text" name="Address" placeholder="Enter your address"
required>
</div>
<div class="inputBox">
<label for="Contact">Contact Number</label>
<input type="number" name="Contact" placeholder="09XXXXXXXXX" required>
</div>
<div class="inputBox">
<label for="Email">Email</label>
<input type="email" name="Email" placeholder="Enter your email" required>
</div>
<div class="register-button">
<button>Register</button>
</div>
</div>
</div>
CSS:
*{
padding: 0;
margin: 0;
box-sizing: border-box;
font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}
body{
justify-content: center;
align-items: center;
display:flex;
margin: 0;
height: 100vh;
background: #9e3697;
background: url(purple.jpg);
background-size: cover;
}
.container{
width: 80%;
max-width: 750px;
padding: 30px;
margin: 0 auto;
border-radius: 10px;
background: rgba(130, 129, 129, 0.5);
}
.user-info {
display: flex;
flex-wrap: wrap;
justify-content: space-between;
padding: 20px 0;
}
.inputBox label{
display:block;
font-size: 18px;
color:rgb(242, 242, 242);
margin-bottom: 5%;
}
.inputBox input{
width: 100%;
padding:10px;
font-size: 16px;
}
.inputBox {
flex-basis: 48%;
margin-bottom: 15px;
}
.register-button {
flex-basis: 100%;
text-align: center;
}
.register-button button{
margin-top: 10%;
background-color: rgb(108, 13, 122),rgb(63, 18, 84);
color: purple;
padding: 15px 30px;
font-size: 18px;
border: none;
border-radius: 5px;
cursor: pointer;
width:100%;
}
.register-button button:hover {
background-color: rgb(166, 55, 217);
}
.gender-buttons label{
display:block;
font-size: 18px;
color:rgb(242, 242, 242);
margin-bottom: 5%;
}
.gender-buttons div {
display: inline-block;
margin-right: 40px;
}
.gender-buttons input[type="radio"] {
transform: scale(1.5);
}
.gender-buttons{
flex-basis: 48%;
margin-bottom: 15px;
}
h1#title{
font-size: 26px;
font-weight: 600;
text-align: center;
padding-bottom: 6px;
color: white;
text-shadow: 2px 2px 2px black;
border-bottom: solid 1px white;
}
.inputfullName {
display: flex;
align-items: center;
margin-bottom: 2%;
width:100%;
}
.inputfullName input {
flex: 1;
padding: 10px;
font-size: 16px;
margin-right: 2%;
}
.inputfullName label {
margin-right: 10px;
}
label#fullName{
display:block;
font-size: 18px;
color:rgb(242, 242, 242);
margin-bottom: 2%;
}
