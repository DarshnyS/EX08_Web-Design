# Ex.08 Customer Registration Form
## AIM
  To write a program in JavaScript for creating a customer registration form for an agro-based company.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define different functions to register the customers based on their qualifications.

### STEP-3
  Using form elements to create the registration details of a customer.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE

<!DOCTYPE html>
<html lang="en"> <head>
<title>Registration Form</title>
<script src="registration-form"></script>
</head>
<body onload="Customer Registration Form();" <body style="background-color:powderblue;">
chi>Customer Registration Forme/h1>
<h2>Registration form for an Agro-based Company</h2>
<ul>
<11><label for="Full Name">Full Name:</label><711> <input type="text" name="Full Name" size="15" 7
<11><label for="Dateofbirth">Date of Birth:</label></11 <input type="DateofBirth" name="Date of Birth" size="12" /> cliclabel for="EmailID">Email ID:</label></li>
<input type="text" name="EmailID" size="50" /> <li><label for="contactno">Contact Number:</label></li>
<input type="text" name="contactno" size="30" /> <li><label for="Country">Country:</label></li>
<select name="Country">
coption selected="" value="Default">(Please select a country)</option>
<option value="AF">Australia</option> <option value "AL">Canada</option>
<option value="DZ">India</option> <option value="AS">Russla</option>
<option value="AD">USA</option>
</select>
<11><label for="address">Address:</label></li>
<input type="text" name="address"size="70"/> <li> <label for="City">City:</label></li>
<input type="text" name="city" size="30" />
<li> <label for="Pincode">Pincode: </label></li>
<input type="text" name="Pincode" />
<li><label for="State">State:</label></li> <input type="text" name="State" size="30" />
<li> <label id="gender">Gender:</label></li> <input type="radio" name="msex" value="Male" /><span>Male</span>
<input type="radio" name="fsex" value="Female" /><span>Female</span>
<li> <label>Language:</label></li>
<input type="checkbox" name="en" value="en" checked /><span>English</span> <input type="checkbox" name="nonen" value="noen" /><span>Non English</span> </ul>
<form action="/action_page.php" onsubmit="myFunction()">
<11><label for="desc">Your Qualification:</label></li> <textarea name="desc" id="desc"></textarea>
</ul>
<input type="submit" value="Submit">
</form>
<script>
function myFunction()
{
alert("The form was submitted");
}
</script>
</form>
</body>
</html>
## OUTPUT

![output 2](https://github.com/DarshnyS/EX08_Web-Design/assets/127816313/ea3cc1d3-a85a-4871-90c2-72ecbb7dbd2a)
![output 1](https://github.com/DarshnyS/EX08_Web-Design/assets/127816313/f4a0df68-3926-4e81-9e1d-39467fd48cac)

## RESULT
  Customer registration form using JavaScript is created successfully.
