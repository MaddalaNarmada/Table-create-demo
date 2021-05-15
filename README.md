# Table-create-demo

Here we are looking the example of creating the table having the format of login page,,,,

Here we can see the code below......


code..


<!DOCTYPE html>
<html>
<head>
	<title>Login page</title>
</head>
<body>
	<center>
		<form>
		<table border="4" cellpadding="4" bgcolor="grey" height="40%" width="40%">
			<tr>
				<td><font color="white">Registered E-mail ID</font></td>
			</tr>
			<tr>
				<td><input type="email" size="35" placeholder="Enter email ID"></td>
			</tr>
			<tr>
				<td><font color="white">Username/Registered Mobile Number</font></td>
			</tr>
			<tr>
				<td><input type="text" size="35" placeholder="Enter Username/Mobile Number" required pattern="[7-9]{1}[0-9]{9}"></td>
			</tr>
			<tr>
				<td><font color="white">Password</font></td>
			</tr>
			<tr>
				<td><input type="password" size="35" placeholder="Enter Password"></td>
			</tr>
			
			<tr align="center">
				<td><input type="submit" value="Login"> &nbsp;&nbsp;&nbsp;
					<input type="reset" value="Reset"></td>
				</tr>
	</table>
	</form>
</center>

</body>
</html>
