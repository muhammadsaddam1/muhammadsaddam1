<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Forms</title>
</head>

<body>
  <h2> This is Html forms Tutorial</h2>

  <form action="backend.php">

    <label for="name">Name :</label>

    <input type="text" name="myName" id="name">

    <br />

    <label for="password">Password:</label>

    <input type="password" name="password" id="password">

    <br />

    <label for="phone-number">phone number</label>

    <input type="tel" name="phone number" id="phone-number">

    <br />

    <label for="role">Role</label>

    <input type="text" name="my Role" id="role">

    <br />

    <label>Email

      <input type="email" name="my email" id="email">
    </label>

    <br />

    <label for="date">Date</label>

    <input type="date" name="date" id="date">

    <br />
    <label for="bonus">Bonus</label>

    <input type="Number" value="my date" id="bonus">

    <br />

    <p>Are you eligible?:</p> <input type="checkbox" value="my Eligibility">

    <br />

    Gender:
    Male<input type="radio" value="Male" name="Gender">
    Female <input type="radio" value="Female" name="Gender">

    <br />
    <label for="Country">Select any Country:</label>

    Pakistan <input type="radio" value="Pakistan" name="country" id="country">
    India<input type="radio" value="India" name="country" id="country">
    China<input type="radio" value="China" name="country" id="country">
    
    <br />
   
      Write about your selef:
      <br />
      <textarea name="decsciption"></textarea>

      <br />
      
      submit:<input type="submit" value="submit now">
      Reset:<input type="Reset" value="Reset now">
    
      <br />
  </form>
</body>
</html>
