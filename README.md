# Environment-day-special-picnic-form-web-page
<!DOCTYPE HTML>
<html>
<head>
<title> Environment day special picnic</title>
<body>
  <style>
body {
  background-image: url('Environment.jpg'
  );
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: 100% 80%;
}
</style>
<form>
<div align="center">
<h1 style="color:red">Environment day special picnic form</h1>
Enter your name:
<input type="text" placeholder="Please enter name" name="UserName" size=35 maxlength=35 value="">
<br></br>
Enter your class:
<input id="std" type="text" placeholder="please enter standard""name="Deptt" size=35 maxlength=35value=""> </br> </br>
name of the interested places:
<textarea name="Comments" placeholder="please enter place" cols=35 rows=1></textarea> </br> </br>
Are you interested in this picnic?
<input type="radio" name="exe" value=1>Yes
<input type="radio" name="exe" value=2>No
<br></br>
Picnic.:
<input type="1100/-" value="1100/-""> </br> </br>
How to pay the picnic fees:
<select name="moviepref" ><option>
<option value=1 selected = "true">online
<option value=2 >Google pay
<option value=3 >Phone pay
<option value=4 >Mi pay
<option value=5 >offline cash pay
</select>
</br></br>
<input type=submit value="Submit form">
</div>
</form>
<script>
alert("Hello! this only for student!");
		document.querySelector(�input�).onchange =   (e)=> {
						console.log(e.target.value)
		}
</script> 
</body>
</html
