<!DOCTYPE html>
<html lang="en" >
<head>
      <title>Welcome to website</title> 
      <meta charset="UTF-8">
      <meta name="viewport"      content="width=device-width, initial-scale=1.0">
       <style>
  #customer-form {
    padding: 20px;
    border: 1px solid #6266f1;
    background-color:#6d26b3;
  }

  #customer-form button {
    padding: 10px;
    background-color:#af1442;
    color: white;
    border: 0;
    border-radius: 5px;
  }

  #customer-form input[type="text"] {
    width: 100%;
    max-width: 250px;
  }
</style>
  </head>
  <body>
      <form action="/tutorial/action.html">
  <fieldset id="customer-form">
    <legend>Customer Information</legend>

    <label>First Name</label><br />
    <input type="text" name="firstname"><br /><br />

    <label>Last Name</label><br />
    <input type="text" name="lastname"><br /><br />

    <label>City</label><br />
    <input type="text" name="city"><br /><br />

    <label for="insurance">
      <input type="checkbox" id="insurance"
             name="hasinsurance"
             value="hasinsurance">
      &nbsp; Has Insurance
    </label><br /><br />

    <button type="submit">Submit</button>
  </fieldset>
</form>  
  </body>    
</html>
