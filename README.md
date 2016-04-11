<html>
<head>
<title>linkedPage</title>
<script type="text/javascript">
function check(form)
{
 
 if(form.user.value == "user" && form.password.value == "pswrd")
  {
    window.open('www.facebook.com')
  }
 else
 {
   window.alert("Error Password or Username Try again")
  }
}
</script>
</head>
<body>
<div align="center">
<form  name="login">
<br>
<h3><font color="blue" face="Tekton Pro">UserName</font></h3>
<input type="text" name="user">
<br><br>
<h3><font color="blue" face="Tekton Pro">Password</font></h3>
<input type="password"  name="password" size="20">

<br>
<br>
<br>
<input type="button" value="Log in" onClick="check(this.form)">
<br>
<br>
<h3><font color="blue" face="Tekton Pro">Your Comment</font></h3>
<textarea rows="5" cols="20" ></textarea>
<br><br><br>
<br>
</form>
</div> 

</body>
</html>
