<!DOCTYPE html>
<body>
    <h2>Registration Form</h2>
    <form action = "#" method = "post">
      <label>First Name:</label><br>
      <input type="text" name="fname" ><br>

      <label>Last Name:</label><br>
      <input type="text" name="lname" ><br>

      <label>Phone No:</label><br>
      <input type="tel" name="phone" pattern="[0-9]{10}" ><br>

      <label>Gmail:</label><br>
      <input type="email" name="email" ><br>

      <label>Address:</label><br>
      <textarea name="address" rows="2"></textarea><br>

      <label>City:</label><br>
      <input type="text" name="city"><br>

      <label>State:</label><br>
      <input type="text" name="state"><br>

      <label>Pincode:</label><br>
      <input type="text" name="pincode" pattern="[0-9]{6}"><br>

      <label>Aadhar No:</label><br>
      <input type="text" name="aadhar" pattern="[0-9]{12}"><br>

      <label>Pan No:</label><br>
      <input type="text" name="pan"><br>

      <label>Gender:</label>
      <div class="gender">
        <input type="radio" name="gender" value="Male"> Male
        <input type="radio" name="gender" value="Female"> Female
        <input type="radio" name="gender" value="Other"> Other
      </div>

      <label>DOB:</label><br>
      <input type="date" name="dob"><br>

      <label>Hobbies:</label><br>
      <div class="hobbies"><br>
        <input type="checkbox" name="hobby" value="Reading"> Reading <br>
        <input type="checkbox" name="hobby" value="Traveling"> Traveling <br>
        <input type="checkbox" name="hobby" value="Music"> Music <br>
      </div><br>

      <label>User ID:</label> <br>
      <input type="text" name="userid" required><br>

      <label>New Password:</label> <br>
      <input type="password" name="password" required> <br>

      <label>Re-enter Password:</label> <br>
      <input type="password" name="repassword" required> <br>

      <div class="btn-container"> <br>
        <button type="submit">Submit</button> 
        <button type="reset" class="cancel">Cancel</button>
      </div>
    </form>
  </div>

</body>
</html>



