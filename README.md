<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Form101</title>
</head>
<body>

  <table>
    <tr>
      <td>
        <img src="ronaldo.jpg" alt="Ronaldo" width="200">
      </td>
      <td>
        <p>
          Learn more about football, teamwork, and sportsmanship. Welcome to our
          Football Activity Program! Please fill out this form to become a member.
          It's free and open to all ages who enjoy playing and learning about football.
        </p>
      </td>
    </tr>
  </table>

  <form>
    <table border="0">
      <tr>
        <td>
          <table>
            <tr>
              <td>Name:</td>
              <td><input type="text" name="name"></td>
            </tr>
            <tr>
              <td>Address:</td>
              <td><input type="text" name="address"></td>
            </tr>
            <tr>
              <td>Email:</td>
              <td><input type="text" name="email"></td>
            </tr>
            <tr>
              <td>Contact Number:</td>
              <td><input type="text" name="contact"></td>
            </tr>
          </table>
        </td>
        <td>
          <b>Gender:</b><br>
          <input type="radio" name="gender" value="male"> Male<br>
          <input type="radio" name="gender" value="female"> Female<br><br>
          <b>Hobbies:</b><br>
          <input type="checkbox" name="hobbies" value="swimming"> Swimming<br>
          <input type="checkbox" name="hobbies" value="biking"> Biking<br>
          <input type="checkbox" name="hobbies" value="reading"> Reading<br>
          <input type="checkbox" name="hobbies" value="watching"> Watching<br>
          <input type="checkbox" name="hobbies" value="playing"> Playing<br>
        </td>
      </tr>
    </table>
  </form>

</body>
