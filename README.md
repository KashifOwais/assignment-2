<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment-2</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
</head>
<body style="background-color: rgb(170, 170, 161);">
    <h1 align="center">Assignment-2</h1>
<p style="color: red; font-style: italic;">
    <u> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ut vero tenetur facere quo ad ex culpa veritatis exercitationem accusantium numquam a corrupti explicabo, incidunt ipsum, rerum nobis cum odit dolorum asperiores! Dolorum, quam magni sit quos beatae ex nam eos expedita ducimus qui dicta iure amet repudiandae in reiciendis voluptatum!</u>
    <p style="color: rgb(30, 255, 0); font-style:bold;">
        <b> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ut vero tenetur facere quo ad ex culpa veritatis exercitationem accusantium numquam a corrupti explicabo, incidunt ipsum, rerum nobis cum odit dolorum asperiores! Dolorum, quam magni sit quos beatae ex nam eos expedita ducimus qui dicta iure amet repudiandae in reiciendis voluptatum!</b>
</p>

<h1>Registration Form</h1>
Use tab keys to move from one input field to the next.
<form name='registration' onSubmit="return formValidation();">
<ul>
<li><label for="userid">User id:</label></li>
<li><input type="text" name="userid" size="12" /></li>
<li><label for="passid">Password:</label></li>
<li><input type="password" name="passid" size="12" /></li>
<li><label for="username">Name:</label></li>
<li><input type="text" name="username" size="50" /></li>
<li><label for="address">Address:</label></li>
<li><input type="text" name="address" size="50" /></li>
<li><label for="country">Country:</label></li>
<li><select name="country">
<option selected="" value="Default">(Please select a country)</option>
<option value="AF">Australia</option>
<option value="AL">Canada</option>
<option value="DZ">India</option>
<option value="AS">Russia</option>
<option value="AD">USA</option>
</select></li>
<li><label for="zip">ZIP Code:</label></li>
<li><input type="text" name="zip" /></li>
<li><label for="email">Email:</label></li>
<li><input type="text" name="email" size="50" /></li>
<li><label id="gender">Sex:</label></li>
<li><input type="radio" name="msex" value="Male" /><span>Male</span></li>
<li><input type="radio" name="fsex" value="Female" /><span>Female</span></li>
<li><label>Language:</label></li>
<li><input type="checkbox" name="en" value="en" checked /><span>English</span></li>
<li><input type="checkbox" name="nonen" value="noen" /><span>Non English</span></li>
<li><label for="desc">About:</label></li>
<li><textarea name="desc" id="desc"></textarea></li>
<li><input type="submit" name="submit" value="Submit" /></li>
</ul>
</form>
<script src="myscripts.js"></script> 
<script>
    $("document").ready( function () {
        alert("Assignment-2");
    }); 
</script>

</body>

</html>
