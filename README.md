<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Forms </title>
</head>
<body>
  <h1> HTML Forms Example. </h1>  
  <form>
    <fieldset>
      <legend> Contact Information: </legend>
  <table border="0" cellpadding ="8" cellspacing="0" >
    <tr> 
        <td> <label for ="fname"> First name. </label> </td>
         <td><input type="text" id="firstName" name="firstName" placeholder="First name"></td>
         <td> Preferred contact method: </td>
      </tr>
      <tr>
        <td><label for="lastName">Last name:</label></td>
        <td><input type="text" id="lastName" name="lastName" placeholder="Last name"></td>
        <td><input type="checkbox"> Email</td>
      </tr>
      <tr>
        <td><label for="email">Email:</label></td>
        <td><input type="email" id="email" name="email" placeholder="Email"></td>
        <td><input type="checkbox"> Telephone </td>
      </tr>
      <tr>
        <td><label for="Telephone">Telephone</label></td>
        <td><input type="tel" name="Telephone" placeholder="Telephone"></td>
      </tr>
    </table>
</fieldset>
<fieldset> 
  <legend> Feedback: </legend>
  <table> 
    <tr>
      <td> <label for = "Message subject"> </label> Message subject:
      <input type = "text" id="Message subject" name = "Message" placeholder="Message subject"></td>
    </tr>
    <tr> 
      <td> 
        <textarea name = "message" rows="15" cols="50">
        </textarea>
      </td>
    </tr>
    <tr>
      <td>
        <label for="doc">Attach a file: </label>
        <input type="file" id ="fileupload"> 
      </td> </tr>
  </table>
  <hr>
  <input type="submit" value="Send">
</fieldset>
</form>
</body>
</html>
